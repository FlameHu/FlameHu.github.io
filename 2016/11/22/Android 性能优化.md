转：http://www.jianshu.com/p/b3b09fa29f65

在Android应用开发过程中，常会出现APP启动慢、界面跳转慢、事件相应慢、滑动和动画卡顿、展现内容慢等性能问题，
对于性能优化，怎么去做，我总结了一下性能优化如何入手，Android性能优化这个系列目前已经完成11篇，涉及到常用
内存优化工具的使用，比如Memory Monitor、MAT、Allaction Tracing、TraceView 等，也涉及到如何提高应用
的启动速度以及页面的渲染速度，还有流畅度的检测。学会这些，基本上可以处理一般的性能问题了。

1. 了解java的内存区域划分、引用、内存泄露以及场景，还有垃圾回收
    http://www.jianshu.com/p/c0e5c13d5ecb
2. 使用Android Studio自带工具Memory Monitor 检测内存泄露
    http://www.jianshu.com/p/ef9081050f5c
3. 另外一种内存泄露的检测工具MAT
    http://www.jianshu.com/p/2d47d1cf5ccf
4. Android渲染机制
    http://www.jianshu.com/p/9ac245657127
5. Allaction Tracing 追踪内存分配
    http://www.jianshu.com/p/d9e426c10581
6. TraceView 是 Android 平台特有的数据采集和分析工具，主要用做热点分析，找出最需要优化的点
    http://www.jianshu.com/p/388c693c1b58
7. StrictMode意思为严格模式，是用来检测程序中违例情况的开发者工具。使用一般是场景是检测主线程中本地磁盘和网络读写等耗时的操作。
注意这个StrictMode是在Anroid2.3以后引入的。严格模式主要检测两大问题，一个是线程策略，即TreadPolicy，另一个是VM策略，即VmPolicy。
    http://www.jianshu.com/p/2ebc9363ea16
8. 如何统计应用的启动时间和性能检查项，并且用TraceView逐个修复
    http://www.jianshu.com/p/a0e242d57360
9. App启动速度优化之启动页设计
    http://www.jianshu.com/p/777fe2f71039
10. 布局优化
    http://www.jianshu.com/p/c0e0cca14162
11. 卡顿分析，正确评测流畅度 
    http://www.jianshu.com/p/d126640eccb1
