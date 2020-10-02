- [一、Java语言概述](#一Java语言概述)
- [二、Java语言的三种技术架构](#二Java语言的三种技术架构)
  * [J2SE(Java 2 Platform Standard Edition)标准版](#j2sejava-2-platform-standard-edition标准版)
  * [J2EE(Java 2 Platform Enterprise Edition)企业版](#j2eejava-2-platform-enterprise-edition企业版)
  * [J2ME(Java 2 Platform Micro Edition)小型版](#j2mejava-2-platform-micro-edition小型版)
- [三、Java语言的特点](#三Java语言的特点)
  * [1. 跨平台/可移植性](#1-跨平台可移植性)
  * [2. 安全性](#2-安全性)
  * [3. 面向对象](#3-面向对象)
  * [4. 简单性](#4-简单性)
  * [5. 高能性](#5-高能性)
  * [6. 分布式](#6-分布式)
  * [7. 多线程](#7-多线程)
  * [8. 健壮性](#8-健壮性)
- [四、JVM、JRE和JDK](#四jvmjre和jdk)
  * [JVM(Java Virtual Machine Java虚拟机):](#JVMJava-Virtual-Machine-Java虚拟机)
  * [JRE(Java Runtime Environment Java运行环境)：](#JREJava-Runtime-Environment-Java运行环境)
  * [JDK(Java Development Kit Java开发工具包)：](#JDKJava-Development-Kit-Java开发工具包)
- [五、数据类型](#五数据类型)
  * [1. 整数类型](#1-整数类型)
  * [2. 浮点数类型](#2-浮点数类型)
  * [3. 布尔类型](#3-布尔类型)
  * [4. 字符类型](#4-字符类型)

# 一、Java语言概述

* 1995年，SUN公司推出的一门高级编程语言。

* SUN=Stanford University Network(斯坦福大学网络公司)
* 2009年SUN公司被甲骨文公司（Oracle）收购



# 二、Java语言的三种技术架构

## J2SE(Java 2 Platform Standard Edition)标准版

​	是为开发普通桌面和商务应用程序提供的解决方案。

​	该技术体系是其他两者的基础，可以完成一些**桌面应用程序的开发**。

## J2EE(Java 2 Platform Enterprise Edition)企业版

​	是为开发企业环境下的应用程序提供的一套解决方案。

​	该技术体系中包含的技术如 Servlet Jsp等，主要针对于**Web应用程序开发**。

## J2ME(Java 2 Platform Micro Edition)小型版

​	是为开发电子消费产品和嵌入式设备提供的解决方案。

​	该技术体系主要应用于小型电子消费类产品，如**手机应用程序**等。

​	*Java5.0版本后，更名为 JAVASE、JAVAEE、JAVAME*



# 三、Java语言的特点

## 1. 跨平台/可移植性

​	通过Java语言编写的应用程序在不同的系统平台上都可以运行

​	**原理**：①只要在需要运行Java应用程序的操作系统上，先安装一个Java 虚拟机(JVM Java Virtual Machine)即可。②由JVM来负责Java程序在该系统中的运行。
![Java跨平台性](https://img-blog.csdnimg.cn/20201002132808927.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3podXlpbmdfb2ZmaWNpYWw=,size_16,color_FFFFFF,t_70#pic_center)
​	因为有了JVM，所以同一个Java程序在三个不同的操作系统中都可以执行。 这样就实现了Java程序的跨平台性。也称为Java具有良好的可移植性。

## 2. 安全性

​	Java适用于网络/分布式环境。Java可以很容易构建出放病毒、防篡改的系统。

## 3. 面向对象

​	Java是完全面向对象的语言。

## 4. 简单性

​	Java相当于C++语法的简化版。

## 5. 高能性

​	

## 6. 分布式

​	Java是为Internet的分布式环境而设计的，因为它能够处理TCP/IP协议。

## 7. 多线程

​	多线程的使用可以带来更好的交互响应和实时行为。

## 8. 健壮性

​	Java是一种健壮的语言。Java程序也可能有异常，即使这样程序也不会崩溃，而是把该异常抛出，再通过异常处理机制加以处理。



# 四、JVM、JRE和JDK
## JVM(Java Virtual Machine Java虚拟机):
是一个虚拟的用于执行字节码的“虚拟计算机”，它也定义了指令集、寄存器集、结构栈、垃圾收集堆、内存区域。JVM负责解释运行Java字节码，边解释边运行，这样，速度就会受到一定影响。
## JRE(Java Runtime Environment Java运行环境)：
包括Java虚拟机(JVM Java Virtual Machine)和Java程序所需的核心类 库等，如果想要运行一个开发好的Java程序，计算机中只需要安装JRE 即可。

## JDK(Java Development Kit Java开发工具包)：
JDK是提供给Java开发人员使用的，其中包含了Java的开发工具，也包 括了JRE。所以安装了JDK，就不用再单独安装JRE了。 其中的开发工具：编译工具(javac.exe) 打包工具(jar.exe)等

***JDK的优缺点***

***忧**：从初学者角度来看，采用JDK开发Java 程序能够很快理解程序中各部分代码之间的关系，有 利于理解Java面向对象的设计思想。*

***劣**：从事大规模企业级Java应用开发非常困 难，不能进行复杂的Java软件开发，也不利于团体 协同开发。*

# 五、数据类型
+ 整型
+ 浮点型
+ 特殊的浮点数
+ 布尔类型
+ 字符类型

## 1. 整数类型
![整数类型](https://img-blog.csdnimg.cn/20201002133309429.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3podXlpbmdfb2ZmaWNpYWw=,size_16,color_FFFFFF,t_70#pic_center)
Java语言的整数常数默认为int型，声明long型常量可以在后面加“l”或“L”。
```java
public class Main{
    public static void main(String[] args){
        int a=10;	//十进制 10
        int b=010;	//八进制（0开头） 8
        int c=0x10;	//十六进制（0x或0X开头） 16
        int d=0b10;	//二进制（0b或0B开头） 2
    }
}
```

## 2. 浮点数类型
![浮点数类型](https://img-blog.csdnimg.cn/20201002133512753.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3podXlpbmdfb2ZmaWNpYWw=,size_16,color_FFFFFF,t_70#pic_center)
*<u>同样是4个字节 为何float的范围比int大？</u>*

* *int 和 float 内在的表示是不一样的。*

* *对于int，第1位是符号位，接下来31位表示 整数部分*
* *对于float，第1位是符号位，接下来8位表 示以2为底的指数(整数部分)，剩下的23位 表示尾数(小数部分)。*

* *对于double，第1位是符号位，接下来11位 表示指数，剩下的52位表示尾数。*

```java
float a = 5.23f	//后缀f或F表示float类型
double b = 7.354D //后缀d或D表示Double类型
double c = 314e-2	//科学计数法 e/E 314*10^(-2)
```

`浮点数误差`

`计算机是二进制的。浮点数没有办法用二 进制进行精确表示。表示浮点数由两个部 分组成：指数和尾数，这样的表示方法一 般都会失去一定的精确度，有些浮点数运 算也会产生一定的误差。`

`浮点数可能产生舍入误差，所以表示可能 不精确，不适用于金融计算。`

`若要精确地表示一个浮点数，可以考虑使 用BigDecimal类`

```java
public class Main {
	public static void main(String[] args) {
		double a = Double.POSITIVE_INFINITY;// 正无穷大
		double b1 = Float.POSITIVE_INFINITY;// 正无穷大，或float
		double b = Double.NEGATIVE_INFINITY;// 负无穷大
		double c = Double.NaN;// 非数
		double d = 6.4 / 0;// 正数除以0得到正无穷大
		double e = -6.4 / 0;// 负数除以0得到负无穷大
		double f = 0.0 / 0;// 0.0除以0得到非数
		double g = Math.sqrt(-6.4);// 对负数开平方得到非数
		System.out.println(a);		//Infinity
		System.out.println(b1);		//Infinity
		System.out.println(b);		//-Infinity
		System.out.println(c);		//NaN
		System.out.println(d);		//Infinity
		System.out.println(e);		//-Infinity
		System.out.println(f);		//Nan
		System.out.println(g);		//Nan
		System.out.println(a == d);	//true
		System.out.println(b == e);	//true
		System.out.println(c == f);	//false
		System.out.println(Double.isNaN(f));//true
	}
}
```

## 3. 布尔类型
![布尔类型](https://img-blog.csdnimg.cn/20201002133611551.png#pic_center)
+ boolean类型只能是true或false，不能像C/C++那样用0或 非0来表示
+ 其他数据类型的值也不能转换成boolean类型

## 4. 字符类型
![字符类型](https://img-blog.csdnimg.cn/20201002133630445.png#pic_center)
+ char类型存储2个字节的Unicode字符。\u后面加上十六进制表示Unicode字符（转义符+[u]Unicode）。范围：0~65535

***ps:***

​	*Unicode编码，解决了乱码问题。但是，如果文本基本上全部是英文的话，用Unicode编码 比ASCII编码需要多一倍的存储空间，在传输上也不划算 。*

​	*UTF-8（8-bit Unicode Transformation Format）编码：把Unicode编码转化为“可变长编码”。UTF-8编码把一个Unicode字符根据不同的字符编码成1-6 个字节，常用的英文字母被编码成1个字节，汉字通常是 3个字节，生僻的字符才会被编码成4-6个字节。*

​	*如果要存储或传输的文本包含大量英文字符，用UTF-8编 码就能大大节省空间。*

+  字符与Unicode的互转

  ```java
  Integer.toHexString();	//转码
  Integer.parseInt();		//解码
  ```

```java
public class Main {
	public static void main(String[] args) {
		String s = Integer.toHexString('香');
        System.out.println(s);	//9999
        char c = (char) Integer.parseInt("9999",16);
        System.out.println(c);	//香
	}
}
```

| 转义符 |     含  义      | Unicode值 |
| :----: | :-------------: | :-------: |
|   \b   | 退格(Backspace) |  \u0008   |
|   \n   |      换行       |  \u000a   |
|   \r   |      回车       |  \u000d   |
|   \t   |   制表符(Tab)   |  \u0009   |
|  \\"   |     双引号      |  \u0022   |
|  \\'   |     单引号      |  \u0027   |
|  \\\   |     反斜杠      |  \u005c   |

