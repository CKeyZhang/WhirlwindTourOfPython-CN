# Python之旅
## 作者序
*Jake VanderPlas, 2016, Summer*

这个仓库包含了我为 O'Reilly 编写的报告《Python 风暴之旅》背后的 Jupyter 笔记本，报告可在 [http://www.oreilly.com/programming/free/a-whirlwind-tour-of-python.csp](http://www.oreilly.com/programming/free/a-whirlwind-tour-of-python.csp) 免费获取，同时报告的 [100 页 PDF](http://www.oreilly.com/programming/free/files/a-whirlwind-tour-of-python.pdf) 也可免费下载。

《Python 风暴之旅》是一本针对已经熟悉其他编程语言的研究人员和开发者快速介绍 Python 语言核心组件的书籍。

该材料特别针对那些希望使用 Python 进行数据科学和 / 或科学编程的人，也作为《Python 数据科学手册》的入门书籍（该手册可在 [http://shop.oreilly.com/product/0636920034919.do](http://shop.oreilly.com/product/0636920034919.do) 购买，其 Jupyter 笔记本也可在 [https://github.com/jakevdp/PythonDataScienceHandbook](https://github.com/jakevdp/PythonDataScienceHandbook) 上查看）。这些材料改编自我在华盛顿大学以及世界各地的各种会议、研讨会和工作坊上讲授的课程和研讨会。

这些材料是使用 **Python 3.5** 编写和测试的，应该适用于任何 Python 3.X 版本。我已尽力标注出 Python 2.X 语法不同的地方。

## 编者序
*Zhang Congke, 2025 ,Spring*

一直以来我都希望能够找到一份可交互的，开源的Python学习库。这在如今这个语言模型迅速发展的时代显得尤为突出。

现如今编程的门槛不断降低，大语言模型极大地提升了编程者的编程效率。在这个时代劝人老老实实写一万行代码或许会受到诸多非议，但我仍然认为对语言本身有所了解是必要的。就如同企业家不一定要了解生产产品的每一道技术细节，但至少应当知道自己是在做什么样的产品，否则难免闹出笑话。

我在重新学习Python语言的过程中偶然接触到这个代码库，感觉 *Jake VanderPlas* 教授编写的笔记作为Python入门教程极为合适。内容浅显易懂，且较为丰富翔实。由于我本人英文不算太好，初读时难免遇到不少障碍，遂决定进行翻译。这个代码库既可以作为Python初学者的入门教程，同时也是一份不错的工具书。

此中文翻译版代码基于Python 3.8运行，建议以此版本作为运行内核进行调试。

此书的姐妹篇 [PythonDataScienceHandbook](https://github.com/jakevdp/PythonDataScienceHandbook) 提供了常用数据处理库的指导，后续我也会尝试翻译并发布。

## 索引

1. [介绍](00-Introduction.ipynb)
2. [如何运行 Python 代码](01-How-to-Run-Python-Code.ipynb)
3. [基本 Python 语法](02-Basic-Python-Syntax.ipynb)
4. [Python 语义：变量](03-Semantics-Variables.ipynb)
5. [Python 语义：运算符](04-Semantics-Operators.ipynb)
6. [内置标量类型](05-Built-in-Scalar-Types.ipynb)
7. [内置数据结构](06-Built-in-Data-Structures.ipynb)
8. [控制流语句](07-Control-Flow-Statements.ipynb)
9. [定义函数](08-Defining-Functions.ipynb)
10. [错误和异常](09-Errors-and-Exceptions.ipynb)
11. [迭代器](10-Iterators.ipynb)
12. [列表推导式](11-List-Comprehensions.ipynb)
13. [生成器和生成器表达式](12-Generators.ipynb)
14. [模块和包](13-Modules-and-Packages.ipynb)
15. [字符串和正则表达式](14-Strings-and-Regular-Expressions.ipynb)
16. [数据科学工具预览](15-Preview-of-Data-Science-Tools.ipynb)
17. [进一步学习的资源](16-Further-Resources.ipynb)
18. [附录：重现图表的代码](17-Figures.ipynb)

## 在线版索引（英文原版）

*(Note: sometimes GitHub's notebook rendering can be slow or finicky.
If you're having trouble with the following links, try viewing the material
[on nbviewer](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/Index.ipynb))*

[Notebook Index](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/Index.ipynb)

1. [Introduction](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/00-Introduction.ipynb)
2. [How to Run Python Code](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/01-How-to-Run-Python-Code.ipynb)
3. [Basic Python Syntax](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/02-Basic-Python-Syntax.ipynb)
4. [Python Semantics: Variables](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/03-Semantics-Variables.ipynb)
5. [Python Semantics: Operators](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/04-Semantics-Operators.ipynb)
6. [Built-In Scalar Types](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/05-Built-in-Scalar-Types.ipynb)
7. [Built-In Data Structures](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/06-Built-in-Data-Structures.ipynb)
8. [Control Flow Statements](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/07-Control-Flow-Statements.ipynb)
9. [Defining Functions](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/08-Defining-Functions.ipynb)
10. [Errors and Exceptions](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/09-Errors-and-Exceptions.ipynb)
11. [Iterators](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/10-Iterators.ipynb)
12. [List Comprehensions](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/11-List-Comprehensions.ipynb)
13. [Generators and Generator Expressions](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/12-Generators.ipynb)
14. [Modules and Packages](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/13-Modules-and-Packages.ipynb)
15. [Strings and Regular Expressions](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/14-Strings-and-Regular-Expressions.ipynb)
16. [Preview of Data Science Tools](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/15-Preview-of-Data-Science-Tools.ipynb)
17. [Resources for Further Learning](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/16-Further-Resources.ipynb)
18. [Appendix: Code To Reproduce Figures](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/17-Figures.ipynb)


## 许可证

这些材料在 "保留所有权利" 的 [CC0](LICENSE)
许可证下发布，因此你可以自由地重用、修改、构建和增强
这些材料，用于任何目的。

尽管如此，我请求（但不要求）如果你使用或改编这些材料，
请包含适当的归属和/或引用；例如

> A Whirlwind Tour of Python by Jake VanderPlas (O’Reilly). Copyright 2016 O’Reilly Media, Inc., 978-1-491-96465-1.

了解更多关于 CC0 的信息，请访问 [这里](https://creativecommons.org/share-your-work/public-domain/cc0/)
