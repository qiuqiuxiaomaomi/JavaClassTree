# JavaClassTree
###Class文件解析

javap解析


![](https://i.imgur.com/HwQ83NJ.png)

<pre>
字节码文件结构
     魔术字 CAFE BABE
     源文件名称.java
     Jdk大版本号
     Jdk小版本号
</pre>

常量池数据类型

![](https://i.imgur.com/6LBXIpD.png)


AccessFlag 访问控制标示

![](https://i.imgur.com/Hcf4imB.png)


类索引

类索引用于确定类的全限定名
通过搜索常量池，得到类的全限定名称


父类索引
与类索引方法相同

接口索引
与类索引方法相同

![](https://i.imgur.com/gWffcrk.png)

<pre>
字段表集合
      字段表用于描述类和接口中声明的变量，包含了类级别变量以及实例变量，但是不包括方法内部声明的局部变量。
</pre>

![](https://i.imgur.com/91gXYOd.png)

<pre>
Java运行时常量池 VS Class文件常量池
</pre>
