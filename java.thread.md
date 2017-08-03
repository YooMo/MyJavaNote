# 线程知识(要想了解线程就必须要了解进程)
## 1 . 进程 : 每一个程序执行时要在内存中开出一片内存用作执行内存,现在正在执行的程序就是进程,一个进程至少包括一个线程
## 2. 线程 : 进程中一个独立的控制单元,线程在控制着进程的执行,至少有一个线程在执行java程序,且线程运行的代码存在于main函数里,这个线程就叫做主线程{fix}
# 在API文档里寻找线程这个类-->java->lang->Thread
# 创建新执行线程有两种方法
## 1 . 江该类声明为Thread的子类(又名继承Thread类).该子类应重写Thread的run方法(函数)
## 步骤:
### 1 . 将该类声明为Thread的子类
### 2 .  重写run函数
### 3 . 创建一个线程(对象),根据子类
### 4 . 访问该子类的start方法
#### 例
```java
class Demo extends Thread{
    public void run(){
        System.out.println("demo run");
    }
}
class Main{
    public static void main(String args[]){
        Demo d = new Demo;//创建好一个线程,且根据Demo类创建
        d.start();
    } 
}
```
