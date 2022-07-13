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

### 创建用户名

```shell
useradd jack
```

创建了一个jack的用户(“jack”是用户名)

> 1. 当创建用户成功后，会自动创建和用户名的家目录。
> 2. 也可以通过useradd -d 指定目录（新的用户名，给新创建的用户指定家目录）

```shell
useradd -d /home/test king
```

### 设置密码

```shell
passwd jack #为jack用户设置密码
```

jack指的是用名，为jack用户设置密码。

> 注意一定要输入用户名不然为root 设置密码

### 删除用户

```shell
userdel jack #会保留家目录
userdel -r jack #删除用户及用户主目录
```

jack 是用户名；（会保留家目录）

建议保留用户名、如果你不知道要不要删除，建议保留。

## 查看用户信息

```shell
id jack #jack是用户名
```

## 切换用户

```shell
su - jack #jack是用户名
```

> 1. 从权限高的用户切换到权限低的用户，不需要输入密码，反之需要。
> 2. 当需要返因到原来用户时，使用exit/logout指令。

## 查看当前用户信息

```shell
who am i #查看当前用户信息（登录用户）
```

## 用户组（权限）

```shell

```
