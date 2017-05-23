---
layout: post
title:  "如何从EXCEL中导入测验/调查问题？"
date:   2017-05-23 19:09:06 +0800
lastDate: 2017-05-23 19:09:06 +0800
category: "importAndExport"
hot: true
tags: 导入 Excel Txt 测验 调查 问题
authors: 
 - KeJun 
helpers: 
storyline: 
   v1: false
   v2: true
   v3: true
   v360: true
---

{% include tips.html content="你可以将问题导入到 Storyline 中，这样可以极大的节省开发时间。" %}


## 将你的问题与答案填入Excel中

* 格式示范：![格式示范](https://ooo.0o0.ooo/2017/05/23/59241b3e414d7.png)
* 具体格式：![具体格式](https://ooo.0o0.ooo/2017/05/23/59241b3e414c9.png)

{% include note.html content="Storyline 只会导入第一个工作表（Sheet1）的问题。其余的工作表会被忽略。" %}
{% include note.html content="导入后会格式化你的Excel（斜体字，字体大小，超链接等将被删除）。" %}
{% include tips.html content="两个杠（//）后面的文字是一个注释。Sl在导入过程中会自动忽略。" %}

## 将Excel导入到Storyline中

1. 打开现有或创建一个`.story`文件。
2. 你可以选择以下任意一种方式导入：
    * 到Storyline2功能区**文件**选项卡，选择**导入**，并**从文件导入问题**（文件-导入-从文件导入问题）。
    * 到Storyline2功能区**主页**选项卡，单击**新建幻灯片**，选择**导入**，并**从文件导入问题**（主页-新建幻灯片-导入-从文件导入问题）。
    * 到Storyline2功能区**插入**选项卡，单击**新建幻灯片**，选择**导入**，并**从文件导入问题**（插入-新建幻灯片-导入-从文件导入问题）。
3. 浏览并选择你要导入的Excel，然后单击打开。
4. 如果格式无误Storyline会显示Excel文件中的所有问题。
5. 选择你要导入的问题，单击导入即可。

{% include warn.html content="如果你的工作簿中有错误，sl会列出它们。你可以点击继续，导入没有错误的问题，也可以点击取消，纠正工作簿中的错误后再将其导入。" %}

## 参考

* [如何从Excel中导入问题？Excel中数据的格式有无要求？](https://xuefeng.cloudkz.cn/topic/77/)
* [Storyline 2: Importing Questions](https://community.articulate.com/articles/importing-questions-into-articulate-storyline-2)
* [视频教程](http://7xl9dn.com1.z0.glb.clouddn.com/%E9%97%AE%E9%A2%981.mp4)
