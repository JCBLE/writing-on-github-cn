# Markdown
> 翻译自：https://help.github.com/articles/markdown-basics

Markdown是一种易于读写的普通文本格式，可以很容易的转换为其他格式如HTML，pdf等。

## 基本格式
### 段落

在Markdown中，段落就只是一行或多行的连续文本，每个段落之间用一个或多个空行分隔。

```
On July 2, an alien mothership entered Earth's orbit and deployed several dozen saucer-shaped "destroyer" spacecraft, each 15 miles (24 km) wide.

On July 3, the Black Knights, a squadron of Marine Corps F/A-18 Hornets, participated in an assault on a destroyer near the city of Los Angeles.
```

### 标题

你可以通过在你的标题文本之前增加1-6个`#`符号，`#`的个数决定了标题字号的大小。

```
# 最大的标题 (相当于 <h1> 标签)
## 2级标题 (相当于 <h2> 标签)
…
###### 6级标题 (相当于 <h6> 标签)
```

### 引用

你可以用`>`标识引用。

> 原谅我的山寨翻译

```
> 原谅我的山寨翻译
```

### 文本修饰

你可以让文本变成**粗体**或*斜体*。

```
*这行字将会是斜体*
**这行字将会是粗体**
```

粗体和斜体都可以用`*`或`_`包围文字来设置，因此如果有需要的话，你可以组合这两种格式来达到**_粗体加斜体_**的效果。**请注意: 符号与文本之间不能有空格**。

```
**每个人都_必须_参加今天5点的会议。**
```

### 列表

#### 无序列表

可以通过在列表项前面放置`*`或`-`来显示无序列表

```
* Item
* Item
* Item

- Item
- Item
- Item
```

推荐使用`-`，以便于其他符号去分开。尽量不要混用`*`和`-`。


#### 有序列表

在列表项前放置`数字.`将可以显示一个有序列表。注意：数字后有一个小数点。

```
1. 苹果
2. 梨子
3. 香蕉
```

需要注意的是数字并不需要是连续。

```
1. 苹果
3. 梨子
6. 香蕉
```

而且数字的顺序并不重要，列表显示的顺序只与书写的顺序有关。

```
6. 苹果
3. 梨子
1. 香蕉
```

事实上数字的值根本不重要，只要不是负数。

```
2. 苹果
2. 梨子
0. 香蕉
```

#### 嵌套列表

可以通过缩进两个空格来创建嵌套的列表。

```
1. 苹果
  1. 首先需要洗净.
  2. 然后需要削皮.
2. 梨子
  * 从前有个人叫孔融.
    * 后来有一个关于孔融的故事.
    * 然后。。。
3. 香蕉
```

### 代码格式化

#### 行内格式化

使用单个`` ` ``（这个符号通常在`Esc`键的下方）将文本显示为特别的等宽字体样式。`` ` ``之间的文本会原样显示，不会再受到其他修饰符的影响。

```
为什么我们不把`超级计划`转变为`**可行性**计划`.
```

#### 多行格式化

使用连续的三个`` ` ``符号来将多行文本显示为一个独立的区块。

````
看看我写的程序：
```
x = 0
x = 2 + 2
what is x
```
````

### 链接

你可以将链接文本包裹在中括号( `[ ]` )中，链接包裹在小括号中 ( `( )` )来显示链接。

比如创建一个链接文本为 “访问GitHub” 并链接到 www.github.com 的链接可以这样写： `[访问GitHub](https://www.github.com)`。

此外还可以查看（后续会翻译）：  
:link:[GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown)  
:link:[Writing on GitHub](https://help.github.com/articles/writing-on-github)  
:link:[Mastering Markdown](http://guides.github.com/features/mastering-markdown/)
