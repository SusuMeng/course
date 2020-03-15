# HTML5 的使用（续）
## HTML 框架、背景和实体（续）
1. 什么是实体？
```
HTML 中预留字符串必须被替换成字符实体
```
2. 常用的字符实体有哪些？
```
不间断空格    &nbsp;
<            &lt;
>            &gt;
等
```
# XHTML 介绍
3. 什么是 XHTML？
```
XHTML 是指可扩展超文本标记语言
XHTML 与HTML4.01几乎是相同的
XHTML 是更严格更纯净的 HTML 版本
XHTML 得到所有主流浏览器的支持
```
4. 为什么使用 XHTML？
```
为了代码的完整性和良好性
```
5. XHTML 的文档声明是什么？
```
DTD：规定了使用通用标记语言的网页语法
```
6. XHTML 的三种文档类型是什么？
```
STRICT(严格类型)
TRANSITIONAL（过渡类型）
FRAMESET（框架类型）
```
7. XHTML 的元素语法是什么？
```
XHTML 元素必须正确嵌套
XHTML 元素必须始终关闭
XHTML 元素必须小写
XHTML 文档必须有一个根元素
```
8. XHTML 属性的语法规则是什么？
```
XHTML 属性必须使用小写
XHTML 属性值必须用引号包围
XHTML 属性最小化也是禁止的
```
# HTML5 与 HTML4的区别
9. HTML5新增了哪些元素？
```
新增的结构元素：section、article、aside、header、hgroup、footer、nav、fligure
新增的其他元素：video、audio、embed、mark、progress、meter、time、ruby、
			   rt、rp、wbrcanvas、command、details、datagrid、Keygen、
			   output、source、menu
新增的 input 元素的类型：email、url、number、range、Date Pickers
```
10. HTML5废除了哪些元素？
```
能使用CSS代替的元素：basefont、big、center、font、s、tt、u 等
不再使用 frame 框架
只有部分浏览器支持的元素
其他被废除的元素
```
11. HTML5中新增了哪些属性？
```
表单相关属性
链接相关属性
其他属性
```
12. HTML5中的全局属性有哪些？
```
contentEditable属性   允许用户编辑元素中的内容
designMode属性     用来指定整个页面是否可编辑
hidden属性       通知浏览器不渲染该元素 使该元素不可见
spellcheck属性    定义是否可以检查元素的拼写错误
tabindex属性     指示其元素是否可以聚焦，以及它是否在何处参与顺序键盘导航
```
13. 如何通过table键获取焦点？
```
默认情况下只有表单元素和链接元素可通过table键获取焦点
tabindex=负值 ，表示元素是可聚焦的，但是不能通过键盘导航来访问到该元素
tabindex="0" ，表示元素是可聚焦的，并且可以通过键盘导航来聚焦到该元素，它的相对顺序是当前处于的DOM结构来决定的。
tabindex=正值，表示元素是可聚焦的，并且可以通过键盘导航来访问到该元素；它的相对顺序按照tabindex 的数值递增而滞后获焦
```
14. HTML5中新增的主体结构元素有哪些？
```
article 元素
section 元素
nav 元素
aside 元素
time 元素与微格式
pubdate 属性
```
15. article 元素的作用是什么？
```
表示文档、页面、应用或网站中的独立结构，其意在成为可独立分配的或可引用的结构
article 元素可以嵌套所用
article 元素可以用来表示插件
```
16. section 元素的作用是什么
```
表示一个包含在HTML文档中的独立部分，它没有更具体的语义元素来表示，一般来说会有包含一个标题。
```
17. acticle 元素和 section 元素的联系和区别？
```
在HTML5中，article 可以看成是一个特殊类的 section 元素，它比 section 元素更加强调
独立性，即 section 元素强调分段或分块，而 article 元素强调的是独立性
```
18. 使用 section 元素时应注意什么?
```
1. 不要将 section 元素作为设置样式的页面容器，这本应该是 div 元素的用法
2. 如果 article元素、aside 元素或 nav 元素更符合使用条件，不要使用 section 元素
3. 不要对没有标题的内容区域块使用 section 元素，因为 section 元素要存在标题
```