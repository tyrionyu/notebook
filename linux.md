# Linux 学习

## 在Linux 世界里，一切皆文件

![文件树](linux.assets/file-tree.png)

`/bin` 最经常使用的命令

`/sbin` 系统管理员管理程序

`/home` 普通用户主目录

`/root` 超级管理权限

`/lib` 动态连接共享库

`/lost+found`

`/etc` 配置文件

`usr` 用户安装的程序

`boot` 启动linux核心文件

`/proc` 虚拟目录

`/src`

`/sys`

`/tmy`

`/dev` 设置管理器

`/mnt` 挂载

`/media` 识别一些设备

`/opt` 安装软件存放的目录

`/usr/local`

`/var`

## 远程登录

1. 远程Xshell
2. 文件-xftp

## vi和vim

vi 文本编辑器

vim 具有程序编辑的能力

三种模式

1. 正常模式
2. 插入模式
    `i/I/o/O/a/A/r/R` 按下全面这些键可以进入编辑模式。（一般是i）

    按`esc`,再输入`：`进入命令行模式

    `：wq`保存并退出

    `q!`强制退出，不保存

    `q`退出

3. 命令行模式

![vim快捷键](linux.assets/linux-vi.png)

![vim快捷键](linux.assets/linux-vi02.png)

![vim快捷键大全-01](linux.assets/vi-vim-cheat-sheet-cn.png)

![vim快捷键大全-02](linux.assets/vi-vim-cheat-sheet.gif)

## 关机&重启命令

`shutdown -h now` 立刻进行关机

`shutdown -h 1` “hello,1分钟后会关机了”

`shutdown -r now` 现在重启动计算机

`halt` 关机

`reboot` 现在重新启动计算机

`sync` 把内存的数据同步到磁盘

## 登录注销

`logout`注销

![注销](linux.assets/logout.png)

## 用户管理

`useradd`