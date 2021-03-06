# 新增的主体元素
1. nav 元素的作用是什么？
```
nav 元素是一个可以用作页面导航的连接组，其中的导航元素连接到其他页面或当前页面的其他部分。
```
2. 是所有的连接组都要放进 nav 元素中吗？
```
不是，只需要将主要的基本连接组放进 nav 元素即可
```
3. nav 元素应用的场景有哪些？
```
传统导航栏、侧边栏导航、页内导航、翻页操作
```
4. aside元素的作用是什么？
```
aside 元素用来表示当前页面或文章的附属信息部分，它可以包含与当前页面或主要内容相关的引用、
侧边栏、广告、导航条，以及其他类似的有区别于主要内容的部分。
```
5. 有哪两种用法？
```
1.在 article 中嵌套使用
2.在 article 之外进行使用，作为页面的附属信息部分
```
6. 什么是微格式？
```
它是一种利用HTML5的class属性对网页添加附属信息的方法。附加的信息有可能是新闻发生的日期、
日期、个人电话号码等
```
7. time元素的作用是什么？
```
用来表示24小时制时间或者公历日期，若表示日期则也可包含时间和时区。此元素意在以机器可读的格式表示日期和时间。
```
8. time元素的属性有哪些？
```
 datetime：该属性表示此元素的时间和日期，并且属性值必须是一个有效的日期格式，并可包含时间。 如果此值不能被解析为日期，元素不会有一个关联的时间戳.
 pubdate：元素给出的日期和时间是文档的发布日期
```
# 新增的非主体结构元素
9. header 元素的作用是什么？
```
<header> 元素用于展示介绍性内容，通常包含一组介绍性的或是辅助导航的实用元素。它通常用来放置整个页面或页面内的一个内容区块的标题，
但也可能包含其他元素，比如 Logo、搜索框、作者名称等
```
10. footer 元素的作用是什么？
```
 <footer> 元素表示最近一个章节内容或者根节点元素的页脚。一个页脚通常包含该章节作者、版权数据或者与文档相关的链接等信息。
```
11. header元素和 footer 元素使用时要注意什么？
```
注意 footer 元素和 header 元素必须不能是 address, header 或者 footer 元素的后代元素。
```
12. hgroup元素的作用是什么？
```
hgroup元素是将标题及其子标题进行分组的元素。它将多个<h1>至<h6>的子元素组装到一起。
```
13. address元素的作用是什么？
```
<address>元素用来在文档中呈现联系信息，也可以定义一个地址（比如电子邮件地址）、签名或者文档的作者身份
```
14. HTML5大纲编排的规则是什么？
```
1. 显式编排内容区域块
2. 隐式编排内容区域块
3. 标题分级
4.不同区域块可以使用相同级别的标题
```
# 新增的表单属性
15. 新增了哪些表单内元素的属性？
```
表单内元素的form属性
表单内元素的formaction属性
表单内元素的formmethod属性
表单内元素的formenctype属性
表单内元素的formtarget属性
表单内元素的formfocus属性
表单内元素的required属性
表单内元素的labels属性
```
16. 表单内元素的form属性的作用是什么？
```
在HTML4中，表单内的从属元素必须书写在表单内部，而在HTML4中，可以把他们书写在任何地方，然后为该元素指定
一个form属性，属性值为该表单的id，这样就可以声明该元素从属于指定表单了
```
17. 表单内元素的formaction属性的作用是什么？
```
在HTML4中，一个表单内的所有元素只能通过表单的action属性被统一提交到另一个页面，而在HTML5中可以为所有的
提交按钮，增加不同的formaction属性，使单击不同的按钮时可以将表单提交到不同的页面。
```