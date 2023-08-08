华硕 VC66-C2  黑苹果 OpenCore EFI

<img src="ScreenShot/VC66-C2.jpg" alt="image" style="zoom:50%;" />

### [ENGLISH](README.en.md)

#### **[B站视频](https://www.bilibili.com/video/BV1j94y1y7tP)**

[OpenCore 0.9.4](https://github.com/acidanthera/OpenCorePkg)

### macOS

- macOS Monterey 12.x
- macOS Ventura  13.x 

### 硬件

- 芯片组: B460
- Bios 版本: 1603 10/18/2022
- 处理器: 英特尔10代 i7-10700
- 内存: 海力士 16GB DDR4 3200Mhz * 1
- 硬盘: 西数 SN 350 1TB MacOS 
- 硬盘: 西数 Green SATA 240G Windows
- 显卡: 英特超核心显卡630
- 声卡: 瑞昱 ALC897
- 读卡器： 瑞昱 USB 2.0
- 有线网卡:  英特尔 L219V 12
- 无线网卡: 英特尔无线网卡（用转接器可更换94360CS2）
- 电源:  ASUS ADP-150CH B 150W

### BIOS设置

```
   Advanced
        |-- CPU Configuratiion
	         |-- SGX:Disabled
	         |-- VMX:Enabled
	      
	      |-- Onboard Devices Configuration
           |-- Serial Port:Disabled
           
    BOOT
	      |-- Secure Boot
	         |-- OS Type:Other OS
	         
		    |-- Boot Configuration
		       |-- Fast Boot:Disabled
		       |-- POST Delay Time:0 sec
```

### 注意事项

 - 安装成功后必须使用 [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) 或者 [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) 生成你自己的 SMBIOS


### 联系我们

QQ群: 23304408

![image](ScreenShot/QRCode.png)



### 常用工具

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) AKA `OCAT`.
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) AKA `OCC`.
- [gibMacOS](https://github.com/corpnewt/gibMacOS) Build your own MacOS image.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.