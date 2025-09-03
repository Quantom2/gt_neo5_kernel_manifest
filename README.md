# How to set up and build
## Initialize repo
```repo init https://github.com/Quantom2/gt_neo5_kernel_manifest.git -b <branch> -m <manifest.xml> --depth=1 --no-tags```

 Use ```oneplus/sm8475``` for branch and ```realme_gt_neo5.xml``` for manifest.xml

 ```repo init https://github.com/Quantom2/gt_neo5_kernel_manifest.git -b oneplus/sm8550 -m realme_gt_5.xml --depth=1 --no-tags```

## Sync
```repo sync --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j<number>```

 Use ```desired number of threads``` for number. Usualy used number of ```4```

## Build
```./kernel_platform/oplus/build/oplus_build_kernel.sh kalama gki ```
