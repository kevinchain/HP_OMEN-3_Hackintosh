# Hackintosh EFI for HP OMEN 3/3Prime
## Instruction 说明
* 此EFI适用于暗影3标准版和电竞版（主板型号HP 838F）
* 本人没有实机，完全是自愿为他人制作的，所有的测试和反馈均通过持有该机型的机友进行
* 本EFI即将不再同步更新，完整EFI已经合并到[shimakazechan的暗影3EFI](https://github.com/shimakazechan/OMEN-by-HP-3-Hackintosh)项目中
* 此EFI只提供CLOVER和OpenCore下的config.plist、电池补丁、USB定制文件等一些差异文件，因为其它部分与暗影精灵2Pro基本相同
* ~~具体的运行状况见我的[暗影精灵2Pro黑苹果EFI](https://github.com/XStar-Dev/HP_OMEN-2Pro_Hackintosh)项目说明~~

## Issues 存在的问题
* 由于暗影精灵的BIOS问题，电池可能在长时间睡眠或反复充放电后出现短暂的异常，常表现为百分比不发生变化，如果是第一次进，请务必断电长按电源键15S并在开机后先进win再进mac，之后基本就正常了
* 如果你使用的是DW1820A无线网卡，蓝牙部分可能在冷启动mac时无法上传固件而导致开机卡死或者直接崩溃，目前仍未找到合适的解决方案
* TypeC转HDMI或DP的输出问题，需要定制核显端口，我没有实体机无法测试，请移步上述所提到的项目

## Thanks 
* 感谢 黑果小兵、Xjn、宪武等提供的教程和技术支持
* 感谢 acidanthera 的团队为黑苹果技术做出的贡献
