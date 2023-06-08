<h1 align="center">
  <br>
  <img src="https://s1.ax1x.com/2023/06/07/pCFC7dK.png"/></a>
  <br>
  XPVPer
  <br>
</h1>
<h2 align="center">一个专注于美观和PVP的Minecraft整合包</h2>

# XPVPer是什么

XPVPer是一个基于Minecraft Java Edition 1.8.9，Forge，LabyMOD制作的整合包

**注意！！！XPVPer不是Minecraft客户端，更不会成为Minecraft客户端**

# 有什么亮点

*注：以下内容皆以原版作为比较*

## 更加美观的UI

[![pCFLKqe.png](https://s1.ax1x.com/2023/06/07/pCFLKqe.png)](https://imgse.com/i/pCFLKqe)

*左侧为XPVPer右侧为原版Minecraft*

[![pCFXaNj.png](https://s1.ax1x.com/2023/06/07/pCFXaNj.png)](https://imgse.com/i/pCFXaNj)

使用FancyMenu，Blur，LabyMOD等MOD实现。

## 高度的可自定义性

作者不封死包括FancyMenu的配置栏 ~~（虽然真的很丑）~~ ，UI资源包在内的所有自定义项，给用户完全的界面自由。

[![pCFX5gx.png](https://s1.ax1x.com/2023/06/07/pCFX5gx.png)](https://imgse.com/i/pCFX5gx)

[![pCFXO5d.png](https://s1.ax1x.com/2023/06/07/pCFXO5d.png)](https://imgse.com/i/pCFXO5d)

## 还有更多等待挖掘。。。

# 如何安装使用

1. MCBBS整合包格式安装。含有HMCL的压缩包安装。
   参照 [Releases](https://github.com/BlockHaity/XPVPer/releases) 给出的教程即可。

2. 命令行安装
   参照 [Runner分支](https://github.com/BlockHaity/XPVPer/tree/Runner) 进行操作即可

# 如何为此项目做贡献

## 发现Bug

发现Bug后在 [Discussions](https://github.com/BlockHaity/XPVPer/discussions) 内进行发帖讨论，获得解决方案后提交issuse。

## 提出建议

在 [Discussions](https://github.com/BlockHaity/XPVPer/discussions) 内提出你的建议，探讨出解决方案后提交Issuse

## 直接动手改代码（PR）

在根目录新建一个 `PR.md` 用来描述你做的改动和实现的功能，后提交PR

## 为什么采用先讨论得到方案后再提交issuse的方式

作者是一名学生，没有太多时间来探讨解决方案，并且作者不太会Java等语言。这样做就可以提升此项目修复Bug的速度。

# 已知Bug

## 在进入 **单人游戏** 或 **多人游戏** 界面后调整窗口大小会导致界面错位的问题。

影响评级：高

是否可以解决：否

原因：该Bug是由FancyMenu所导致的，而适用于Minecraft 1.8.9 Forge的FancyMenu已经停更。无法通过除改源代码的方法修复。

治标不治本的方案：先最大化窗口再进入 **单人游戏** 或 **多人游戏** 界面，在后续使用中尽量避免拉伸窗口。