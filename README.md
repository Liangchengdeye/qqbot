# qqbot
## 一、介绍
qqbot 是一个用 python 实现的、基于腾讯 SmartQQ 协议的 QQ 机器人框架，可运行在 Linux 、 Windows 和 Mac OSX 平台下。

你可以通过扩展 qqbot 来实现：

监控、收集 QQ 消息
自动消息推送
聊天机器人
通过 QQ 远程控制你的设备
## 二、安装方法
在 Python 2.7/3.4+ 下使用，用 pip 安装：

pip install qqbot
## 三、 实例
在此例子中，通过判断对方发过来的文字内容进行特定内容回复，同时，为了丰富回复内容，我将QQ自带的大量表情也添加到了规则库当中，
这样对方即使给你发送一些聊天表情，比如笑脸，哭脸，等各种表情，这边都会有所监听，都可做相应回复，因为这个例子就是最简单的测试demo，
所以会监听所有聊天消息，可能会给群里发大量消息，所以，慎用。
