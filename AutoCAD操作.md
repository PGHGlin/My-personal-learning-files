# AutoCAD

## 一、快捷键的使用

> **注意**：单纯字母意思是在英文输入下先输入字母，然后回车/空格确定（输入完字母会有提示）再执行
>
> 标准术语应该叫***左手键***（maybe

### <1>基本快捷键（辅助性）

1. $F7$——显示/隐藏栅格（整个界面背后的网格）

2. $ESC$——命令取消

3. CAD中，很多时候$space$键能代替回车起到确定的作用，同时还有***重复上次命令***（经常使用很方便）的作用。

4. 在英文输入状态下，鼠标为默认进去的状态（没有进行其他操作），键盘输入$op$按下$space$即可进入选项菜单，进行操作。

5. $F9$——捕捉栅格模式开启/关闭

6. $shift$+滚轮可以旋转到三维视角查看图形

7. $F8$——正交限制光标，开启后只能画出水平或~~树枝~~竖直的线

8. $F10$——极轴追踪

   ![1662817163986](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662817163986.png?raw=true)

   右键这个按钮可以调整追踪的最小单位值

   ![1662817203263](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662817203263.png?raw=true)

9. $F11$——对象捕捉追踪，即常见的几何关系的提示，垂直、重合、平行等都会提示，默认是开，使用时再次确认一下

### <2>输入打开菜单型

1. $OS$英文输入状态下输入即可打开草图设置的菜单

![1662860937433](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662860937433.png?raw=true)

2. $CTRL+1$——特性编辑，会弹出一个菜单可以进行一些属性的改变

   ![1662970227460](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662970227460.png?raw=true)

3. $B$——创建块(block)，选择后

   ![1662965572575](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662965572575.png?raw=true)

   先输入名称，之后点击拾取点，选择块的基点，之后再点选择对象，把要创建成块的图形框选，再按下空格会回到这个菜单，确定即可完成创建块。创建块的目的就是类似与直线和多段线的关系，块就作为一个整体可以移动或者其他操作。$X$是可以完成分解块的操作的。

4. $H$——填充(hatch)

   ![1662966306185](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662966306185.png?raw=true)

   ![1662966319729](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662966319729.png?raw=true)

5. $LA$——图层(layer)，![1662966539472](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662966539472.png?raw=true)

6. $D$——标注设置(dimstyle)。点击修改会出现第二幅图的设置![1662969986912](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662969986912.png?raw=true)

   ![1662969996643](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662969996643.png?raw=true)

### <3>操作型

1. $X$——分解命令，比如一个矩形，选中后按下$X$，会分解成四条直线

2. $O$——偏移命令。**偏移**操作：按下o，空格后（或者直接点击命令![1662886450748](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662886450748.png?raw=true)），之后，方法一：首先输入偏移距离，空格确定后，鼠标点击要偏移的“图形”，然后鼠标放在”图形“两侧会自动提示偏移后的图形，根据需要再次点击鼠标确定偏移；方法二：可以在任意地方(意思是不用非得在要偏移的图形上)点两个点，这两个点的距离就是偏移的距离，剩下的操作和前面的一样了

3. $E$——删除。和$delete$作用一样

4. $CO$——复制(copy)，启用后选择起始终止点即可完成复制。

5. $MI$——镜像(mirror)，选择目标完成后按下确定，然后确定镜像的起始点和终点，即可完成镜像，完成镜像后会提示是否保留源文件，保留会留下之前的图形，反之不保留。

6. $M$——移动，选择移动好的图形，点击确定，之后确定起始结束两个点，即可完成移动。

7. $RO$——旋转，选择好旋转的图形，确定，之后确定基点即旋转中心点，之后鼠标可控制旋转，也可以***极轴追踪*** 喔

8. $SC$——缩放(scale)，选择好缩放的图形，确定，之后确定基点，鼠标拉动可以改变缩放程度，或者输入缩放比例

9. $DI$——测量长度快捷键

10. $S$——拉伸(scratch)，***只有选择两条线的交点会被拉伸移动*** (一般用右框全选，注意此时同样选择到交点才有用，如果边在，但是交点不在同样不行，可以参照这里[👉点我👈]( [3.3 拉伸实例（二）_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1Q5411S7p9?p=20&spm_id_from=pageDriver&vd_source=77cd21a4f94b79d81644448ac1a6da1e) )）

11. $EX$——延伸(extend)，输入确定后，第一个选择要延伸到的地方，确定，再选择要延伸的图形确定即可完成

12. $TR$——修剪(trim)，和拉伸延伸的操作差不多，先确定要剪到的边，再选择要剪的图形。**注意**：剪切的线必须穿过要剪切到的边，否则会出现下面这个提示，也就***意味着裁了一边，另一边就不能再被裁了*** ）

    ![1662948682875](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662948682875.png?raw=true)

13. $BR$——打断(break)，可将一条直线打断成两条，或者切成两条直线

14. $J$——合并(join)，将多条线合并

15. $LTS$——全局线性比例快捷键，开启后输入一个线性比例值即可改变所有的(这个一般用在画虚线)

16. 

### <4>绘图型

$REC$——矩形绘制快捷键。

$L$——直线绘制快捷键

$C$——圆绘制快捷键

$POL$——多边形绘制快捷键

$A$——圆弧绘制快捷键

$SPL$——曲线绘制快捷键

$CHA$——倒角(chamfer)，即使没有相交，直接点击两条线就可以完成倒角

$F$——圆角(fillet)，**注意**：默认时圆角半径是0，和倒角是一样的，需要自己调一下

$DT$——单行文字。$T$——多行文字。

$DED$——标注(dimedit)；$DAL$——对齐标注；$DAR$——弧长标注；$DRA$——半径标注；$DDI$——直径标注；$QDIM$——快速标注；$DBA$——基线标注(需要有一个基线)；$DCO$——连续标注(需要有一个基线)；

$AR$——阵列(arry)。

![1662968546296](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662968546296.png?raw=true)

创建阵列默认是矩形，注意到左上角、右下角有三角形，可以通过拖动或者输入想要的行数列数；右上角的功能也容易想到是直接同时改变行和列；注意到原图形上面和右面也有三角形，这里的三角形是改变这两个方向的间距的。

环形阵列：

![1662968971776](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662968971776.png?raw=true)

中心的方块用来移动，原图形的方块用来改变和中心的距离，三角标识用来改变角度，同样可以在下方找到具体的操作栏![1662969042421](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662969042421.png?raw=true)

路径阵列(新版本才有)：

首先需要画一条曲线，方块用来改变行数，三角用来改变距离。

![1662969350813](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662969350813.png?raw=true)

## 二、使用技巧

1. ![1662707156820](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662812474008.png?raw=true)

   在这个选项下选择“将当前工作空间另存为”即可把更改的界面样式保存起来，可以联系到solid works中也有类似的另存一个模板的操作。
   
2. 捕捉栅格模式记得关闭，当放大时软件会卡顿，因为鼠标移动时会固定在栅格点（跟立创EDA一样），所以放大时会感觉鼠标一卡一卡的，快捷键$F9$开启关闭。

3. 框选的技巧，只用鼠标左键点两次，确定起始和结束端点绘制选择矩形，不是**长按**，AutoCAD从左框选目标必修覆盖整个目标，但是从右到左只要框选到，目标的一部分，目标都会被选中，这个操作和立创EDA中的框选是一样的，被选择的部分会高亮显示。

4. 双击鼠标滚轮可以使缩放的图形直接以最大化形式出现在面板中。***solid works也有这个功能，在CAD里面学到才去试的！***

5. ![1662861102903](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662861102903.png?raw=true)

   点击后进入对象捕捉设置界面，全选可以提高使用体验（推荐全部选择），即输入$os$之后弹出来的设置界面

6. ![1662861575615](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662861575615.png?raw=true)

   此处勾选上选多条线需要按$shift$，不勾选直接点就会多选，不勾选时按$shift$是减选。框选后也可以用$shift$再框进行减选。

7. 旋转时，有时会需要高级一点的误差不会太大的可以使用参照旋转

   ![1662902720721](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662902720721.png?raw=true)

   选择后需要确定旋转的方向，以矩形贴近直线为例

   ![1662902905023](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662902905023.png?raw=true)

   之后第三点就点击直线上一点就好了

   ![1662902952697](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662902952697.png?raw=true)

8. 如果想要一条直线和一个圆弧相交，首先肯定想到的是用倒角，但是

   ![1662964606848](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662964606848.png?raw=true)

   这tm是选择直线，所以圆弧是选择不了的，这时候圆角就起到作用了，将圆角半径设成0即可完成

   ![1662964693979](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662964693979.png?raw=true)

   这里是选择对象，所以可以选圆弧

## 三、常识性知识

1. AutoCAD保存文件的后缀是.dwg,注意保存文件的时间，低版本是打不开高版本的文件的。

   ![1662812474008](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662812474008.png?raw=true)可以在面板输入op进入菜单选项进行这里的修改从而使老师或者其他人用的低版本可以打开文件

2. 放大缩小是以鼠标所在位置放缩~~**小心别放大着找不到东西去哪咯！**~~

3. CAD的默认单位是$mm$（毫米）

4. 正交和极轴追踪是冲突的两个功能，一个开另一个就会被关闭

5. 直接画一个图形（矩形、圆形等）是一个整体（一条线），和直线围出来的不一样。

6. 一条直线两个端点选中可以进行拉伸的操作，选中中点可以移动直线的位置。选中两条直线的交点也有讲究，如果只是选了一条线，那么会拉伸一条线，同时选两条会拉伸两条线。矩形等图形顶点会拉伸成不规则形状，边中点会拉伸成平行四边形（矩形情况下），也可以理解为移动那条边。

7. 多段线和直线的区别：

   1. 多段线是整体，直线是分开的。

   2. 多段线有更多的功能，直线没有（上为多段线，下为直线，可以清楚看到区别，可输入后面字母，也可点击）

      ![1662863078868](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662863078868.png?raw=true)

      ![1662863097814](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662863097814.png?raw=true)

      （PS：多段线画圆弧默认圆弧是相切的)

   3. 分解命令会让多段线变成直线，所以如果之前设置了线宽，分解后将不再有线宽这个属性.
   
8. 画矩形时，会出现这样的菜单![1662898733653](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662898733653.png?raw=true)

   后面的这两个框是***第二个点相当于第一个点的坐标***，输入完第一个(X相对值)之后按下$TAB$或者 $,$  键即可输入下一个值.

9. ![1662901068566](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662901068566.png?raw=true)![1662901081340](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662901081340.png?raw=true)![1662901569914](https://github.com/PGHGlin/My-personal-learning-files/blob/main/Photo/1662901569914.png?raw=true)

   画矩形时可以画倒角矩形，这两个距离是倒角的两条边。

10. 画圆时有切点画圆，确定两个切点后，会弹出一个半径，要求自己输入的半径大于这个值即可

## 四、个人看法

其实操作几次，就可以发现这个软件的操作风格是比较繁琐的（个人看法），原因可能在于需要反复的按空格或者回车。快捷键没有solid works那么好用，毕竟一个鼠标就可以把直线，圆，标注都召唤出来，而这里面的***左手键***按完之后需要空格或者回车去确定一次，就会复杂一些。再说说移动复制之类这种的操作，风格大体是先把功能召唤出来，第一次需要选择要操作的图形，因为这里面选择可以直接鼠标多选，所以需要按下确定完成图形的选取，之后便是跟据选的操作进行特有的命令，之后需要再点一次空格，之后是选择操作之后的位置，个人认为比较离谱吧，因为即使是移动一个物体也不是简单的选择一个位置，而是需要选择起始点和结束点，也没太搞懂具体是个怎么起始结束的，总之能看到效果就行了吧。



​	















