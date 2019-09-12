### Java运行环境

跨平台：不区分操作系统



**JVM**

Java虚拟机

JVM本身不是跨平台的

Java是跨平台的



**JRE**

Java运行环境

包含了JVM



**JDK**

Java开发工具包

包含JRE和开发人员的工具



**path**

系统级设置



**Java开发三个步骤**

编写程序（后缀.java）---编译器编译程序--运行机器码

javac.exe编译器

java.exe解释器

---

### HelloWorld程序讲解

**一个简单的程序解释**

```java
// public class 后面代表定义一个类的名称，类是Java当中所有源代码的基本组织单位
public class helloworld {
    // main方法
    // 代表程序执行的起点
    public static void main(String[] args) {
        System.out.println("Hello, World!!!");
    }
}
```



---

### 关键字 标识符

**关键字**

java已经定义好的单词，具有特殊含义

特点：完全小写的字母



**标识符**

在程序中，我们自己定义的内容。自己为类，方法，变取的名字叫做标识符

命名规范

类名：大驼峰式

变量名，方法名：小驼峰式



---

### 常量 变量

常量

在程序运行期间，固定不变的数据。

- 字符串常量 双引号引起来的部分
- 整数常量
- 浮点数常量
- 字符常量 单引号引起来的部分
- 布尔常量 true,false
- 空常量 null **不能直接用来打印输出**



















