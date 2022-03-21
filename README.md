
# 设计模式是什么？
    设计模式是软件设计中常见问题的典型解决方案。 它们就像能根据需求进行调整的预制蓝图， 可用于解决代码中反复出现的设计问题。
    设计模式与方法或库的使用方式不同， 你很难直接在自己的程序中套用某个设计模式。 模式并不是一段特定的代码， 而是解决特定问题的一般性概念。 你可以根据模式来实现符合自己程序实际所需的解决方案。

# 模式包含哪些内容？
    大部分模式都有正规的描述方式， 以便在不同情况下使用。 模式的描述通常会包括以下部分：
* ***意图***部分简单描述问题和解决方案
* ***动机***部分将进一步解释问题并说明模式会如何提供解决方案
* ***结构***部分展示模式的每个部分和它们之间的关系
* ***在不同语言中的实现***提供流行编程语言的代码， 让读者更好地理解模式背后的思想

# 设计模式分类
    不同设计模式的复杂程度、 细节层次以及在整个系统中的应用范围等方面各不相同。
    最基础的、 底层的模式通常被称为惯用技巧。
    最通用的、 高层的模式是构架模式。例如MVP，MVC，MVVM等。
# 所有模式可以根据其意图或目的来分类
* ***创建型模式***提供创建对象的机制， 增加已有代码的灵活性和可复用性。
* ***结构型模式***介绍如何将对象和类组装成较大的结构， 并同时保持结构的灵活和高效。
* ***行为模式***负责对象间的高效沟通和职责委派。

- 创建型模式
    这类模式提供创建对象的机制， 能够提升已有代码的灵活性和可复用性。
    - 工厂方法模式
        工厂方法模式是一种创建型设计模式， 其在父类中提供一个创建对象的方法， 允许子类决定实例化对象的类型。
    - 抽象工厂模式
    ```
    抽象工厂模式是一种创建型设计模式， 它能创建一系列相关的对象， 而无需指定其具体类。
    ```
    - 生成器模式
    ```
    生成器模式是一种创建型设计模式， 使你能够分步骤创建复杂对象。 该模式允许你使用相同的创建代码生成不同类型和形式的对象。
    ```
    - 原型模式
    ```
    原型模式是一种创建型设计模式， 使你能够复制已有对象， 而又无需使代码依赖它们所属的类。
    ```
    - 单例模式
    ```
    单例模式是一种创建型设计模式， 让你能够保证一个类只有一个实例， 并提供一个访问该实例的全局节点。
    ```
- 结构型模式
    这类模式介绍如何将对象和类组装成较大的结构， 并同时保持结构的灵活和高效。
    - 适配器模式
    - 桥接模式
    - 组合模式
    - 装饰模式
    - 外观模式
    - 享元模式
    - 代理模式
- 行为模式
    这类模式负责对象间的高效沟通和职责委派。
    - 责任链模式   
    - 命令模式
    - 迭代器模式
    - 中介者模式
    - 备忘录模式
    - 观察者模式
    - 状态模式
    - 策略模式
    - 模板方法模式
    - 访问者模式
