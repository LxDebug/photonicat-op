# PhotoniCat-Openwrt 自动化构建仓库
方案默认引用 Lean 的源码，因为他的 README 影响了我开始学习编译，也就有了这个项目，而且他的源码非常的优秀。
## 硬件列表
- 高通QCA1023 B/G/N/AC (2.4G/5G)
- rk3568
## 刷入方法
> Flash into lede:

>   Run first: dd if=openwrt-xxx.img of=/dev/mmcblk0

>   Then brush the img file to sdcard and insert it,

>   the system will boot from above.

> Note:

>   Since rockchip does not release any code to power up their device, disabled emmc for now until we can remove rkbin.

