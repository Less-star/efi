--------[ 概览 ]----------------------------------------------------------------------------------

  电脑型号            HP ENVY Notebook 笔记本电脑
  操作系统            Windows 10 专业版 64位 ( 4.09.00.0904 )

  处理器              英特尔 Core i5-6200U @ 2.30GHz 双核
  主板                惠普 80DF ( 6th/7th Generation Intel Processor Family I/O - 9D48 笔记本芯片组 )
  主显卡              英特尔 HD Graphics 520 ( 128 MB / 惠普 )
  内存                8 GB ( SK Hynix LPDDR3 1600MHz )
  主硬盘              建兴 L8H-256V2G-HP ( 256 GB / 固态硬盘 )
  显示器              三星 SDC415A ( 13.3 英寸  )
  声卡                瑞昱  @ 英特尔 High Definition Audio 控制器
  网卡                英特尔 Wi-Fi 6 AX1650X 160MHz

--------[ 日志 ]----------------------------------------------------------------------------------

前序

   -----------Wi-Fi蓝牙；正常
   -----------声卡，显卡：正常
   ----------- CPU变频：正常
   -----------SD读卡器：正常
   -----------USB端口：已定制
   -----------鼠标键盘触控板手势：正常
   -----------鼠标仿白设置
   -----------亮度调节，电量显示：正常
   -----------引导windos：正常


更新

2021-01-09:  禁用S3睡眠模式，修复SD睡眠崩溃
2021-01-10:  升级引导至 OC 0.6.5 修复Wi-Fi自驱动 删减无用的ssdt补丁
2021-01-11:  增加仿冒以太网
2021-01-13:  开启OC引导只扫描Mac启动项（支持sast/nvme）
2021-01-16:  定制acpi修补缺失设备（管理小姐姐定制）
2021-01-20:  重新定义ssdt/Kexts注释名
2021-01-20:  修复OC引导 Windows
2021-01-24:  增加OC引导背景
2021-01-27:  移动Windows启动项至oc目录下用于单磁盘boot默认启动项为oc
2021-01-31:  修复睡眠功能，关闭禁用s3，休眠一整天不掉电
