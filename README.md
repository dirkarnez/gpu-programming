gpu-programming
===============
### Docs
- https://bootlin.com/pub/conferences/2017/kr/ripard-drm/ripard-drm.pdf
- https://cgit.freedesktop.org/xorg/driver/xf86-video-armsoc/tree/src/armsoc_driver.c

- ### Tools
- freedreno
- [Etnaviv](https://github.com/etnaviv)
  - https://www.x.org/wiki/Events/XDC2015/Program/Stach_etnaviv.pdf
  - [Etnaviv: An Open-Source Driver For Vivante GPUs - Phoronix](https://www.phoronix.com/news/MTI3MjU)
  - [Multiple Render Targets for etnaviv | Christian Gmeiner](https://christian-gmeiner.info/2025-01-16-mrt/)
- lima

### GPUs
- ARM Mali 400 MP2 GPU
  - [fxlin/mali: Everything we learnt from hacking Arm Mali GPUs.](https://github.com/fxlin/mali)
  - [PinePhone - PINE64](https://pine64.org/devices/pinephone/)
  - [解读指标 Mali-400MP4 GPU 指标_mali400mp2-CSDN博客](https://blog.csdn.net/qq_45763093/article/details/117550231)
  - [ARM GPU(mali-400 MP)-CSDN博客](https://blog.csdn.net/weixin_34204722/article/details/91983713)
  - [ARM GPU(Mali G610)及其驱动、OpenGLES、性能测试相关 - ArnoldLu - 博客园](https://www.cnblogs.com/arnoldlu/p/18175082)
  - [Mali GPU User-Space Binary Drivers](https://developer.arm.com/downloads/-/Mali%20GPUs%20User-Space%20Binary%20Drivers)
  - [Mali 5th Gen GPU Architecture](https://developer.arm.com/downloads/-/Mali%205th%20Gen%20GPU%20Architecture)
  - [The Mailbox Peripheral | Building an Operating System for the Raspberry Pi](https://jsandler18.github.io/extra/mailbox.html)
  - [mali_kbase - kernel/google-modules/gpu - Git at Google](https://android.googlesource.com/kernel/google-modules/gpu/+/refs/heads/android-gs-raviole-5.10-android13/mali_kbase)
- VideoCore
  - [circle/addon/vc4/interface at 3bbfd6e31a64e5891aa12d479b2d795bfa6b1ec4 · rsta2/circle](https://github.com/rsta2/circle/tree/3bbfd6e31a64e5891aa12d479b2d795bfa6b1ec4/addon/vc4/interface)
- Vivante
  - [drivers/mxc/gpu-viv - linux-imx - Git at Google](https://coral.googlesource.com/linux-imx/+/refs/heads/251xb/drivers/mxc/gpu-viv)
  - [android-imx6-kitkat/kernel_imx.git/3.10/0002-Solve-GPU-kernel-build-issue.patch at master · rabeeh/android-imx6-kitkat](https://github.com/rabeeh/android-imx6-kitkat/blob/master/kernel_imx.git/3.10/0002-Solve-GPU-kernel-build-issue.patch)
  - [prothesman/VivanteGPU: from https://github.com/laanwj/etna_viv](https://github.com/prothesman/VivanteGPU)
  - https://bbs.aw-ol.com/assets/uploads/files/1665722589258-705bbf1c-39d1-4dd4-a7f8-18839c8e40a4-vivante.programming.viplite.api-v1.10-sw1.7.0-b-20220329.pdf
  - https://www.infineon.com/assets/row/public/documents/30/44/infineon-vivante-vglite-vector-graphics-api-user-manual-usermanual-en.pdf
  - https://github.com/nxp-imx/linux-imx/blob/be78e49cb4339fd38c9a40019df49b72fbb8bcb7/drivers/mxc/gpu-viv/hal/kernel/gc_hal_kernel_preemption.h#L201
  - [STM32 定时器详细篇（基于HAL库） - 东小东 - 博客园](https://www.cnblogs.com/dongxiaodong/p/14351398.html)
- GPU agnostic
  - [VG-Lite General GPU — LVGL documentation](https://docs.lvgl.io/9.2/overview/renderers/vg_lite.html)
    - [VG-Lite General GPU（VG-Lite通用GPU） — LVGL 文档](https://lvgl.100ask.net/master/details/integration/renderers/vg_lite.html)
    - [lvgl/src/draw/vg_lite at master · Sunrisepeak/lvgl](https://github.com/Sunrisepeak/lvgl/tree/master/src/draw/vg_lite)
    - https://www.nxp.com/docs/zh/application-note/AN14210.pdf

### CICD
- [glmark2/.github/workflows/build.yml at master · glmark2/glmark2](https://github.com/glmark2/glmark2/blob/master/.github/workflows/build.yml)

### Multi GPUs
- [nv-legate/cupynumeric: NumPy and SciPy on Multi-Node Multi-GPU systems](https://github.com/nv-legate/cupynumeric)
- [nv-legate/legate: The Foundation for All Legate Libraries](https://github.com/nv-legate/legate)

### Reference
- [Apple M1 GPU分析 | Kevin Wen's Blog](https://wenxiaoming.github.io/2021/03/27/Apple%20M1%20GPU%20Analysis/)  
