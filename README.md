# how-to-use-github
如何使用github进行一些实际需要的操作
## 如何创建一个项目
 [新建一个项目仓库链接](https://jingyan.baidu.com/article/8cdccae9269b1f315413cde2.html)
## 如何编辑README.md
### 标题
#加空格加标题：表示一级标题，以此类推。
##二级标题  
###三级标题  
####四级标题  
#####五级标题  
######六级标题
### 显示文本
#### 普通文本
这是一段普通的文本，直接回车不能换行，<br>  
要使用\<br>进行换行或者增加空白行，用‘\’转义字符来输出特殊字符，如\ 加\<br>就可以在页面输出\<br><br>
直接回车不能换行，可以在上一行文本后面补两个空格，这样下一行的文本就换行了。或者就是在两行文本直接加一个空行。也能实现换行效果，不过这个行间距有点大。
#### 单行文本
使用两个Tab符实现单行文本。注意在句子前面加两个Tab <br>
  Hello, 我是罗晋
#### 部分文字的高亮
使用‘’把文字圈起来，注意这不是单引号，而是Tab上方，数字1左边的按键（注意使用英文输入法）。<br>
Thank `You` . Please `Call` Me `Coder` <br>
我的`名字`叫`罗晋`
#### 文字超链接
语法为\[文字](链接)<br>
如：\[程序羊的github](https://github.com/hansonwang99/JavaCollection)<br>
效果：[程序羊的github](https://github.com/hansonwang99/JavaCollection)<br>
鼠标悬停显示提示信息，即在URL之后 用双引号括起来一个字符串。同样要注意这里是英文双引号。<br>
如：\[程序羊的github](https://github.com/hansonwang99/JavaCollection"程序羊的Java学习路线")<br>
#### 层级结构
##### 一级结构
语法：\* 加词或句子, 要注意的是星号* 后面要有一个空格。否则显示为普通星号<br>
例子：<br>
\* 昵称：迪迦 <br> 
\* 别名：奥特曼 <br> 
\* 英文名：TiGa <br>
效果：
* 昵称：迪迦 <br> 
* 别名：奥特曼 <br> 
* 英文名：TiGa <br>
##### 多级结构
如二级圆点和三级。就是多加一个2个Tab <br>
例子：<br>
\* 编程语言  <br> 
Tab Tab\* 脚本语言  <br> 
Tab Tab Tab Tab\* Python<br> 
Tab Tab Tab Tab\* Javascript<br> 
效果：
* 编程语言  <br> 
  * 脚本语言  <br> 
    * Python <br>
    * Javascript <br>
##### 缩进
语法：>加句子或词<br>
例子：
\>数据结构  <br>
\>>树  <br>
\>>>二叉树  <br>
\>>>>平衡二叉树  <br>
效果：
>数据结构  
>>树  
>>>二叉树  
>>>>平衡二叉树  
>>>>>满二叉树
##### 本页面节点跳转
语法：\[内容](#节点名)<br>
例子：<br>
\[跳到显示文本](#显示文本)<br>
\[回到顶部](#readme)<br>
效果：
[跳到显示文本](#显示文本) <br>
[回到顶部](#readme) <br>
### 插入图片
* 来源于网络的图片 <br>
基本的语法:叹号! + 方括号[ ] + 括号( ) 其中叹号里是图片的URL<br>
例子1：\!\[baidu](http://www.baidu.com/img/bdlogo.gif)<br>
例子2：\!\[baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")<br>
效果：右图在<br>
![baidu](http://www.baidu.com/img/bdlogo.gif)
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
* GitHub仓库里的图片 <br>
基本的语法:叹号! + 方括号[ ] + 括号( ) 其中叹号里是图片的URL<br>
![GitHub](https://github.com/luojin1010/how-to-use-github/迪迦头像.jpg)
