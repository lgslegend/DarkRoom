# DarkRoom

适用于htc Sense系统（目前只在我7.0的u11上测试过）的免root免adb的app冻结工具

## 下载地址

- [github release](https://github.com/EAGzzyCSL/DarkRoom/releases/tag/v1.0)

- [百度网盘](https://pan.baidu.com/s/1pKQ5Ip9)

## 工作原理

- htc的Sense系统在查看第三方的app时存在一个停用按钮，点击停用按钮即可停用该app，停用后app便处于冻结状态，不会有后台进程，消息推送等行为。再次点击启用即可启用该app。

![禁用按钮](/readme/disable.jpg)

- 其他手机系统目前尚未发现该特性，故DarkRoom目前并不支持其他系统。
- 通过安卓的无障碍服务可以实现自动化的点击，并实现一键冻结，批量冻结功能。

## 目前功能

- 添加app到冻结列表，从冻结列表移除app
- 为app创建桌面快捷方式
- (批量)冻结app

## 功能演示

![example](/readme/example.gif)

## 待完善

- 快捷方式的桌面图标美化
- 通过搜索添加app
- 解决批量冻结后多个设置界面的返回


## 优点

- 不需要root
- 不需要adb，不需要删除已有账户信息
- 上手简单

## 缺点

- 冻结速度慢
- 功能不完善

## 注意事项

- 请慎对系统应用进行冻结，除非你很清楚这样做会发生什么。
- 冻结与解冻第三方app并不依赖该app，如果在有app尚处于冻结状态时卸载DarkRoom并导致被冻结的app无法解冻，请进入`设置 -> 应用程序`点击标记为已禁用的app对其进行启用操作即可，但为了方便建议选择解冻全部app后卸载DarkRoom。（__注意，此条并不适用于其他冻结功能的app，尤其是依赖root权限工作的app，所以使用其他冻结类app时请依然慎重卸载并参考app的相关说明__）

## 个人承诺

- 无病毒无广告无挖矿，不会窃取用户隐私
- 开源

## 免责声明

- 鉴于长得越帅责任越重，我自认为不应该对任何因使用本app造成的手机损坏等其他连带后果承担责任。
- 本人不保证提供对项目的终生维护。



