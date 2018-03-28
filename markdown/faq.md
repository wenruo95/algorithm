## select/poll/epoll模型

## MapReduce

## ProtoBuf

## Spark

## Hadoop

## dubbo

## 创建者/消费者模型

生产者消费者问题（英语：Producer-consumer problem）,也称有限缓冲问题（英语：Bounded-buffer problem），是一个多线程同步问题的经典案例。

	该问题描述了共享固定大小缓冲区的两个线程——即所谓的“生产者”和“消费者”——在实际运行时会发生的问题。
	生产者的主要作用是生成一定量的数据放到缓冲区中，然后重复此过程。与此同时，消费者也在缓冲区消耗这些数据。
	该问题的关键就是要保证生产者不会在缓冲区满时加入数据，消费者也不会在缓冲区中空时消耗数据。

解决方法:

	要解决该问题，就必须让生产者在缓冲区满时休眠（要么干脆就放弃数据），等到下次消费者消耗缓冲区中的数据的时候，生产者才能被唤醒，开始往缓冲区添加数据。
	同样，也可以让消费者在缓冲区空时进入休眠，等到生产者往缓冲区添加数据之后，再唤醒消费者。
	通常采用进程间通信的方法解决该问题，常用的方法有信号灯法等。
	如果解决方法不够完善，则容易出现活锁的情况。出现死锁时，两个线程都会陷入休眠，等待对方唤醒自己。该问题也能被推广到多个生产者和消费者的情形。

## 正则匹配

> https://c.runoob.com/front-end/854

	^(?!commit_by_shell).*$									<=> 过滤掉commit_by_shell
	(zengwei|linguangliang|liangjiangqiang)					<=> 匹配zengwei、linguangliang、liangjiangqiang

## Lua5.3

> [目录](http://cloudwu.github.io/lua53doc/contents.html)


> [内容](http://cloudwu.github.io/lua53doc/manual.html)