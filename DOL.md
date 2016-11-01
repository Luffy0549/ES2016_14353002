#LAB2 DOL实例分析&编程

##实验任务

1. 修改example2，让3个square模块变成2个, tips:修改xml的iterator 

2. 修改example1，使其输出3次方数，tips:修改square.c 

提示：修改代码之后要重新编译、运行（sudo ant –f runexample.xml –Dnumber=XXX）XXX是 运行example的号码，比如上面是2和1.

##实验过程

1.更改i的平方为立方
![Ubuntu-2016-10-24-17-17-43.png](https://ooo.0o0.ooo/2016/10/24/580dd7bc0f870.png)
运行结果如下
![Ubuntu-2016-10-24-17-21-41.png](https://ooo.0o0.ooo/2016/10/24/580dd8d14eb24.png)
![Ubuntu-2016-10-24-18-32-51.png](https://ooo.0o0.ooo/2016/10/24/580de3ede66b3.png)
![Ubuntu-2016-10-24-18-43-20.png](https://ooo.0o0.ooo/2016/10/24/580de60dc7f0a.png)



2.将example2.xml中 value = "2" 改为 value = "3"
![Ubuntu-2016-10-24-17-28-04.png](https://ooo.0o0.ooo/2016/10/24/580dd8d73761d.png)
![Ubuntu-2016-10-24-17-36-09.png](https://ooo.0o0.ooo/2016/10/24/580dd8e417478.png)更改后example2架构中包含2个square进程，结果为i^4
![Ubuntu-2016-10-24-17-35-54.png](https://ooo.0o0.ooo/2016/10/24/580dd8dd536e0.png)
![Ubuntu-2016-10-24-18-43-51.png](https://ooo.0o0.ooo/2016/10/24/580de60dca137.png)

##实验感想

更改dol实例了解了各个文件功能：

src文件夹：各进程（生产者，消费者，处理模块）的功能定义；

example1.xml：系统架构（即模块连接方式定义）。