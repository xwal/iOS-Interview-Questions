# iOS-Interview-Questions

## 使用指南

```shell
$ git clone --recursive --depth=1 https://github.com/chaoskyme/iOS-Interview-Questions.git
```

## iOS 面试问题列表

* [12 Essential iOS Interview Questions from top 3% developers company](http://www.toptal.com/ios/interview-questions)
* [All you need to know about iOS technical interview including some tips for preparing, questions and some coding exercises](http://www.raywenderlich.com/53962/ios-interview-questions)
* [Swift Interview Questions And Answers](https://www.raywenderlich.com/762435-swift-interview-questions-and-answers)
* [强力iOS面试题](http://www.jianshu.com/p/2e7ae4457083)
* [道长的 Swift 面试题](http://www.jianshu.com/p/07c9c6464f83)
* [Swift 烧脑体操 - 唐巧博客](http://blog.devtang.com/2016/02/27/swift-gym-1-nested-optional/)

## iOS 笔试题库

### 知识类

#### 基础知识

1. keyWindow和window的区别

2. assign copy retain区别

3. HTTP的数据传输

4. 动态绑定

5. subclass category protocol extension 区别

6. 单例的实现

7. performSelector:withObject:方法的作用是什么？

8. 解释一下多态

9. 如何实现深拷贝

10. http和socket通信的区别，tcp和udp的区别，session和cookie的区别

11. block实现原理

12. 响应链

13. frame 和 bounds

14. 写一个宏MIN，这个宏输入两个参数并返回较小的一个

    `#define MIN(a,b) ((a)>(b)?(b):(a))`

15. 什么是KeyPath

16. `#import、#include、@class`的区别？

17. UIView和CALayer的区别和联系

18. 输出内容

    ```
    main()
    {
    	int a[5] = {1, 2, 3, 4, 5};
    	int *ptr=(int *)(&a+1);
    	printf("%d %d", *(a+1), *(ptr-1));
    }
    ```

19. 关键字 const的含义

    ```
    const int a;
    int const a;
    const int *a;
    int * const a;
    int const * a const;
    ```

20. 关键字 volatile的含义

21. static 关键字的作用

22. extern "C"的作用

23. KVO的实现原理

24. Block的种类，__block有什么作用

25. UITableView优化

26. @synthesize和@dynamic有什么区别

27. CoreGraphics和CoreAnimation有什么联系

28. 线程、进程、RunLoop的区别和联系

29. 如何高性能的给UIImageView添加圆角

30. 手势滑动的消息传递机制

#### 进阶知识

1. drawRect 一定会影响性能吗？UI Dynamic与UIKit Animation的最本质区别是什么？
2. 如何用 UIImageView 显示超大分辨率的图？如果要支持缩放呢？
3. 了解 fishhook吗？说说为什么fishhook不能修改非动态链接库中的符号？
4. C++调用虚方法与Objective-C 发消息有什么区别？
5. 了解placement new吗？Objective-C 中如何实现这个功能？
6. 如何在 ARC环境下用 C++ 标准库容器来管理 Objective-C 对象？
7. id、self、super 它们从语法上有什么区别？
8. isa是什么？是指向Class对象本身的指针吗？
9. block修改捕获变量除了用 __block 还可以怎么做？有哪些局限性？
10. NSDictionary与NSHashTable有什么区别，它们的使用场景是怎样的？
11. 如何评价 Swift 中 String index的设计？
12. 假设一个与服务器的TCP连接，忽然断网，服务器能在短时间内知会离线吗？
13. 为什么 Wireshark 不能直接抓取 SSL的原始数据？
14. backtrace 是在用户态实现的吗？能否讲讲实现它的大致思路？
15. malloc 的指针 double free 产生的异常与访问 freed 指针有可能产生的异常有什么区别？为什么访问freed指针不一定产生异常？
16. RunLoop是一个不停歇在运行的死循环吗？为什么？
17. 看过runtime的源码吗？源码中常有的fastpath、slowpath是什么？
18. runtime中SideTables（不是SideTable）存在的意义是什么？
19. Objective-C是如何保证系统升级后的ABI稳定性的？

#### MrPeak

##### 中级

1. 什么是arc？（arc是为了解决什么问题诞生的？）
2. 请解释以下keywords的区别： `assign vs weak`, `__block vs __weak`
3. `__block`在arc和非arc下含义一样吗？
4. 使用atomic一定是线程安全的吗？
5. 描述一个你遇到过的retain cycle例子。(别撒谎，你肯定遇到过)
6. +(void)load; +(void)initialize；有什么用处？
7. 为什么其他语言里叫函数调用， objective c里则是给对象发消息（或者谈下对runtime的理解）
8. 什么是method swizzling?
9. UIView和CALayer是啥关系？
10. 如何高性能的给UIImageView加个圆角？（不准说layer.cornerRadius!）
11. 使用drawRect有什么影响？（这个可深可浅，你至少得用过。。）
12. SDWebImage里面给UIImageView加载图片的逻辑是什么样的？（把UIImageView放到UITableViewCell里面问更赞）
13. 麻烦你设计个简单的图片内存缓存器（移除策略是一定要说的）
14. 讲讲你用Instrument优化动画性能的经历吧（别问我什么是Instrument）
15. loadView是干嘛用的？
16. viewWillLayoutSubView你总是知道的。。
17. GCD里面有哪几种Queue？你自己建立过串行queue吗？背后的线程模型是什么样的？
18. 用过coredata或者sqlite吗？读写是分线程的吗？遇到过死锁没？咋解决的？
19. http的post和get啥区别？（区别挺多的，麻烦多说点）
20. 我知道你大学毕业过后就没接触过算法数据结构了，但是请你一定告诉我什么是Binary search tree? search的时间复杂度是多少？我很想知道！

##### 高级

1. NSString 如何计算字符的个数？
2. PKI体系当中加密和签名有什么区别？
3. 如何自己高效实现NSUserDefault？
4. 解释下TCP的慢启动特性。
5. 如何用HTTP实现长连接。
6. HTTP 2.0 针对同一个域名的多个请求，会建立多少个TCP连接？
7. 数据库建表的时候索引有什么用？
8. Full Text Search 为什么快？
9. iOS 下如何实现指定线程数目的线程池？
10. 介绍下 iOS 设备获取唯一设备号的历史变迁。
11. 函数式编程当中的first-class function是什么意思？
12. 如何使用runtime hook一个class的某个方法，又如何hook某个instance的方法？
13. 谈下 Objective-C 都有哪些锁机制，你一般用哪个？
14. 聊下 HTTP post的body体使用 form-urlencoded和multipart/form-data的区别
15. 让你设计一种机制检测UIViewController的内存泄漏，你会怎么做？
16. 通过[UIImage imageNamed:]生成的对象什么时候被释放？
17. applicationWillEnterForeground和applicationDidBecomeActive都会在哪些场景下被调用？举例越多越好。
18. 如何终止正在运行的工作线程？
19. 穷举 iOS 下所有的本地持久化方案。

### 代码设计

1. 设计一个图片内存缓存器
2. 单词翻转
3. 二叉树广度优先遍历的实现
4. 对MVC和MVVM的理解
5. 现有一函数rand100()可以生成0-99的随机数，在这个函数的基础上设计一个可以产生0-9999随机数的函数rand10000()
6. 统计一个较长字符串(由小写字母构成)中每个字符出现的次数，并打印出出现最多的5个字母和出现的次数。

### 算法题

刷 LeetCode