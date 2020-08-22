# FBI

FBI 是一个开源的 3DS 应用管理器.

本仓库为 FBI 的简体中文版本.

原仓库: https://github.com/Steveice10/FBI

# 注意

**请确保系统已安装简体中文字库**

**请确保系统已安装简体中文字库**

**请确保系统已安装简体中文字库**

你可以使用 [SharedFontTool](https://github.com/dnasdw/SharedFontTool) 来临时安装简体中文字库, 也可以使用 [3DS 系统简体中文化补丁](https://tieba.baidu.com/p/6802255931) 直接将简体中文字库写入并汉化系统. 如果你的机器为中国神游版, 可直接使用.

最新版安装包二维码
![QR Code](https://user-images.githubusercontent.com/29033099/90957443-2000d280-e4c0-11ea-99ff-8150a043db72.png)

---

## 特性

* Browse and modify the SD card, TWL photos, TWL sounds, save data, and ext save data.
* Export, import, and erase save data from DS cartridges.
* Export, import, and delete save data secure values.
* Install titles/tickets from a file system, over a local network, or over the Internet with a URL or QR code.
  * Automatically imports title seeds on installation, either from the Internet or the SD card.
* Browse and delete pending titles (downloaded updates, in-progress eShop titles, etc).
* Customize appearance by placing replacements for RomFS resources in "sdmc:/fbi/theme/".

* Only available when run from a CIA, 3DS, or a 3DSX under Luma3DS:
  * Browse and modify CTR NAND, TWL NAND, and system save data.
  * Dump the raw NAND image to the SD card.
  * Launch titles installed to the system.

## 编译

 - 需要 [devkitARM](http://sourceforge.net/projects/devkitpro/files/devkitARM/) 中的 3ds-curl, 3ds-zlib, 3ds-jansson

 - 需要 [buildtools](https://github.com/Steveice10/buildtools)

```
git clone https://github.com/Steveice10/buildtools
make
```

## 感谢

[Steveice10](https://github.com/Steveice10): 提供源码

[Rintim](https://github.com/Rintim): 辅助汉化

>Banner: Originally created by [OctopusRift](http://gbatemp.net/members/octopusrift.356526/), touched up by [Apache Thunder](https://gbatemp.net/members/apache-thunder.105648/), updated for new logo by [PabloMK7](http://gbatemp.net/members/pablomk7.345712/).

>Logo: [PabloMK7](http://gbatemp.net/members/pablomk7.345712/)

>SPI Protocol Information: [TuxSH](https://github.com/TuxSH/) ([TWLSaveTool](https://github.com/TuxSH/TWLSaveTool))
