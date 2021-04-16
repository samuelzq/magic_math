# 第十一章 微积分的魔力

  
y = x11 =&gt; y’ = 11x10

## 

**沿着切线前进**

数学是科学的语言，用来描述大多数自然规律的数学是微积分。微积分是关于事物如何生长、变化和移动的数学。在本章中，我们将学习如何确定函数变化的速率，以及如何用更简单的函数，比如多项式来近似复杂的函数。微积分也是一种强大的优化工具，它可以用来决定如何选择你的数，以最大化数量（如利润或体积）或最小化数量（如成本或旅行距离）。

举个例子，假设你有一个正方形的硬纸板，每边12英寸，如下图所示。假设你从角落里切出x乘x的方块，然后把结果的标签折叠起来，创建一个托盘。结果托盘的最大可能体积是多少？

我们先把体积视为x的函数，托盘的底部会有面积\(12 − 2x\)\(12 − 2x\)而托盘的高度是x，所以托盘的体积是

V = \(12 − 2x\)2x

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image002.png)

x取什么值时，盒子的体积最大？

我们的目标是选择x的值来使体积尽可能大。我们不能选择太大或太小的x。例如，如果x = 0或x = 6，那么这个盒子的体积是0。x的最优值介于两者之间。

下面是函数y = \(12 − 2x\)2x在x从0到6时的曲线图。当x = 1时，我们计算出体积是y = 100。当x = 2时，y = 128。当x = 3时， y = 108。x = 2的值看起来很有希望，但也许有一个真实的在1到3之间的数会是更好得选择？

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image004.png)

使y = \(12 − 2x\)2x最大的那一点有一条水平的切线。

在最大值的左边，函数是向上的，斜率是正的，向右，它是向下的，斜率是负的。所以，在最大值点上，函数既不增加也不减少：它在两者之间转换。为了更精确地说，在这个最优点，有一条水平的切线（斜率为0）。在这一章中，我们将用微积分来求出0到6之间的点，过这一点的切线是水平的。

说到切线，我们将在这一章中讨论很多问题。例如，我们刚刚考虑的问题是找到切去一角的最佳方法。事实上，我们将在这一章中削减很多的角。微积分是一个庞大的学科，典型的教科书包含了上千页。在短短几十页的篇幅里，我们只能涵盖一些亮点。在这本书中，我们将不讨论积分的主题，它可用来计算复杂物体的面积和体积；我们只关注微分，它量度函数如何增长和变化。

可分析的最简单的函数是直线。第二章中，我们注明直线y = mx + b的斜率是m。这样，如果x增加1，y就增加m。例如，直线y = 2x + 3的斜率是2。如果我们将x增加1（从10到11），则y增加2（从23增加到25）。

下图中，我们画了不同直线的图形。其中y = −x的斜率为-1，y = 5的斜率是0。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image006.png)

直线的图形

给定任意两点，我们可以画一条线，并在不需要直线公式的情况下确定直线的斜率。穿过点\(x1, y1\) 和 \(x2, y2\)的直线的斜率由rise over run公式得出:

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image008.png)

例如取直线y = 2x + 3上两点\(0, 3\)和\(4, 11\)。连接两点的直线的斜率是

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png)

这恰好是我们在最初的直线等式中看到的。

选择考虑方程y = x2 + 1，如下面的曲线所示。这张图不是一条直线，我们可以看到斜率一直在变化。让我们试着确定过点\(1, 2\)的切线的斜率。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image012.png)

对y = x2 + 1，找出过点\(1, 2\)的直线的斜率

坏消息是需要两个点才能确定斜率，而我们只有一个点\(1, 2\)。因此我们首先通过观察一条穿过曲线上两个点的线\(称为割线\)来求切线斜率的近似值。如果x = 1.5，那么y  = 1.52 + 1 = 3.25。我们来看看从\(1, 2\)到\(1.5, 3.25\)的这条线的斜率。根据斜率公式，这条割线的斜率是

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image014.png)

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image016.png)

用割线逼近切线

为了更好的逼近切线，我们将第二个点向\(1, 2\)移动。例如，如果x = 1.1, 则 y = \(1.1\)2 + 1 = 2.21。所得割线的斜率是m = \(2.21 − 2\)/\(1.1 − 1\) = 2.1。在下表中可见，当第二个点越来越靠近\(1, 2\)时，割线的斜率越发接近2。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image018.png)

看看当x = 1 + h在h = 1时，会发生什么。但可能只是与x = 1相差丝毫的距离。此时y = \(1 + h\)2 + 1 = 2 + 2h + h2。这条割线的斜率就是

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image020.png)

当h越来越接近于0时，割线越来越接近2。正式地,我们说

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image022.png)

这个符号表示当h趋于0时，2 + h的极限是2。直觉上，当h越来越接近于0时，2 + h越来越接近2。所以我们发现，曲线y = x2 + 1在点（1, 2）的切线的斜率是2。

一般情况是这样的。对于函数y = f \(x\)，我们想求出点\(x, f \(x\)\)处切线的斜率。如下图所示，穿过点\(x, f \(x\)\)和邻点\(x + h, f \(x + h\)\)的割线的斜率是

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image024.png)

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image026.png)

穿过点\(x, f\(x\)\) 和 \(x + h, f\(x + h\)\)的割线的斜率是![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image028.png)

我们使用符号f′\(x\)表示切线在点 \(x,  f\(x\)\)的斜率，所以

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image030.jpg)

这是一个复杂的定义，我们来举几个例子。对直线 y = mx + b，它的函数是f\(x\) = mx + b。我们用x + h替换x得到 f\(x + h\) = m\(x + h\) + b。所以割线的斜率等于

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image032.jpg)

无论x的值是多少，切线的斜率都等于m，所以 f′\(x\) = m。这能够讲得通，因为直线的斜率y = mx + b 总是m。

现在让我们使用刚刚的定义来推导y = x2 上各点切线的斜率。这里，我们有

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image034.jpg)

当h等于0时，我们有 f′\(x\) = 2x。

对f \(x\) = x3，我们得到

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image036.jpg)

当h等于0时，我们得到 f′\(x\) = 3x2。

给定函数y = f\(x\)，确定微分函数f'\(x\)的过程称为微分。 好消息是，一旦我们找到了几个简单函数的导数，我们就可以很容易地确定更复杂函数的导数，而无需使用上面给出的正式的基于极限的定义。 以下定理非常有用。

**定理：**如果u\(x\) = f \(x\) + g\(x\)，则u′\(x\) = f′\(x\) + g′\(x\)。 换句话说，和的导数就是导数的和。 另外，如果c是任何实数，则c f\(x\)的导数是c f ′\(x\)。

作为这个定理的结果，由于y = x3具有导数3x2并且y = x2具有导数2x，因此 y = x3 + x2的导数是3x2 + 2x。 为了说明第二种说法，函数y = 10x3的导数为30x2。

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p><b>&#x8BC1;&#x660E;&#xFF1A;</b>&#x4EE4;u(x) = f (x) + g(x)&#x3002;&#x5219;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image038.jpg"
          alt/>
        </p>
        <p>&#x4E24;&#x8FB9;&#x540C;&#x65F6;&#x53D6;h &#x2192; 0&#x7684;&#x6781;&#x9650;&#xFF0C;&#x6211;&#x4EEC;&#x5F97;&#x5230;</p>
        <p>u&#x2032;(x) = f&#x2032;(x) + g&#x2032;(x)</p>
        <p>&#x25A1;</p>
        <p>&#x8BF7;&#x6CE8;&#x610F;&#xFF0C;&#x5F53;&#x6211;&#x4EEC;&#x5728;&#x6C42;&#x7B49;&#x5F0F;&#x7684;&#x53F3;&#x8FB9;&#x7684;&#x6781;&#x9650;&#x65F6;&#xFF0C;&#x6211;&#x4EEC;&#x5229;&#x7528;&#x4E86;&#x603B;&#x548C;&#x7684;&#x6781;&#x9650;&#x662F;&#x6781;&#x9650;&#x7684;&#x603B;&#x548C;&#x8FD9;&#x4E00;&#x7ED3;&#x8BBA;&#x3002;
          &#x6211;&#x4EEC;&#x4E0D;&#x4F1A;&#x5728;&#x8FD9;&#x91CC;&#x5BF9;&#x5B83;&#x8FDB;&#x884C;&#x4E25;&#x683C;&#x8BC1;&#x660E;&#xFF0C;&#x4F46;&#x76F4;&#x89C9;&#x662F;&#xFF0C;&#x5982;&#x679C;&#x6570;a&#x8D8A;&#x6765;&#x8D8A;&#x63A5;&#x8FD1;A&#x5E76;&#x4E14;b&#x8D8A;&#x6765;&#x8D8A;&#x63A5;&#x8FD1;B&#xFF0C;&#x5219;a
          + b&#x8D8A;&#x6765;&#x8D8A;&#x63A5;&#x8FD1;A + B&#x3002; &#x8BF7;&#x6CE8;&#x610F;&#xFF0C;&#x4E58;&#x79EF;&#x7684;&#x6781;&#x9650;&#x662F;&#x6781;&#x9650;&#x7684;&#x4E58;&#x79EF;&#xFF0C;&#x5546;&#x7684;&#x6781;&#x9650;&#x662F;&#x6781;&#x9650;&#x7684;&#x5546;&#x3002;
          &#x4F46;&#x6B63;&#x5982;&#x6211;&#x4EEC;&#x5C06;&#x770B;&#x5230;&#x7684;&#xFF0C;&#x5BFC;&#x6570;&#x7684;&#x76F8;&#x5E94;&#x89C4;&#x5219;&#x5E76;&#x4E0D;&#x90A3;&#x4E48;&#x76F4;&#x622A;&#x4E86;&#x5F53;&#x3002;
          &#x4F8B;&#x5982;&#xFF0C;&#x4E58;&#x79EF;&#x7684;&#x5BFC;&#x6570;&#x4E0D;&#x662F;&#x5BFC;&#x6570;&#x7684;&#x4E58;&#x79EF;&#x3002;</p>
        <p>&#x5BF9;&#x4E8E;&#x5B9A;&#x7406;&#x7684;&#x540E;&#x534A;&#x90E8;&#x5206;&#xFF0C;&#x5982;&#x679C;
          v(x) = c f (x)&#xFF0C;&#x90A3;&#x4E48;&#x6211;&#x4EEC;&#x6709;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image040.jpg"
          alt/>
        </p>
        <p>&#x7ED3;&#x8BBA;&#x5F97;&#x8BC1;</p>
        <p>&#x25A1;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

为了求f\(x\) = x4的微分，让我们先将函数f\(x + h\)展开，f\(x + h\) = \(x + h\)4 = x4 + 4x3h + 6x2h2 + 4xh3 + h4。多项式的系数1、4、6、4、1看起来很熟悉，它们正是第四章介绍过的帕斯卡三角的第4行。这样我们便有了

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image042.jpg)

随着h → 0，我们得到f′\(x\) = 4x3。你看到其中的模式了吗？ x、x2、x3和x4的导数分别为1、2x、3x2和4x3。将相同的逻辑应用于更高的指数给了我们以下强大的规则。导数的另一个通用符号是y'，所以让我们开始在这里使用它。

**定理（指数法则）：**对于 n ≥ 0,

y = xn 的导数是 y ′ = nxn−1

例如

如果y = x5，则y′ = 5x4

如果y = x10，则y′ = 10x9

即使是一个常数函数，如y = 1，也可以通过这个规则来求导。因为对于任意x，1 = x0且y = x0具有导数0x-1 = 0。 这是有道理的，因为y = 1是水平的。 作为指数法则和先前定理的结果，我们现在可以为任何多项式求导。 例如，如果

y = x10 + 3x5 - x3 - 7x + 2520

则

y'= 10x9 + 15x4 - 3x2 - 7

当n不是正整数时，指数法则也是正确的。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image044.png)  
 ![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image046.png)  
 ![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image048.png)  
 ![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image050.png)

但我们尚未准备好证明它们。 在我们学习如何对更复杂的函数进行微分之前，让我们利用迄今为止学到的知识来解决一些其他有趣且实用的最优化问题。

最大最小问题

微分可帮助我们确定函数最大值或最小值的位置。 例如，在x取什么值时，抛物线y = x2 - 8x + 10会达到其最低点？

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image052.jpg)

抛物线y = x2 − 8x + 10 在 y′ = 0时处于它的最低点

最低点的切线斜率必须为0。由于y'= 2x - 8，求解2x - 8 = 0。结果告诉我们：当x = 4时，抛物线处于最低点（此时y = 16 - 32 + 10 = - 6）。 对于函数y = f\(x\)，满足f'\(x\)= 0的x称为f的临界点。 对于函数y = x2 - 8x + 10，唯一的临界点是x = 4。

最大值发生在哪里？ 在上述问题中，没有最大值，因为x2 - 8x + 10的y值可以任意大。 但是如果x被限制在一个区间内，比如0≤ x ≤6，那么y在其中一个端点上是最大的。 在这里，我们看到当x = 0时，y = 10；当x = 6时，y = -2，所以函数在x = 0时被最大化。一般来说，我们有下面的重要定理。

**定理（优化定理）：**如果一个可微函数y = f\(x\)在点x\*处被最大化或最小化，那么x\*必须是f的临界点或者一个端点。

让我们回到本章开头的盒子问题。 在这里，我们有兴趣使以下函数最大化

y =\(12 - 2x\)2x = 4x3 - 48x2 + 144x

其中x要求在0到6之间。我们希望找到使y值最大化的x值。 由于我们的函数是一个多项式，我们可以看到它有导数

y' = 12x2 - 96x + 144 = 12\(x2 - 8x + 12\)=  12\(x – 2\)\(x – 6\)

因此该函数具有临界点x = 2和x = 6。

该盒子在两个端点x = 0和x = 6处具有体积0，因此体积在那里最小化。 它在另一个临界点x = 2处有最大体积，即y = 128立方英寸。

微分法则

我们能微分的函数越多，我们能解决的问题就越多。也许微分中最重要的函数是指数函数y = ex。y = ex最特殊的地方是它等于它自己的导数。

**定理:** 对y = ex, 有y′ = ex。

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p>&#x4E3A;&#x4EC0;&#x4E48; f (x) = ex&#x6EE1;&#x8DB3; f&#x2032;(x) = ex&#xFF1F;&#x8FD9;&#x662F;&#x57FA;&#x672C;&#x7684;&#x60F3;&#x6CD5;&#x3002;&#x9996;&#x5148;&#x6CE8;&#x610F;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image054.jpg"
          alt/>
        </p>
        <p>&#x73B0;&#x5728;&#x8BF7;&#x56DE;&#x5FC6;e&#x7684;&#x5B9A;&#x4E49;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image056.jpg"
          alt/>
        </p>
        <p>&#x8FD9;&#x610F;&#x5473;&#x7740;&#x5F53;n&#x8D8A;&#x6765;&#x8D8A;&#x5927;&#x65F6;&#xFF0C;(1
          + 1/n)n&#x8D8A;&#x6765;&#x8D8A;&#x63A5;&#x8FD1;e&#x3002;&#x73B0;&#x5728;&#x4EE4;
          h = 1/n&#x3002;&#x5F53;n&#x975E;&#x5E38;&#x5927;&#x65F6;&#xFF0C;h = 1/n&#x63A5;&#x8FD1;0&#x3002;&#x8FD9;&#x6837;&#x5BF9;&#x63A5;&#x8FD1;0&#x7684;h&#xFF0C;e
          &#x2248; (1 + h)1/h&#x3002;</p>
        <p>&#x5982;&#x679C;&#x6211;&#x4EEC;&#x5728;&#x7B49;&#x5F0F;&#x4E24;&#x8FB9;&#x5404;&#x6C42;h&#x6B21;&#x5E42;&#x3002;&#x6839;&#x636E;&#x6307;&#x6570;&#x5B9A;&#x5F8B;
          &#xFF0C;&#x6211;&#x4EEC;&#x5C06;&#x770B;&#x5230;</p>
        <p>eh &#x2248; 1 + h</p>
        <p>&#x6240;&#x4EE5;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image058.jpg"
          alt/>
        </p>
        <p>&#x8FD9;&#x6837;&#x5F53;h&#x8D8B;&#x8FD1;0&#x65F6;&#xFF0C;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image060.jpg"
          alt/>
        </p>
        <p>&#x8D8B;&#x8FD1;&#x4E8E; ex&#x3002;</p>
        <p>&#x25A1;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

是否还有其它函数是它们自己的导数？有的，不过它们都形如y = cex，其中c是一个实数。（请注意，这包括c = 0的情况，此时我们得到常数函数y = 0）。

我们已经看到，当我们将函数相加时，和的导数就是导数的和。 那么相乘的结果是什么呢？遗憾的是乘积的导数并不是导数的乘积。但是求乘积的导数并不是很难，正如下面的定理所证明的那样。

**定律（导数乘法法则）：**如果 y = f \(x\)g\(x\)，则y′ = f\(x\)g′\(x\) + f′\(x\)g\(x\)

例如，根据乘法法则， y = x3ex的导数可以这么求，令 f \(x\) = x3、g\(x\) = e。所以

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image062.jpg)

注意当 f \(x\) = x3、g\(x\) = x5时，根据乘法法则，它们乘积的导数x3x5 = x8是

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image064.jpg)

结果与指数法则一致。

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p><b>&#x8BC1;&#x660E;&#xFF08;&#x4E58;&#x6CD5;&#x6CD5;&#x5219;&#xFF09;&#xFF1A;</b>&#x4EE4;u(x)
          = f (x)g(x)&#x3002;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image066.jpg"
          alt/>
        </p>
        <p>&#x5206;&#x5B50;&#x90E8;&#x5206;&#x540C;&#x65F6;&#x52A0;&#x4E0A;&#x548C;&#x51CF;&#x53BB;
          f (x + h)g(x)</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image068.jpg"
          alt/>
        </p>
        <p>&#x968F;&#x7740; h &#x2192; 0&#xFF0C;&#x7ED3;&#x679C;&#x53D8;&#x6210;f
          (x)g&#x2032;(x) + f&#x2032;(x)g(x)</p>
        <p>&#x25A1;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

乘法法则不仅在计算上有用：它还使我们能够找到其它函数的导数。 例如，我们以前证明了正指数的指数法则。 但是现在我们可以证明该法则在指数为分数和负数时也成立。

例如指数法则预测：如果![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image070.png)，则![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image072.png)。

让我们使用乘法法则验证一下它为何是对的。假设

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image074.jpg)

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image076.jpg)

我们在等式两边同时求导，根据乘法法则，我们得到

u\(x\)u′\(x\) + u′\(x\)u\(x\) = 1

这样2u\(x\)u′\(x\) = 1，

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image078.jpg)

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p>&#x6307;&#x6570;&#x6CD5;&#x5219;&#x540C;&#x65F6;&#x9884;&#x6D4B;&#x4E86;&#x8D1F;&#x6307;&#x6570;
          y = x&#x2212;n&#x7684;&#x5BFC;&#x6570;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image080.jpg"
          alt/>
        </p>
        <p>&#x4E3A;&#x8BC1;&#x660E;&#x8FD9;&#x4E00;&#x70B9;&#xFF0C;&#x4EE4;u(x) =
          x&#x2212;n, &#x5176;&#x4E2D; n &#x2265; 1&#x3002;&#x6839;&#x636E;&#x5B9A;&#x4E49;&#xFF0C;
          x &#x2260; 0&#x65F6;&#xFF0C;&#x6709;u(x) xn = x&#x2212;nxn = x0 = 1</p>
        <p>&#x5F53;&#x6211;&#x4EEC;&#x5BF9;&#x7B49;&#x5F0F;&#x4E24;&#x8FB9;&#x540C;&#x65F6;&#x6C42;&#x5FAE;&#x5206;&#xFF0C;&#x4E58;&#x6CD5;&#x6CD5;&#x5219;&#x544A;&#x8BC9;&#x6211;&#x4EEC;</p>
        <p>u(x)(nxn&#x2212;1) + u&#x2032;(x)xn = 0</p>
        <p>&#x5C06;&#x7B2C;&#x4E00;&#x9879;&#x79FB;&#x5230;&#x7B49;&#x5F0F;&#x53F3;&#x8FB9;&#xFF0C;&#x5E76;&#x540C;&#x65F6;&#x9664;&#x4EE5;xn</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image082.jpg"
          alt/>
        </p>
        <p>&#x25A1;</p>
        <p>&#x8FD9;&#x6837;&#xFF0C;&#x5982;&#x679C; y = 1/x = x&#x2212;1&#xFF0C;&#x5219;y&#x2032;
          = &#x2212;1/x2&#x3002;</p>
        <p>&#x5982;&#x679C;y = 1/x2 = x&#x2212;2&#xFF0C;&#x5219;y&#x2032; = &#x2212;
          2x&#x2212;3 = &#x2212; 2/x3</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

第7章中，我们希望能找到是函数y = x + 1/x值最小的正数x。

使用巧妙的几何方法，我们证明这一点是x = 1。但是使用微积分，我们不必如此聪明。我们仅需解决y′ = 0，即1 − 1/x2 = 0。满足我们需求的唯一正数是x = 1。

三角函数也可求微分。 请注意，为了使下面的定理成立，角必须以弧度表示。

**定理：**如果y = sin x，则y'= cos x。 如果y = cos x，则y'=-sin x。 换句话说，正弦的导数是余弦，余弦的导数是负的正弦。

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p>&#x65C1;&#x767D;</p>
        <p><b>&#x8BC1;&#x660E;&#xFF1A;</b>&#x8BC1;&#x660E;&#x4F9D;&#x8D56;&#x4E8E;&#x4E0B;&#x9762;&#x7684;&#x5F15;&#x7406;&#x3002;
          &#xFF08;&#x5F15;&#x7406;&#x662F;&#x4E00;&#x4E2A;&#x53EF;&#x4EE5;&#x5E2E;&#x52A9;&#x6211;&#x4EEC;&#x8BC1;&#x660E;&#x66F4;&#x91CD;&#x8981;&#x7684;&#x5B9A;&#x7406;&#x7684;&#x63CF;&#x8FF0;&#x3002;&#xFF09;</p>
        <p><b>&#x5F15;&#x7406;&#xFF1A;</b>
        </p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image084.jpg"
          alt/>
        </p>
        <p>&#x8FD9;&#x5C31;&#x662F;&#x8BF4;&#xFF0C;&#x5BF9;&#x4E8E;&#x63A5;&#x8FD1;0&#x7684;&#x4EFB;&#x4F55;&#x5FAE;&#x5C0F;&#x89D2;&#x5EA6;h&#xFF08;&#x4EE5;&#x5F27;&#x5EA6;&#x8868;&#x793A;&#xFF09;&#xFF0C;&#x5176;&#x6B63;&#x5F26;&#x503C;&#x975E;&#x5E38;&#x63A5;&#x8FD1;h&#xFF0C;&#x5176;&#x4F59;&#x5F26;&#x503C;&#x975E;&#x5E38;&#x63A5;&#x8FD1;1&#x3002;&#x4F8B;&#x5982;&#xFF0C;&#x8BA1;&#x7B97;&#x5668;&#x663E;&#x793A;sin
          0.0123 = 0.0122996.... &#x548C;cos0.0123 = 0.9999243...&#x3002;&#x73B0;&#x5728;&#x5047;&#x8BBE;&#x5F15;&#x7406;&#x6210;&#x7ACB;&#xFF0C;&#x6211;&#x4EEC;&#x53EF;&#x4EE5;&#x5FAE;&#x5206;&#x6B63;&#x5F26;&#x51FD;&#x6570;&#x548C;&#x4F59;&#x5F26;&#x51FD;&#x6570;&#x3002;
          &#x6211;&#x4EEC;&#x4F7F;&#x7528;&#x4E86;&#x7B2C;9&#x7AE0;&#x7684;sin(A
          + B)&#x6052;&#x7B49;&#x5F0F;&#x3002;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image086.jpg"
          alt/>
        </p>
        <p>&#x968F;&#x7740; h &#x2192; 0&#xFF0C;&#x6839;&#x636E;&#x6211;&#x4EEC;&#x7684;&#x5F15;&#x7406;&#xFF0C;&#x4E0A;&#x9762;&#x7684;&#x8868;&#x8FBE;&#x5F0F;&#x53EF;&#x4EE5;&#x5199;&#x6210;(sin
          x)(0) + (cos x)(1) = cos x.&#x3002;&#x540C;&#x6837;&#x53EF;&#x4EE5;&#x5F97;&#x5230;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image088.jpg"
          alt/>
        </p>
        <p>&#x5F53;h &#x2192; 0&#xFF0C;&#x8868;&#x8FBE;&#x5F0F;&#x53D8;&#x6210;(cos
          x)(0) &#x2212; (sin x)(1) = &#x2212; sin x</p>
        <p>&#x7ED3;&#x8BBA;&#x5F97;&#x8BC1;</p>
        <p>&#x25A1;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p>&#x6211;&#x4EEC;&#x53EF;&#x4EE5;&#x5229;&#x7528;&#x4E0B;&#x56FE;&#x8BC1;&#x660E;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image090.jpg"
          alt/>
        </p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image092.jpg"
          alt/>
        </p>
        <p>&#x5728;&#x4E0A;&#x9762;&#x7684;&#x5355;&#x4F4D;&#x5706;&#x4E0A;R = (1,
          0)&#x3001;P = (cos h, sin h)&#x3002;&#x5176;&#x4E2D;h&#x662F;&#x4E00;&#x4E2A;&#x5F88;&#x5C0F;&#x7684;&#x6B63;&#x89D2;&#x3002;&#x540C;&#x6837;&#x5728;&#x76F4;&#x89D2;&#x4E09;&#x89D2;&#x5F62;OQR&#x4E2D;&#xFF0C;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image094.jpg"
          alt/>
        </p>
        <p>&#x76F4;&#x89D2;&#x4E09;&#x89D2;&#x5F62;OPS&#x7684;&#x9762;&#x79EF;&#x662F;&#xBD;cos
          h sin h&#xFF0C;&#x76F4;&#x89D2;&#x4E09;&#x89D2;&#x5F62;OQR&#x7684;&#x9762;&#x79EF;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image096.jpg"
          alt/>
        </p>
        <p>&#x73B0;&#x5728;&#x770B;&#x770B;&#x6247;&#x5F62;OPR&#xFF0C;&#x5B83;&#x662F;&#x4E00;&#x4E2A;&#x6954;&#x5F62;&#x3002;&#x5355;&#x4F4D;&#x5706;&#x9762;&#x79EF;&#x662F;&#x3C0;12
          = &#x3C0;&#xFF0C;&#x6247;&#x5F62;OPS&#x7684;&#x9762;&#x79EF;&#x662F;&#x5355;&#x4F4D;&#x5706;&#x7684;h/(2&#x3C0;)&#x3002;&#x8FD9;&#x6837;&#x6247;&#x5F62;&#x9762;&#x79EF;&#x662F;&#x3C0;(h/2&#x3C0;)
          = h/2&#x3002;</p>
        <p>&#x56E0;&#x4E3A;&#x6247;&#x5F62;OPS&#x5305;&#x542B;&#x4E09;&#x89D2;&#x5F62;OPS&#x5E76;&#x88AB;&#x4E09;&#x89D2;&#x5F62;OQR&#x5305;&#x542B;&#x3002;&#x6BD4;&#x8F83;&#x5B83;&#x4EEC;&#x7684;&#x9762;&#x79EF;&#xFF0C;&#x6211;&#x4EEC;&#x5F97;&#x5230;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image098.jpg"
          alt/>
        </p>
        <p>&#x901A;&#x8FC7;&#x90FD;&#x4E58;&#x4EE5;
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image100.png"
          alt/>&#xFF0C;&#x6211;&#x4EEC;&#x5F97;&#x5230;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image102.png"
          alt/>
        </p>
        <p>&#x5BF9;&#x4E8E;&#x6B63;&#x6570;&#xFF0C;&#x5982;&#x679C;a &lt; b &lt;
          c, &#x5219; 1/c &lt; 1/b &lt; 1/a&#x3002;&#x6240;&#x4EE5;&#xFF0C;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image104.png"
          alt/>
        </p>
        <p>&#x73B0;&#x5728;&#x5230;h &#x2192; 0&#xFF0C;cosh&#x548C;1/cosh&#x90FD;&#x8D8B;&#x8FD1;&#x4E8E;1&#x3002;&#x8FD9;&#x6837;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image106.png"
          alt/>
        </p>
        <p>&#x25A1;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p>&#x65C1;&#x767D;</p>
        <p>&#x4F7F;&#x7528;&#x4E4B;&#x524D;&#x7684;&#x7ED3;&#x679C;&#x548C;&#x5C11;&#x91CF;&#x7684;&#x4EE3;&#x6570;&#xFF0C;&#x6211;&#x4EEC;&#x80FD;&#x8BC1;&#x660E;
          <img
          src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image108.png"
          alt/>&#x3002;&#x5229;&#x7528;&#x4E4B;&#x524D;&#x7684;&#x7ED3;&#x679C;&#x548C;&#x51E0;&#x884C;&#x4EE3;&#x6570;&#xFF08;&#x5305;&#x62EC;
          <img
          src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image110.png"
          alt/>&#xFF09;&#x3002;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image112.png"
          alt/>
          <br />
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image114.png"
          alt/>
        </p>
        <p>&#x73B0;&#x5728;&#x53E6;h &#x2192; 0&#xFF0C;
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image116.png"
          alt/>&#xFF0C;
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image118.png"
          alt/>= 0&#x3002;</p>
        <p>&#x6240;&#x4EE5;
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image120.png"
          alt/>&#x3002;</p>
        <p>&#x25A1;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

一旦我们知道了正弦和余弦的导数，我们就可以对正切函数进行微分。

**定理：**对于y = tan x，y' = 1 /\(cos2x\) = sec2x。

**证明：**令u\(x\) = tan x = \(sin x\)/\(cos x\)。 然后

tan\(x\)cos x = sin x

对两边求微分并使用乘法法则，我们得到

tan x\(-sin x\) + tan'\(x\)cos x = cos x

除以cos x并求解tan'（x）

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image122.jpg)

其中倒数第二步实际上是将等式cos2 x + sin2 x = 1除以cos2 x。

□

利用相似的方法我们可以证明微分的除法法则。

**定理（除法法则）：**如果u\(x\) = f \(x\)/g\(x\)，则

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image124.jpg)

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p><b>&#x9664;&#x6CD5;&#x6CD5;&#x5219;&#x7684;&#x8BC1;&#x660E;&#xFF1A;</b>&#x56E0;&#x4E3A;u(x)g(x)
          = f (x)&#xFF0C;&#x5F53;&#x6211;&#x4EEC;&#x4E24;&#x8FB9;&#x540C;&#x65F6;&#x6C42;&#x5FAE;&#x5206;&#x65F6;&#xFF0C;&#x6839;&#x636E;&#x4E58;&#x6CD5;&#x6CD5;&#x5219;</p>
        <p>u(x)g&#x2032;(x) + u&#x2032;(x)g(x) = f&#x2032;(x)</p>
        <p>&#x4E24;&#x8FB9;&#x540C;&#x65F6;&#x4E58;&#x4EE5;g(x),</p>
        <p>g(x)u(x)g&#x2032;(x) + u&#x2032;(x)g(x)g(x) = g(x)f&#x2032;(x)</p>
        <p>&#x5C06;g(x)u(x) &#x66FF;&#x6362;&#x6210; f (x) &#xFF0C;u&#x2032;(x)&#x6B63;&#x662F;&#x6211;&#x4EEC;&#x60F3;&#x8981;&#x7684;&#x3002;</p>
        <p>&#x25A1;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

我们知道如何对多项式、指数函数，三角函数等进行微分。 我们已经看到如何在函数被加，乘和除时进行微分。 **连锁规则**（陈述如下，但不做证明）告诉我们如何对复合函数进行微分。 例如，f\(x\) = sin x且g\(x\) = x3，那么

f\(g\(x\)\) = sin\(g\(x\)\) = sin\(x3\)

注意反过来得到不同的函数

g\(f\(x\)\) = g\(sin x\) = \(sin x\)3

**定理（连锁法则）：**y = f \(g\(x\)\), 有 y′ = f′\(g\(x\)\)g′\(x\)

例如, 如果f \(x\) = sin x, g\(x\) = x3, 则f′\(x\) = cos x、g′\(x\)=3x2。根据连锁法则y = f \(g\(x\)\) = sin\(x3\), y′ = f′\(g\(x\)\)g′\(x\) = cos\(g\(x\)\)g′\(x\) = 3x2 cos\(x3\)

更一般的，根据连锁法则 y = sin\(g\(x\)\), y′ = g′\(x\) cos\(g\(x\)\)。根据相同的逻辑y = cos\(g\(x\)\)，y′ = −g′\(x\) sin\(g\(x\)\)。

另一方面，对函数y = g\(f \(x\)\) = \(sin x\)3，, 根据连锁法则y′ = g′\(f\(x\)\)f′\(x\) = 3\(f\(x\)2\)，f′\(x\) = 3 sin2 x cos x

更一般的，根据连锁法则y = \(g\(x\)\)n, y′ = n\(g\(x\)\)n−1 g′\(x\)。依据连锁法则，函数y = \(x3\)5的结果是什么样的呢？

y′ = 5\(x3\)4\(3x2\) = 5x12\(3x2\) = 15x14

结果和指数法则一致。

让我们求的微分

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image126.jpg)

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image128.jpg)

指数函数的微分也变得很容易。因为ex 是它自身的微分，如果y = eg\(x\), 则

y′ = g′\(x\)eg\(x\)

例如, y = ex3 的导函数是 y′ = \(3x2\)ex3.

注意函数y = ekx具有导函数y' = kekx = ky。 这是使指数函数如此重要的属性之一。 当一个函数的增长率与其输出的大小成正比时，指数函数就会出现。 这就是为什么指数函数经常出现在财务和生物问题中的原因。

自然对数函数ln x具有这样的性质

eln x = x

对x &gt; 0，让我们使用连锁法则推算它的导数。令u\(x\) = ln x，我们得到 eu\(x\) = x。接下来u′\(x\) = 1/x。换句话，如果y = ln x，则y′ = 1/x。再次应用连锁法则y = ln\(g\(x\)\)，

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image130.jpg)

我们总结连锁规则的结果如下。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image132.jpg)

让我们运用连锁规则来解决奶牛问题！ 奶牛克拉拉在河以北一英里处，这条河从东向西流。 谷仓位于它目前位置以东三英里，以北一英里处。 它从河边喝水，然后回到谷仓。为以减少它的总步行量，它应该在河边的哪一点停下来喝水？

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image134.jpg)

奶牛克拉拉问题：在河边的哪一处停下了喝水，奶牛经过的路程最短

假定克拉拉沿直线从 \(0, 1\)走到\(x, 0\)饮水，根据勾股定理（或者距离公式），这一段路程的长度是√\(x²+1\)。回到谷仓B = \(3, 2\)的距离是

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image136.jpg)

这样问题变成，在0和3之间推导x，使得下面的方程值最小

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image138.jpg)

我们对上面的方程式求微分并令其等于0

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image140.jpg)

你可以验证，x = 1，等式左边变成，其值正好是0。

我们可以使用第7章中的镜像法来证实我们的答案。想象一下，饮水之后，克拉拉不再去（3，2）的谷仓，而是去了谷仓的镜像B'=（3， - 2），如下图所示。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image142.jpg)

利用镜像，我们有一个不同的解题方法

克拉拉到B'的距离与到B的距离完全相同。从河上到河下的每个点必须在某处穿过x轴。 具有最短距离的路径是从（0，1）到（3，-2）（斜率-3 / 3 = -1）的直线。这条直线当x = 1时与x轴相交。本方法不需要微分或平方根！

神奇的应用：泰勒级数

当我们在上章末尾证明欧拉方程时，我们依靠的是以下神秘的公式：

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image144.jpg)

在我们搞清楚它们是如何得到的之前，让我们先轻松一下。看看对ex的级数的每一项求微分时会发生什么？例如，指数法则告诉我们，x4 / 4的导数！是\(4x3\)/ 4！ = x3/ 3！，这是级数中的前一项。换句话说，当我们将ex的级数微分时，我们再次得到ex的级数，这与我们对ex的认识一致！

如果我们对x - x3 / 3！ + x5 / 5！ - x7 / 7！ +···的各项求微分，我们得到1 - x2 / 2！ + x4 / 4！ - x6 / 6！ +···，这与正弦函数的导数是余弦函数的事实一致。同样，当我们求余弦级数的微分时，我们得到了正弦级数的负值。还要注意，该级数确认了cos 0 = 1，并且因为每个指数都是偶数，所以cos\(- x\)的值将与cos x相同，这些都是我们知道的事实。 （例如，\(-x\)4/4！= x4 / 4 !）同样，对于正弦级数，我们看到sin 0 = 0并且因为所有指数都是奇数，我们得到sin\(- x\)= - sin x。

现在让我们看看这些公式是如何得来的。在本章中，我们学习了如何找到最常用函数的导数。但有些时候，计算它的二阶导数或三阶导数或更多阶导数也是很有用的。我们用f’’\(x\)，f’’’\(x\)等表示函数的高阶导数。二阶导数f’’\(x\)量度函数在点（x，f\(x\)）处函数斜率（也称为凹度）的变化率。三阶导数测量二阶导数的变化率，依此类推。

上面给出的公式称为泰勒级数，以英国数学家布鲁克泰勒（Brook Taylor，1685-1731）命名。对于具有导数f′\(x\)，f″\(x\)，f′″\(x\)等的函数f\(x\)，当x非常接近于0时，我们有

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image146.jpg)

非常接近是什么意思呢？对于某些函数，如 ex、 sin x和cos x，所有的x都是非常接近。但是对另一些我们将在后面看到函数，x必须很小，否则级数展开就不能很好的近似原函数。

让我们看看f \(x\) = ex的公式是什么？因为ex是它的第一个（第二、第三……）导数，所以

f \(0\) = f′\(0\) = f″\(0\) = f′″\(0\) = · · · = e0 = 1

 ex 的泰勒级数是 1 + x + x2/2! + x3/3! + x4/4! + . . . 。当x非常小时，我们只要计算级数的前几项即可得到一个精确值的近似。

让我们应用这种方法计算复利。在上一章中，我们看到，在5%连续复利下，$1000本金一年后会变成$1000e0.05 = $1051.27。不过我们可以用二阶泰勒多项式近似得到一个很好的估计。

$1000\(1 + 0.05 + \(0.05\)2/2!\) = $1051.25

三阶多项式得出$1051.27。

我们在下图中说明泰勒近似，其中y = ex与其前三个泰勒多项式一起绘制。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image148.jpg)

ex的泰勒近似

当我们增加泰勒多项式的阶数时，近似值变得越来越精确，特别是对于接近0的x值。那么泰勒多项式是如何使它们工作得这么好？ 一阶近似（也称为线性近似）说，对于接近0的x，

f\(x\) ≈ f\(0\) + f′\(0\)x

这是通过点（0，f\(0\)）并具有斜率f'\(0\)的直线。 同样，可以证明，第n次泰勒多项式经过点（（0，f\(0\)）时和 原函数f\(x\)具有相同的一阶导数，相同的二阶导数，相同的三阶导数等等，直到第n阶导数。

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p>&#x6CF0;&#x52D2;&#x591A;&#x9879;&#x5F0F;&#x548C;&#x6CF0;&#x52D2;&#x7EA7;&#x6570;&#x53EF;&#x4EE5;&#x88AB;&#x5B9A;&#x4E49;&#x6210;&#x5F53;x&#x63A5;&#x8FD1;&#x4EFB;&#x610F;&#x7684;&#x6570;&#x3002;&#x7279;&#x522B;&#x7684;&#x662F;&#xFF0C;f
          (x)&#x57FA;&#x70B9;a&#x5904;&#x7684;&#x6CF0;&#x52D2;&#x7EA7;&#x6570;&#x662F;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image150.jpg"
          alt/>
        </p>
        <p>&#x4E0E;&#x5F53;a = 0&#x65F6;&#x4E00;&#x6837;&#xFF0C;&#x5BF9;&#x4E8E;&#x6240;&#x6709;&#x8DB3;&#x591F;&#x63A5;&#x8FD1;a&#x7684;&#x5B9E;&#x6570;&#x6216;&#x590D;&#x6570;x&#xFF0C;&#x8BE5;&#x6CF0;&#x52D2;&#x7EA7;&#x6570;&#x7B49;&#x4E8E;f(x)&#x3002;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

让我们看看 f \(x\) = sin x的泰勒级数。注意f′\(x\) = cos x， f″\(x\) = − sin x， f′″\(x\) = − cos x， f″″\(x\) = sin x = f \(x\) 。当它在0处取值时，从f\(0\)开始，我们得到0, 1, 0, −1, 0, 1, 0, −1, . . . 的循环模式，使得x的每一个偶次幂在泰勒级数中消失。因此，对于x的所有值\(以弧度计算\)

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image152.jpg)

类似的，对于f \(x\) = cos x，我们得到

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image154.jpg)

最后，让我们看一个例子。此例子中，泰勒级数在x取一些值时等于该函数，但不是x的所有值。考虑

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image156.jpg)

这里f \(0\) = 1，使用连锁法则，前几阶导数是

f′\(x\) = −1\(1 − x\)−2\(−1\) = \(1 − x\)−2

f″\(x\) = \(−2\)\(1 − x\)−3\(−1\) = 2\(1 − x\)−3

f′″\(x\) = −6\(1 − x\)−4\(−1\) = 3!\(1 − x\)−4

f″″\(x\) = −4!\(1 − x\)−5\(−1\) = 4!\(1 − x\)−5

 继续这种模式（或通过归纳法证明），我们看到\(1 − x\)−1的第n阶导数是n!\(1 − x\)−\(n+1\)，当x = 0时，第n阶导数刚好是n !. 因此，泰勒级数给了我们

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image158.jpg)

但是这个方程只有在x在-1和1之间时才有效。例如，当x大于1时，相加的数变得越来越大，总和将不确定。

我们将在下一章详细讲述这个级数。 与此同时，你可能想知道将无穷的数加起来是什么意思。 这样的总和怎么能有一个结果？ 这是一个值得研究的问题。我们会在探索无穷的本质时，试图回答它。在那里我们会遇到许多令人惊讶，困惑，不直观和美丽的结果。

