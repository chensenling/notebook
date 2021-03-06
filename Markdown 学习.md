



# Makedown 语法部分

---

## 代码块
将代码块写在前面，是因为以下将大量用到代码块，以免读者混淆。
代码块 敲一个tab 或者4个空格键，完成代码块的创建。

行内代码块使用 ` 包裹内容。

注意：一定tab开始位置必须在最左边。
例：行内代码：
	`dfsddfsdsfdsdfsdfsdfsdfsdffdsfdfsds`
		代码块：
		
	asdadsadsadsadsadsadsadsadsadsa\dfsd
	dsfadfadfsadfsadf
	dfsadfsadfa
	fadfsdfsafd
	afsdssfds
	
		
		
## 标题
代码：

	# 一号标题
	## 二号标题
	### 三号标题
	#### 四号标题
	##### 五号标题
	###### 六号标题


## 字体
	斜体 / 粗体
	代码：
	*斜体* / _斜体_
	**粗体** 
	***斜粗体***
	~~删除线~~

效果：
*斜体* / _斜体_
**粗体** 
***斜粗体***
~~删除线~~

## 超链接
Markdown 具有两种形式的链接语法格式：**行内式**和**参考式**两种。
### 行内式
语法格式：	

	[超链接](链接地址)

例：
	
	这是百度的超链接 [baidu](http://www.baidu.com)
这是百度的超链接 [baidu](http://www.baidu.com)

行内样式 还具有一个 title 属性，作用 为 鼠标悬浮时 出现链接的标题
语法格式：
 [超链接](链接地址 “地址的标题”)

例：

	这是百度的链接[baidu](http://www.baidu.com "this baidu")
	
这是百度的链接[baidu](http://www.baidu.com "this baidu")
### 参考式
参考式与行内式最大的区别在与参考式能 先给链接 标上标号 最后统一的完成 链接地址的赋予。
而 将大段的链接地址 变为了一个 特定的 标号，这将大大减少编辑的工作量

语法格式：
[链接文字][标号] / [链接文字][]

例：

	下面有三个顶尖的互联网企业的网址分别为 [阿里巴巴][1] 、[腾讯][2] 、[百度][3]。
	
	[1]:http://alibaba.com
	
	[2]:http://tencent.com
	
	[3]:http://baidu.com
下面有三个顶尖的互联网企业的网址分别为 [阿里巴巴][1] 、[腾讯][2] 、[百度][3]。

[1]:http://alibaba.com

[2]:http://tencent.com

[3]:http://baidu.com

### 自动链接
{ #index}
将文字或其他自动转化为 链接
语法格式：
<链接文字>

	例：
	这是邮箱<1603565928@example.com>
这是邮箱<1603565928@example.com>

## 锚点
锚点 就是在当前页面任意**标题**位置做的标记，便于快捷的定位到取得位置。

语法格式：
标题 {#索引}
* 锚点标记必须位于标题的后面

		例：
		跳转到[自动链接](#index)
	跳转到[自动链接](#index)

### 列表
列表 分为 无序列表 和有序列表。
无序列表：
+、-、*

	例：
	+ 测试一
	- 测试二
	* 测试三
	* 
+ 测试一
- 测试二
* 测试三

有序列表：
数字加小数点（.）

	例：
	1. test1
	2. test2
1. test1
2. test2
###### 列表注意
在列表中希望得到 如 2009. 1这样的日期或其他什么的时候，应注意使用 转义符 \  将 . 保留下来。
例：
+ 2019. 2.3  
+ 2019\.2.3 使用转义符 \




### 定义型列表
名词进行定义的，一个 ：加上一个tab（四个空格）

	markdown
	:	Markdown是标记型语言
	
	github
	:	github是一个同性交流的网站

markdown

:	Markdown是标记型语言

github
:	github是一个同性交流的网站

### 列表缩进
+ 但我不能放歌， 悄悄是别离的笙箫； 夏虫也为我沉默， 沉默是今晚的康桥！

	悄悄的我走了， 正如我悄悄的来；	我挥挥衣袖，不带走一片云彩。

### 引用
在引用块中 Markdown的语法有效，而在代码块中一切的Markdown语法无效。
符号：
	>
>一级引用
>> + 二级引用

### 图片
插入图片和超链接相似。图片=！+超链接
格式：

	![图片](图片链接)

### 表格
	one|two|three
	-|-|-
	1|2|3
	
one|two|three
-|-|-
1|2|3



	
	
	

