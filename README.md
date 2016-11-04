# 分享一些我认为好的文章和书籍

___

## 引言

先前一直有个想法就是把自己读过并感觉非常好的东西记录下来，做个积累，也方便日后用到时，方便查找，但是，由于自己一直的拖延心理始终没做出行动。现在由于自己读过的文章与书籍越来越多，为了留住那些曾经触动自己的东西，我觉得现在是时候take action了。由于这个repository是我刚刚弄的，有些书已经读过很长时间了，因此我需要整理总结一下，把我几年前读过的好书加在这个repository中。

无论是让我拍案叫绝的书籍，还是那些触动我心灵的读物，我都会放在这个repository里分享出来，内容不仅仅限于技术。我会对每个书籍作出一个大致的总结，让其它人少走一些弯路，从而选择出一本更适合自己的书籍，节约大家宝贵的时间，同时我也会为每本书籍和每篇文章加上相应的Tag，以供大家参考。同时对于一些技术类书籍，我会加上我的一个主观难度系数，5 :star:「 最难」 1 :star: 「最简单」。每个人的知识背景不同，对于难度的认知也不尽相同，因此大家参考一下就好。

当然了，如果大家有什么认为好的资料，非常欢迎大家email me（vincenthan1994 AT gmail.com）。

**友情提示：** 查看资料的Tag可以快速了解资料的主题。

___

## 资料

___


#### **Tag** :zap: histogram(直方图) :zap: bar chart(条形图) :zap: R语言plot直方图

[How to Read and Use Histograms in R](http://flowingdata.com/2014/02/27/how-to-read-histograms-and-use-them-in-r/)

文章首先比较了直方图和条形图之间的区别，并用[NBA数据集](https://github.com/hanxlinsist/bookstore/blob/master/datasets/NBA-Census-10.14.2013.csv)具体解释我们应该怎样看直方图，并用具体的R脚本实现了直方图。

**难度系数:** :star: :star:

___

#### **Tag** : :zap: scales

[Scales of Measurement in Statistics](http://stattrek.com/statistics/measurement-scales.aspx)

文章介绍了4个scales，分别是nominal, ordinal, interval, 和ratio scales。也就是特征值的变量类型，比如离散的还是连续的。只不过前面几个是统计学中的术语。

**难度系数:** :star:

___

#### **Tag** : :zap: ggplot2 :zap: facet_grid() :zap: facet_wrap()

[Facets (ggplot2)](http://www.cookbook-r.com/Graphs/Facets_(ggplot2)/)

文章用具体的实例来讲解R语言ggplot2包的facet_grid()和facet_wrap()方法。如果你熟悉seaborn的话，它和seaborn的facetgrid方法相似。

**难度系数:** :star:

___

#### **Tag** : :zap: ggplot2 :zap: smooths

[How can I explore different smooths in ggplot2](http://www.ats.ucla.edu/stat/r/faq/smooths.htm)

文章主要用R语言的ggplot2包去在数据上加smooths来拟合数据从而观察数据的趋势。

**难度系数:** :star:

___

#### **Tag** : :zap: R :zap: table函数

[R Function of the Day: table](http://www.r-bloggers.com/r-function-of-the-day-table/)

文章用自己生成的数据集并提出了相应要探索的问题。从而演示table函数解决提出的问题。

**难度系数:** :star:

___

#### **Tag** : :zap: 对数变换(Log Transformations)

[Log Transformations for Skewed and Wide Distributions](https://www.r-statistics.com/2013/05/log-transformations-for-skewed-and-wide-distributions-from-practical-data-science-with-r/)

文章主要介绍了对数据进行Log Transformations的好处，以及在什么样的情况下采用这种变换最为合适。

**难度系数:** :star: :star:

___

#### **Tag** : :zap: box plot

[How to Read and Use a Box-and-Whisker Plot](http://flowingdata.com/2008/02/15/how-to-read-and-use-a-box-and-whisker-plot/)

文章主要教你怎样看懂box plot。[正态分布与box plot](https://en.wikipedia.org/wiki/File:Boxplot_vs_PDF.svg)

**难度系数:** :star:

___

#### **Tag** : :zap: R :zap: Date

[Date Formats in R](http://www.r-bloggers.com/date-formats-in-r/)

文章主要讲R语言导入字符串或数字作为日期的方法。

**难度系数:** :star:

___

#### **Tag** : :zap: Pearson correlation :zap: Kendall rank correlation :zap: Spearman correlation

[Correlation (Pearson, Kendall, Spearman)](http://www.statisticssolutions.com/correlation-pearson-kendall-spearman/)

文章主要介绍这三种度量两个变量之间correlation的方法，并在什么样的假设下才成立，在什么样的变量关系下用哪种方法。

**难度系数:** :star: :star: :star:

___

#### **Tag** : :zap: R :zap: Apply家族函数

[R tutorial on the Apply family of functions](https://www.datacamp.com/community/tutorials/r-tutorial-apply-family#gs.WOqq9Ow)

文章用具体的实例介绍R语言中Apply家族函数的使用方法和一些与其有密切关联的函数。

**难度系数:** :star:

___

#### **Tag** : :zap: R绘图 :zap: 图形参数

[Graphical Parameters](http://www.statmethods.net/advgraphs/parameters.html)

文章主要讲在用R语言绘图时，用一些图形参数调整图形的字体，颜色，坐标，标题等。

**难度系数:** :star:

___

#### **Tag** : :zap: One-Way Tables :zap: Two-Way Tables

[One-Way Tables](http://stattrek.com/statistics/one-way-table.aspx?Tutorial=AP)
[Two-Way Tables](http://stattrek.com/statistics/two-way-table.aspx?Tutorial=AP)

文章介绍统计学中One-Way Tables和Two-Way Tables的概念，读完这篇文章以后，大家能熟练运用这两个概念去做统计分析。

**难度系数:** :star:

___

#### **Tag** : :zap: Linux命令 :zap: shell脚本

[Linux命令行与shell脚本编程大全(第2版)](https://www.amazon.cn/Linux%E5%91%BD%E4%BB%A4%E8%A1%8C%E4%B8%8Eshell%E8%84%9A%E6%9C%AC%E7%BC%96%E7%A8%8B%E5%A4%A7%E5%85%A8-Richard-Blum/dp/B0096EXMS8/ref=sr_1_2)

这是一本关于Linux命令很好的入门书，它全面细致地讲解了常用的Linux命令。这本书也介绍了怎么写Linux Shell脚本，包括介绍了基本语法，函数，处理用户的一些输入等。但是，这本书只给了很少地脚本例子。如果你已经掌握了很多的Linux命令，并且也可以写一些基本的Shell，那么这本书并不适合你，你应该去找一些更深入的书来看。还有一点建议就是：**千万不要把整个书仔细地从头到尾看下去，你应该大致去了解一些命令，掌握一些基础，剩下的你用到什么就去看什么，否则就算你一下都看完，过后你不用，很快就忘记了，会白白浪费先前的时间。**

**难度系数:** :star:

#### **Tag** : :zap: java web :zap: servlet :zap: 域对象的线程安全性

[Java theory and practice: Are all stateful Web applications broken?](http://www.ibm.com/developerworks/library/j-jtp09238/index.html)

这篇文章主要介绍了servlet中的2个域对象，一个是ServletContext，另一个是HttpSession. 相信学过Java Web的人都会“使用”这2个对象。但是，你真的会使用吗？在高并发的情况下，它们会有什么样的线程问题呢？Brian Goetz（author of Java Concurrency in Practice）在文章中详细地介绍了在高并发的情况下会出现的问题，并用具体的实例来演示可能出现的线程安全问题，并一步步解决出现的问题。

**难度系数:** :star: :star: :star:

#### **Tag** : :zap: java :zap: 磁盘 I/O :zap: 网络 I/O

[深入分析 Java I/O 的工作机制](http://www.ibm.com/developerworks/cn/java/j-lo-javaio/)

这篇文章主要介绍了I/O 的内在工作机制，你将了解到：Java 的 I/O 类库的基本架构；磁盘 I/O 工作机制；网络 I/O 的工作机制；其中以网络 I/O 为重点介绍 Java Socket 的工作方式；你还将了解到 NIO 的工作方式，还有同步和异步以及阻塞与非阻塞的区别，最后还有一些常用的关于 I/O 的优化技巧。

**难度系数:** :star: :star: :star:
