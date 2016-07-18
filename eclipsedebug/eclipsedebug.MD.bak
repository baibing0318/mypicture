Eclipse后台调试方法
===================

进入debug模式：
　1、设置断点
　2、启 servers端的debug模式
   3、运行程序，在后台遇到断点时，进入debug调试状态


----------


快捷键
-------------

> **作用域   功能     快捷键 **
> - 全局 单步返回 F7 
> - 全局 单步跳过 F6 
> - 全局 单步跳入 F5 
> - 全局 单步跳入选择 Ctrl+F5 
> - 全局 调试上次启动 F11 
> - 全局 继续 F8 
> - 全局 使用过滤器单步执行 Shift+F5 
> - 全局 添加/去除断点 Ctrl+Shift+B 
> - 全局 显示 Ctrl+D 
> - 全局 运行上次启动 Ctrl+F11 
> - 全局 运行至行 Ctrl+R 
> - 全局 执行 Ctrl+U

说明
-------------

> - Step Into (also F5) 跳入
> - Step Over (also F6) 跳过
> - Step Return (also F7) 执行完当前method，然后return跳出此method
> - step Filter 逐步过滤 一直执行直到遇到未经过滤的位置或断点(设置Filter:window-preferences-java-Debug-step Filtering)
> - resume 重新开始执行debug,一直运行直到遇到breakpoint。
    例如 ：A和B两个断点，debug过程中发现A断点已经无用,去除A断点，运行resume就会跳过A直接到达B断点。
> - hit count 设置执行次数 适合程序中的for循环(设置 breakpoint view-右键hit count)
> - inspect 检查 运算。执行一个表达式显示执行值
> - watch 实时地监视对象、方法或变量的变化
> - 我们常说的断点(breakpoints)是指line breakpoints,除了line breakpoints,还有其他的断点类型：field(watchpoint)breakpoint,method breakpoint ,exception breakpoint.
> - field breakpoint 也叫watchpoint(监视点) 当成员变量被读取或修改时暂挂
> - 添加method breakpoint 进入/离开此方法时暂挂(Run-method breakpoint)
> - 添加Exception breakpoint 捕抓到Execption时暂挂(待续...)
     断电属性
   1.hit count 执行多少次数后暂挂 用于循环
   2.enable condition 遇到符合你输入条件(为ture\改变时)就暂挂
   3.suspend thread 多线程时暂挂此线程
   4.suspend VM 暂挂虚拟机
> - variables 视图里的变量可以改变变量值，在variables 视图选择变量点击右键--change value.一次来进行快速调试。
> - debug 过程中修改了某些code后--〉save&build-->resume-->重新暂挂于断点
> - resume 当debug调试跑出异常时,运行resume,重新从断点开始调试
> - 如果一行有很多方法,
当第一次按F5键就跳入这一行第一个方法,F6一步一步调试,F7跳出这方法.
当第二次按F5键就跳入这一行第二个方法,F6一步一步调试,F7跳出这方法.
以此类推.想进入这一行第几个方法,就按几次F5和F7.

#### <i class="icon-file"></i>配图

查看逻辑结构：
-------------
![image](https://github.com/baibing0318/mypicture/blob/master/eclipsedebug/a1.jpg)
![image](https://github.com/baibing0318/mypicture/blob/master/eclipsedebug/a2.jpg)

条件Debug：
-------------
![image](https://github.com/baibing0318/mypicture/blob/master/eclipsedebug/a3.jpg)
![image](https://github.com/baibing0318/mypicture/blob/master/eclipsedebug/a4.jpg)

异常断点
-------------
![image](https://github.com/baibing0318/mypicture/blob/master/eclipsedebug/a5.jpg)

