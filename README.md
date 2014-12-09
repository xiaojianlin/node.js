#Node.js基本命令

##1、node语法：

要运用node.js的相关语法，先要确保电脑已经安装了Node.js。然后在命令行输入‘node’.

输入了’node’命令后，可以看到命令行发生变化，进入node编辑器状态，这时可以在里面输入你想要输入的代码，Node.js可以直接运行代码段。
<p>例如：</p>

<pre><code>> var numbers = 123 ;
undefined
> console.log (numbers);
123
undefined
>
</code></pre>

可以看到，在Node.js窗口下直接返回数字123.非常方便。

##2、debug用法：

debug是在代码中起到断点的作用，可以方便调试代码。使用时，需将代码’debug‘添加到需断点的位置即可。

##3、require和exports：

在Node.js中，其强大的功能是可以将文件进行关联，方便相互之间的调用。

<p>示例:</p>

<pre><code>//在文件rocjer.js中，添加如下代码
exports.name = functoin (){
  console.log('Hello');
}
//然后在另一个文件中引用时如下
var recker = require('.rocjer.js');
rocker.name();
//输出‘Hello’
</code></pre>

上诉代码中，两个文件在一个文件夹中。需要注意的是代码require和exports需成对出现。
