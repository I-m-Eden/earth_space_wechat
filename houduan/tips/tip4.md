Python不只是一门编程语言，根据你的使用方法，它也可以是一个超级计算器，作业helper。根据小编本人的使用经验，本期学术tips，我们来介绍一下Python。



### **安装Python**

Python的官网为: 

https://www.python.org

下载Python的网址为：

https://www.python.org/downloads



目前Python3已经出到了Python3.10.0，但是推荐安装Python3.8.x，现在3.9和3.10都在debug阶段，并且目前大多数Python库都是基于Python3.8.x。



我们就以3.8.10为例：



![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlgfse87g0xreZ5qfpWXQ4xI5WCgplYLQsF7oia9KeO6PkyKW18L6WoBqQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



在downloads界面下拉后点击Python3.8.10。

![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlgxjSjpAic4Xad86QsdLg0sE27YiaTjQfAHGzjzqJkRBs9vLIShhvo7YNw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

下拉后根据自己的系统选择版本，推荐是最下面的installer。

安装Python的过程相信大家都会做，这里就不讲了。



### **IDLE使用教学**

如果是默认设置的话，能够在下面的任务栏中或者windows菜单中找到Python IDLE的快捷方式：

![图片](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)



点开之后就到了Python Shell：

![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlg7R1vXHo1zcaRicGfCI7o3x7vF2efGfiaTmRm7Hb9gdWcDAvdmUibFbGNQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



Python Shell 是Python自带的集成开发环境，具有一些辅助功能。当然，相比于VS Code来说这些辅助功能还是太弱了。不过对于最简单的使用来说这些特性足够了。



Python—高级计算器（当然，你用matlab也是完全可以的）



![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlg4n8tUAvxHMPwFtH6j2Ngia8jc1dZL2QTgmbBg5lnDWCxhf9uj7PeL2w/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlgib56XDbX8zFTjxjyicLQFIzia5ZC06R0uIrsYzoCW0uetYv8pFicmv3ibCQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



在Python Shell里面可以直接敲算式来获得结果，Python Shell的一个好处就是小编敲进去的表达式如果有返回值的话（1+1返回2这样的），它就会直接输出这个值（严谨一些的说是调用对象的__repr__方法）。



math这个库是Python标准库里面的一部分，里面有很多函数，除了上面展示的还有log、gamma等。cmath与math的函数基本是一样的，但它是用于复数计算。（你#include <cmath>，小编import cmath，我们都有光明的前途）





### **Python—实验报告Helper**

（吾日三省吾身，预习报告写了吗，实验报告写完了吗，误差分析懂了吗）

这里就不得不说Python的几个重量级库了，matplotlib、scipy和numpy，这三个库都是需要单独安装，不在Python标准库里面。

一般安装库都是用pip安装。



如果你安装python是默认安装的话，Python3.8.x的文件夹路径应该是：

C:\\Users\(你的用户名)\AppData\Local\Programs\Python\Python38



![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlgtAYWflMr06HiagkddePJsJnsFgmYMSaQujynvfpg3S0KcGFWIObYkeg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

在里面点开Scripts的文件夹，在里面找到pip，有不同后缀的版本都行。



![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlgxzPQh8Q4Kl8Ljojh5HREIvoVk8jlgL4jcsQXibYLjXfia0tbCIXGGjtQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



由于小编还安装了别的一些东西，所以文件夹里面东西多，如果是刚安装，scripts文件夹就光是pip。



这个时候win+R，在弹出的对话框里面输入cmd，打开命令行界面，把pip拖进命令行界面，在后面敲入install [库的名称]。



![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlgfPSUgKF9Gc8jTGEBG3q1ueuvKJqLmSRqhpzqYHmYA6MzHSs1TfDASw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



（不要在意为什么里面出现了隔壁的名字，隔壁有一个python库下载的镜像服务器，国内下载起来更快）

这里面小编已经安装过了，没安装的情况下它会走进度条，最终结束的时候没有红字就是成功，黄字都是提醒pip可以更新的信息，可以不用管。



**Numpy库**是其他两个库的基础，也是Python很多常用科学库的基础，它提供了array这种数据结构以及各种函数和方法。严格来说array是张量，它可以是一维的向量，也可以是二维的矩阵，甚至是更高维度的。



Numpy的最基础使用就可以作为线代Helper。



![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlgZ4hJIFSHn4aV1WNtAoKUUOVkv6cEGZibZqyB4Yx8bYia5ibKkxibHOKkOw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



比如说求逆矩阵就可以用numpy轻松解决，只不过numpy不能支持分数、根号运算，所以用它来一件做题是不太可能了，但是可以去很快检验一下答案。

以上只是numpy的冰山一角，限于篇幅，这里只能展现这么多，如果感兴趣的同学可以自己去探索，使用numpy可以干很多很多事情。



接下来就是重量级的部分，比如说**数据处理**，看图：



![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlgpTf9jUkJwNRWl7q54HdpnUyo6jELfK1dRl3PoXczeLT84ArTR6Cd7A/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

比如说画图：



![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlgMhFNrpjiaWl2FkSnYrx4P0OyVtqqibhs1AKxGrOOCyrMPKdicqA7eg0mg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



细心的同学可能注意到了下面有一个保存的标志，点击一下就可以把图保存到本地（有选保存位置的对话框）。使用plt的其他函数还可以加上表头、坐标轴的单位，保存下来就直接能插入实验报告里面，岂不美哉。



![图片](https://mmbiz.qpic.cn/mmbiz_png/L95QgCH4cVlK402XzSS9kicA3oKlKHKlgfLXZ6dbuSicmv7FOIOIhJicnS5hkj4lYf1D5AnTRre9TojTXSttj9Z5Q/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

学习python，包括C也是一样，很大程度上都需要搜索引擎的帮助，哪个函数的参数是怎么回事，我遇到了这个报错是怎么回事，大家在编程的学习中一定要好好利用网络，并且多尝试，多练手，这样才能成为独当一面的程序员科研人员。



本期学术tips就到这里，感谢大家的阅读。