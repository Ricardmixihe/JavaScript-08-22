## JavaScript 是脚本语言

JavaScript 是一种轻量级的编程语言。

JavaScript 是可插入 HTML 页面的编程代码。

JavaScript 插入 HTML 页面后，可由所有的现代浏览器执行。

HTML 中的 Javascript 脚本代码必须位于 **<script>** 与 **</script>** 标签之间。

Javascript 脚本代码可被放置在 HTML 页面的 **<body>** 和 **<head>** 部分中。

您可以在 HTML 文档中放入不限数量的脚本。

脚本可位于 HTML 的 <body> 或 <head> 部分中，或者同时存在于两个部分中。

## JavaScript 显示数据

JavaScript 可以通过不同的方式来输出数据：

- 使用 **window.alert()** 弹出警告框。
- 使用 **document.write()** 方法将内容写到 HTML 文档中。
- 使用 **innerHTML** 写入到 HTML 元素。
- 使用 **console.log()** 写入到浏览器的控制台。



## JavaScript：改变 HTML 内容

使用 JavaScript 来处理 HTML 内容是非常强大的功能。

### 实例

[x=document.getElementById("demo");]()  	//查找元素 

[x.innerHTML="Hello JavaScript";]()  			   //改变内容

## JavaScript 字面量

**在编程语言中，一般固定值称为字面量，如 3.14。**

**数字（Number）字面量** 可以是整数或者是小数，或者是科学计数(e)。

**字符串（String）字面量** 可以使用单引号或双引号:

**表达式字面量** 用于计算

**数组（Array）字面量** 定义一个数组：[40, 100, 1, 5, 25, 10]

**对象（Object）字面量** 定义一个对象：

[{firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"}]()

**函数（Function）字面量** 定义一个函数：

[function myFunction(a, b) { return a * b;}]()



## JavaScript 变量

在编程语言中，变量用于存储数据值。

JavaScript 使用关键字 **var** 来定义变量， 使用等号来为变量赋值

[var x, length]()

[x = 5]()

[length = 6]()



## JavaScript 操作符

JavaScript使用 **算术运算符** 来计算值: 

[(5 + 6) * 10]()

JavaScript使用**赋值运算符**给变量赋值： 

[x = 5
y = 6
z = (x + y) * 10]()

***JavaScript语言有多种类型的运算符：***

| 类型                   | 实例      | 描述                   |
| :--------------------- | :-------- | :--------------------- |
| 赋值，算术和位运算符   | = + - * / | 在 JS 运算符中描述     |
| 条件，比较及逻辑运算符 | == != < > | 在 JS 比较运算符中描述 |



## JavaScript 语句

在 HTML 中，JavaScript 语句用于向浏览器发出命令。

语句是用分号分隔：

[x = 5 + 6;
y = x * 10;]()



## JavaScript 关键字

JavaScript 关键字用于标识要执行的操作。

和其他任何编程语言一样，JavaScript 保留了一些关键字为自己所用。

**var** 关键字告诉浏览器创建一个新的变量：

[var x = 5 + 6;
var y = x * 10;]()

JavaScript 同样保留了一些关键字，这些关键字在当前的语言版本中并没有使用，但在以后 JavaScript 扩展中会用到。

以下是 JavaScript 中最重要的保留关键字（按字母顺序）：

| abstract | else       | instanceof | super        |
| -------- | ---------- | ---------- | ------------ |
|          |            |            |              |
| boolean  | enum       | int        | switch       |
|          |            |            |              |
| break    | export     | interface  | synchronized |
|          |            |            |              |
| byte     | extends    | let        | this         |
|          |            |            |              |
| case     | false      | long       | throw        |
|          |            |            |              |
| catch    | final      | native     | throws       |
|          |            |            |              |
| char     | finally    | new        | transient    |
|          |            |            |              |
| class    | float      | null       | true         |
|          |            |            |              |
| const    | for        | package    | try          |
|          |            |            |              |
| continue | function   | private    | typeof       |
|          |            |            |              |
| debugger | goto       | protected  | var          |
|          |            |            |              |
| default  | if         | public     | void         |
|          |            |            |              |
| delete   | implements | return     | volatile     |
|          |            |            |              |
| do       | import     | short      | while        |
|          |            |            |              |
| double   | in         | static     | with         |



## JavaScript 注释

不是所有的 JavaScript 语句都是"命令"。双斜杠 **//** 后的内容将会被浏览器忽略：

// 我不会执行



## JavaScript 数据类型

JavaScript 有多种数据类型：数字，字符串，数组，对象等等：

[var length = 16;                  												  // Number 通过数字字面量赋值 
var points = x * 10;               											   // Number 通过表达式字面量赋值
var lastName = "Johnson";             								    // String 通过字符串字面量赋值
var cars = ["Saab", "Volvo", "BMW"];      						  // Array 通过数组字面量赋值
var person = {firstName:"John", lastName:"Doe"}; 	  // Object 通过对象字面量赋值]()



## JavaScript 函数

JavaScript 语句可以写在函数内，函数可以重复引用：

**引用一个函数** = 调用函数(执行函数内的语句)。

[function myFunction(a, b) {
  return a * b;                // 返回 a 乘以 b 的结果
}]()

##### 

------

## JavaScript 字母大小写

JavaScript 对大小写是敏感的。

当编写 JavaScript 语句时，请留意是否关闭大小写切换键。

函数 *[**getElementById**]()* 与 *[**getElementbyID**]()* 是不同的。

同样，变量 **[*myVariable*]()** 与 *[**MyVariable**]()* 也是不同的。



# JavaScript 语句

------

JavaScript 语句向浏览器发出的命令。语句的作用是告诉浏览器该做什么。

## 分号 ;

分号用于分隔 JavaScript 语句。

通常我们在每条可执行的语句结尾添加分号。

使用分号的另一用处是在一行中编写多条语句。

## JavaScript 代码

JavaScript 代码是 JavaScript 语句的序列。

浏览器按照编写顺序依次执行每条语句。

## JavaScript 代码块

JavaScript 可以分批地组合起来。

代码块以左花括号开始，以右花括号结束。

代码块的作用是一并地执行语句序列。

## JavaScript 语句标识符

JavaScript 语句通常以一个 **语句标识符** 为开始，并执行该语句。

语句标识符是保留关键字不能作为变量名使用。

下表列出了 JavaScript 语句标识符 (关键字) ： 

| 语句         | 描述                                                         |
| :----------- | :----------------------------------------------------------- |
| break        | 用于跳出循环。                                               |
| catch        | 语句块，在 try 语句块执行出错时执行 catch 语句块。           |
| continue     | 跳过循环中的一个迭代。                                       |
| do ... while | 执行一个语句块，在条件语句为 true 时继续执行该语句块。       |
| for          | 在条件语句为 true 时，可以将代码块执行指定的次数。           |
| for ... in   | 用于遍历数组或者对象的属性（对数组或者对象的属性进行循环操作）。 |
| function     | 定义一个函数                                                 |
| if ... else  | 用于基于不同的条件来执行不同的动作。                         |
| return       | 退出函数                                                     |
| switch       | 用于基于不同的条件来执行不同的动作。                         |
| throw        | 抛出（生成）错误 。                                          |
| try          | 实现错误处理，与 catch 一同使用。                            |
| var          | 声明一个变量。                                               |
| while        | 当条件语句为 true 时，执行语句块。                           |

------

## 空格

JavaScript 会忽略多余的空格。您可以向脚本添加空格，来提高其可读性。

## 对代码行进行折行

您可以在文本字符串中使用反斜杠对代码行进行换行。



# JavaScript 变量

------

变量是用于存储信息的"容器"。

x=5
y=6
z=x+y

在代数中，我们使用字母（比如 x）来保存值（比如 5）。

通过上面的表达式 z=x+y，我们能够计算出 z 的值为 11。

在 JavaScript 中，这些字母被称为变量。

## JavaScript 变量

与代数一样，JavaScript 变量可用于存放值（比如 x=5）和表达式（比如 z=x+y）。

变量可以使用短名称（比如 x 和 y），也可以使用描述性更好的名称（比如 age, sum, totalvolume）。

- 变量必须以字母开头
- 变量也能以 $ 和 _ 符号开头（不过我们不推荐这么做）
- 变量名称对大小写敏感（y 和 Y 是不同的变量）

## JavaScript 数据类型

JavaScript 变量还能保存其他数据类型，比如文本值 [(name="Bill Gates")]()。

在 JavaScript 中，类似 ["Bill Gates"]() 这样一条文本被称为字符串。

JavaScript 变量有很多种类型，但是现在，我们只关注数字和字符串。

当您向变量分配文本值时，应该用双引号或单引号包围这个值。

当您向变量赋的值是数值时，不要使用引号。如果您用引号包围数值，该值会被作为文本来处理。



## 声明（创建） JavaScript 变量

在 JavaScript 中创建变量通常称为"声明"变量。

我们使用 var 关键词来声明变量：

[var carname;]()

变量声明之后，该变量是空的（它没有值）。

如需向变量赋值，请使用等号：

[carname="Volvo";]()

不过，您也可以在声明变量时对其赋值：

[var carname="Volvo";]()

## 一条语句，多个变量

您可以在一条语句中声明很多变量。该语句以 var 开头，并使用逗号分隔变量即可：

[var lastname="Doe", age=30, job="carpenter";]()

## Value = undefined

在计算机程序中，经常会声明无值的变量。未使用值来声明的变量，其值实际上是 undefined。

在执行过以下语句后，变量 carname 的值将是 undefined：

## 重新声明 JavaScript 变量

如果重新声明 JavaScript 变量，该变量的值不会丢失：

在以下两条语句执行后，变量 carname 的值依然是 "Volvo"：

## JavaScript 算数

您可以通过 JavaScript 变量来做算数，使用的是 = 和 + 这类运算符：

## 使用 let 和 const (ES6)

在 2015 年以前，我们使用 var 关键字来声明 JavaScript 变量。

在 2015 后的 JavaScript 版本 (ES6) 允许我们使用 const 关键字来定义一个常量，使用 let 关键字定义的限定范围内作用域的变量。

# JavaScript 数据类型

------

**值类型(基本类型)**：字符串（String）、数字(Number)、布尔(Boolean)、空（Null）、未定义（Undefined）、Symbol。

**引用数据类型（对象类型）**：对象(Object)、数组(Array)、函数(Function)，还有两个特殊的对象：正则（RegExp）和日期（Date）。

## JavaScript 拥有动态类型

JavaScript 拥有动态类型。这意味着相同的变量可用作不同的类型：

### 实例

var x;        // x 为 undefined
var x = 5;      // 现在 x 为数字
var x = "John";   // 现在 x 为字符串



## JavaScript 字符串

字符串是存储字符（比如 "Bill Gates"）的变量。

字符串可以是引号中的任意文本。您可以使用单引号或双引号：

### 实例

[var carname="Volvo XC60";
var carname='Volvo XC60';]()

## JavaScript 数字

JavaScript 只有一种数字类型。数字可以带小数点，也可以不带：

### 实例

var x1=34.00;   //使用小数点来写
var x2=34;     //不使用小数点来写

## JavaScript 布尔

布尔（逻辑）只能有两个值：true 或 false。

[var x=true;
var y=false;]()

## JavaScript 数组

下面的代码创建名为 cars 的数组：

[var cars=new Array();
cars[0]="Saab";
cars[1]="Volvo";
cars[2]="BMW";]()

或者 [(condensed array):]()

[var cars=new Array("Saab","Volvo","BMW");]()

## JavaScript 对象

对象由花括号分隔。在括号内部，对象的属性以名称和值对的形式 (name : value) 来定义。属性由逗号分隔：

[var person={firstname:"John", lastname:"Doe", id:5566};]()

上面例子中的对象 (person) 有三个属性：firstname、lastname 以及 id。

## Undefined 和 Null

Undefined 这个值表示变量不含有值。

可以通过将变量的值设置为 null 来清空变量。

### 实例

[cars=null;
person=null;]()

## 声明变量类型

当您声明新变量时，可以使用关键词 "new" 来声明其类型： 

[var carname=new String;
var x=   new Number;
var y=   new Boolean;
var cars=  new Array;
var person= new Object;]()



# JavaScript 函数

------

函数是由事件驱动的或者当它被调用时执行的可重复使用的代码块。



## JavaScript 函数语法

函数就是包裹在花括号中的代码块，前面使用了关键词 function：

[function *functionname*()
{
  *// 执行代码*
}]()



## 调用带参数的函数

在调用函数时，您可以向其传递值，这些值被称为参数。

这些参数可以在函数中使用。

您可以发送任意多的参数，由逗号 (,) 分隔：

myFunction(*argument1,argument2*)

## 带有返回值的函数

有时，我们会希望函数将值返回调用它的地方。

通过使用 return 语句就可以实现。

在使用 return 语句时，函数会停止执行，并返回指定的值。

### 语法

[function myFunction()
{
  var x=5;
  return x;
}]()

## 局部 JavaScript 变量

在 JavaScript 函数内部声明的变量（使用 var）是*局部*变量，所以只能在函数内部访问它。（该变量的作用域是局部的）。

您可以在不同的函数中使用名称相同的局部变量，因为只有声明过该变量的函数才能识别出该变量。

只要函数运行完毕，本地变量就会被删除。

------

## 全局 JavaScript 变量

在函数外声明的变量是*全局*变量，网页上的所有脚本和函数都能访问它。

------

## JavaScript 变量的生存期

JavaScript 变量的生命期从它们被声明的时间开始。

局部变量会在函数运行以后被删除。

全局变量会在页面关闭后被删除。

------

## 向未声明的 JavaScript 变量分配值

如果您把值赋给尚未声明的变量，该变量将被自动作为 window 的一个属性。

这条语句：

carname="Volvo";

将声明 window 的一个属性 carname。

非严格模式下给未声明变量赋值创建的全局变量，是全局对象的可配置属性，可以删除。





```javascript
var var1 = 1; // 不可配置全局属性
var2 = 2; // 没有使用 var 声明，可配置全局属性

console.log(this.var1); // 1
console.log(window.var1); // 1
console.log(window.var2); // 2

delete var1; // false 无法删除
console.log(var1); //1

delete var2; 
console.log(delete var2); // true
console.log(var2); // 已经删除 报错变量未定义
```





# JavaScript 作用域

------

作用域是可访问变量的集合。

------

## JavaScript 作用域

在 JavaScript 中, 对象和函数同样也是变量。

**在 JavaScript 中, 作用域为可访问变量，对象，函数的集合。**

JavaScript 函数作用域: 作用域在函数内修改。

------

## JavaScript 局部作用域

变量在函数内声明，变量为局部变量，具有局部作用域。

局部变量：只能在函数内部访问。

// 此处不能调用 carName 变量

 function myFunction() { 

  	 var carName = "Volvo";    // 函数内可调用 carName 变量 

}


尝试一下 »

因为局部变量只作用于函数内，所以不同的函数可以使用相同名称的变量。

局部变量在函数开始执行时创建，函数执行完后局部变量会自动销毁

## JavaScript 全局变量

变量在函数外定义，即为全局变量。

全局变量有 **全局作用域**: 网页中所有脚本和函数均可使用。 

### 实例

[var carName = " Volvo";  // 此处可调用 carName 变量 function myFunction() {    // 函数内可调用 carName 变量 }]()



## JavaScript 变量生命周期

JavaScript 变量生命周期在它声明时初始化。

局部变量在函数执行完毕后销毁。

全局变量在页面关闭后销毁。

------

## 函数参数

函数参数只在函数内起作用，是局部变量。

------

## HTML 中的全局变量

在 HTML 中, 全局变量是 window 对象: 所有数据变量都属于 window 对象。

### 实例

//此处可使用 window.carName  function myFunction() {    carName = "Volvo"; }