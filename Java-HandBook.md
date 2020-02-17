# Java

* [类型](#类型)
* [关键字](#关键字)
* [集合]
* [泛型]


------
## 类型

#### 8种数据类型各占多少字节？
<details>
<summary>展开</summary>

类型 | 字节数
---|---
int | 4
short | 2
long | 8
byte | 1
float | 4
double | 8
char | 2
boolean | 1
</details>

#### int 和Integer的区别
<details>
<summary>展开</summary>
1.  Integer是int的包装类，int则是java的一种基本数据类型。  
2.  Integer变量必须实例化后才能使用，而int变量不需要。  
3.  Integer实际是对象的引用，当new一个Integer时，实际上是生成一个指针指向此对象；而int则是直接存储数据值。  
4.  Integer的默认值是null，int的默认值是0。  

</details>
---
## 关键字

#### protected，private，public，default确定访问权限
<details>
<summary>展开</summary>

|关键字|类内部|本包|子孙类|其他包|
|-|-|-|-|-|
|public|可以|可以|可以|可以|
|protected|可以|可以|可以|不可以|
|default|可以|可以|不可以|不可以|
|private|可以|不可以|不可以|不可以|

protected：本包和所有子类都可见（本包中的子类非子类均可访问，不同包中的子类可以访问，不是子类不能访问）

</details>

#### volatile
<details>
<summary>展开</summary>


</details>