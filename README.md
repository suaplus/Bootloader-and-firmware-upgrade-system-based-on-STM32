# Bootloader-and-firmware-upgrade-system-based-on-STM32
针对STM32设计Bootloader、恢复出厂程序与应用程序的三分区固件架构，实现上电启动判定、程序跳转、串口固件更新及多链路分片下载，形成"下载、外部Flash暂存 、B 区搬运 、A区运行"的升级闭环。
