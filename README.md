# java_note
## JAVA 基础
1. HashMap 的源码，实现原理； JDK8 做了什么优化
2. HashMap 扩容机制，为什么都是 2 的 N 次幂
3. ArrayList 和 Vector 的区别，扩容机制等
4. CopyOnWriteArrayList 原理
5. HashSet 和 TreeSet 原理
6. ArrayBlockingQueue 和 LinkedBlockingQueue 区别
7. 集合迭代器的原理
8. 传值和传引用的区别
9. 动态代理
10. JDK8 ConcurrentHashMap 的原理

## 多线程
1. 创建多线程的方式，以及线程的状态转换
2. 线程的中断机制
3. ThreadPoolExecutor 初始化参数； Executors 静态方法
4. synchronized 的使用方式及原理
5. 偏向锁、轻量级锁、自旋锁等优化
6. ReentrantLock 的特点及 AQS 原理
7. Semaphore、CountDownLatch、CyclicBarrier 等使用
8. ThreadLocal 的原理、与 Thread 类的关系、以及内存泄漏问题
9. volatile 的原理及内存屏障相关
10. Lock 接口有哪些实现类，使用场景是什么
11. 悲观锁，乐观锁，优缺点，CAS 有什么缺陷，该如何解决
12. ABC 三个线程如何保证顺序执行
13. 生产者消费者模式的实现方式
14. 如何实现控制线程在某段时间内完成，不完成就撤销

## JVM
1. JVM 的内存区域
2. 字符串常量池相关
3. 对象的内存布局，涉及到锁的部分
4. 类加载的过程，以及双亲委派机制、自定义类加载器
5. GC 常见算法，CMS 以及 G1 的垃圾回收过程，CMS 的各个阶段哪两个是 Stop the world 的，CMS 会不会产生碎片，G1 的优势
6. 标记清除、复制和标记整理算法的理解以及优缺点
7. eden survivor 区的比例，为什么是这个比例，eden survivor 的工作过程
8. JVM 如何判断一个对象是否该被 GC，可以视为 root 的都有哪几种类型
9. 强软弱虚引用的区别以及 GC 对他们执行怎样的操作
10. Java 是否可以 GC 直接内存
11. 常用的 JVM 调优参数
12. GC 优化的步骤
13. 当出现了内存泄漏或内存溢出，怎么排错
14. CMS 和 G1 收集过程

## 数据库相关
1. 常见的数据库优化手段
2. 索引的优缺点，以及索引选择
3. B+树索引的原理
4. 数据库连接池
5. MySQL 的锁机制
6. MVCC 和 ReadView
7. InnoDB 的一些特性
8. 数据库三范式

## 计算机网络、操作系统
1. TCP，UDP 区别
2. 三次握手，四次挥手，为什么要四次挥手
3. 长连接和短连接，连接池适合长连接还是短连接
4. OSI 七层模型
5. 用户态和内核态

## 数据结构和算法
1. 红黑树、AVL 树
2. B 树、B+树
3. 排序算法
4. 一致性 Hash 算法，一致性 Hash 算法的应用
5. TopK 问题
6. 判断链表是否有环

## 缓存相关
1. redis 支持的数据类型及使用场景
2. redis 单线程为什么还那么快
3. redis 如何存储一个 String 的
4. redis 的过期策略
5. redis 的部署方式，主从，集群
6. redis 的哨兵模式，一个 key 值如何在 redis 集群中找到存储在哪
7. redis 持久化策略
8. 缓存穿透、缓存击穿、缓存雪崩问题及解决方法
9. 缓存和数据库一致性问题

## 框架相关
1. Spring 的常用注解及作用
2. Spring Bean 的生命周期
3. Spring 怎么解决单例 Bean 的循环依赖问题
4. Spring 对于 IOC 的扩展点有哪些
5. Spring AOP 的原理，及代理对象调用过程（责任链+递归调用）
6. Spring 的事务机制，及执行流程
7. Spring 使用了哪些设计模式
8. Mybatis 基于接口完成查询的过程及原理
9. Mybatis 的一级缓存和二级缓存
10. Quartz 是如何完成定时任务的；集群同步机制

## 分布式相关
1. 分布式事务的控制
2. 分布式锁如何设计
3. 分布式 session 如何设计
4. dubbo 的组件有哪些，及其作用
5. dubbo SPI 机制；远程接口调用过程
6. dubbo 支持的协议及序列化方式
7. dubbo 的负载均衡和容错策略
8. zookeeper 的 ZAB 协议工作原理
9. zookeeper 的 Watcher 机制
10. zookeeper 的 Watcher 机制
11. zookeeper 的数据存储
12. zookeeper 的负载均衡算法
13. rocketmq 的模块功能
14. rocketmq 的高可用及高性能
15. elasticsearch 的系统架构及读写过程
16. elasticsearch 在数据量很大的情况下（数十亿级别）如何提高查询效率啊
17. eureka 的相关原理，和 zookeeper 的比较
