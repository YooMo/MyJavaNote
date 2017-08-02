String 知识点=c=
===

1.indexOf lastIndexOf
---

| Function | Description |
|:- |:- |
| int indexOf(String str) | 正向查找您的字符串内某个字符串,找到后返回这个字符或字符串当前索引= = |
| int lastIndexOf(String str) | 反向查找您的字符串内某个字符串,找到后返回这个字符串当前索引(注意 : 上面这哥们和这个兄弟都是返回从前到后的索引!)  |

#### 例:

```java
int indexof (To find the char or string);
int lastindexof(To find the char or string 反向查找正向返回索引)
```

2. substring
---

| Function | Description |
|:- |:- |
| String substring(int beginIndex) | 截取从索引 `beginIndex` 到最后的字符串并返回 |
| String substring(int beginIndex,int endIndex) | 截取从索引 `beginIndex` 到 `endIndex` 的字符串并返回，不包括索引为 `endIndex` 的字符 | 

#### 例 :
```java
String substring(4,6)
/*
截取某个字符串内索引4到索引6之内的字符串,且截取的字符串包括索引4且在索引6之前
*/
```

3.startswith endswith
---

| Function | Description |
|:- |:- |
| boolean startsWith(String prefix) | 判断某字符串是否由 `prefix` 开头 |
| boolean endsWith(String prefix) | 判断是否由 `prefix` 结尾 |

#### 例 : 
```java
boolean startswith(某个字符串);
boolean endswith (某个字符串);
```
