# Markdown 使用方法
## ———— Atom 版
[标题](#title)
[段落格式](#para)
[列表](#list)
[区块](#block)
[代码](#code)
[链接](#link)
[图片](#pic)
[表格](#table)
[高级技巧](#other)

***
---

## <span id="title">标题</span>
+ 使用 # 号标记
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题（六级标题为止）
```
ex.
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

+ 使用 = 和 - 标记一级和二级标题
```
一级标题
==
二级标题
--
```
ex.

一级标题
==
二级标题
--

---

## <span id="para">段落格式</span>
1. 段落
+ Markdown 段落没有特殊的格式，直接编写文字就好，段落的换行是使用两个以上空格加回车。
```
这是第一个段落(此处两个空格)
这是第二个段落
```
+ 当然也可以在段落后面使用一个空行来表示重新开始一个段落。
```
This is first paragram
（此处一个空行）
This is second paragram
```

2. 字体
+ 可以使用的字体
```
*斜体*
_斜体_
**粗体**
__粗体__
***粗斜体***
___粗斜体___
```
ex.

*斜体*  `(*斜体*)`

_斜体_  `(_斜体_)`

**粗体**  `(**粗体**)`

__粗体__  `(__粗体__)`

***粗斜体*** `(***粗斜体***)`

___粗斜体___ `(___粗斜体___)`

3. 分割线
+ 使用三个 * 或 -
```
***
* * *
---
- - -
```
ex.
***
* * *
---
- - -

4. 删除线
+ 在文字的两端分别加上两个波浪线 ~~
```
~~删除线~~
```
ex.
~~删除线~~

5. 下划线
+ 使用 HTML 的 `<u>` 标签来实现
```
<u>下划线</u>
( </u> 是删除该格式)
```
ex.
<u>下划线</u>

6. 脚注
+ 脚注是对文本的补充说明，使用 `[^footnote]`
```
脚注[^1]

[^1]:这是脚注内容
```
ex.
脚注[^1]

[^1]:这是脚注

---

## <span id="list">列表</span>
1. 无序列表
* 使用 * 、 + 、 -
```
* 第一项
* 第二项
+ 第一项
+ 第二项
- 第一项
- 第二项
```
ex.
* 第一项
* 第二项
+ 第一项
+ 第二项
- 第一项
- 第二项

2. 有序列表
* 数字并加上 . 号
```
1. 第一项
2. 第二项
```
ex.
1. 第一项
2. 第二项

---

## <span id="block">区块</span>
+ 用 > 表示一层区块
```
> 区块一
>> 区块二
>>> 区块三
```
ex.
> 区块一
>> 区块二
>>> 区块三

---

## <span id="code">代码</span>
1. 行代码用两个 ` 表示
```
`这是代码`
```
ex.
`这是代码`

2. 段代码用一对 ``` 表示
```
这是代码1
这是代码2
这是代码3
```

---

## <span id="link">链接</span>
+ 链接书写格式如下
```
[名字](链接)
```
ex.
[百度](https://www.baidu.com/)

---

## <span id="pic">图片</span>
+ 图片书写格式如下
```
![名字](链接)
```
ex.
![前桥工科大学logo](https://www.maebashi-it.ac.jp/images/logo.gif)

---

## <span id="table">表格</span>(jupyter notebook中无法搭建表格)
1. 表格书写格式如下
```
| 行1列1 | 行1列2 | 行1列3 |(该行为表头)
| ------ | ------ | ------ |(与 - 的个数无关，但是长度对齐更美观)
| 行2列1 | 行2列2 | 行2列3 |
| 行3列1 | 行3列2 | 行3列3 |
```
ex1.
| 行1列1 | 行1列2 | 行1列3 |
| - | - | - |
| 行2列1 | 行2列2 | 行2列3 |
| 行3列1 | 行3列2 | 行3列3 |
ex2.
| 行1列1 | 行1列2 | 行1列3 |
| ------ | ------ | ------ |
| 行2列1 | 行2列2 | 行2列3 |
| 行3列1 | 行3列2 | 行3列3 |

2. 对齐方式
```
| :- |:该列左对齐
| :-: |:该列居中
| -: |:该列右对齐
```
ex.
| 行1 | 行1列2 | 行1列3 |
| :- | :-: | -: |
| 行2列1 | 列2 | 列3 |
| 行3 | 列2 | 列3 |

---

## <span id="other">高级技巧</span>
HTML标签
| 标签 | 含义 |
| --- | --- |
| `<b>` | 定义粗体文本 |
| `<i>` | 定义斜体文本 |
| `<code>` | 定义代码文本 |
| `<kbd>` | 定义键盘文本 |
| `<sup>` | 定义上标文本 |
| `<sub>` | 定义下标文本 |
| `<time>` | 定义日期/时间 |
