# Markdown语法

### 标题设置
在markdown当中设置标题，有两种方法
* 第一种：通过在文字下方添加“ = ”和 “ - ”，他们分别代表一级标题和二级标题
* 第二种：在文字开头加上“#”，通过“#”数量表示几级标题。(一共只有1-6个标题，1级标题字体最大)。

### 块注释
（blockquote）
* 通过在文字开头加“>”表示块注释。（当 > 和文字之间添加五个Blank时，块注释的文字会有变化。）

>     aaaaaaaaaaaa
>     aaaaaaaaaaaaaaaaaaaaaa
>     aaaaaaaaaaavvvvvvvvvvvvv
>     ddddddddddddddd
>     dcccccccccccc

### 斜体
* *将需要设置为斜体的文字两端使用1个“*”或者“_”夹起来。

### 粗体
* **将需要设置为粗体的文字两端使用两个“*”或者“_”夹起来。**

### 无序列表
* 在文字开头添加（*，+ and -）实现无序列表，但是要注意在（*，+ and -）和文字之间需要添加空格。
（建议：一个文档中只是用一种无序列表的表示方法）

### 有序列表
* 使用数字后面跟上英文句点

### 链接
markdown中右两种方式，实现链接，分别问内联方式和引用方式。
* 内联方式：This is an [baidu link](http://www.baidu.com)
* 引用方式： I get 10 times more traffic from [Google][1] than from [Yahoo][2] or [MSN][3]
[1]:http://google.com/          'Google'
[2]:http://search.yahoo.com/    'Yahoo Search'
[3]:http://search.msn.com/      'MSN Search'

### 图片
图片的处理方式和链接的处理方式，非常的类似
* 内联方式：`![alt text](/path/to/img.jpg "Title")`
* example:`![联系素材](markdownM.png)`
* 引用方式:<br>
`![alt text][id]`<br>
`[id]:/path/to/img.jpg "Title"`

### 代码
HTML中所谓的code，实现方式有两种
* 第一种：简单文字出现一个代码框。使用`<blockquote>`,(`注意不是单引号，而是ESC键下的一个按键`)
* 第二种： 大片文字需要实现代码框。使用tab和四个空格。
    <p>hello 2017</p>
    <p>hello 2017</p>
    <p>hello 2017</p>
<pre>
<code>
\<p\>hello world \</p\>
</code>
</pre>

### 脚注
* 实现方式如下
    hello[^hello]


    [^hello]:hi

### 下划线
* 在空白行下方添加三条‘-’横线。

- - -
