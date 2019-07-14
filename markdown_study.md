# Markdown
###优点
***
1. 专注你的文字内容而不是排版样式，安心写作。
2. 轻松的导出 HTML、PDF 和本身的 .md 文件。
3. 纯文本内容，兼容所有的文本编辑器与文字处理软件。
4. 随时修改你的文章版本，不必像文字处理软件生成若干文件版本导致混乱。
5. 可读、直观、学习成本低。
***

###使用 markdown 的误区
***
 "We believe that writing is about content, about what you want to say – not about fancy formatting."

                                我们坚信写作写的是内容，所思所想，而不是花样格式。

                                                                        --Ulysses for Mac
***

#Markdown 支持的编辑器
###在线
* Github
* Stackedit
* 简书
* 博客园
* 马克飞象

###Windows
* MarkdownPad
* MarkPad
* Smark
* Miu

###Mac
* Mou
* Macdown
* UIysses
* Typora

#markdown 语法
###标题级别
***
# 一级标题
## 二级标题
### 三级标题
***

### 无序列表
* 王爵的技术小黑屋
* 萌新 UP 主
* 不会写代码的程序员

### 或者 无序列表(另一种写法)
- 王爵的技术小黑屋
- 萌新 UP 主
- 不会写代码的程序员

### 有序列表
1. 我们都是地球人
2. 为啥你就不会 markdown?
3. 看完还不会就要被安排

### 链接的写法
[王爵的技术小黑屋](https://www.youtube.com/biezhi)

### 带Title
[王爵的技术小黑屋](https://www.youtube.com/biezhi "此处可能有炸弹")

### 图片
![](https://i.loli.net/2018/07/19/5b509930126d1.jpg)

### 带 Title
![alt](https://i.loli.net/2018/07/19/5b509930126d1.jpg "嘤嘤嘤")

### 引用方式
![alt][img01]

[img01]: https://i.loli.net/2018/07/19/5b5099f425674.jpg "会不会markdown"

**粗体**

__粗体__

*看，我斜了没*
_真的很斜_

***粗体＋斜体***

~~此处的故事只能用泪水掩盖~~

###`单行代码引用`
> 从明天起，做一个幸福的人   

###多行引用
> 从明天起，做一个幸福的人   
> 喂马、劈柴，周游世界  

### 表格 
注意： 有默认样式（左对齐）、居中、右对齐

| 姓名   | 年龄 |    三围    |
| ----- |:----:| ----------:|
| 罗欲凤 | 18   | 18, 27, 30 |
| 秋刀鱼 | 26   | 28, 25, 33 |

### 代码渲染片段
默认不写格式则是bash。如有设定好的格式要写上，如：python、sh
```go
package main
import "fmt"
func main(){
   fmt.Println("王爵的技术小黑屋");
}
```

###分割线
***
