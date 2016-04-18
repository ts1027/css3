# css3
>这是选择器
css3的练习
-----------------------------------------------------------------
- 2016-04-18

##css3选择器
1.css后代选择器
	- .list li:only-child      选中list中唯一一个li子元素
	list :only-child         选中list中唯一一个子元素

:root  选择文档的根元素。 【选择的是html】
p:empty  选择没有子元素的每个 <p> 元素（包括文本节点）。
快标签的宽高是父容器的


3.伪类选择器
	- :focus  匹配获得焦点的input元素
	- ：first-letter 匹配p标签的第一个文字
	- ：firsr-line  匹配p标签的第一行文字
	- ：before	在某个p标签之前插入内容。（插入的是行内标签）
	- ：after	在某个p标签之后插入内容

> :before、:after 功能

> 1.清除浮动

```css
/*清除浮动*/
.clf:after,.clf:before{
	content:"“";
	display:bolck;
	clear:both;
}
```
> 2.做一些常用的效果  “”  加上图标

4.属性选择器
	- [attr] 选择带有指定属性的元素
	- [attr=value] 选中带有选中值的时候
	- [attribute~=value]  选中指定的

5.UI伪类选择器