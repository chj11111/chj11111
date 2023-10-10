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
    public static Single get_single() {
        return s;
    }  
```
###静态方法只能调用静态属性（主要是由对象生成顺序所导致的）
###单子模式的优点：节省内存
###构建新的对象耗费资源
###什么时候用全静态方法？什么时候用单子模式？
###程序加载顺序：静态->非静态
###全静态就会导致系统耗费大量资源
```ArrayList```动态数组，不记录数据类型，用Object存储
###构造方法
```ArrayList mylist = new ArrayList();```
```add()```方法添加元素
```get()```方法返回元素

###泛型不接收继承

