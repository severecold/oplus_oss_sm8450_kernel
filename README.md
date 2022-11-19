# OPPO SM8450 Opensource kernel build
### Based on 
 + [oppo opensource kernel for sm8450](https://github.com/oppo-source/android_kernel_oppo_sm8450)
 + [kernel modules](https://github.com/oppo-source/android_kernel_modules_and_devicetree_oppo_sm8450.git)
 + [gck common-android12-5.10](https://source.android.com/docs/setup/build/building-kernels)

### How to build
> * cd kernel_platform
> * SKIP_MRPROPER=1 AGING_DEBUG_MASK=2 LTO=full BUILD_CONFIG=common/build.config.msm.waipio VARIANT=gki ./build/build.sh
