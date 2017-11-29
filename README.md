# XYXDomeTabBarController
使用Swift编写的轻量的DomeTabBar，凸起按钮可以任意设定一个位置。
<center> ![gif](./ReadMe/aa.gif) </center>

框架一共三个文件，分别是：
- XYXDomeTabBarController 继承自UITabBarController，在这里初始化所有ChildViewController
- XYXDomeTabBar 用来自定义凸起按钮
- XYXShadeView 用来自定义凸起按钮的点击后操作

'''
/// domeIndex 用来制定凸起按钮的位置，从0开始计数
/// 需注意的一点是，本Demo并不对domeIndex进行越界检查，调用时请根据自己添加的chilViewController的个数来确定domeIndex数值
let tabBar = XYXDomeTabBar.init(frame: self.tabBar.frame, domeIndex:0)
'''

domeIndex = 0时：👇
<center> ![domeIndex = 0](./ReadMe/0.png)</center>>

domeIndex = 1时：👇
<center> ![imdomeIndex = 1](./ReadMe/1.png)</center>

domeIndex = 2时：👇
<center> ![domeIndex = 2](./ReadMe/2.png)</center>

domeIndex = 3时：👇
<center> ![domeIndex = 3](./ReadMe/3.png)</center>

domeIndex = 4时：👇
<center> ![domeIndex = 4](./ReadMe/4.png)</center>
