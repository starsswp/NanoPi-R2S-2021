本仓库fork DHDAXCW/NanoPi-R2S-2021 修改了部分配置，仅供自己使用

# 中文简体 | [English](https://github.com/starsswp/NanoPi-R2S-2021/blob/main/EngLish.md)
# NanoPi-R2S-2021 每天自动更新插件和内核版本。
## 👉使用本固件前，请严格遵守国家互联网使用相关法律规定,不要违反国家法律规定！👈
## 强烈推荐三星TF卡\海康TF卡。哪怕是很难刷上的固件，只有三星刷上可以开机。
这一个月我没电脑都在讨乞（求电脑中~）。。。 
### 默认编译 
- 用户名：root 密码：password 管理IP：192.168.1.1
- x86_64固件下载 https://github.com/starsswp/lede/releases
### - beta：高大全
### - stable：稳定精简
### - WANLAN：互换 高大全

## 提示
 - 我的固件加了动态超频，不管热不热这是取决后台运行程序在跑什么。
 - 感觉很热  就加风扇，推荐 风扇6cm×6cm，薄1cm，usb也行 或者端子线zh1.5

### 更新日志 8.12
- 新增cpu控制器，方便调整频率
- 新增对r2s超频至1.6GHz  准备加风扇吧！
- 更改内核对低速TF卡的优化支持
- 修复passwall全协议缺失问题等
- 修复asswall在Simple-Obfs的编译问题。
- 其他编译流程修复和优化。
