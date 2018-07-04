appium+python+PO 自动化测试框架
====
1.项目概述
-------
使用目前较为流行的UI自动化测试工具Appium，
语言选择python2，利用ddt进行数据驱动，
yaml管理项目的定位，
unittest进行组织测试用例，测试设备真机,
测试报告使用HTMLTestRunner进行测试用例完成后测试报告的生成。
###
2.目录简介
-------
* 2.1 base：存放基础封装，如driver。
* 2.2 business：业务层，封装业务相关的方法。
* 2.3 case：存放测试用例，程序入口在test_case.py中。
* 2.4 config：配置相关，包括定位信息和启动命令信息。
* 2.5 handle：操作层，封装对页面元素的操作API。
* 2.6 jpg：错误截图，用例执行过程中，如果失败会截图保存。
* 2.7 log：存放日志文件，多线程运行多个设备，会生成多个日志文件。
* 2.8 page：page层，封装页面元素。
* 2.9 report：测试报告，收集每次运行结果。
* 2.10 untils： 公共的工具模块。


3.效果展示图
-------
整体结构
###
![](https://github.com/hanyguoguo/appiumPythonPO/blob/master/img/tree.png)

控制台展示
###
![](https://github.com/hanyguoguo/appiumPythonPO/blob/master/img/workbench.png)

测试日志
###
![](https://github.com/hanyguoguo/appiumPythonPO/blob/master/img/testlog.png)

测试报告
###
![](https://github.com/hanyguoguo/appiumPythonPO/blob/master/img/testreport.png)
