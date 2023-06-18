# B760-12490F-AX200-RX588-OC9.3-VenturaEFI

#### 配置
CPU：i5-12490F  
主板：昂达B760  
显卡：蓝宝石RX588  
网卡/蓝牙：AX200  

#### 定制
1、CPU12代/13代通用，如果CPU和我型号不一样可以修改\EFI\OC\config.plist 【revcpuname】改为你想显示的CPU型号；  
2、网卡/蓝牙（AX200, AX201, AX210, AX211, AX411）都能用；  
3、显卡免驱卡都能使用；  
4、USB已按照昂达B760SD4-ITX-W主板进行定制，主板不同可以删除\EFI\OC\Kexts\USBPorts.kext文件即可；  
5、建议重新生成三码使用，不会可以跳过直接使用。  

#### 主板设置
CPU电源管理 -> CFG锁定 -> 关闭  
CSM配置 -> 关闭  
安全启动 -> 关闭  