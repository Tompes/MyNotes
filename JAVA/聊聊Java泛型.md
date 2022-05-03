# 聊聊Java泛型

泛型是Java中的一种常用技术，使用泛型可以提高代码复用能力

## 1. 什么是泛型

> 泛型的本质是参数化类型，即使用的时候将类型作为参数进行传递，在代码逻辑不关注具体类型的时候使用。

泛型有多种：

1. 泛型类

2. 泛型接口

3. 泛型方法
   
   

泛型类：

```java
class HelloWorld <T>{
    T hello;
    HelloWold(){}
}
```

泛型方法：

```java
class HelloWorld{
    public <T> T[] sort(T[] elems){
        //...
    }
}
```

泛型接口：

```java
interface HelloWorld<T>{
    void add(T p,T e);
}
```

## 2. 泛型是如何实现的？

> 泛型





























