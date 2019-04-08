# Android_Question
记录2019年社招面试过程中的一些问题，供大家参考，可以补充和指正，一起成长～

<div align=center>
<img src="image/androidImg.png" width = "70%" height = "70%"/>
</div>

## 面试题：
###### Issues中有参考答案。可以补充指正，也可提及自己的答案～

#### 面试题1.
Android开发过程中的版本适配问题？

#### 面试题2.
关于协程的概念

#### 面试题3.
synchronized和lock的区别？

#### 面试题4.
Handler机制如何保证消息不错乱？消息延迟是如何实现的？Handler、Looper、MessageQueue三者对应关系？内存泄漏如何避免？Looper中的死循环为什么不会引器主线程ANR？

#### 面试题5.
开发过程中如果想替换第三方jar中的某个class文件，或者在开发时你的class文件与jar中的重名，但是你想使用自己的应该如何解决？如果你替换掉某个方法又该怎么解决？

#### 面试题6.
IO与NIO的区别？

#### 面试题7.
单例模式有几种写法以及各自的优劣？

#### 面试题8.
ArrayList 和LinketList区别？hashmap的实现原理？hashmap与hashtable的区别？

#### 面试题9.
gson序列化数据时如何排除某个字段？

#### 面试题10.
ButterKnife与Xutils注解的区别？以及Retrofit中的注解是如何处理的？

#### 面试题11.
jvm的类加载机制？

#### 面试题12.
列举一些git版本控制的常用操作符？

#### 面试题13.
AsyncTask的原理以及弊端？AsyncTask为什么要求在主线程加载，对象为什么要在主线程创建？

#### 面试题14.
Android开发中的屏幕适配方案？

#### 面试题15.
多线程中sleep和wait的区别？

#### 面试题16.
输出字符串中的第一个不重复的字符，例如：<br/>
	&nbsp; &nbsp;“hello”输出 ‘h’<br/>
	&nbsp; &nbsp;“abbac”输出 ‘c’<br/>
	&nbsp; &nbsp;“abdabe”输出 ‘d’

#### 面试题17.
对有序int数组去重，并输出去重后的长度，并打印出来，要求时间复杂度为O(n)，空间复杂度为O(1)。<br/>
例如：int[] array = {-1,0,0,2,4,4,4,6};<br/>
&nbsp; &nbsp;长度为：5，打印结果为：-1，0，2，4，6

#### 面试题18.
假设有A，B，C三个线程，在A线程的执行过程中去执行B线程，并且等待B线程的执行结果，然后去执行C线程，然后当C线程执行完成后，返回结果给A线程。不阻塞线程，如何实现？（相关描述我也记不太清了，可能有些不准确，考点就是Future）

#### 面试题19.
ThreadLocal作用？