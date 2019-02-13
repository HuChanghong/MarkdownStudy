 * [一、Markdown 是什么？](#%E4%B8%80markdown-%E6%98%AF%E4%BB%80%E4%B9%88)
  * [二、印象笔记里 Markdown 有什么特点？](#%E4%BA%8C%E5%8D%B0%E8%B1%A1%E7%AC%94%E8%AE%B0%E9%87%8C-markdown-%E6%9C%89%E4%BB%80%E4%B9%88%E7%89%B9%E7%82%B9)
  * [三、如何创建 Markdown 笔记？](#%E4%B8%89%E5%A6%82%E4%BD%95%E5%88%9B%E5%BB%BA-markdown-%E7%AC%94%E8%AE%B0)
  * [四、印象笔记 Markdown 笔记支持哪些语法？](#%E5%9B%9B%E5%8D%B0%E8%B1%A1%E7%AC%94%E8%AE%B0-markdown-%E7%AC%94%E8%AE%B0%E6%94%AF%E6%8C%81%E5%93%AA%E4%BA%9B%E8%AF%AD%E6%B3%95)
    * [设置分级标题](#%E8%AE%BE%E7%BD%AE%E5%88%86%E7%BA%A7%E6%A0%87%E9%A2%98)
* [一级标题](#%E4%B8%80%E7%BA%A7%E6%A0%87%E9%A2%98)
  * [二级标题](#%E4%BA%8C%E7%BA%A7%E6%A0%87%E9%A2%98)
    * [三级标题](#%E4%B8%89%E7%BA%A7%E6%A0%87%E9%A2%98)
      * [四级标题](#%E5%9B%9B%E7%BA%A7%E6%A0%87%E9%A2%98)
        * [五级标题](#%E4%BA%94%E7%BA%A7%E6%A0%87%E9%A2%98)
          * [六级标题](#%E5%85%AD%E7%BA%A7%E6%A0%87%E9%A2%98)
    * [加粗文本](#%E5%8A%A0%E7%B2%97%E6%96%87%E6%9C%AC)
    * [斜体](#%E6%96%9C%E4%BD%93)
    * [下划线](#%E4%B8%8B%E5%88%92%E7%BA%BF)
    * [删除线](#%E5%88%A0%E9%99%A4%E7%BA%BF)
    * [添加分隔线](#%E6%B7%BB%E5%8A%A0%E5%88%86%E9%9A%94%E7%BA%BF)
    * [引用文本](#%E5%BC%95%E7%94%A8%E6%96%87%E6%9C%AC)
    * [添加符号列表或者数字列表](#%E6%B7%BB%E5%8A%A0%E7%AC%A6%E5%8F%B7%E5%88%97%E8%A1%A8%E6%88%96%E8%80%85%E6%95%B0%E5%AD%97%E5%88%97%E8%A1%A8)
    * [添加待办事项](#%E6%B7%BB%E5%8A%A0%E5%BE%85%E5%8A%9E%E4%BA%8B%E9%A1%B9)
    * [插入链接](#%E6%8F%92%E5%85%A5%E9%93%BE%E6%8E%A5)
    * [插入图片](#%E6%8F%92%E5%85%A5%E5%9B%BE%E7%89%87)
    * [插入表格](#%E6%8F%92%E5%85%A5%E8%A1%A8%E6%A0%BC)
    * [插入图表](#%E6%8F%92%E5%85%A5%E5%9B%BE%E8%A1%A8)
    * [插入行内代码或代码块](#%E6%8F%92%E5%85%A5%E8%A1%8C%E5%86%85%E4%BB%A3%E7%A0%81%E6%88%96%E4%BB%A3%E7%A0%81%E5%9D%97)
    * [插入数学公式](#%E6%8F%92%E5%85%A5%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F)
    * [插入流程图](#%E6%8F%92%E5%85%A5%E6%B5%81%E7%A8%8B%E5%9B%BE)
    * [插入时序图](#%E6%8F%92%E5%85%A5%E6%97%B6%E5%BA%8F%E5%9B%BE)
    * [插入甘特图](#%E6%8F%92%E5%85%A5%E7%94%98%E7%89%B9%E5%9B%BE)
    * [设置目录](#%E8%AE%BE%E7%BD%AE%E7%9B%AE%E5%BD%95)
  * [五、印象笔记 Markdown 支持什么快捷键？](#%E4%BA%94%E5%8D%B0%E8%B1%A1%E7%AC%94%E8%AE%B0-markdown-%E6%94%AF%E6%8C%81%E4%BB%80%E4%B9%88%E5%BF%AB%E6%8D%B7%E9%94%AE)
>本文内容来自印象笔记官网,版权归印象笔记官方所有.原文链接:[印象笔记Markdown入门指南](https://list.yinxiang.com/markdown/eef42447-db3f-48ee-827b-1bb34c03eb83.php)  
此处仅对印象笔记Markdown的用法做一些粗浅的学习,本文的格式完全采用GFM标准.
## 一、Markdown 是什么？
>Markdown 是一种轻量级的「标记语言」，创始人为约翰·格鲁伯，用简洁的语法代替排版，目前被越来越多的知识工作者、写作爱好者、程序员或研究员广泛使用。其常用的标记符号不超过十个，相对于更为复杂的 HTML 标记语言来说，Markdown 十分的轻量，学习成本也不需要太多，且一旦熟悉这种语法规则，会有沉浸式编辑的效果。

>印象笔记 Markdown 支持 CommonMark 和 GFM (**GitHub Flavored Markdown**) 标准。



## 二、印象笔记里 Markdown 有什么特点？
* **一键创建：**  
支持 Markdown 独立的一键新建入口，为深度 Markdown 用户提供更好的效率体验；
* **支持丰富的主流 Markdown 语法：**  
支持文字相关样式、序号列表、任务列表、表格、TOC 目录、多种图表、数学公式、流程图、时序图、甘特图等；
* **支持插入图片：**  
可插入网络图片 或 直接拖动本地图片、复制剪贴板中的图片到 Markdown 笔记中；
* **支持多种模式切换：**  
编辑与预览模式、纯编辑模式以及纯预览模式；
* **支持多种编辑主题：**  
预置了白色、黑色、深空灰和印象绿主题，默认为印象绿，未来会有更多主题提供；
* **跨平台同步：**  
创建的 Markdown 笔记可在登录了印象笔记帐户的各端查看，未来更多端会支持创建和编辑 Markdown 笔记；
* **演示模式：**  
Markdown 笔记支持演示模式查看；
* **支持其他印象笔记特点功能：**  
笔记标注、导出 PDF、设置提醒、工作群聊共享-查看&amp;编辑笔记等。
## 三、如何创建 Markdown 笔记？
1. 点击左上角「新建 Markdown 笔记」来创建新的 Markdown 笔记,另外，也支持配置隐藏「新建 Markdown 笔记」按钮，Windows 用户直接右单击「新建 Markdown 笔记」按钮，即可隐藏，Mac 用户可以右单击左侧边栏空白处，取消勾选「新建 Markdown 笔记」来完成隐藏此按钮
2. 点击菜单栏-文件-新建笔记-新建 Markdown 笔记（Mac 上为顶部菜单栏-文件-新建 Markdown笔记）
3. 使用快捷键 Ctrl+alt+D（Mac 上 CMD+D）来快速创建 Markdown 笔记
## 四、印象笔记 Markdown 笔记支持哪些语法？
—— 以下语法均支持在编辑工具栏直接操作 —— 
### 设置分级标题
语法示例：

`# 一级标题`
# 一级标题
`## 二级标题`
## 二级标题
`### 三级标题`
### 三级标题
`#### 四级标题`
#### 四级标题
`##### 五级标题`
##### 五级标题
`###### 六级标题`
###### 六级标题

### 加粗文本
语法示例：

`**印象笔记**`
**印象笔记**
### 斜体
语法示例：

`*印象笔记*`
*印象笔记*
### 下划线
语法示例：

`<u>印象笔记</u>`  
<u>印象笔记</u>
>这里很奇怪在preview中无法实现underline效果  
>学习了HTML5之后了解在HTML5中<u></u>标签已经被废弃,所以可以知道github这里应该是使用了严格意义上的HTML5
### 删除线
语法示例：

\~\~印象笔记不支持Markdown\~\~
~~印象笔记不支持Markdown~~
### 添加分隔线
语法示例：
\* \* \*
* * *
### 引用文本
语法示例： 

&gt;近日，印象笔记宣布完成重组。作为Evernote已在中国独立运营近6年的品牌，印象笔记将成为由中方控股的中美合资独立运营实体，并获得红杉宽带跨境数字产业基金首轮数亿元人民币投资。
>近日，印象笔记宣布完成重组。作为Evernote已在中国独立运营近6年的品牌，印象笔记将成为由中方控股的中美合资独立运营实体，并获得红杉宽带跨境数字产业基金首轮数亿元人民币投资。
### 添加符号列表或者数字列表
语法示例：
```
* 使用 iOS 版本印象笔记如何快速保存内容？
    1. 启用印象笔记 Widget ——印象笔记·剪贴板
    2. 复制粘贴任意内容     
        * 微信
    3. 滑动到 Widget 插件区域即可完成保存  
* 印象笔记·剪贴板有什么特点？
    * 快：开启自动模式，可以自动保存剪贴板的任意内容
    * 一切：只要可以复制粘贴就可以保存
    * 有序：全部保存在「我的剪贴板」笔记本并以时间来命名
```
* 使用 iOS 版本印象笔记如何快速保存内容？
    1. 启用印象笔记 Widget ——印象笔记·剪贴板
    2. 复制粘贴任意内容     
        * 微信
    3. 滑动到 Widget 插件区域即可完成保存  
* 印象笔记·剪贴板有什么特点？
    * 快：开启自动模式，可以自动保存剪贴板的任意内容
    * 一切：只要可以复制粘贴就可以保存
    * 有序：全部保存在「我的剪贴板」笔记本并以时间来命名
### 添加待办事项
语法示例：
```
三只青蛙
* [x] 第一只青蛙
* [ ] 第二只青蛙
* [ ] 第三只青蛙
```
三只青蛙
* [x] 第一只青蛙
* [ ] 第二只青蛙
* [ ] 第三只青蛙
### 插入链接
语法示例：

`[印象笔记官网]( https://www.yinxiang.com/ )` 
[印象笔记官网]( https://www.yinxiang.com/ )
### 插入图片
印象笔记支持嵌入网络图片或者直接拖入本地图片，其中本地图片格式支持 jpg、png 和 gif。

语法示例：

`![image](https://www.yinxiang.com/blog/wp-content/uploads/2018/07/%E5%94%AE%E7%A5%A8%E5%BE%AE%E4%BF%A1%E5%B0%81%E9%9D%A22.png)`

![image](https://www.yinxiang.com/blog/wp-content/uploads/2018/07/%E5%94%AE%E7%A5%A8%E5%BE%AE%E4%BF%A1%E5%B0%81%E9%9D%A22.png)
另外，针对插入的本地图片可以控制图片大小，在拖拽、拷贝或者点击插入本地图片之后，直接在图片名称后面（无需空格）添加以下语法均可以按照以下要求控制图片大小：
* @w=300
* @h=150
* @w=200h=100
* @h=100w=200

示例:  
`![image](https://www.yinxiang.com/blog/wp-content/uploads/2018/07/%E5%94%AE%E7%A5%A8%E5%BE%AE%E4%BF%A1%E5%B0%81%E9%9D%A22.png)@w=100`  
<img src="https://www.yinxiang.com/blog/wp-content/uploads/2018/07/%E5%94%AE%E7%A5%A8%E5%BE%AE%E4%BF%A1%E5%B0%81%E9%9D%A22.png" alt="yinxiang" title="印象" width="100px" />
>备注:GFM不支持此语法,此处图片效果由html实现
### 插入表格
示例
```
| 帐户类型 | 免费帐户 | 标准帐户 | 高级帐户 |
| --- | --- | --- | --- |
| 帐户流量 | 60M | 1GB | 10GB |
| 设备数目 | 2台 | 无限制 | 无限制 |
| 当前价格 | 免费 | ￥8.17/月 | ￥12.33/月|
```
| 帐户类型 | 免费帐户 | 标准帐户 | 高级帐户 |
| --- | --- | --- | --- |
| 帐户流量 | 60M | 1GB | 10GB |
| 设备数目 | 2台 | 无限制 | 无限制 |
| 当前价格 | 免费 | ￥8.17/月 | ￥12.33/月|
### 插入图表
目前支持饼状图、折线图、柱状图和条形图，只需将 type 改为对应的pie、line、column 和 bar。

>\`\`\`chart  
,预算,收入,花费,债务  
June,5000,8000,4000,6000  
July,3000,1000,4000,3000  
Aug,5000,7000,6000,3000  
Sep,7000,2000,3000,1000  
Oct,6000,5000,4000,2000  
Nov,4000,3000,5000,  
>  
>type: pie  
title: 每月收益  
x.title: Amount  
y.title: Month  
y.suffix: $  
\`\`\`
    

![chart_pie.png](https://github.com/HuChanghong/MarkdownStudy/blob/master/img/chart_pie.png "chart_pie")

### 插入行内代码或代码块
印象笔记 Markdown 语法支持几十种编程语言的高亮的显示。
语法示例：

>\`\`\`python  
#!/usr/bin/python  
import re  
>
>line = "Cats are smarter than dogs"
>
>matchObj = re.match( r'(.*) are (.*?) .*', line, re.M|re.I)
>
>if matchObj:      
    print "matchObj.group() : ", matchObj.group()  
    print "matchObj.group(1) :", matchObj.group(1)  
    print "matchObj.group(2) : ", matchObj.group(2)  
else:      
    print "No match!!"  
\`\`\`
```python
#!/usr/bin/python
import re

line = "Cats are smarter than dogs"

matchObj = re.match( r'(.*) are (.*?) .*', line, re.M|re.I)

if matchObj:    
    print "matchObj.group() : ", matchObj.group()
    print "matchObj.group(1) :", matchObj.group(1)
    print "matchObj.group(2) : ", matchObj.group(2)
else:    
    print "No match!!"
```
    
### 插入数学公式
印象笔记 Markdown 支持绝大多数的 LaTeX 数学公式
语法示例：
```math
e^{i\pi} + 1 = 0
```
![math.png](https://github.com/HuChanghong/MarkdownStudy/blob/master/img/math.png)  
更多数学公式的输入可以参考： [KaTeX](https://khan.github.io/KaTeX/docs/supported.html)
### 插入流程图
语法示例：
>\`\`\`mermaid  
graph TD  
A[模块A] -->|A1| B(模块B)  
B -->C{判断条件C}  
C -->|条件C1| D[模块D]  
C -->|条件C2| E[模块E]  
C -->|条件C3| F[模块F]  
\`\`\`  

![graph_TD.img](https://github.com/HuChanghong/MarkdownStudy/blob/master/img/graph_TD.png)  
### 插入时序图
语法示例：
>\`\`\`mermaid  
sequenceDiagram  
A->>B: 是否已收到消息？  
B-->>A: 已收到消息  
\`\`\`  

![sequenceDiagram.img](https://github.com/HuChanghong/MarkdownStudy/blob/master/img/sequenceDiagram.png)  

### 插入甘特图
语法示例：
>\`\`\`mermaid  
gantt  
title 甘特图  
dateFormat YYYY-MM-DD  
section 项目A  
任务1 :a1, 2018-06-06, 30d  
任务2 :after a1 , 20d  
section 项目B  
任务3 :2018-06-12 , 12d  
任务4 : 24d  
\`\`\`  

![gantt.img](https://github.com/HuChanghong/MarkdownStudy/blob/master/img/gantt.png)  
### 设置目录
设置之后可以自动根据设置的分级标题来自动生成目录。  
语法示例：  
`[TOC]`

## 五、印象笔记 Markdown 支持什么快捷键？
Windows 端  

|新建 Markdown 笔记|Ctrl+Alt+D|  
|:---:|:---:|  
|粗体|Ctrl+B|  
|斜体|Ctrl+I|  
|删除线|Ctrl+T|  
|下划线|Ctrl+U|  
|分隔线|Ctrl + Shift + -|  
|编号列表|Ctrl + Shift + O|  
|项目符号列表|Ctrl + Shift + B|  
|插入待办事项|Ctrl + Shift + C|  
|代码块|Ctrl+Shift+L|  
|插入日期和时间|Alt + Shift + D|  
|撤销|Ctrl+Z|  
|在笔记内搜索|Ctrl+F|  

Mac 端  

|新建 Markdown 笔记|CMD+D|
|:---:|:---:|
|粗体|CMD+B|
|斜体|CMD+I|
|删除线|CMD+S|
|分隔线|CMD+L|
|编号列表|CMD+Shift+O|
|项目符号列表|CMD+Shift+U|
|插入待办事项|CMD+Shift+T|
|代码块|CMD+Shift+P|
|撤销|CMD+Z|
|在笔记内搜索|CMD+F|
