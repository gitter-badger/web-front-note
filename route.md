前端的学习主要是三个部分：
HTML, CSS, JavaScript

#### HTML
HTML决定了一个页面具体显示什么内容。

例如：

```html
<h1>Hello World</h>
```

这一部分代码表示网页中有一个内容为"Hello World"的一级标题，其中`<h1>`标志着一级标题的开始，`</h1>`标志着一级标题的结束。

#### CSS
CSS决定了内容以何种样式显示。

例如：

```html
<h1 style="color: blue;">Hello World</h>
```

其中`style="color: blue;"`便属于CSS部分，作用在于将一级标题"Hello World"以蓝色字体显示。

#### JavaScript
JavaScript决定了当某一行为发生时，浏览器执行什么样的动作。

例如：

```html
<script>
  $(document).ready(function(){
    $("h1").css("color","red")
  });
</script>
<h1>Hello World</h>
```

其中`<script>`和`</script>`之间的内容为JavaScript(这里采用的是jQuery库中的内容，会在JavaScript中详述)，定义了以下内容：

* 当浏览器加载完成之后，将一级标题"Hello World"的字体颜色设置成红色。

学习框架先从HTML开始，再进行CSS的基础准备。

当完成HTML和CSS的基础知识储备之后，学习一些CSS的高级技能，包括对bootstrap的应用。

最后进行JavaScript的学习。
