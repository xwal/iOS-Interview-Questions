#iOS-Interview-Questions

## 使用指南

使用以下命令更新仓库数据：

```shell
$ git clone --depth=1 https://git.coding.net/chaosky/iOS-Interview-Questions.git
$ git submodule init
$ git submodule update
```

## iOS 面试问题列表

* [12 Essential iOS Interview Questions from top 3% developers company](http://www.toptal.com/ios/interview-questions)
* [20 iOS Developer Interview Questions and Answers for getting you ready for your interview](https://www.codementor.io/ios/tutorial/ios-interview-tips-questions-answers-objective-c)
* [A small guide to help those looking to hire a developer or designer for iOS work While tailored for iOS, many questions could be used for Android developers or designers as well A great self-test if you're looking to keep current or practice for your own interview](https://github.com/CameronBanga/iOS-Developer-and-Designer-Interview-Questions)
* [All you need to know about iOS technical interview including some tips for preparing, questions and some coding exercises](http://www.raywenderlich.com/53962/ios-interview-questions)
* [Interview Questions for iOS and Mac Developers from the CEO of Black Pixel](https://blackpixel.com/writing/2013/04/interview-questions-for-ios-and-mac-developers-1.html)
* [iOS Interview Questions and Answers including such topics as Development Basics, App states and multitasking, App states, Core app objects](http://www.geekinterview.com/Interview-Questions/iOS)
* [关于一些 iOS 面试问题的解答](http://draveness.me/guan-yu-xie-ios-wen-ti-de-jie-da/)
* [iOS面试题大全-点亮你iOS技能树](http://www.jianshu.com/p/a3b61b2f6e66)
* [给新人的iOS面试资料（2016年3月6日更新）](http://www.jianshu.com/p/866c78b2130d)
* [iOS:BAT面试题](http://www.jianshu.com/p/682de90106b5)
* [强力iOS面试题](http://www.jianshu.com/p/2e7ae4457083)
* [4道过滤菜鸟的iOS面试题](http://www.jianshu.com/p/fd5d193f3d36)

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

## 张莹老师面试题整理

- 简历上写的所有技术（所以不会的不要给我乱写啊，简历没整好，你就被问死了）
- 简历上公司的项目相关
  - 1、即时通讯   不局限于xmpp，以及环信，还有其他的，比如nodjsc聊天
  - 2、项目实现了哪些功能，哪些是你负责的，怎么完成的
- 其他技术
  - 1、多线程
  - 2、内存管理
  - 3、手势滑动的消息传递机制
  - 4、collectionView怎样实现所有图片围城圆圈
  - 5、第三方库和第三方库底层的东西。
  - 6、用过即使通讯没，登陆注册，还有评论，分享没有？
  - 7、Category和添加子类的区别，啥时候不能用Category？
  - 8、数组排序，几种方法？你会用哪几种？
  - 9、企业里面记录代码错误的日志的那个叫什么?
  - 10、数据结构和算法
  - 11、曲线
  - 12、版本管理
  - 13、svn以及git
  - 14、上架
  - 15、json解析为空的时候怎么解决
  - 16、极光推送，线程优缺点，内存机制，yymodel原理。强弱引用，自定义。block得用法，哪里用。
  - uiview里block为啥不完成循环
- 一.技术:
  - 1.Xcode 编程工具的使用:
    - a.如何搜索函数?
    - b.了解其他iOS 开发工具吗?
    - c.Xcode 自带的工具:Instruments,ApplicationLoader
  - 2.代码姿势:
    - a.关键字:static,extern;@property :copy,strong,retain,assign(重要,每次必问)
    - b.常用设计模式:单例,系统自带常用单例包括?
    - c.多线程 & 运行时UI操作在哪个线程执行?该线程是并行 还是串行?dispatch,  NSOperationQueue;网络请求:导航控制器X 推出视图控制器A,A 新建了一个线程,请求图片,最后显示;但是此时如果视图控制器A 在图片请求完成前,被Pop掉,怎么去检测A 是否存在?怎么解决?(这儿有一个陷阱,问题应该是怎么解决A所开辟的线程,而不是去怎么检测A 是否存在);
    - d.SDK & 第三方地图SDK,讯飞语音,即时通讯,推送,分享AFNetWorking:怎么实现的?SDWebImage:用到了什么技术?怎么实现的?
    - e.其他响应式编程,了解吗?swift 了解吗? i0S 8 和 iOS 9 更新了什么东西?
    - f.你目前遇到最大的开发难题是什么?说来听听(最恶心)  给你看看我们现在的项目,你看你要做多久能做出来?
- 二.表达:
  - 1.你开发的应用怎么开发的,用到了什么,怎么实现的,自己上架的吗?自己运营,还是?
  - 2.你认为开发APP,需要注意什么?
  - 3.你上一家公司干什么的,主要负责什么模块
  - 4.你期待在5年内达到怎样成绩,职业规划?
  - 5.如果让你管理两个团队,一个弱,一个强,你怎么管理?(思路很重要)

还有MRC和ARC的区别各种花样

正现在问区别，问日志这些有很多

## 高级面试题

- 微信如何搜索附近人
- 模糊搜索和精确搜索
- 即时通讯的UI布局，要是你会用多少个cell
- 有没有直播经验
- 最近的ipv6上架的问题，以及了解ipv6是什么
- 消息传递机制了解吗，你用它做过什么？
- iOS 如何优化
- instruments用过哪些工具，如何测试核心动画性能
- 沙盒机制
- ffmpeg，opengl了解吗
- 如何收集App异常信息（比如：崩溃、闪退等）
- 离屏渲染了解么，了解的话说一下你一般从哪几方面操作的
- 了解GCD的信号量机制么？能谈谈你对它的理解么？
- 聊一下RAC（ReactiveCocoa）和MVVM，你对它的看法
- block底层实现
- 响应链的理解
- KVC和KVO
- lldb（gdb）常用的调试命令
- label的可显示区域
- 热更新有几种实现方法，你最常用哪种


