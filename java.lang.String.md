# String 知识点=c=

## 1.indexof , lastindexof

### indexof : 正向查询您的字符串内某个字符或字符串,找到后返回这个字符或字符串当前索引= =

### lastindexof : 反向查询您的字符串内某个字符或字符串,找到后返回这个字符或字符串当前索引(注意 : 上面这哥们和这个兄弟都是返回从前到后的索引!)

#### 例 : 

```java
int indexof (To find the char or string);
int lastindexof(To find the char or string 反向查找正向返回索引)
```
## 2.substring : 顾名思义(雾  表示截取字符串  会在下面例子中给出详细格式{fix}
## 普通格式1 : substring(开始索引,结束索引);

## 普通格式2 : substring(开始索引);(从这个开始索引一直到最后全部截取)


#### 例 :
```java
String substring(4,6)
/*
截取某个字符串内索引4到索引6之内的字符串,且截取的字符串包括索引4且在索引6之前
*/
```
## 3.startswith,endswith

## 判断某字符串是否由哪个字符串开头(startswith管这事),判断是否由哪个字符串结尾(endswith管这事),并返回boolean值
#### 例 : 
```java
boolean startswith(某个字符串);
boolean endswith (某个字符串);
```
QAQ