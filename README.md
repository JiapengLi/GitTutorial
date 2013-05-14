# Github and Git Tutorial #
介绍使用Github账户+mysysgit+TortoiseGit进行代码管理。

## 安装 ##

### 安装mysysgit ###

下载地址：[mysysgit](http://code.google.com/p/msysgit/downloads/list?q=full+installer+official+git)。下面的截图来自[Git-1.8.1.2-preview20130201.exe](http://code.google.com/p/msysgit/downloads/detail?name=Git-1.8.1.2-preview20130201.exe&can=2&q=full+installer+official+git) 。

![mysysgit-address](./image/mysysgit_download_url.jpg)

安装过程：
0.启动

![mysysgit-0](./image/mysysgit_install0.jpg)

1.默认

![mysysgit-1](./image/mysysgit_install1.jpg)

2.默认

![mysysgit-2](./image/mysysgit_install2.jpg)

3.默认

![mysysgit-3](./image/mysysgit_install3.jpg)

4.默认

![mysysgit-2](./image/mysysgit_install4.jpg)

5.这步骤很重要，选中 **Checkout as-is** 。这样使用 **git clone** 时，git不会擅自改动所获文件的换行符。

![mysysgit-1](./image/mysysgit_install5.jpg)

6.默认

![mysysgit-2](./image/mysysgit_install6.jpg)

7.安装完成。

![mysysgit-1](./image/mysysgit_install7.jpg)

###安装Tortoise###
下载地址：[TortoiseGit](http://code.google.com/p/tortoisegit/wiki/Download?tm=2) 。下面的截图来自[TortoiseGit 1.8.3.0 - 32-bit](http://tortoisegit.googlecode.com/files/TortoiseGit-1.8.3.0-32bit.msi) 。

![Tortoisegit-address](./image/tortoisegit_download_url.jpg)

0.启动

![tortoise-install0](./image/tortoisegit_install0.jpg)

1.默认-Next

![tortoise-install1](./image/tortoisegit_install1.jpg)

2.默认-Next

![tortoise-install2](./image/tortoisegit_install2.jpg)

3.默认-Next

![tortoise-install3](./image/tortoisegit_install3.jpg)

4.默认-Install

![tortoise-install4](./image/tortoisegit_install4.jpg)

5.完成

![tortoise-install5](./image/tortoisegit_install5.jpg)

## 设置 ##

### TortoiseGit 设置 ###

开始->所有程序->TortoiseGit->Settinigs，填入 **Name** 和 **Email** 信息。

这里需要说明，每次通过GIT提交文件时都需要 **Name** & **Email** 信息。这个信息会连同 **Commit Comment** 显示在Github的Commit记录里。

![tortoise-settings](./image/tortoisegit_settings.jpg)

提交之后可以在仓库 **Commit** 记录中体现出来

![git-user-info](./image/git_user_name.jpg)

***为简单起见其他所有的项目我们都不做修改，可以在使用中逐渐摸索。***