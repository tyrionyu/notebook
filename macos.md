# Mac OS

## 输入法

1. 翻页选词，在输入文字时，可以用小反括号键选“【”、“】”
2. 混合输入，按`shift`可以输入大写字母；按`option`可以输入数字；
3. 拆字输入，如输入（三个水水水）按`shift+空格`；
4. 标注声调，系统偏号设置->键盘->输入法->"英文"-“ABC（扩展）”
`option+AEV~`代表四个音调。再输入元字母。
5. 拼音间隔，如输入（西安，xi`"`an）就可以了。（余额宝yu`"`e`"`b）；
6. Emoji，`command+control+空格`

## 文件管理

## 声音

有时候 Mac 从睡眠状态恢复之后没有声音，这是 Mac OS X 系统的一个 Bug。这是因为 Mac OS X 的核心音频守护进程「coreaudiod」出了问题，虽然简单的重启电脑就能解决，但是如果此时开启了很多程序后者有其他情况不想重启电脑的话，可以按照下面的方法解决此问题。
操作步骤：
1、在 Mac 中打开活动监视器（在 Finder 的「应用程序」中搜索「活动监视器」可以找到）。
2、在「活动监视器」窗口右上角的搜索框里输入「audio」，此时可以搜索到「coreaudiod」进程。
3、选中「coreaudiod」进程，点击「活动监视器」窗口左上角的「退出进程」按钮，在弹出的对话框中点击「退出」。
4、「coreaudiod」进程退出后会自动重启，这时声音就恢复了。

## 切换到root用户

命令：sudo su
清除：clear
node -v `#查看node版本`
npm -v `#查看npm版本`
cnpm -v `#查看cnpm版`

pwd `#查看当前所在位置`
mkdir blog `#新建blog文件夹`
cd blog/ `#进入文件夹`
ls -l `#查看生成的文件`
vim hello-world.md `#打开编辑hello-world文件`

## 软件推荐

- Cheatsheet（快捷键提示工具）
- Snap(过Snap快捷键快速切换应用)
- Fliqlo(时间屏保)
- Snip（简单高效的截图工具）
- Tickeys(模拟机械键盘音效)
- Aria2GUI(下载软件)
- 欧陆词典
- Skim/PDF Expert
- typora(markdown编辑器)
- Itsycal(在任务栏上可以看日历)
- keka(压缩软件)

## Mac 电脑浏览器字体显示异常解决方案

前言：突然发现浏览器中部分字体有问题。例子：mac 电脑Safari浏览器中某些页面的文字有夹杂的书法字体。解决方案：打开「字体册」，选择菜单栏「文件」中的「恢复标准字体」。

## Homebrew

### 安装应用

`brew install 应用名`

### 应用Homebrew Cask 安装 Mac App

- `brew cask install atom`
- `brew cask install 应用名称`
- `brew cask install <甲应用名称> <乙应用名称> <丙应用名称>`

### 搜索应用

- `brew cask search 应用名` 列出所有可以被安装的软件，当然你也可以直接前往上文提供的 Homebrew Cask 搜索。
- `brew cask search google` 这里是查找所有与 google 有关的软件，google 关键词可以自行替换
- `brew cask info 软件名` 查找相关软件的信息
- `brew search 应用名`（一般需英文名）

### 更新应用

- `brew outdated` 检查可更新应用有哪些
- `brew upgade` 更新所有的应用
- `brew upgrade 应用名` 更新指定应用

### 清理旧版

- `brew cleanup` 把应用的旧版本和缓存删除
- `brew cleanup 应用名` 指定需要清理缓存的应用
- `brew home 应用名` 访问应用官网
