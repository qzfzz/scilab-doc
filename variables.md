# 变量
scilab的变量定义与其他类的脚本语言相似如python, php, bash, javascript等不需要定义可以直接赋值（即第一次赋值为其定义）。
也可以使用转换函数来进行定义这样我们定义的变量.
如
```scilab
a=3
disp(a)

a1=3.2
disp(a1)

a2='hello'
disp(typeof(a2))

disp(a2)
b=[1,2,3]
disp(b)
disp(typeof(b))

c=[1,2,3;4,5,6]
disp(c)

c=int32(9)
disp(c)
disp(typeof(c))
```

