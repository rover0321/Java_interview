#Java面试题
1.

``` java
public class Test {
    static {
        a = 20;
    }

    private static int a = 10;

    public static void main(String[] args) {

        System.out.println("a=" + a); // 请写出上述程序的输出结果。

    }
}

```
2.
请结合项目的实际应用，谈谈你对Spring AOP的理解。

3.
Cookie与Session的共同点和区别是什么？在Java Web中，Session对象什么时候生成？

4.
多线程的并发与并行有什么区别？

5.
请简述一下面向对象设计的几个基本原则。

6.
如何用关系型数据库描述树状结构数据？

7.
请用Java语言写一个装饰者模式的示例代码。




8.
请编写源代码去掉重复项，并保留原顺序。

```java

// 原始数组
char[] list = {'a', '1', 'x', 'b', 'e', 'f', 'f', 'e', 'a', 'g', 'h', 'b', 'm'};

// 处理后数组
char[] newList = {'a', '1', 'x', 'b', 'e', 'f', 'g', 'h', 'm'};

```
9.
一个不透明的箱子里共有红，黄，蓝，绿，白五种颜色的小球，各个小球的数量非常多而且接近相等，每种颜色的小球大小相同，质量相等，每个人从篮子里抽出两个小球，请问至少需要多少个人抽，才能保证有两个人抽到的小球颜色全部相同？

