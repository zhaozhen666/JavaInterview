# Java基础

* hashmap1.7跟1.8？优化点？红黑树化为什么是8？退化为什么？
* dp怎么玩？回溯怎么玩？递归怎么玩？stack能解决啥问题？fifo能解决啥问题？dfs怎么玩？bfs怎么玩？
* 双亲委派模型。JDBC和双亲委派模型关系
* TCP四次挥手，TIME_WAIT发生在哪一方 TIME_WAIT过多如何处理 
* HashMap底层结构 put操作讲一下,HashMap、HashMap如何保证线程安全、ConcurrentHashMap
* 从ConcurrentHashMap一路问到锁&锁优化->LongAdder->伪共享->缓存行填充->cas等诸多技术细节；
* 观察者模式与中介者模式有什么区别？
* 手写一个基于懒汉式的双重检测的单例。
* HashMap相关?为什么要引入红黑树？ 如何在红黑树中插入一个节点。 链表是如何转换为红黑树的？
* 对ConcurrentHashMap的理解，⽐如在什么地⽅会涉及到线程安全问题以及ConcurrentHashMap是如何解决的？
* Http请求的完全过程
* HashMap扩容的触发条件是什么
* HashMap的实现原理，什么是hash碰撞，怎样解决hash碰撞？
* mysql 的sql本身没问题的情况下，没走索引原因
* mysql快照是怎么实现的
* mysql分页有什么优化 
* 讲一下Http，HTTP安全不？HTTPS如何解决的？HTTP的数字证书如何认证？TCP与UDP区别？TCP为什么要四次？ 为什么TIME_WAIT 等待的时间是 2MSL？已经主动关闭连接了为什么还要保持资源一段时间呢？ TIME_WAIT 过多有什么危害？如果已经建⽴了连接，但是客户端突然出现故障了怎么办？保活机制说一下？
* 说一下undolog， redolog MySQL如何保证redo log和binlog的数据是一致的，如果一个sql执行很慢，你能分析一下原因吗？ 为什么数据库会选错了索引
* 对乐观锁和悲观锁的理解；
* hashMap什么情况下会出现循环链表？concurrentHashMap写的时候用什么锁？
* 定义Integer x=20 Integer y=200 在内存里是个什么过程？ volite关键字的原理？它能保证原子性吗？AtomicInteger底层怎么实现的？
* threadLocal关键字有用过吗？如果没有重写initialValue方法就直接get会怎样？
* 1.java的基本数据类型与包装类； 2、final修饰变量类方法； 3、String为什么是不可变的，以及new String(“abc”)创建了几个对象； 4、String、StringBuffer、以及StringBuilder的区别； 5、static修饰变量，方法，代码块； 6、重写跟重载的区别； 7、接口跟抽象类； 8、反射、继承、枚举、异常等知识点； 9、为什么要重写hashcode和equals方法，以及hashcode相同equals是否相同
* 集合相关 1、ArrayList的底层实现、扩容过程、add过程、Fail-Fast机制； 2、ArrayList与Linkedlist、Vectot的区别； 3、如何获得一个线程安全的List； 4、CopyOnWriteArrayList是如何实现线程安全的； 5、Linkedlist的底层实现，以及如何使用LinkedList实现一个LRU； 6、TreeSet、HashSet、LinkedHashSet的底层实现以及之间的区别； 7、PriorityQueue、LinkedBlockingQueue、ArrayBlockingQueue的实现以及区别； 8、HashMap的底层实现，扩容过程，达到阈值一定会扩容吗、put过程、树化过程，如何确定负载因子、以及为什么线程不安全和1.8做了哪些优化； 9、HashMap与HashTable的区别，如何获得一个线程安全的Map； 10、ConcurrentHashMap为什么是线程安全的，以及1.8做了哪些优化； 11、LinkedHashMap的底层实现，以及如何实现LRU； 12、TreeMap的底层实现； 13、迭代器的实现；
* 1. 面向对象的特点有哪些？ 2. 列举几个java常用的package及其作用 3. 接口和抽象类有什么联系和区别 4. 重载和重写有什么区别 5. java有哪些基本数据类型？ 6. Java支持的数据类型有哪些？什么是自动拆装箱？ 7. int 和 Integer 有什么区别 8. 数组有没有length()方法？String有没有length()方法？ 9. Java中符号>>和>>>有什么区别？ 10. Java类的实例化顺序 11. 什么是值传递和引用传递 （1）值传递是对基本型变量而言的,传递的是该变量的一个副本,改变副本不影响原变量. （2）引用传递一般是对于对象型变量而言的,传递的是该对象地址的一个副本, 并不是原对象本身 。 12. String能被继承吗？为什么？ 13. String和StringBuilder、StringBuffer的区别？
* 深拷贝和浅拷贝。 
* Integer a1 = new Integer(2); Integer a2 = new Integer(2); a1.equals(a2)的结果？？ 
* 为什么在重写equals方法的时候要重写hashcode的方法？
* HTTP 1.0 和 HTTP 2.0 的区别 HTTP 2.0 做了哪些优化
*  JDK中偏向锁、自旋锁、轻量级锁、重量级锁的区别？ JDK锁自旋的自旋阈值了解吗？如何调整自旋次数？
* 如果相等hash对象太多，那么怎么解决迭代的影响？
* 服务器CPU数量及线程池数量的关系？
* 一亿条记录，内存中肯定放不下，要怎么找出其中最大的十条？
* 为什么要用读写锁而不用synchronized这种同步锁？ 
* 事务隔离性的理解，为什么会有脏读，可重复读，提交读等。
* 了解哪些设计模式，6个设计原则分别是什么？每种设计原则体现的设计模式是哪个？
* 如何实现session共享？用Redis该如何实现？
* 常见的stackoverflowexception,outofmemoryexception是怎么回事；
* top和jstack命令用过没，jstack命令的nid是什么意思，怎么查看java某个进程的线程？
* ABA怎么发生的，怎么解决ABA问题
* Mysql对联合索引有优化么？会自动调整顺序么？哪个版本开始优化？
* 什么是死锁？ 2.死锁产生的条件？ 3.怎样避免死锁？
* TCP三次握手和四次挥手的流程，为什么断开连接要4次,如果握手只有两次，会出现什么 .TIME_WAIT和CLOSE_WAIT的区别 .说说你知道的几种HTTP响应码 
