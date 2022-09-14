# Blender 技巧

## 视图

`1`正交前视图；`3`正交右视图；`7`正交顶视图
`command+1`后视图；`command+3`左视图；`command+7`底视图；

`9`反转视图；

`0`进入摄影机视图

`5`正交视图/透视图切换

`.`对像最大化显示

`+`、`-`放大缩小视图

`/`、`\`局部视图，只显示选中的物体

## 默认打开一个文件会加载用户界面

打开一个新的文件不想用他的窗口设置，可以按`N`在右侧不勾选`加载用户界面`即可。
![配置文件](blender-tips.assets/ui-jm.png)

## 配置文件

在blender 的安装目录下面，找到版本号，在文件夹下新建一个`config`的文件，配置信息会存储到这个文件夹下面。
![配置文件](blender-tips.assets/config.png)

## 全局与局部坐标

`,` 坐标切换

## 开启吸附

`shift+tab`开启吸附

临时开启，按`ctrl`;

投影至自身，勾选后顶点可以对齐到物体自身的顶点上面

![投影至自身](blender-tips.assets/xifu.png)

## 衰减编辑

`o`

## 游标与选中吸附对齐

`shift+S`

`shift+C` 游标回到世界坐标

`shift+右键拖动` 快速移动游标

![投影至自身](blender-tips.assets/ybdq.png)

> 选中项到游标（保持偏移），如果选多个物体对齐到游标保持偏移，它对齐的是两个物体的质中心。

![选中项到游标（保持偏移）](blender-tips.assets/bcpy.png)

## 网格物体的合并与分离

`ctrl+J` 合并（合并后的原点为活动项原点）

`p` 分离（分离后原点为分离物体原点）

`L` 选择相连元素

## 重复执行上一步操作

`shift+R`

## 第一人称观察与手持拍摄

`shift+~`

`wsadqe` 前后左右上下

`shift` 加速

`alt` 减速

`空格` 前进至准星

`alt+o` 平滑关键帧

## 物体隐藏和禁用

`H` 隐藏

`alt+H` 显示隐藏

## 父子级关系

`ctrl+p` 选中多个物体（导航面板中按住shift,往父极上拖）

`alt+p` 清空父级（导航面板中按住shift,往外拖）

## 物体镜像变换

`ctrl+M`镜像变换,再输入x,y,z(按中键也可以)

## 网格建模

`1,2,3`点线面切换

`shift+1/2/3` 多模式加/减选

## 工具栏调大小

1. 将鼠标移动工具栏上，按键盘上的`+、-`可对工具栏上的UI放大/缩小。
2. 向右拖动工具拖动边缘，可依次并排工具栏，有名称工具栏

## 挤出到选区

![挤出](blender-tips.assets/jc.png)

`E` 挤出（单个面默认沿法向、多个面默认沿质心法向，可按XYZ直接切换轴向移动，也可以按`shift+xyz`锁定轴向也可以进入对应的视图进行挤出）

> 挤出并移动导致重叠点问题。1.撤销取消（`ctrl+Z`），不要使用右键。2.按距离合并选中点（按`m`）

`shift+z`线框模式

`alt+z` 透显模式

点、与线也可以用挤出

`ctrl+右键`

## 沿法向挤出和挤出各个面

> 面有正反，蓝色为正，红色为反。正法向位于正面。

沿法向挤出(均等偏移)

![均等偏移](blender-tips.assets/jdpy.png)

`alt+E`编辑模式下，即可弹出全部和挤出相关的功能。

## 重复挤出新方法

老方法（先执行一次挤出，然后再按`shift+R`,重复上一步操作。

新方法（选择挤出对像，`alt+e`使用重复挤出功能，注意偏移量设置）

## 内插面工具

`I` 内插面工具

深度（在使用的同时，按`ctrl`+左键上下拖动）

`o` 外插

`b` 边界

`i` 分离

## 边线倒角与顶点倒角

![倒角](blender-tips.assets/dj.png)

![偏移量、深度、宽度](blender-tips.assets/dj-py-sd-kd.png)

`ctrl+B` 边线倒角(1.鼠标中键调整分段数；2.按`S`移动鼠标也可以增加段数)；

`ctrl+shift+b`顶点倒角

`a` 调整倒角宽度

`p` 形状轮廓，移动鼠标可以凸起来，或凹下去(0.25,0.25的调整)

## 倒角材质编号

![倒角材质编号](blender-tips.assets/dj-czbh.png)

材质编号（从上到下为0、1、2...依次递增）

## 倒角硬化法向

![倒角法向](blender-tips.assets/dy-fx.png)

![倒角法向](blender-tips.assets/dj-yhfx.png)

![倒角外斜接、内部](blender-tips.assets/dj-wxj-nb.png)

> 1.物体模式避免不均等缩放；2.尽量编辑模式调整形态比例；3.应用变换自救（ctrl+A）

![顶点倒角之球形化](blender-tips.assets/dj-dddj.png)

## 循环切割

`ALT+左键`选择循环边（开启三键模拟的双击）

`CTRL+ALT+左键`选择并排边（开启三键模拟的按住ctrl+双击）

`按住ctrl` 选择最短路径（选择首尾边）

![循环切割](blender-tips.assets/xhqg.png)

`CTRL+R` 循环切割（切割次数`滚轮`;`CTRL`吸附；`shift`微调；限定`C`或`ALT`临时切换；）

![切割均匀](blender-tips.assets/qg-jy.png)

## 切割与切分

`K` 切割

## 多边形建形工具

`shift+9` 多边形建形

## 旋绕和旋绕复制

![旋绕](blender-tips.assets/xr.png)

记得开启面朝向。

![旋绕管道](blender-tips.assets/xr-gd.png)

![旋绕副本](blender-tips.assets/xr-fb.png)

## 平滑与随机化工具

![平滑](blender-tips.assets/ph.png)

`q` 打开收藏夹

![平滑](blender-tips.assets/py-xg.png)

![随机](blender-tips.assets/sj.png)

## 顶点与线线滑移

`G`边线/单顶点滑移（G+G）

`shift+V` 多点顶点滑移

> 滑动过程中按住`ctrl`或`shift` 可实现精准偏移或微调。
> 另外在滑移过程不是自己相样的方向可以按`F`转换（参数中“均匀”/翻转）

![滑移](blender-tips.assets/hy.png)

右上角有一个合并顶点开光

![滑移](blender-tips.assets/hy-uv.png)

打开“校正UV”贴图会同步进行更改。

## 法向缩放与推拉

`alt+左键` 循环面选择（编辑模式>面模式）

`alt+S` 法向缩放

推拉，等距离（使用推拉所有对象从原位置偏移相同距离。）

## 切变

切变滑块垂直轴向，结合轴颜色找到xyz(红色X,绿色Y，蓝色Z)

## 球形化

`alt+shift+s` 球形化

## 断离区域与断离边线

`v` 断离区域(注意右键取消的是移动，当心重叠点，要再按ctrl+z,撤销一步)

`alt+d` 断离边线（断离后可开启滑移功能）

## 选择

`a` 全选

`alt+a`/`aa` 取消选择

`b` 框选

`c` 刷选

`shift+G`选择相似，点、线、面、在不同的模式下会有不同的显示功能
