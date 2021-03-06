# 设计模式

虽然设计模式与语言无关，但这并不意味着每一个模式都能在每一门语言中使用.1996
年，`Peter Norvig `在题为[Design Patterns in Dynamic Languages](http://norvig.com/designpatterns/)
的演讲中指出，Gamma 等人合著的《设计模式：可复用面向对象软件的基础》一
书中有23个模式，其中有16个在动态语言中'不见了，或者简化了'.他讨论的是Lisp 和Dylan,
不过很多相关的动态特性在Python中也能找到.

《设计模式：可复用面向对象软件的基础》的作者在引言中承认，所用的语言决定了哪些
模式可用：

    程序设计语言的选择非常重要，它将影响人们理解问题的出发点。我们的设计模式采用了
    Smalltalk 和C++ 层的语言特性，这个选择实际上决定了哪些机制可以方便地实现，而哪些则不能。
    若我们采用过程式语言，可能就要包括诸如“集成”“封装”和“多态”的设计模式。
    相应地，一些特殊的面向对象语言可以直接支持我们的某些模式，例如CLOS 支持多方法概念，
    这就减少了访问者模式的必要性.

具体而言，Norvig 建议在有一等函数的语言中重新审视“策略”“命令”“模板方法”和“访问者”模式.

通常，我们可以把这些模式中涉及的某些类的实例替换成简单的函数，从而减少样板代码.

+ 策略模式
+ 命令模式
