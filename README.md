## 效果
![GIF.gif](GIF.gif)
## 简介
使用SVG路径元素实现箭头动画。
## 实现
多个箭头沿着路径运动。以不同的起始位置，并且箭头会随着路径改变方向.
## 思路
计算路径上每一点的切线方向，并相应地旋转箭头。

以下是关键步骤的概述，以确保箭头能够随路径转变方向：

1、获取SVG路径元素的引用，并计算其总长度。

2、使用getPointAtLength方法来获取路径上特定长度的点的位置。

3、计算当前点和下一个点的方向，以此来确定箭头应该旋转的角度。

4、使用setAttribute方法来更新箭头的transform属性，包括平移（translate）和旋转（rotate）。


