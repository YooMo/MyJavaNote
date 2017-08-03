StringBuilder , StringBuffer
===

1. StringBuilder
---

 一种高效率的构建字符串的方式，与StringBuffer相比线程不安全（多线程访问时丢失了数据你还不知道）但占用内存更小．

2. StringBuffer
---
另一种高效率构建字符串的方式，与StringBuffer相比线程安全（因为加了一把＂锁＂）但占用内存更大

# 注意：　他们俩的＂特性＂虽然有所出入，但是他们的使用方法是相同的
## 他们俩所调用的方法　：　
### 1. append : 向StringBulider或StringBuffer所创建的对象内添加字符串或更多
#### 例
```java
class Main{
    public static void main(String args[]){
        StringBuffer sb = new StringBuffer();
        sb.append("您想输入的字符串或更多其他的东西")；
    }
}
```
### 2. delete : 向StringBuilder或StringBuffer所创建的对象中删除几索引到几索引．
#### 例
```java
class Main{
    public static void main(String args[]){
        StringBuffer sb = new StringBuffer();
        sb.append("YooMoZuiShuai");
        sb.delete(5,12);
    }
}
```
### length : 向StringBuilder或StringBuffer所创建的对象中取该对象的字符串长度并返回一个int值．
#### 例
```java
class Main{
    public static void main(String args[]){
        StringBuffer sb = new StringBuffer();
        sb.append("MaxPower")；
        sb.length();
    }
}
```
