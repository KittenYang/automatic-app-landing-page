---
layout: page
title: 使用指南
include_in_header: true
---

# 莫斯使用指南

## 问题反馈群

<img src="https://oneyear2.kittenyang.com/charming/charming-intro/charming_wx_qr_code.JPG" style="zoom: 33%;" />

## 新建对话

点击： <kbd>首页</kbd> -> <kbd>对话</kbd> -> <kbd>右下角的聊天按钮</kbd>



## 常用命令

通常从其他地方导入一个现成的模板，很多时候并不知道怎么使用，往往不知道要输入什么。有了==常用命令==，相当于事先帮你包装好了一组常用的命令。你不再需要输出繁琐的一句话，只需点击一下。

比如我拿到一个雅思考官的对话，，通常80%的用户一进来都会让考官随便出个题，现在有了「出题」命令，你只需点击一下，GPT 就会直接给你出一个题，免去你手动输入重复的==给我出一道题==。以此类推，==参考答案==、==评分==，所有常用的命令你都可以包装成一个一个命令。

长按可以把命令带入输入框，方便一些需要输入自定义内容的场景。



<img src="./pics/command.png" alt="IMG_7688" style="zoom:25%;" />





## 使用 Siri

Charming 目前的 Siri 接入是市面上的终极方案。传统的方案都是手写了一大串快捷指令，并且需要传入自己的 API Key，且只能一轮，聊天的内容也会随着对话结束而消失，这样就很不方便。Charming 是和 Siri 深度对接的：

1. `可以继续已有对话或者创建新对话`

2. `可以多轮且携带上下文的对话`

3. `自动保存聊天内容到App`

当然了，仍然是不需要 API Key 的（有 Token 额度的前提下）

另外如果你有 HomePod 或者 Apple Watch，也是可以直接在他们上面对话的。



## Siri 识别不准

Siri 有时候会出现识别不准的情况，这是只能靠苹果修复了。你可以尝试换一个容易识别的短语，如下：

![IMG_772](https://oneyear2.kittenyang.com/charming/charming-intro/pics/siri_change_name.png)





## 提示“检测到代理，请关闭代理”

大概率是因为你在 Token 模式下。目前 Token 已经在服务器做了一次代理了，因此才得以使国内用户无阻碍、顺畅地使用 chatGPT，目前不支持本地再开启代理，所以如果是 Token 模式下，请**`直连`**哦~

