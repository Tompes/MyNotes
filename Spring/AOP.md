# Spring AOP 面向切面编程

> AOP ( Aspect Oriental Programming ) 面向切面编程，是一种编程思想，和面向过程和面向对象相对应。我们可以把面向对象编程看成纵向的，而AOP就是横向的，通过非侵入式的方式去为已有代码添加新的功能。

## AOP的优点

- 降低耦合度
- 提高可扩展性
- 便于维护

## AOP 如何实现

Spring AOP 使用 cglib 动态代理来实现

Spring使用cglib在原对象的基础上创建一个代理对象，加入AOP代码逻辑。

