- C++构造函数有哪几种？分别有什么用途？
- const 的用途？
- 阐述一下代码会发生什么？
```
class A{
    public:
        A(double i);  
        // explicit A(double i);  
        //virtual ~A(){}
};
A a = 2;
```
- 写一个C++类，可以实现无类型操作，例如a=1, a='abc', a=3.134
- std::deque的底层实现,  std::queue的实现
- std::make_shared的原理，
- shared_from_this的作用
- T&、std::unique_ptr<T>、std::unique_ptr<T> &, std::unique_ptr<T> &&的区别?
- shared_ptr是线程安全的吗？如何做到线程安全?
- 内联函数、构造函数、静态成员函数可以是虚函数吗? 必须是public的吗? 自己实现了构造函数，比那一期会怎么做?
- inline关键字用来做什么？什么情况下会内联什么情况下不会内联？
- 什么是结构体内存对齐，如何内存对齐，内存对齐有什么好处？
- constexpr常量表达式是什么？用途是什么？
- std::enable_if怎么使用？作用是什么?
- 结构化绑定有什么优势？
- 如果基类中有虚函数，纯虚函数，子类集成后，没有实现，可以吗？虚函数可以是static的吗？
- 如果是单cpu的系统，还有没有做多线程安全保护吗？cpu绑定有必要吗？
- “vtable是什么时候创建？如果编译时，报错undefined reference to `vtable”，可能会是什么原因？
- gdb的时候如果想查看调用栈信息，怎么看？
- 返回一个局部对象的引用，和返回一个局部对象的右值引用，有何区别？
- new和malloc区别？ 内存碎片？
- 在类继承中，子类如何调用父类的构造函数？
- 在类外部有个同名函数，可以直接使用吗？
- const函数中使用了非const修饰的变量，非const函数使用了const修饰的变量可以吗？
- 你自己提供一个库，如何考虑接口，编译集成，多态，用户程序如何升级？
- c++如何支持异步调用？
- 空指针是否可以调用成员函数？成员函数中是否可以调用delete this？
- map迭代器失效怎么避免？
- static成员变量可以类中赋值吗？
- 类中定义了一个成员函数，没有实现会不会有啥问题？
- shared_ptr是线程安全的吗？读写如何保证线程安全?
- 依赖动态链接库的头文件中如有inline函数会怎样？
-  C++ 里可能出现的内存问题大致有哪几个方面？
    1. 缓冲区溢出  . 空悬指针/野指针  3. 重复释放  4. 内存泄漏  5. 不配对的 new[]/delete   6. 内存碎片
