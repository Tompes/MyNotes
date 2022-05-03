# Spring 的 IoC

> IoC 就是 控制反转，即交出对象的的控制权给到IoC容器，由Spring框架来管理对象。
>
> 在使用时候，通过DI（依赖注入）的方式来直接注入并使用。  

## 优点

- 降低了耦合度
- 不需要手动去创建对象，简化了操作



## IoC容器的设计

> Spring IoC 主要基于 BeanFactory 和 ApplicationContext

BeanFactory 是 IoC容器的最底层接口，**ApplicationContext** 是对**BeanFactory**的**继承和扩展**，在大多数场景下，都会使用ApplicationContext作为IoC容器。

### BeanFactory

- BreanFactory 是Spring中最底层的接
- 提供了基础的IoC功能
  - 负责配置，创建和管理bean。

### ApplicationContext

- ApplicationContext 继承了 BeanFactory，同样可以提供IoC的基本功能

- ApplicationContext对BeanFactory进行了扩展：

  - 支持AOP
  - 支持统一的资源加载
  - 支持国际化
  - 支持消息机制

  