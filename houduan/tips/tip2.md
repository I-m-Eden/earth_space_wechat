大家是否曾因为高数和普物等专业课上各种各样的求导、积分运算而苦恼呢？普通计算器可以帮我们验证一些基本算式的答案，但它无法实现复杂的积分、矩阵运算，也没有绘制图像等功能。我们这期学术tips 向大家介绍一款强大的数学工具——**Wolfram|Alpha（https://www.wolframalpha.com/），Mathematica**（你可以在北大的正版软件平台找到它的下载链接）。





### Tips 1 Wolfram|Alpha 数学搜索引擎



Wolfram|Alpha是一个计算知识引擎，它的网址链接是 https://www.wolframalpha.com/ ，除了网页版，还可以下载手机app （https://products.wolframalpha.com/mobile/）。



点进网页会看到一个橙色的输入框，按照一定的格式规范输入，就可以得到你想要的结果，比如下图：

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/L95QgCH4cVl9iaCaBtGqlVRrumcXyVZG7wSxsDv2GichRjk1Fzes2RdBgo50ssrcISNVPDbuHdarRGMMZeBicVIhg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

图中的 “\int” 表示积分，“_0^{\infty}” 表示从 0 积分到正无穷。敲下回车就会得到积分结果。除了输入公式语言，我们还可以点击搜索框下方的 “MATH INPUT”，输入图形化的公式。

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/L95QgCH4cVl9iaCaBtGqlVRrumcXyVZG7tyhSztxFB0dGQlp9Mwia54Zto4of7chKuS8K29LOF7SEduhtsDO3ibJA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

我们可以对一个函数进行泰勒展开

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/L95QgCH4cVl9iaCaBtGqlVRrumcXyVZG7esiaCg5y4fFucIOvd7HiatbzAibwDOhFsCGFxwlMJTDdlep8QicoU1AMicA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

除了这些基本计算，Wolfram 还可以解微分方程、画三维图像、进行矩阵运算…… 这些功能可以为我们解决复杂问题提供大量帮助。

### Tips 2  Mathematica

如果想处理更复杂的计算问题，单个搜索框可能就不够用了。下面我们介绍的是Wolfram Mathematica——一个科学计算软件。

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/L95QgCH4cVl9iaCaBtGqlVRrumcXyVZG7ibAMVzU7B8ODFaA6J6IYDr8l69kwBuRfU7PCNiaCQfu3pkkcdXbScgwA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

在前面我们介绍了网页版计算引擎，这个tips中我们要介绍的是它的软件版本——Mathematica。这个软件的“体积”较大，你可以在北大软件平台（https://software.pku.edu.cn/）上找到下载链接。除了可以实现前面提到的计算功能，它可以设置函数与变量，甚至可以直接写代码，可以实现许多一个搜索框干不了的事。

例如我们可以定义函数或变量，并在之后多次引用它

```mathematica
In[1]:= f[x_,y_]=x*x+y*y

In[2]:= f[1,2]+f[3,4]
Out[2]:= 30
```

还可以写 For 循环语句：

```mathematica
In[3]:= sum = 0;
		For[i = 1, i <= 10, i++;
 			sum = sum + f[i + 1, i + 1] - f[i, i];
 		]
		sum
Out[3]:= 280
```

Mathematica 还有许多基本的功能，在这里我们就不具体介绍了，大家可以在网上找到Mathematica的使用教程。

![图片](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/L95QgCH4cVl9iaCaBtGqlVRrumcXyVZG7BoibKro1F3809PhQSjiaRv7F64PYKFcqb8LjkQtCevMA2AsZDsH9vSOw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)