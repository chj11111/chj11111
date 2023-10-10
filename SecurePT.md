#安全编程技术
##类加载器是什么？
##类加载器的委托模式？
##单子模式？仅有一个对象
###单子模式{
1、私有构造方法
2、指向自己实例的静态引用
3、以自己实例为返回值的公有方法
}
```
no public but private
private static Single s = new Single();
public static Single get_single()
{
    return s;
}

