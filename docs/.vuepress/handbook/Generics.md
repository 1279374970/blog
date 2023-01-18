**一、去除**** img ****标签底部空白的方法**

![](RackMultipart20230118-1-tvu9ry_html_8a3f9f81e4a630ce.png)

**二**** flex ****布局**

![](RackMultipart20230118-1-tvu9ry_html_e0a7b083f59eaba8.png)

justify-content: space-evenly;

table布局

\<table\>

\<tr\>

\<th\>\</th\>

\</tr\>

\<tr\>

\<td\>\</td\>

\</tr\>

\</table\>

如何设置scroll的高度

可以通过height:calc(%-头部)

function() {

this.counter+= 1

等同于 function () {

if(++this.counter)

watch 事件监听

监听数据的变化 可以增加性能(避免重复监听数据的改变)

v-if="Object.keys(detailInfo).length !== 0"

**监听数据是否挂在在**** dom ****上如果没有的话就不显示该内容**

**解决**** scroll ****滑动的加载出现卡顿问题**

![](RackMultipart20230118-1-tvu9ry_html_e2b779f9a3ba19ee.png)

先监听图片的加载

执行loadImg() , 数据的长度和加载的长度进行判断

执行下一步的自定义事件$emit ,在scroll组件上 定义一个 ref

获取到scroll组件的refresh() ,并执行

x详细操作如下:

![](RackMultipart20230118-1-tvu9ry_html_e925c380498e8cac.png)

![](RackMultipart20230118-1-tvu9ry_html_9b747c97007fac03.png)

**逻辑运算符**

![](RackMultipart20230118-1-tvu9ry_html_e4a423739e4644dd.png)

时间戳 转化成时间格式化字符串(常用)

![](RackMultipart20230118-1-tvu9ry_html_ae7efa358b074e4d.png)

正则表达式 字符串

时间格式化很重要在以后的公司百分之百会遇到的

滚动的问题

compute 是依赖已有变量来计算一个目标变量,大多数情况都是多个变量,并且 computed 具有缓存机制,依赖值不变的情况下其直接读取缓存进行赋值,computed不能进行异步操作

2.watch 时间挺某个变量的变化,并执行相应的回调函数,通常是一个变量的变化决定多个变量的变化,watch 可以进行异步操作

简单记就是:一般情况下compute是多对一

watch是一对多

vue的生命周期

![](RackMultipart20230118-1-tvu9ry_html_47e94308f5711cac.jpg)

数组的迭代方法

ECMAScript 为数组定义了五个迭代方法

每个方法都接收两个参数; 要在每一项上的函数和(可选项) 运行该函数的作用域对象--影响this的值

传入这些方法中的函数会接受参数:数组项的值 该函数中的位置和数组对象本省.

根据使用的方法不同,这个函数执行后的返回值可能会也可能不会影响方法的返回值.

以下是这五个迭代方法的作用.

1.every ()

对数组中的每一项运行给定的函数,如果该函数对每一项都返回true,则返回true.

2. some ()

对数组的每一项运行给定的函数,如果该函数对任一的返回true ,则返回ttrue.

filter ()

对函数中的每一项运行给定函数,返回该函数会返回true 的项组成的数组

map ()

对数组中的每一项运行给定函数,返回的每次函数调用的结果组成的数组

forEach ()

对数组的每一项运行给定的函数,该方法没有返回值,本质上与使用for循环迭代数组一样.

用户评价

![](RackMultipart20230118-1-tvu9ry_html_935abf27386ea169.png)

取消全局事件的监听 this.$bus.$off()

![](RackMultipart20230118-1-tvu9ry_html_724302331d42511f.png)

在离开的时候取消这个函数

要先将这个函数拿出来

解决公用一个goosItem 数据的加载问题 在mounted()里面获获取全局的$bus 并定义起方法 =\>

newRefresh() 这个方法其实就是包装的防抖函数 ,

在使用后再deactived里面取消全局的$bus 及方法 讲方法定义在外面 用this.来引用

如果该路由再Keep- alive里面排除的那么应该在 该组件下的destroyed ()里取消

![](RackMultipart20230118-1-tvu9ry_html_1258a1096c414a5c.png)

混入 :mixin

继承可以减少类的代码

对象里面的重复代码不能用继承

在组件中重复使用的一些代码

可以定义一个mixin.js的文件要将混入的文件及依赖的文件导入其中

在到需要的地方引入文件 和在下面定义 mixin :[传入的混入的对象]

混入是vue里面的高级部分

![](RackMultipart20230118-1-tvu9ry_html_144f3d73d9895e84.png)

topcontrol

![](RackMultipart20230118-1-tvu9ry_html_27e368a6d8ec9e66.png)

深入对象

![](RackMultipart20230118-1-tvu9ry_html_afb5792802529016.png)

![](RackMultipart20230118-1-tvu9ry_html_29c551eb087f1dd9.png)

![](RackMultipart20230118-1-tvu9ry_html_4bba15377510d5b4.png)

**for**** 循环遍历**

![](RackMultipart20230118-1-tvu9ry_html_b05db2189220fa07.png)

**嵌套数组的解构**

**在**** js ****中数组是可以嵌套的**

获取嵌套的里面的属性

可已通过

array[][]

还可以使用解构语法

[,,,,[,,array]]

使用展开语法(Spred Syntax) 和剩余参数

(Rest Parameter)

从es6开始通过...(连续三个点)可以在数组结构中使用展开语法和剩余参数

使用剩余参数时,...出现在节构语法中语法表达式的左边

使用展开语法时,..出现在结构语法表达式的右边

**解构的使用场景**

1.使用解构来交换值

let frist = '10'

let second = '20'

[first , second] = [second , frist];

合并数组

const array1 = []

const array2 = []

const newarray = [...array1,...array2]

**作用域插槽**** ( ****最新**** )**

attribute语法

为了能在子组件里定义的插槽能在父组件里使用,我们将子组件里插槽的对象

作为\<slot\>元素的一个Sttribute绑定上去

\<span\>

\<slot v-bind:user="user"\>

{{ user.lastName }}

\</slot\>

\</span\>

绑定在\<slot\>元素多行的attribute被称为插槽prop 在父级作用域中,我们可以使用带值的

v-slot来定义我们提供的插槽prop的名字

\<current-user\>

\<template v-slot:default="slotProps"\>

{{ slotProps.user.firstName }}

\</template\>

\</current-user\>

这个例子中,我们选择将包含所有的插槽prop的对象明明为sloProps,但是也可使使用任意你喜欢的名字.

阻止事件冒泡

.stop

阻止默认事件

.prevent

冒泡事件由内向外,变成由外向内

.capture

去除收尾空格

trim

不需要响应式的数据的处理方式

方法一

data () {

this.list1 = {xxxxxxxxxxxxx}

this.list2 = {xxxxxxxxxxxxx}

this.list3 = {xxxxxxxxxxxxx}

}

方法二

data () {

list1.Object.freeze({xxxxxxxxxxxxx}),

list2.Object.freeze({xxxxxxxxxxxxx}),

list3.Object.freeze({xxxxxxxxxxxxx}),

list4.Object.freeze({xxxxxxxxxxxxx}),

}

object.key()

object.value()

object.assign()

可以实现对象的合并

![](RackMultipart20230118-1-tvu9ry_html_183dbc044fdc1789.png)

高阶函数

![](RackMultipart20230118-1-tvu9ry_html_e9f36f57a6f8df3f.png)

**浅拷贝 深拷贝**

浅拷贝 其实就是简单对象 更深层次对象级别的拷贝就会修改里面的属性 和变量位置的赋值修改其中的变量属性 就会被修改 (只拷贝最外面一层)

Object.assign(,) 完成了对象的拼接(也是属于浅拷贝)

深拷贝

判断是数据类型的时候 array 和object 时要先判断array 因为数组也是object类型

var obj ={

name :'xioahu',

age :23,

old :{

name:'xioafang',

age:15

},

arr: [23,12,21]

}

var o = {

}

function deepCopy (newobj,oldobj) {

for(var k in oldobj ) {

//判断属性的属性值属于那种类型

var item = oldobj[k]

//是否是数组类型

if(item instanceOf Array ) {

newonj[k] = []

//是的话再次执行

deepCopy(newobj[k],item)

//判断是否是对象属性

}else if(item instance Object) {

newobj[k] = {};

deepcopy(newobj[k] ,item)

//判断是否是简单数据类型

}else {

newobj[k] = item

}

}

}

deepCopy(o , obj )

创建set结构数据

var num = new Set(['a','b'])

利用set() 去重

![](RackMultipart20230118-1-tvu9ry_html_efa25051fe076f28.png)

查看数据类型

Object.proprototype.toString().call(查询对象)

![](RackMultipart20230118-1-tvu9ry_html_eaa971dcdcbc3c3b.png)

![](RackMultipart20230118-1-tvu9ry_html_20bc43d722bc0f8d.png)