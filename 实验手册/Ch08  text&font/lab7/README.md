#实验七 CSS基本修饰实战（一）
##一、 实验背景

在web开发过程中，只有HTML代码的页面是非常不美观的，为了让页面变得更漂亮我们必须借助CSS来对HTML的页面元素进行修饰，本章内容中介绍了CSS对HTML中的文字的修饰，包括字体、字号、风格、加粗等，对文本的修饰，包括文本的对齐方式、缩进、行高、文本颜色等，还介绍了CSS对HTML中的超链接的样式修饰，包括为访问过的超链、已访问过的超链接样式，以及鼠标经过超链接的样式等。
  
##二、 实验目的

通过实验能灵活的掌握CSS对HTML中的字体、文本、超链接样式的修饰。

在上一个实验的基础上，对index.html、list.html、content.html页面中的文字，段落和超链接做样式上的修饰，修饰的效果如下图所示：

![](resource/images/index效果图.png)<br/>
图2- 1 index.html 效果图<br/>
![](resource/images/list页效果图.png)<br/>
图2- 2 list.html 效果图<br/>
![](resource/images/content页效果图.png)<br/>
图2- 3 content.html 效果图

##三、 准备材料
本实验用到的图片素材及文字素材全部为的成果（lab5）。

##四、 实验步骤
步骤1.	在css文件夹中创建文件style.css，先然后在index.html，list.html，content.html页面中引用此CSS文件。

步骤2.	在style.css文件中设置三个网页中的通用样式：

1.	将所有html中的默认文字改成12px大小的灰色Arial字体。
2.	将文本的行高统一设置为2em。
3.	将网页中所有的超链接字体设置为：默认的#727272 颜色，没有下划线，当鼠标经过时显示下划线。
4.	将网页中栏目菜单中的普通文字设置为14px大小#b9f605颜色，加粗。
5.	将网页中栏目菜单中的超链接字体设置为白色。
6.	鼠标经过栏目菜单中的超链接时字体变成#b9f605颜色，没有下划线，大小不变。
7.	特殊的栏目中的最后一个超链接默认文字颜色为#fdb306。

步骤3.	对index.html，list.html，content.html三个页面分别做具体的内容样式的设置：首先在css文件夹中创建index.css文件，并在index.html中引用它，然后在index.css中定义index.html中特有的一些元素样式的修饰

![](resource/images/index页文字特殊样式.png)<br/>
图 3-2  index.html文字特殊样式<br/>
图示中的新闻超链接样式比较独特，在index.css中对此超链接做特殊设置：字体为微软雅黑、16px、#65a7d0、加粗。

步骤4.	在css文件夹中创建list.css文件，并在list.html中引用它，然后在list.css中定义list.html中特有的一些元素样式的修饰 

![](resource/images/list页中文字特殊样式.png)<br/>
图 3-3  list.html中文字特殊样式
如上图所示，在list.html中左侧的导航菜单的样式是list.html中特有的，在list.css中设置此导航菜单中超链接的文字为：14px，鼠标经过超链接时：颜色变为#b9f605色，无下划线。

步骤5.	在css文件夹中创建content.css，并在content.html中引用content.css文件，并在content.css文件中对content.html中特殊的元素样式做修饰：

![](resource/images/content中文字特殊样式.png)<br/>
图 3-4  content.html中文字特殊样式

如上图，页面中的一级标题设置为：微软雅黑、20px、#686868、不加粗。
二级标题设置为：Arial、12px、#a9a8a8、不加粗。
![](resource/images/content中文字特殊样式2.png)<br/>
图 3-5  content.html中文字特殊样式

如上图，content.html页面底部的上一篇，下一篇字体颜色设置为：#22a3d3。

![](resource/images/content页缩进样式.png)<br/>
图 3-5  content.html中文本的缩进样式

如上图所示，在内容页中每一段文本都有缩进，所以在content.css中对于段落做缩进设置，缩进值为2em。

至此，整个网页中关于文字的样式修饰基本完成。

##五、 实验总结
1. 总结实验过程中碰到问题及解决办法
2. 实验过程中的感悟

##六、 推荐阅读
1.  网站前端开发(文件,html,js,css)规范文档整理：http://www.111cn.net/cssdiv/css/57963.htm 
