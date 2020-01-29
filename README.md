# HP_OMEN-3_Hackintosh
## Instruction 说明
* 此EFI适用于暗影3标准版和电竞版，无论你是i5还是i7
* 此EFI只提供CLOVER和OpenCore下的config.plist、电池补丁和USB定制文件等一些差异文件，因为其它部分与暗影精灵2Pro完全相同
* 具体的运行状况见我的[暗影精灵2Pro黑苹果EFI](https://github.com/XStar-Dev/HP_OMEN-2Pro_Hackintosh)项目说明

## Issues 存在的问题
* 如果反复进行放电再充电到满电（一般人不会这么做），最后可能出现电量锁在100%不再变化，此为暗影精灵通病，原因来自ACPI中的代码，尚未找到完美的解决方案
* 如果你使用的是DW1820A无线网卡，蓝牙部分可能在冷启动mac时无法上传固件而导致开机卡死或者直接崩溃，目前仍未找到合适的解决方案

## 如果你有发现任何新问题，请提交issue，我将跟进修复
* 感谢 黑果小兵、Xjn、宪武等提供的教程和技术支持
* 感谢 acidanthera 的团队为黑苹果技术做出的贡献
