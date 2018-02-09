# Markdown

## 何为Markdown？

Markdown 是一种轻量级标记语言。它允许人们使用易读易写的纯文本格式编写文档，然后转换成有效的HTML文档，从而实现快速排版。

Markdown 的一大特点是**可读性**。也就是说，它能直接在“字面上的”被阅读，而不用被一些格式化指令标记（例如RTF与HTML）。

许多网站都使用 Markdown 或是其变种，例如：GitHub、reddit 等，为用户讨论带来便利。

更多信息可以到官方网站查看：https://daringfireball.net/projects/markdown/

## Markdown两三话

### Markdown与Word有什么区别？

当然，它们都用来输入带格式的文字。在Word中，用户通过点击例如“加粗”、“倾斜”等按钮赋予文字不同的格式，这种模式被称为 WYSIWYG（_What You See Is What You Get，所见即所得_）。而对于 Markdown，用户输入**纯文字**，通过编辑器的处理，得到一份带格式的文档；或通过编译器，输出为带格式的HTML文档。也就是说，Markdown 本质上是一种**标记语言**。
Markdown 的这种特性决定了它在编辑时往往不能即时地显示效果，而需要用户在「输入文字」和「编辑文字」两个状态中切换。但是这看似怪异的操作习惯也形成了 Markdown 的独特优势。

* **书写流畅。**

    写作时无需在键盘与鼠标之间来回切换，所有格式与文字均由键盘完成。

* **格式几乎不随编辑器改变。**

    很多人都有这样一种体验：在自己的电脑上编辑的 Word 文档，由于版本等问题，在别人的电脑上打开后，格式却大相径庭。Markdown 很少出现这种问题：它有一套通用的标准。虽然它的一些变种加入了一些独特的语法，但常用格式的标记不会改变。

* **易于浏览。**

    对于 MS Word 的 doc (docx) 文件，要取得最佳的预览效果，必须安装臃肿的 MS Office 或 WPS ，亦或是使用加载缓慢的 Office Online 才可查看。而对于 Markdown，由于其开源与统一标准，有很多便捷快速的在线工具（例如 Madoko，它甚至支持 LaTeX 公式）支持在线预览 Markdown，免去了安装软件的繁琐。

### Markdown 入门

#### Markdown 文件

*.md 与 *.markdown 都是 Markdown 文件。

#### Markdown 语法

1. **标题**
    ```
    # 一级标题
    ## 二级标题
    ......
    #### 四级标题	
    ```
    
    本节标题`Markdown 语法`即为四级标题。其中 `一级标题`与 `四级标题` 还有一种写法:
    
    ```
    一级标题
    ====================
    二级标题
    --------------------
    ```
        
2. **加粗、斜体与下划线**
    ```
    *加粗*	, /斜体/, _下划线_, -删除线-
    ```

3. **引用**
    ```
    > 苟利国家生死以，岂因祸福避趋之。
    ```
    效果：
    > 苟利国家生死以，岂因祸福避趋之。	  

    引用可以嵌套。如果要在一个引用里插入一个引用，可以用两个>开头。依此类推，根据嵌套层次加相应数量的符号。

4. **链接**
    ```
    [上海交通大学-电子信息与电气工程学院](http://www.seiee.sjtu.edu.cn/)
    ```
    效果：
    [上海交通大学-电子信息与电气工程学院](http://www.seiee.sjtu.edu.cn/)

5. **图片**
    ```
    ![Markdown](http://markdown.tw/images/208x128.png)
    ```

6. **有序列表**
    ```
    1. 第一项
    2. 第二项
    3. 第三项
    ......
    ```

7. **无序列表**
    ```
    * 项目
    * 项目
    * 项目
    ......
    ```

8. **代码**
    ```
    `print('Hello Markdown!')`
    ```

9. **代码块**
```
	```
	def main():
		print('Hello Markdown!')
	```
```

10. **表格**
    ```
    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |
    ```
    效果：
    
    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |

### Markdown 编辑器

