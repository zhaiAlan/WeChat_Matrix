# WeChat_Matrix
微信卡顿，异常处理Demo
iOS Demo在文件夹
/samples/sample-iOS/MatrixDemo


卡顿开始方法在
控制器TestLagViewController 中的startBlockMonitor方法
调用底层    [_cbMonitor startBlockMonitor];
调用         [_blockMonitor start];
    初始化参数
    创建观察者     [self addRunLoopObserver];
    开启监听线程 [self addMonitorThread]


