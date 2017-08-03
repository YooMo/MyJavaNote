StringBuilder , StringBuffer
===

1. StringBuilder
---

 一种高效率的构建字符串的方式，与StringBuffer相比线程不安全（多线程访问时丢失了数据你还不知道）但占用内存更小．

2. StringBuffer
---
另一种高效率构建字符串的方式，与StringBuffer相比线程安全（因为加了一把＂锁＂）但占用内存更大

**注意：　他们俩的＂特性＂虽然有所出入，但是他们的使用方法是相同的**

| Function | Description |
|:- |:- |
| void append(String str) | 向StringBulider或StringBuffer所创建的对象内添加字符串或更多 |
| 花式重载 | 介绍同上 |

***

#### 例

```java
class Main{
    public static void main(String args[]){
        StringBuffer sb = new StringBuffer();
        sb.append("您想输入的字符串或更多其他的东西")；
    }
}
```

***

| Function | Description |
|:- |:- |
| void delete (int start,int end) | 从StringBuilder或StringBuffer所创建的对象中删除从索引 `start` 到索引 `end` 的字符串．

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

***

| Function | Description |
|:- |:- |
| int length() | 返回StringBuilder或StringBuffer对象中该对象的字符串长度 |
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
