---
title: Gitk安装
date: 2018-09-09 20:00:37
tags: Git
     
---


安装 Homebrew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
将以上命令粘贴至终端。

安装完之后想确认下是否安装成功？在命令行输入brew回车试下，如果能显示出Example usage说明安装成功了。
接下来事安装git，通过brew安装最新的git将会自带gitk。在命令行输入这两行命令安装git：

brew update
brew install git
安装完毕后输入

which git
看看git的文件所在地址是

/usr/local/bin/git
试运行下这行命令：
which gitk
看看gitk所在的地址：
/usr/local/bin/gitk

搞定！