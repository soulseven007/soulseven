---
description: 语法速看，及时查询！
---

# markdown入门

## 开始

markdown在当前阶段似乎已成为必不可少的一个工具，因此学习并熟练使用它已然成为必经之路。

> tips 1：markdown各应用工具之间可能会存在细微差异，以及快捷键在各应用工具之间的自主定义的差别。选择一个您习惯的编辑器似乎是很有必要的，这能很好的提高您编写markdown的速度
>
> tips 2：编写markdown的过程中，除却其本身的语法之外，也可以直接使用HTML中的一些标签，有时候这样可能更方便一些。

## 基本语法

所有的markdown应用程序都支持基本语法

| 元素 | markdown语法 | 渲染 |
| :--- | :--- | :--- |
| 标题 | \# h1  \#\# h2  \#\#\# h3  ...  \#\#\#\#\#\# h6 |  |
| 粗体 | \*\*bold text\*\* | **粗体** |
| 斜体 | \*italicized text\* | _斜体_ |
| 块引用 | &gt; blockquote |  |
| 有序列表 | 1. First item  2. Second item  3. Third item |  |
| 无序列表 | - First item  - Second item  - Third item |  |
| 代码 | \`code\` | `code` |
| 水平线 | --- |  |
| 超链接 | \[title\]\([https://www.example.com](https://www.example.com)\) | [超链接](https://docs.soulseven.cn/) |
| 图片 | !\[alt text\]\(image.jpg\) |  |

## 扩展语法

并非所有Markdown应用程序都支持这些元素

| 元素 | markdown语法 |
| :--- | :--- |
| 表格 |   `| Syntax | Description |  | ----------- | ----------- |  | Header | Title |  | Paragraph | Text |` |
| 围栏代码块 |  ```````  {  "firstName": "John",  "lastName": "Smith",  "age": 25  }  ``````` |
| 脚注 |  Here's a sentence with a footnote. \[^1\]  \[^1\]: This is the footnote. |
| 标题ID |  \#\#\# My Great Heading {\#custom-id} |
| 自定义列表 |  `term  : definition` |
| 删除线 |  `~~The world is flat.~~` |
| 任务列表 |   `- [x] Write the press release  - [ ] Update the website  - [ ] Contact the media` |

> 如本页，基本语法部分使用了markdown的语法，扩展语法部分则使用了html中的`table`以及`code`等标签。另，由于作者此前虽然对这些内容感兴趣并多次想要熟练使用，但事实确实拖沓懈怠了无数次，也因此本文带来的不足及错漏之处还请各位见谅，也请各位不吝指教，万分感激！

参考链接：\[markdown\]\([http://markdown.p2hp.com/index.html](http://markdown.p2hp.com/index.html)\)

