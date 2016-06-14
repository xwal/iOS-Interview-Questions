#iOS-Interview-Questions

## iOS 面试问题列表

* [12 Essential iOS Interview Questions from top 3% developers company](http://www.toptal.com/ios/interview-questions)
* [20 iOS Developer Interview Questions and Answers for getting you ready for your interview](https://www.codementor.io/ios/tutorial/ios-interview-tips-questions-answers-objective-c)
* [A small guide to help those looking to hire a developer or designer for iOS work While tailored for iOS, many questions could be used for Android developers or designers as well A great self-test if you're looking to keep current or practice for your own interview](https://github.com/CameronBanga/iOS-Developer-and-Designer-Interview-Questions)
* [All you need to know about iOS technical interview including some tips for preparing, questions and some coding exercises](http://www.raywenderlich.com/53962/ios-interview-questions)
* [Interview Questions for iOS and Mac Developers from the CEO of Black Pixel](https://blackpixel.com/writing/2013/04/interview-questions-for-ios-and-mac-developers-1.html)
* [iOS Interview Questions and Answers including such topics as Development Basics, App states and multitasking, App states, Core app objects](http://www.geekinterview.com/Interview-Questions/iOS)
* [关于一些 iOS 面试问题的解答](http://draveness.me/guan-yu-xie-ios-wen-ti-de-jie-da/)

## iOS面试题整理

最近整理
- AFNetworking的原理与NSURLSession的区别
- Block的种类，__block有什么作用
- 单例的种类
- SDWebImage的原理
- HTTP协议上传
- 运行时的作用和工作原理
- 支付集成
- MJRefresh原理

常见题目
- 类别和继承的区别，什么时候不用类别
- 如何实现MRC和ARC混编
- 对MVC和MVVM的理解
- 深拷贝和浅拷贝的实现
- 网络请求同步和异步的理解
- GCD底层的三种队列和用法
- CALayer和UIView的关系
- 什么是懒加载
- 如何查找内存泄露
- 简述沙盒机制
- UITableView优化手段
- 属性修饰符strong、weak、assign和copy的区别
- UIView的frame和bounds有什么不同
- 类与类之间传值有哪些方式
- 如何获取键盘的高度
- 委托、通知、KVO分别在什么场景下使用
- @synthesize和@dynamic有什么区别
- 数据持久化方法
- 什么是keyPath
- 谈谈对RunLoop的理解
- CoreGraphics和CoreAnimation有什么联系
- 谈谈对响应者链的理解
- 用变量a给出下面的定义：一个整型变量、一个指向整型变量的指针、一个指向指向一个整型变量指针的指针、一个有10个整数的数组、一个指向有10个整数的数组的指针、一个指向有一个整数参数且返回一个整数的函数的指针
- 如何进行内存泄露的追踪
- 线程和进程的区别和联系
- 视图控制器的生命周期
- block是如何捕获外部变量的，为什么使用__block修饰的外部变量可以在block中被修改
- 更新约束需要调用什么方法
- 通知UIView刷新要调用什么方法
- 如何获得一个UIView所属的UIViewController
- Objective-C中KVO是如何实现的
- 如何让自己定义类的对象作为属性时可以用copy修饰符
- Interface Builder中的“User Defined Runtime Attributes”如何使用
- 什么情况下报“unrecognized selector”错误
- 怎样实现多个异步任务完成后统一回调一个结束方法
- 一个对象的isa指针指向什么，有什么作用
- NSRunLoop和线程有什么关系
- 如何高性能的给UIImageView添加圆角
- 如何对iOS设备进行性能测试
- 说一下App上架流程
- 简述应用程序的生命周期
- git的fetch、push和pull分别有什么用
- 是否使用过CoreAnimation、CoreText和CoreImage
- iOS系统架构的四个层次
- NSNotification是同步还是异步的


代码题

- 写一个单例模式的例子
- 写一个代理模式的例子
- 定义一个枚举有几种方式
- 用代码移除视图view上所有的UIButton
- 现有一函数rand100()可以生成0-99的随机数，在这个函数的基础上设计一个可以产生0-9999随机数的函数rand10000()
- 有一个整数数列，你可以交换其中任意两个数来得到一个新数列，求一共可以得到多少种可能的结果。int getTotal(int arr[N])
- Tom要在家里举行宴会，他虽然有很多根筷子但是筷子的长度并不完全相同，现在已知每根筷子的长度，要求每位客人都能拿到相同长度的筷子，求最多可以邀请多少客人。int getMax(int arr[N])
- 统计一个较长字符串(由小写字母构成)中每个字符出现的次数，并打印出出现最多的5个字母和出现的次数。