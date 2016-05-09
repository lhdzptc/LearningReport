# index
1. [关于Markdown](#about)
2. [Markdown基本使用](#use)
3. [Markdown表格和公式](#table)

# about 1.关于Markdown
![简明教程1-关于Markdown](http://img.blog.csdn.net/20150315100429879)

## 1.1前言
Markdown是一种轻量级的标记语言，把作者从繁杂的排版工作中解放出来，实现**易读易写**的文章写作，已经逐渐成为事实上的行业标准。CSDN博客支持Markdown可以让广大博友更加专注于博客内容，大赞。但是，不少博友可能对Markdown比较生疏，本博接下来用一个系列文章《Markdown简明教程》扼要介绍Markdown，希望可以对大家有所帮助。

系列教程目录

- **关于Markdown**
- Markdown基本使用
- Markdown表格和公式
- Markdown UML绘图

## 1.2啥是Markdown
Markdown的目标是实现**易读易写**，成为一种**适用于网络的书写语言**。  
我们写作文章时经常会遇到一些困扰。试想一下，您在使用Word写作文档，您经常需要暂停写作，选中某个部分，然后利用排版工具为该部分添加排版格式，然后才能继续您的写作；如果你要写网络文档，情况可能更糟，如果需要呈现一个列表，您需要使用```<ul><li>```等若干多的标签实现；我们的写作思路经常会被各种各样的排版操作而打断，使我们不能专注于写作。  
Markdown正是为此而生，用简洁的语法代替排版，把作者从繁杂的排版操作中解放出来，**更加专注于写作内容**， 内容、格式、插图、代码、甚至公式、流程图等，只需要使用键盘即可完成，**轻松完成文章写作**。
Markdown 是一种用来写作的轻量级「标记语言」， 可以轻松转换成html格式、pdf格式，HTML是一种网络文章的发布规范，而Markdown是一种**网络文章写作规范**。Github、Wordpress、CSDN、简书等行业知名网站均支持Markdown，Markdown已逐渐成为**事实上的网络写作规范**。

## 1.3为啥Markdown 

接下来，我们通过Markdown的优缺点，看看为啥Markdown。
### 1.3.1 Markdown优点
1. 专注内容
	使作者可以更加关注文章内容、更加关注写作本身。
2. 易学易写易读
    语法简单，容易学习。操作简单，容易书写。格式简洁大方，可读性强。
3. 兼容性强
    纯文本内容，兼容几乎所有的文本编辑器和html编辑器。
4. 格式转换方便
    可以轻松导出为HTML格式、PDF格式、MD格式，便于实现文章内容的存储和传播，例如将博客转存为电子书，例如将博客发布到hexo博客系统等。
5. 功能强大
    兼容html语法、特殊字符自动转换、轻松绘制表格、公式、流程图等。
    
### 1.3.2 Markdown的缺点
1. 格式难于自定义
    因为Markdown更加关注内容、更加关注写作本身，因此Markdown在格式自定义方面有所欠缺，例如Markdown默认链接在新页面打开，更改起来比较麻烦，需要编写额外代码实现功能。
2. 需要额外编译器
    浏览器不会默认编译Markdown，需要额外的编译器进行编译。

尽管有一些缺点，Markdown的强大之处更加诱人，别犹豫别徘徊，值得一试。请大家摩摩拳擦擦掌，开启您的Markdown之路吧。

## 1.4 学习资源
1. [创始人John Gruber的Markdown语法说明](http://daringfireball.net/projects/markdown/syntax)
2. [Markdown中文版语法说明](http://wowubuntu.com/markdown/)
3. [Github help](https://help.github.com/articles/markdown-basics/)
4. [Markdown tw](http://markdown.tw/)
5. [Markdown Tutorial，一个学习测试平台](http://markdowntutorial.com/)
6. [Learning Markdown](http://www.makeuseof.com/tag/learning-markdown-write-web-faster/#chapter-1)
7. [markable-同步编译成html源码或网页](http://markable.in/editor/)
8. [Markdown Syntax Cheat Sheet](http://markable.in/file/aa191728-9dc7-11e1-91c7-984be164924a/)
9. [stackedit](https://stackedit.io/)

[回目录](#index)

# use 2. Markdown基本使用
![简明教程2-Markdown基本使用](http://img.blog.csdn.net/20150315154015934)

## 2.1 前言
Markdown是一种轻量级的标记语言，把作者从繁杂的排版工作中解放出来，实现**易读易写**的文章写作，已经逐渐成为事实上的行业标准。CSDN博客支持Markdown可以让广大博友更加专注于博客内容，大赞。但是，不少博友可能对Markdown比较生疏，本博接下来用一个系列文章《Markdown简明教程》扼要介绍Markdown，希望可以对大家有所帮助。

系列教程目录

- 关于Markdown
- **Markdown基本使用**
- Markdown表格和公式
- Markdown UML绘图

本文为《Markdown简明教程》系列教程的第2篇Markdown基本使用，学习Markdown的基本语法，了解格式化文本，格式化代码、列表、图片、链接、转义符等，下一篇文章我们来研读Markdown的扩展使用。

## 2.2 基本语法

### 2.2.1 文本格式化

#### 2.2.1.1 强调文字
我们使用```*斜体文字*```的方式倾斜文字，```**加粗的文字**```的方式加粗文字，使用```***加粗的斜体字***```同时加粗和倾斜文字。

下面的Markdown代码：
```markdown
*斜体文字*
**加粗文字**
***加粗的斜体文字***
```
将会编译成html：

```html
<em>斜体文字</em>
<strong>加粗文字</strong>
<strong><em>加粗的斜体文字</em></strong>
```
显示在网页上的结果为：
*斜体文字*
**加粗文字**
***加粗的斜体文字***

#### 2.2.1.2 添加删除线

我们可以使用markdown给文字添加删除线：
```markdown
~~添加删除线的文字~~
```
编译成html之后：

```html
<del>添加删除线的文字</del>
```
显示在网页上结果为：
~~添加删除线的文字~~

#### 2.2.1.3 标题

Markdown 支持两种标题的语法，类 Setext 和类 atx 形式。
```markdown
类Setext形式采用底线的形式.
一号标题
=============
二号标题
-------------
类Atx形式则是在行首插入1到6个#，对应到标题1到标题6.
# 一号标题
## 二号标题
### 三号标题
#### 四号标题
##### 五号标题
###### 六号标题
```
解析成html：

```html
<h1>一号标题</h1>
<h2>二号标题</h2>
<h3>三号标题</h3>
<h4>四号标题</h4>
<h5>五号标题</h5>
<h6>六号标题</h6>
```
显示在网页上结果为：
![标题结果](http://img.blog.csdn.net/20150315122728424)

#### 2.2.1.4 引用
Markdown通过在引用的文字之前添加">"标记达到引用的效果，引用段落的时候可以偷懒只在整个段落的第一行最前面加上 >。引用里面可以使用强调、链接等其他语法。

```markdown
> 这里是一段引用
> 也可以偷懒只在首行引用一个段落

> 引用段落：Markdown是一种轻量级的标记语言，把作者从繁杂的排版工作中解放出
  来，实现**易读易写**的文章写作，已经逐渐成为事实上的行业标准。

>**结束引用，用个空行**
```
编译成html之后：

```html
<blockquote>
	<p>这里是一段引用
	也可以偷懒只在首行引用一个段落</p>
	<p>引用段落：Markdown是一种轻量级的标记语言，把作者从繁杂的排版工作中解放出来，实现<strong>易读易写</strong>的文章写作，已经逐渐成为事实上的行业标准。</p>
	<strong>结束引用，用个空行</strong>
</blockquote>
```
显示在网页上结果为：
> 这里是一段引用
> 也可以偷懒只在首行引用一个段落

> 引用段落：Markdown是一种轻量级的标记语言，把作者从繁杂的排版工作中解放出来，实现**易读易写**的文章写作，已经逐渐成为事实上的行业标准。

>**结束引用，用个空行**

引用可以嵌套，使用不同数量的“>”表示层次。

```markdown
> 这里是个引用
> > 嵌套引用
> 
> 这里是个引用
```
编译成html之后：

```html
<blockquote>
	<p>这里是个引用</p>
	<blockquote>
		<p>嵌套引用</p>
	</blockquote>
	<p>这里是个引用</p>
</blockquote>
```
显示在网页上结果为：

> 这里是个引用
> > 嵌套引用
> 
> 这里是个引用

### 2.2.2 代码格式化

#### 2.2.2.1 行内代码
使用反引号"`"包含实现行内代码。
```markdown
我们可以使用`<br>`换行，也可以使用`<p></p>`实现。
`高亮`文字
```
编译成html之后：
```html
我们可以使用<code>&lt;br&gt;</code>换行，也可以使用<code>&lt;p&gt;&lt;/p&gt;</code>实现。
<code>高亮</code>文字。
```
显示在网页上结果为：
我们可以使用`<br>`换行，也可以使用`<p></p>`实现。
`高亮`文字

#### 2.2.2.2 区块代码
如果需要在代码内插入反引号，需要多个反引号开始和结束一段代码。
如果需要代码块和语法高亮，可以采用三个反引号的方式，同时可以注明语言类型。

```
 ```ruby
 require 'redcarpet'
 markdown = Redcarpet.new("Hello World!")
 puts markdown.to_html
 ```
```

### 2.2.3 列表
#### 2.2.3.1 无序列表
无序列表使用星号、加号或是减号作为列表标记，如果不按列表显示，前面记得加一空行。

```markdown
- Red
- Green
- Blue
```
解析为
```html
<ul>
	<li>Red</li>
	<li>Green</li>
	<li>Blue</li>
</ul>
```
显示在网页上结果为：

- Red
- Green
- Blue

#### 2.2.3.2 有序列表
使用数字接着一个英文句点表示一个有序列表， 注意前面的数字对列表没有影响。

```markdown
1. 文字
2. 图片
4. 表格
```
解析成html：

```html
<ol>
	<li>文字</li>
	<li>图片</li>
	<li>表格</li>
</ol>
```
显示在网页结果为：

1. 文字
2. 图片
4. 表格

#### 2.2.3.3 列表嵌套
列表可以嵌套，添加tab缩进表示层次。例如下面的Markdown代码：

```markdown
1. 文字
	1. 强调
		- 粗体
		- 斜体
		- 粗体和斜体
	2. 引用
2. 图片
3. 表格
```
转换成html为：

```html
<ol>
	<li>文字
	<ol>
		<li>强调
			<ul>
				<li>粗体</li>
				<li>斜体</li>
				<li>粗体和斜体</li>
			</ul>
		</li>
		<li>引用</li>
	</ol>
	</li>
	<li>图片</li>
	<li>表格</li>
</ol>
```
显示在网页上结果为：

1. 文字
	1. 强调
		- 粗体
		- 斜体
		- 粗体和斜体
	2. 引用
2. 图片
3. 表格

#### 2.2.3.4 多段列表
列表项里可以包含多个段落，每个项目下的段落都必须缩进 4 个空格或是 1 个制表符：

```markdown
1. 学习Markdown
	学习Markdown的网站，我们可以参考文章结尾的学习资源，文档、案例、教程。
	学习起来很简单。
2. 使用Markdown
	可以使用客户端和在线编辑器。
```
在网页上显示结果为：

1. 学习Markdown
	学习Markdown的网站，我们可以参考文章结尾的学习资源，文档、案例、教程。
	学习起来很简单。
2. 使用Markdown
	可以使用客户端和在线编辑器。

<div id="link"></div>

### 2.2.4 链接

Markdown 支持两种形式的链接语法： 行内式和参考式两种形式。

#### 2.2.4.1 行内式链接

首先来看行内式，只要在方块括号后面紧接着圆括号并插入网址链接即可，如果你还想要加上链接的 title 文字，只要在网址后面，用双引号把 title 文字包起来即可。

```markdown
欢迎大家访问我的[博客](http://blog.csdn.net/whqet/ "博客")。
也可以不指定[链接](http://blog.csdn.net)的title。
```
解析成html：

```html
欢迎大家访问我的<a href="http://blog.csdn.net/whqet/" title="博客">博客</a>。
也可以不指定<a href="http://blog.csdn.net">链接</a>的title。
```
显示在网页上，结果为：

欢迎大家访问我的[博客](http://blog.csdn.net/whqet/ "博客")。
也可以不指定[链接](http://blog.csdn.net)的title。

#### 2.2.4.2 参考式链接

参考式链接需要进行链接内容定义，然后引用该定义设置链接。
链接内容定义格式为：
```markdown
[链接名]: 链接地址 "链接title"
[链接名]: 空格(或tab) 链接地址 空格 "链接地址"(可省略)
```
设置链接的格式为
```markdown
[链接文字][链接名称]
```
如下面代码所说：
```markdown
请大家访问我的[博客][blog],获取更多信息。
[blog]: http://blog.csdn.net/whqet "我的CSDN博客"
```
解析成html为：

```html
请大家访问我的<a href="http://blog.csdn.net/whqet" title="我的CSDN博客">博客</a>,获取更多信息。
```
显示在网页上结果为：
请大家访问我的[博客][blog],获取更多信息。
[blog]: http://blog.csdn.net/whqet "我的CSDN博客"

#### 2.2.4.3 页内导航

我们同样可以使用markdown实现页内导航，步骤如下：

1. 先定义一个锚记
	```<div id="footer"></div>```
2. 然后设置页内链接
	```[到底部](#footer)```	
我们可以类似的方式去实现文章的页内导航。单击下面的链接跳转到2.4链接。

[跳到链接开始位置](#link)

### 2.2.5 图片
Markdown 使用一种和链接很相似的语法来标记图片，同样也允许两种样式： 行内式和参考式。
行内式图片如下所示：
```markdown
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
```
参考式图片如下所示：
```markdown
![Alt text][id]
[id]: url/to/image  "Optional title attribute"
```
到目前为止， Markdown 还没有办法指定图片的宽高，如果你需要的话，你可以使用普通的 <img> 标签。
**注意**：CSDN图片如果大于显示区域，则图片宽度自适应，如果图片较小则以原始尺寸显示。
![宽度自适应](http://img.blog.csdn.net/20150315150246382)
![原始尺寸显示](http://img.blog.csdn.net/20150315150151855)

### 2.2.6 分割线
你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：

```markdown
* * *
***
*****
- - -

---------------------------------------

```

### 2.2.7 转义

Markdown 可以利用反斜杠来实现转义， 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：
``` markdown
\   反斜线
`   反引号
*   星号
_   底线
{}  花括号
[]  方括号
()  括弧
#   井字号
+   加号
-   减号
.   英文句点
!   惊叹号
```

## 2.3 动手实践
1. 大家可以通过CSDN的**管理博客-博客配置-编辑器类型**设置默认的编辑器为Markdown编辑器，然后新建文章，就可以体验Markdown编辑器了。
2. 利用在线编辑工具体验Markdown，例如[markable](http://markable.in/editor/)，或[stackedit](https://stackedit.io/editor), 或[作业部落](https://www.zybuluo.com/mdeditor)等。
3. 下载客户端，window平台下的[MarkdownPad](http://markdownpad.com/)或mac平台下的[mou](http://25.io/mou/)。

[回目录](#index)

# table
# 3. Markdown的表格和公式
![Markdown简明教程3-Markdown表格和公式](http://img.blog.csdn.net/20150315213015570)
## 3.1 前言
Markdown是一种轻量级的标记语言，把作者从繁杂的排版工作中解放出来，实现**易读易写**的文章写作，已经逐渐成为事实上的行业标准。CSDN博客支持Markdown可以让广大博友更加专注于博客内容，大赞。但是，不少博友可能对Markdown比较生疏，本博接下来用一个系列文章《Markdown简明教程》扼要介绍Markdown，希望可以对大家有所帮助。

系列教程目录

- 关于Markdown
- Markdown基本使用
- **Markdown表格和公式**
- Markdown UML图

本文为《Markdown简明教程》系列教程的第3篇Markdown表格和公式，主要讲解Markdown实现表格、公式。下一篇文章我们来研读Markdown UML图。

## 3.2  表格

### 3.2.1 表格
Markdown使用管线图的方式实现表格，表格里面可以使用强调、链接等行内格式。
下面代码所示为一个基本的表格：
```markdown
教程标题| 主要内容
-------|----------
关于Markdown | 简介Markdown，Markdown的优缺点
Markdown基础 | Markdown的**基本语法**，格式化文本、代码、列表、链接和图片、分割线、转义符等
Markdown表格和公式 | Markdown的**扩展语法**，表格、公式
```
解析html如下：

```html
<table>
	<thead>
		<tr>
			<th>教程标题</th>
			<th>主要内容</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>关于Markdown</td>
			<td>简介Markdown，Markdown的优缺点</td>
		</tr>
		<tr>
			<td>Markdown基础</td>
			<td>Markdown的<strong>基本语法</strong>，格式化文本、代码、列表、链接和图片、分割线、转义符等</td>
		</tr>
		<tr>
			<td>Markdown扩展</td>
			<td>Markdown的<strong>扩展语法</strong>，表格、公式、UML图</td>
		</tr>
	</tbody>
</table>
```
在网页中结果如下：
教程标题| 主要内容
-------|----------
关于Markdown | 简介Markdown，Markdown的优缺点
Markdown基础 | Markdown的**基本语法**，格式化文本、代码、列表、链接和图片、分割线、转义符等
Markdown表格和公式 | Markdown的**扩展语法**，表格、公式

**注意**，为了美观起见，可以把**前后端**管线补齐，如下面代码所示。
```markdown
|  教程标题   | 主要内容                      |
|------------|------------------------------|
|关于Markdown | 简介Markdown，Markdown的优缺点|
|Markdown基础 | Markdown的**基本语法**，格式化文本、代码、列表、链接和图片、分割线、转义符等|
|Markdown扩展 | Markdown的**扩展语法**，表格、公式、UML图|
```
**注意**，表头下面的虚线为了更好的分隔表头和表格内容，长度随意。

### 3.2.2 表格对齐方式

**注意**，我们同时可以指定表格单元格的对齐方式，如下面代码所示。

```markdown
| Day     | Meal     | Price   |
|:--------|---------:|:-------:|
| Monday  | pasta    | $6      |
| Tuesday | chicken  | $8      |
```
显示在网页上结果为：
| Day     | Meal     | Price   |
|:--------|--------- |:-------:|
| Monday  | pasta    | $6      |
| Tuesday | chicken  | $8      |
**注意**，表格列的宽度设置不能设置。Markdown更加关注内容，因此格式设置性能较弱，如果确实需要设置，请使用CSS。

## 3.3  公式

通过使用**MathJax**，我们可以让Markdown解析LaTeX数学表达式，通常情况下，我们需要引入MathJax插件才可能工作。

```html
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
```
CSDN已经内置了这个插件，我们就不需要手动插入了，可以直接写数学公式了。

### 3.3.1 行内公式

我们使用`$...$`的方式来包含行内公式，例如
```markdown
一个简单的数学公式,求圆的面积$S=\pi r^2$。
```
编译之后表现在网页上，结果为：
一个简单的数学公式,求圆的面积$S=\pi r^2$。

### 3.3.2 陈列公式（displayed formulas）

陈列公式使用`$$...$$`来表示，例如。
```markdown
如果使用陈列公式，结果为：
一个简单的数学公式，求圆的面积。
$$
	S=\pi r^2
$$
```
解析在网页上结果为：
一个简单的数学公式，求圆的面积。
$$
	S=\pi r^2
$$

## 3.3.3 MathJax语法

1. 使用\alpha、\beta、\gamma表示希腊字母α、β、γ， 使用\Gamma表示大写希腊字母Γ等，如下表所示。

| 字母 | 实现| 字母| 实现 |
|-----|-----|-----|-----|
| $ Α $|`A`|$ \alpha$| `\alhpa`|
| $ B $|`B`|$ \beta$| `\beta`|
| $ \Gamma $|`\Gamma`|$ \gamma$| `\gamma`|
| $ \Delta $|`\Delta`|$ \delta$| `\delta`|
| $ E $|`E`|$ \epsilon$| `\epsilon`|
| $ Z $|`Z`|$ \zeta$| `\zeta`|
| $ H $|`H`|$ \eta$| `\eta`|
| $ \Theta $|`\Theta`|$ \theta$| `\theta`|
| $ I $|`I`|$ \iota$| `\iota`|
| $ K $|`K`|$ \kappa$| `\kappa`|
| $ \Lambda $|`\Lambda`|$ \lambda$| `\lambda`|
| $ M $|`M`|$ \mu$| `\mu`|
| $ N $|`N`|$ \nu$| `\nu`|
| $ \Xi $|`\Xi`|$ \xi$| `\xi`|
| $ O $|`O`|$ \omicron$| `\omicron`|
| $ \Pi $|`\Pi`|$ \pi$| `\pi`|
| $ P $|`P`|$ \rho$| `\rho`|
| $ \Sigma $|`\Sigma`|$ \sigma$| `\sigma`|
| $ T $|`T`|$ \tau$| `\tau`|
| $ \Upsilon $|`\Upsilon`|$ \upsilon$| `\upsilon`|
| $ \Phi $|`\Phi`|$ \phi$| `\phi`|
| $ X $|`X`|$ \chi$| `\chi`|
| $ \Psi $|`\Psi`|$ \psi$| `\psi`|
| $ \Omega $|`\v`|$ \omega$| `\omega`|

2.  利用{}实现优先级。
例如`$ x_i^2 $`实现$x_i^2$，而`$ x_{i^2} $`实现$x_{i^2}$。
例如`$ \lim_{x\to\infty} $实现`$\lim_{x\to\infty}$。
3.  常用数学运算符表示如下。

|运算符| 说明 | 运算符案例 | 案例实现 | 
|-----|----- |----- |----- |
|+|加| $ x + y $ | `$ x + y $` |
|-|减|$ x - y $ | `$ x - y $` |
|\times|乘| $ x \times y $ | `$ x \times y $` |
|\cdot|乘| $ x \cdot y $ | `$ x \cdot y $` |
|\ast|乘| $ x \ast y $ | `$ x \ast y $` |
|\div|除| $ x \div y $ | `$ x \div y $` |
|\frac|分数| $ \frac {x}{y} $ | `$ \frac{x}{y} $` |
|^|上标| $ x ^ y $ | `$ x ^ y $` |
|_|下标|$ x _ y $ | `$ x _ y $` |
|\sqrt|开二次方| $ \sqrt x $ | `$ \sqrt x $` |
|\sqrt|开方|$ \sqrt[x]{y^4+3y-1} $ | `$ \sqrt[x]{y^4+3y-1} $` |
|\pm|加减|$ x \pm y $ | `$ x \pm y $` |
|\mp|减加| $ x \mp y $ | `$ x \mp y $` |
|=|等于| $ x = y $ | `$ x = y $` |
|\leq|小于等于| $ x \leq y $ | `$ x \leq y $` |
|\geq|大于等于| $ x \geq y $ | `$ x \geq y $` |
|\ngeq|不大于等于| $ x \ngeq y $ | `$ x \ngeq y $` |
|\not\geq|不大于等于| $ x \not\geq y $ | `$ x \not\geq y $` |
|\neq|不等于| $ x \neq y $ | `$ x \neq y $` |
|\approx|约等于| $ x \approx y $ | `$ x \approx y $` |
|\equiv|恒等于| $ x \equiv y $ | `$ x \equiv y $` |
|\bigodot|定义运算符| $ x \bigodot y=x+y^2 $ | `$ x \bigodot y=x+y^2 $` |
|\bigotimes|定义运算符| $ x \bigotimes y=x+y^2 $ | `$ x \bigotimes y=x+y^2 $` |
|\in|属于| $ x \in y $ | `$ x \in y $` |
|\notin|不属于| $ x \notin y $ | `$ x \notin y $` |
|\subset|子集| $ x \subset y $ | $ x \subset y $ |
|\not\subset|非子集| $ x \not\subset y $ | $ x \not\subset y $ |
|\subseteq|子集| $ x \subseteq y $ | $ x \subseteq y $ |
|\supset|超集| $ x \supset y $ | $ x \supset y $ |
|\supseteq|超集| $ x \supseteq y $ | $ x \supseteq y $ |
|\cup|并| $ x \cup y $ | `$ x \cup y $` |
|\cap|交| $ x \cap y $ | `$ x \cap y $` |
|\log|对数| $ \log(x) $ | `$ \log(x) $` |
|\overline|平均数| $ \overline{x} $ | `$ \overline{x} $` |
|\overline|连线符号| $ \overline{a+b+c+d} $ | `$ \overline{a+b+c+d} $` |
|\underline|下划线| $ \underline{a+b+c+d} $ | `$ \underline{a+b+c+d} $` |
|\overbrace|上大括号|$\overbrace{a+\underbrace{b+c}_{1.0}+d}^{2.0}$|`$\overbrace{a+\underbrace{b+c}_{1.0}+d}^{2.0}$`|
|\underbrace|下大括号|$\underbrace{a+d}_3 |$|`$\underbrace{a+d}_3$`|
|\partial|部分| $ \frac{\partial x}{\partial y} $ | `$ \frac{\partial x}{\partial y} $` |
|\lim|极限| $ \lim_{x\to\infty} $ | `$ \lim_{x\to\infty} $` |
|\displaystyle|块公式格式| $ \displaystyle \lim_{x\to\infty} $ | `$ \displaystyle \lim_{x\to\infty} $` |
|\sum|求和| $ \sum_1^n $ | `$ \sum_1^n $` |
|\infty|极限| $ \sum_{i=0}^\infty i^2 $ | `$ \sum_{i=0}^\infty i^2 $` |
|\int|积分| $ \int_0^1 x^2 {\rm d}x $ | `$ \int_0^1 x^2 {\rm d}x $` |
|\ldots|底端对齐的省略号| $ 1,2,\ldots,n $ | `$ 1,2,\ldots,n $` |
|\cdots|中线对齐的省略号| $  x_1^2 + x_2^2 + \cdots + x_n^2 $ | ` x_1^2 + x_2^2 + \cdots + x_n^2` |
|\uparrow|上箭头| $  \uparrow $ | `$ \uparrow $` |
|\Uparrow|上箭头| $  \Uparrow $ | `$ \Uparrow $` |

给个小作业：
$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

本文为《Markdown简明教程》系列教程的第3篇Markdown表格和公式，主要讲解Markdown实现表格、公式。下一篇文章我们来研读Markdown UML图。

## 3.4 深入

 1. [MathJax官方网站](http://www.mathjax.org/)
 2. [MathJax手册](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)
 3. [MathJax使用LaTeX语法编写数学公式教程](http://iori.sinaapp.com/17.html)
 4. [Mathjax与LaTex公式简介](http://mlworks.cn/posts/introduction-to-mathjax-and-latex-expression/)
 5. 小敏纸的[博文](http://blog.csdn.net/lanxuezaipiao/article/details/44341645)

[回目录](#index)
