---
title: Atom 的炫酷插件 activate-power-mode
date: 2016-04-22 20:00:43
categories:
    - Atom
tags:
    - atom
    - 插件
---
---

# Atom 简介

[Atom][] 是一款免费的编辑器，我一般在写 Web 项目的时候使用。写 Java 项目用 Eclipse， 其他直接用 Notepad++，别问我为什么不用 Sublime。喜欢这款编辑器的主要原因是它的黑色扁平化主题风格非常炫酷，功能也比较强大，缺点就是比较吃内存，启动比较慢( ╯□╰ )。最近使用 Atom 搭建自己的博客【没错，就是现在这个博客】，想到了 [activate-power-mode][] 插件的炫酷效果，于是就体验了一下。下面介绍下详细安装过程。

<!-- more -->

# 安装 activate-power-mode

注意：本文针对 *Windows* 平台，其他平台也类似，自己琢磨吧~

先上图！

![activate-power-mode](activate-power-mode.gif)

## 准备

*   [Atom][]
*   [activate-power-mode][]
*   [Node.js][]

点击上面的三个链接，分别下载下来 Atom、activate-power-mode、Node.js，然后安装 Atom、Node.js。

## 安装插件

解压下载下来的 activate-power-mode zip 包，移动到 `xxx\.atom\packages` 下，比如我的是 `C:\Users\cylong\.atom\packages` ，接下来进入到 `activate-power-mode` 目录下，打开 cmd，输入：

{% code lang:sh %}
    npm install # 安装必要的 module
{% endcode %}

之后重启 Atom ，使用右键选择 `Toggle` 或者 `Ctrl ＋ Alt ＋ O` 就启动插件了，体验炫酷的效果吧！

## 插件设置

刚开始用的时候感觉蛮好玩的，非常爽。然后用了不到一分钟，我就觉得眼睛要瞎了！估计在玩个几分钟就真的瞎了！！果然这个插件只适合玩玩，屏幕震动效果闪瞎我的双眼！要是能够把震动效果删除会不会好一点？于是自己开始找这个插件的设置，果然有！

*   首先点击 Atom 左上角的 `File` 按钮
*   进入到 `Settings`
*   找到 `packages` 设置
*   找到  `activate-power-mode`
*   进入到  `Settings`
*   找到 `Screen Shake - Enable`， 将前面的 √ 去掉

之后就只有颗粒效果啦，现在感觉好多了吧(●'◡'●)。插件设置中还有颗粒大小的设置，自己根据需要修改吧~

# 总结

把屏幕震动效果关掉后感觉好很多了。也一直在用这个效果，感觉还是蛮帅的~如果读者有更好的 Atom 插件或者使用技巧，欢迎留言或者 [联系我][]。最后推荐下自己比较喜欢的编辑器 [Atom][] 吧 (●'◡'●)

---

> 文章标题：<a href='{{ permalink }}' title='{{ title }}' >{{ title }}</a>
> 文章作者：[cylong](http://www.cylong.cc/about/ "cylong")
> 文章链接：<a href='{{ permalink }}' title='{{ title }}' >{{ permalink }}</a>
> 有问题或者建议欢迎在下方评论。欢迎转载、引用，但希望标明出处，感激不尽(●'◡'●)


[Atom]: https://atom.io/ "Atom"
[activate-power-mode]: https://github.com/JoelBesada/activate-power-mode "activate-power-mode"
[Node.js]: http://nodejs.org/ "Node.js"
[联系我]: /about/#联系我