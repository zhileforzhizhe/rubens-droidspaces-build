# rubens-droidspaces-build

红米 K50（rubens，天玑 8100）DroidSpaces 容器内核自动编译流水线。

- 源码：ProjectRubens/kernel_xiaomi_mt6895（K50 官方维护团队，lineage-22.1 / 安卓 15）
- 补丁：DroidSpaces 官方 GKI kABI 补丁（SYSVIPC + POSIX_MQUEUE，不破坏原厂驱动兼容性）
- 功能：容器全套配置（命名空间/进程间通信/设备管理）+ KernelSU（root 保留）
- 打包：AnyKernel3 刷机包，可用 KernelFlasher 直接刷入

触发方式：Actions 页面手动触发（workflow_dispatch）。
