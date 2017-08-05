java学习汇总
===

1.hello,world
---
讲述如何使用命令让控制台打出"hello,world"，其中还包括main函数如何创建等．
例:
```java
class Main{
    public static void main(String args[]){
    System.out.println("hello,world!");
    }
}

```

***

2.常用的符号
---

1. \+  - * / ％　这五个符号分别表示加，减，乘，除，求余，int 类型与int 类型相计算之后，返回 int 值．依次类推，float类型与float类型相计算之后，返回float,double 类型与double类型相计算之后，返回double 

    + **注意，int类型与其他类型相运算时,int类型可能会上升精度，比方说： int类型与float相运算返回float,int与double类型相运算返回double**

2. == >= <= !=这四个符号分别表示，等于，大于，小于，不等于．它们返回布尔值boolean．常用于数值的判断大小．

3. =　常用于数据的赋值．
 
例
 
 ```java
int lol = 233;
 ```
3.数组
---

自认为难的一节,快被元素和索引玩吐了的我= =

数组：数据连起来就叫数组，有两种表达方式

``` java
int array[] = new int{3,1,2,5,6};
int array1[] = new int[5];//数组长度是５，内容都是类型的默认值．
```
####  如何访问数组内的某个索引所代表的数据呢？

```java
int array[] = new int[8];
array[4];
/*访问array数组内的第四个索引（喵的是第五个元素）
但如果你想访问第八个索引
会报错
*/
```

4.面向对象
---

面向对象是一个很简单的概念，首先根据一个类，这里的类就像一个模板，通过这个模板创建一个新的东西，这个东西就是对象．

5.线程
---
查我 [文档](java.lang.Thread.md) 去！
