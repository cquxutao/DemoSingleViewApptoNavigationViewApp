# DemoSingleViewApptoNavigationViewApp
将iOS  Single View App 转换为iOS Navigation View App（代码方式）

方式1：代码方式，步骤如下：
1. 在AppDelegate.swift中设置根视图为UINavigationController
let rootViewController = ViewController()
let rootNavigationController = UINavigationController(rootViewController:rootViewController)
self.window!.rootViewController = rootNavigationController

2. 修改ViewController的背景颜色（SB默认的背景颜色为黑色）
self.view.backgroundColor = UIColor.white

3. 添加标题
self.title = "DemoSingleViewApptoNavigationViewApp"

3. 运行结果显示，Single View App已经转换为了Navigation View App
