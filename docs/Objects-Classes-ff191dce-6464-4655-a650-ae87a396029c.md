# Objects & Classes

- 方法返回时使用return new:

    return new object(a);
    //相当于
    Object o = new Object(a);
    return 0;

- 数组列表：

假设想创建一个用于存储整数的 ArrayList, 可以使用下面代码来创建一个列表吗？

     ArrayList<int> list = new ArrayList<>()；

 答案是不行。这样行不通，因为存储在 ArrayList 中的元素必须是一种对象。不能使用 诸如 int 的基本数据类型来代替一个泛型类型。然而，你可以创建一个存储 Integer 对象的 ArrayList, 如下所示：

    ArrayList<Integer> list = new ArrayList<>();