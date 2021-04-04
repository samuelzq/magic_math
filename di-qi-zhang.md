# 第七章

  


## 几何的魔力

一些几何惊喜

让我们从一个可以被当作魔术的几何问题开始。在另一张纸上，按照下面的步骤做。

步骤1，画一个具有四条边的图形，各条边不相交\(这叫做四边形\)。按顺时针顺序给四个角A、B、C和D标上\(见下面的一些例子\)。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg)

三个四边形

步骤2，将四条边的中点标记成E、F、G和H。

步骤3，将各中点连接起来形成四边形EFGH。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image006.jpg)

中点连接起来总是产生一个平行四边形

信不信由你，EFGH肯定是一个平行四边形。换句话 ![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image008.png)和![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png)平行、![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image012.png)和![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image014.png)平行（ ![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image008.png)和![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png)等长，![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image012.png)和![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image014.png)等长）。上图中已经说明了，你最后试试更多的例子。

几何中充满了这样的惊喜。将简单的逻辑参数应用到最简单的假设中，往往会得到很好的结果。让我们做一个小测验来测试你的几何直觉，有些问题的答案很直观，但有些问题的答案会让你大吃一惊，即使在你已经适度学习了几何之后。

**问题1：**一个农民想要建一个周长52英尺的矩形栅栏。怎样建才能使矩形的面积最大化?

A. 正方形（每边13英尺）。

B. 长宽比接近黄金比例1.618（长16英尺，宽10英尺）.

C. 长边尽可能长（接近26英尺）

D. 以上都不对

**问题2：**考虑下面的平行线，在下面的线上有X和Y两个点。我们希望在上面的直线上选择第三个点，这样由X、Y和这个点组成的三角形周长最小。应该选择哪一个点？

A. 点A，该点距离X和Y等距。

B. 点B，B、X、Y组成直角三角形

C. 点C

D. 随便选，所有三角形的周长相等

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image016.jpg)

在上面的直线上选取哪个点组成的三角形周长最小？哪个三角形面积最大？

**问题3：**上图中哪个点和X、Y组成的三角形面积最大？

A.  点A

B.  点B

C.  点C

D.  随便选，所有三角形面积相等

**问题4：**美式橄榄球场上两个门柱之间的距离是360英尺\(120码\)。一根长360英尺的绳子将被紧紧地绑在两个门柱的底部，当额外的一英尺的绳子被加进去。绳子能沿球场中心拉起多高?.

A.  离地面小于1英尺

B.  刚好可以从下面爬过去

C.  可以从下面走过去

D.  可以开过一辆卡车

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image018.jpg)

距离360英尺的两个球门柱之间系上一条361英尺的绳子。这根绳子可以在场地中心被提起多高？

**答案1：**对于任何给定的周长，要使矩形的面积最大化，你应该让所有的边长度相等。因此，最佳的形状将是一个正方形。

**答案2：**A。在X和Y的中点上选择A点，将会产生最小周长的三角形XAY。

**答案3**：所有三角形的面积相同。

**答案4：**D。在场地的中心，绳子可以被拉起超过13英尺。足够高，以至于大多数卡车可以通过。

我们可以用简单的代数来解释第一个答案。对于一个顶部和底部长度为b\(b为底\)和左右长度h \(h为高度\)的矩形，矩形的周长是2b + 2h，这是所有四个边长度的和。面积测量矩形可以填入什么，是b和h的乘积。因为周长是52英尺，所以我们有2b + 2h = 52，或者等效于

b + h = 26

因为h = 26 − b，我们希望最大的面积bh等于b\(26 − b\)= 26b − b2

b的什么值会使等式值最大呢？在第11章中，我们将会看到用微积分的简单解法。但是我们也可以通过使用第2章中给出的方法来找到b。请注意,

26b − b2 = 169 − \(b2 − 26b + 169\) = 169 − \(b − 13\)2

以上恒等式就是我们选择b为基底时，矩形的面积。当 b = 13时，矩形面积是169 − 02 = 169。当 b ≠ 13时，面积是169 − \(不等于0的数\)2。

因为我们要从169中减去一个正值，结果肯定要比169小。所以，当b = 13和h = 26 − b = 13时，矩形的面积最大。关于几何的一个神奇的事情是，农夫的栅栏有52英尺并不重要。为了最大化矩形在给定任意周长p时的面积，可以用同样的技术来证明最优的形状是正方形，各边的长度都是p/4。

为了解释其他的问题，我们首先要看一些看似矛盾的结果，并探索一些几何学的经典。为什么三角形有180度？什么是勾股定理？你怎么知道两个三角形的形状是一样的，我们为什么要在乎呢？

经典几何

几何学的主题可以追溯到古希腊。几何学的名称来源于希腊语单词“地球”\(geo\)和“测量”\(metria\)，而几何学的最初用途是研究测绘中的地质测量，以及天文学等天体应用。但古希腊人是演绎推理的大师，并将其发展成为今天的艺术形式。所有当时已知的几何结果\(约公元前300年\)都由欧几里得\(euclid\)汇编成《几何原本》一书，该书成为最成功的教科书之一。这本书介绍了数学严密性、逻辑推理、公理方法和证明的思想，这些方法仍然被数学家们所利用。

欧几里得从五个公理开始\(也称为公设\)，它们是我们应该接受的常识。一旦你接受了这些公理，你就可以从原则上推导出所有的几何定理。这是欧几里得的五个公理\(实际上，他描述的第五公理有点不同，但我们的描述和他的描述是等价的\)。

1.    从一[点](https://zh.wikipedia.org/wiki/%E9%BB%9E)向另一[点](https://zh.wikipedia.org/wiki/%E9%BB%9E)可以引一条直线。

2.    任意[线段](https://zh.wikipedia.org/wiki/%E7%BA%BF%E6%AE%B5)能无限延伸成一条直线。

3.    给定任意线段，可以以其一个端点作为[圆心](https://zh.wikipedia.org/wiki/%E5%9C%93%E5%BF%83)，该线段作为[半径](https://zh.wikipedia.org/wiki/%E5%8D%8A%E5%BE%84)作一个[圆](https://zh.wikipedia.org/wiki/%E5%9C%86)。

4.    所有[直角](https://zh.wikipedia.org/wiki/%E7%9B%B4%E8%A7%92)都[相等](https://zh.wikipedia.org/wiki/%E7%9B%B8%E7%AD%89)。

5.    若两条直线都与第三条直线相交，并且在同一边的[内角](https://zh.wikipedia.org/wiki/%E5%86%85%E8%A7%92)之和小于两个直角，则这两条直线在这一边必定相交。

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p>&#x6211;&#x8981;&#x6F84;&#x6E05;&#x7684;&#x662F;&#xFF0C;&#x5728;&#x8FD9;&#x4E00;&#x7AE0;&#x4E2D;&#xFF0C;&#x6211;&#x4EEC;&#x5C06;&#x7814;&#x7A76;&#x5E73;&#x9762;&#x51E0;&#x4F55;(&#x4E5F;&#x79F0;&#x4E3A;&#x6B27;&#x51E0;&#x91CC;&#x5FB7;&#x51E0;&#x4F55;)&#x3002;&#x6B27;&#x51E0;&#x91CC;&#x5FB7;&#x51E0;&#x4F55;&#x5047;&#x8BBE;&#x6211;&#x4EEC;&#x5728;&#x4E00;&#x4E2A;&#x5E73;&#x9762;&#x4E0A;&#x5DE5;&#x4F5C;&#xFF0C;&#x6BD4;&#x5982;x-y&#x5E73;&#x9762;&#x3002;&#x4F46;&#x662F;&#x5982;&#x679C;&#x6211;&#x4EEC;&#x6539;&#x53D8;&#x4E00;&#x4E9B;&#x516C;&#x7406;&#xFF0C;&#x6211;&#x4EEC;&#x4ECD;&#x7136;&#x53EF;&#x4EE5;&#x5F97;&#x5230;&#x6709;&#x8DA3;&#x548C;&#x6709;&#x7528;&#x7684;&#x6570;&#x5B66;&#x7CFB;&#x7EDF;&#xFF0C;&#x6BD4;&#x5982;&#x7403;&#x9762;&#x51E0;&#x4F55;&#xFF0C;&#x5B83;&#x53EF;&#x4EE5;&#x89C2;&#x5BDF;&#x7403;&#x9762;&#x4E0A;&#x7684;&#x70B9;&#x3002;&#x5728;&#x7403;&#x9762;&#x51E0;&#x4F55;&#x4E2D;&#xFF0C;&#x76F4;&#x7EBF;&#x662F;&#x6700;&#x5927;&#x5468;&#x957F;&#x7684;&#x5706;(&#x79F0;&#x4E3A;&#x5927;&#x5706;)&#xFF0C;&#x56E0;&#x6B64;&#xFF0C;&#x6240;&#x6709;&#x7684;&#x7EBF;&#x90FD;&#x5FC5;&#x987B;&#x5728;&#x67D0;&#x5904;&#x76F8;&#x4EA4;&#xFF0C;&#x6240;&#x4EE5;&#x5E73;&#x884C;&#x7EBF;&#x4E0D;&#x5B58;&#x5728;&#x3002;&#x5982;&#x679C;&#x7B2C;5&#x516C;&#x7406;&#x88AB;&#x6539;&#x53D8;&#x4E86;&#xFF0C;&#x90A3;&#x4E48;&#x603B;&#x6709;&#x4E24;&#x6761;&#x4E0D;&#x540C;&#x7684;&#x76F4;&#x7EBF;&#x901A;&#x8FC7;P&#x70B9;&#x5E73;&#x884C;&#x4E8E;l&#xFF0C;&#x90A3;&#x4E48;&#x6211;&#x4EEC;&#x5C31;&#x5F97;&#x5230;&#x4E86;&#x4E00;&#x4E2A;&#x53EB;&#x505A;&#x53CC;&#x66F2;&#x51E0;&#x4F55;&#x7684;&#x4E1C;&#x897F;&#xFF0C;&#x5B83;&#x672C;&#x8EAB;&#x5C31;&#x6709;&#x6F02;&#x4EAE;&#x7684;&#x5B9A;&#x7406;&#x3002;&#x827A;&#x672F;&#x5BB6;m.
          c. escher&#x521B;&#x4F5C;&#x7684;&#x8BB8;&#x591A;&#x6770;&#x51FA;&#x4F5C;&#x54C1;&#x90FD;&#x662F;&#x57FA;&#x4E8E;&#x8FD9;&#x79CD;&#x51E0;&#x4F55;&#x5B66;&#x3002;&#x4E0B;&#x56FE;&#x662F;&#x9053;&#x683C;&#x62C9;&#x65AF;&#xB7;&#x9093;&#x7EB3;&#x59C6;&#x4F7F;&#x7528;&#x53CC;&#x66F2;&#x51E0;&#x4F55;&#x89C4;&#x5219;&#x521B;&#x5EFA;&#x7684;&#xFF0C;&#x5E76;&#x6388;&#x6743;&#x672C;&#x4E66;&#x4F7F;&#x7528;&#x3002;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image020.jpg"
          alt/>
        </p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

碰巧，欧几里得遗漏了一些公理，其中一些我们会在必要时提及。因为这一章并不是要取代所有的几何教科书，所以我们不会尝试去定义和证明所有的东西。我将假设你对点、线、角度、圆、周长和面积的意义有一个直观的概念，我会尽量把术语和符号保持在最小化，这样我们就可以把注意力集中在几何学的有趣的思想上。

例如，我假设你已经知道，或者愿意接受，一个圆有360度，记为360°。角度的测量值在0°到360°之间。想想时钟的指针，连接在一个圆的中心。在1点钟的时候，指针指向圆圈的1/12，所以它们形成一个30°的角。在3点钟的时候，指针表示圆的四分之一，所以它们形成一个90°角。90度角被称为直角，形成它们的线或线段被称为垂线。直线，如6点钟，角度为180度。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image022.jpg)

30°、90°和180°的角

这里有一个有用的符号。连接点A和B的线段表示为![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image024.png)，它的长度省略掉上面的横线，所以长度是AB。

当两条线相交时，它们会形成四个角，如下面的图所示。关于这些角，我们能说些什么呢？注意相邻的角\(像a和b\)一起形成一条直线，它有180度。因此，角a和角b必须加到180度。这样的角称为补角。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image026.jpg)

当两条线相交时，相邻的角之和为180。不相邻的角\(称为对顶角\)是相等的。这里角a和c形成了对角，角b和角d同样。

以下性质适用于每一对相邻的角。

a + b = 180°

b + c = 180°

c + d = 180°

d + a = 180°

用第一个恒等式减去第二个恒等式得a − c = 0，即a = c。

用第二个恒等式减去第三个恒等式得b = d。

当两条直线相交时，不相邻的两个角被称为对角。我们刚刚证明了**对角定理**：对角相等。

我们下一个目的是证明三角形内角之和为180度。要做到这一点，我们首先需要说一些平行线。如果两条不同的直线不相交，则我们称它们是平行的（记住直线两端无限延伸）。下图是一对平行线l1和l2，第三条直线l3与它们不平行，它和两条平行线分别相交于P和Q点。如果你看这幅图，就会发现直线l3依同一角度穿过l1和l2。也就是说，我们认为a = e。我们称之为角a和e是同位角（其它同位角的例子有角b和角f，角c和g，角d和h）。当然，同位角应该是相等的，但这实际上这一结论不能由原来的5个公理推导出。因此，我们需要一个新的公理。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image028.jpg)

同位角相等。这里a = e、b = f、c = g、d = h。

**同位角定理：**同位角相等。

当与对角定理结合时，这说明在上图中，我们必须有

a = c = g = e

b = d = h = f

数学书给出了一些相等的角对的特殊名称。例如，角a和角g，形成Z型，称为内错角。因此，我们已经证明了任何角都等于它的对角、同位角和内错角。我们现在用这个结果来证明几何的基本定理。

**定理：**三角形的内角之和是180度。

**证明：**考虑一个三角形ABC，有角a、b和c，现在画一条穿过B点的直线，这条直线与穿过A和C的直线平行。

角d、b和e形成一条直线，所以d + b + e = 180°。但是注意，角a和角d，角c和e都是内错角，因此d = a和e = c，所以a + b + c = 180°。

□

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image030.jpg)

为什么a + b + c = 180°。

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b> &#x65C1;&#x767D;</b>
        </p>
        <p>&#x4E09;&#x89D2;&#x5F62;&#x7684;180&#xB0;&#x5B9A;&#x7406;&#x662F;&#x5E73;&#x9762;&#x51E0;&#x4F55;&#x7684;&#x4E00;&#x4E2A;&#x57FA;&#x672C;&#x4E8B;&#x5B9E;&#xFF0C;&#x4F46;&#x5728;&#x5176;&#x5B83;&#x51E0;&#x4F55;&#x4E2D;&#x5E76;&#x4E0D;&#x4E00;&#x5B9A;&#x662F;&#x8FD9;&#x6837;&#x3002;&#x4F8B;&#x5982;&#xFF0C;&#x8003;&#x8651;&#x5728;&#x4E00;&#x4E2A;&#x5730;&#x7403;&#x4E0A;&#x753B;&#x4E00;&#x4E2A;&#x4E09;&#x89D2;&#x5F62;&#xFF0C;&#x4ECE;&#x5317;&#x6781;&#x5F00;&#x59CB;&#xFF0C;&#x6CBF;&#x7740;&#x4EFB;&#x4F55;&#x4E00;&#x6761;&#x7ECF;&#x7EBF;&#x5411;&#x4E0B;&#x5230;&#x8D64;&#x9053;&#xFF0C;&#x5728;&#x8D64;&#x9053;&#x4E0A;&#x53F3;&#x8F6C;&#xFF0C;&#x7ED5;&#x5730;&#x7403;&#x56DB;&#x5206;&#x4E4B;&#x4E00;&#x5708;&#xFF0C;&#x7136;&#x540E;&#x518D;&#x53F3;&#x8F6C;&#xFF0C;&#x76F4;&#x5230;&#x4F60;&#x56DE;&#x5230;&#x5317;&#x6781;&#x3002;&#x8FD9;&#x4E2A;&#x4E09;&#x89D2;&#x5F62;&#x5B9E;&#x9645;&#x4E0A;&#x5305;&#x542B;&#x4E09;&#x4E2A;&#x76F4;&#x89D2;&#xFF0C;&#x5185;&#x89D2;&#x4E4B;&#x548C;&#x662F;270&#xB0;&#x3002;&#x5728;&#x7403;&#x9762;&#x51E0;&#x4F55;&#x4E2D;&#xFF0C;&#x4E09;&#x89D2;&#x5F62;&#x7684;&#x5185;&#x89D2;&#x4E4B;&#x548C;&#x4E0D;&#x662F;&#x6052;&#x5B9A;&#x7684;&#xFF0C;&#x4E14;&#x89D2;&#x5EA6;&#x4E4B;&#x548C;&#x5927;&#x4E8E;180&#x7684;&#x7A0B;&#x5EA6;&#x4E0E;&#x9762;&#x79EF;&#x6210;&#x4E00;&#x5B9A;&#x6BD4;&#x4F8B;&#x3002;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

在几何课上，很多注意力都集中在证明各种对象是全等的，这意味着通过滑动、旋转或翻转一个物体，我们可以得到另一个物体。例如，下面的三角形ABC和DEF是全等的，因为我们可以滑动三角形DEF，使它与三角形ABC完全重叠。在我们的图中，当两个边\(或角\)有相同数目的斜条时，这表明它们有相同的长度\(或度量\)。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image032.jpg)

全等三角形

我们用符号≅来表示全等、ABC ≅ DEF表示两个三角形全等。这相当于说长度和角度是完美匹配的。具体来说，边长AB、BC和CA分别等于DE、EF和FD。相关的角A、B、C分别等于角D、E、F。图中，相同大小的角已由相同标记标识，同样相等的边也用相同标记标识了。

一旦你知道一些边和角相等，剩下的就能很自然地得出。例如，如果你知道所有三个边都相等，并且这两对角相等\(比如∠A = ∠D和∠B = ∠E\)，那么第三对角肯定相等，所以三角形必然全等。然而，我们甚至不需要所有这些信息。一旦你知道的两个边长相等AB = DE和AC = DF,你知道它们的夹角也相等,在这里∠A = ∠D，那么剩下的其他一切都被定死了：BC = EF、∠B = ∠E和∠C = ∠F。我们称之为边角边（SAS）公理。

SAS公理并不是一个定理，因为它不能被前面的公理证明。但是一旦我们接受了它，我们就可以严格地证明其它有用的定理，比如SSS \(边边边\)、ASA\(角边角\)、AAS\(角角边\)。没有一个类似的定理叫SSA\(或它令人尴尬的反写的同名物\)，因为公共角必须在两个相等的边之间，以确保全等性。定理SSS是最有趣的，因为它说如果两个三角形有相等的边度，那么它们也必须有相等的角。

让我们应用SAS来证明重要的等腰三角形定理。它的两条边长度相等的三角形是等腰三角形。当我们讨论它的时候，让我们再提一些其他类型的三角形。等边三角形三个边的长度相等。一个有90角的三角形被称为直角三角形。如果三角形的所有角都小于90°，那么我们就有一个锐角三角形。如果三角形有一个角大于90°，则被称为钝角三角形。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image034.jpg)

等边三角形、锐角三角形、直角三角形和钝角三角形

**等腰三角形定理：**如果ABC是等腰三角形，且边长AB = AC，那么与这些边相对的角肯定也相等。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image036.jpg)

等腰三角形定理：如果AB = AC、则∠B = ∠C

**证明：**从A点画一条线将∠A 分割成两个相等的角度，如下图所示\(这被称为角A的角平分线\)。我们说它在点x处与线段AB相交。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image038.jpg)

等腰三角形定理可以通过画一个角平分线来证明，然后将边角边公理应用到新创建的三角形中。

我们认为三角形BAX和CAX是全等的。这是边角边定理的结果，因为BA = CA\(由等腰假设\)，∠BAX = ∠CAX（因为角平分线）和AX = AX（这里并没有打印错误哦！AX两个三角形比较的三角形共有的一条边，它的长度是一样的!），因为BAX ≅ CAX，另一边和角也必须相等。具体来说，∠B = ∠C，这正是我们要证明的。

□

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p>&#x7B49;&#x8170;&#x4E09;&#x89D2;&#x5F62;&#x5B9A;&#x7406;&#x4E5F;&#x53EF;&#x4EE5;&#x7528;SSS&#x5B9A;&#x7406;&#x8BC1;&#x660E;&#x3002;&#x5BF9;&#x4E8E;&#x8FD9;&#x4E2A;&#x8BC1;&#x660E;&#xFF0C;&#x8BA9;M
          &#x8868;&#x793A;
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image040.png"
          alt/>&#x7684;&#x4E2D;&#x70B9;BM = MC&#xFF0C;&#x7136;&#x540E;&#x753B;&#x51FA;&#x7EBF;&#x6BB5;
          <img
          src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image042.png"
          alt/>&#x3002;&#x50CF;&#x4E4B;&#x524D;&#x7684;&#x8BC1;&#x660E;&#x4E00;&#x6837;&#xFF0C;&#x4E09;&#x89D2;&#x5F62;BAM&#x548C;CAM&#x662F;&#x5168;&#x7B49;&#x7684;&#xFF0C;&#x56E0;&#x4E3A;BA
          = CA (&#x7B49;&#x8170;)&#xFF0C;AM = AM&#x548C;MB = MC(&#x4E2D;&#x70B9;)&#x3002;&#x56E0;&#x6B64;&#xFF0C;&#x901A;&#x8FC7;SSS&#xFF0C;BAM
          &#x2245; CAM&#xFF0C;&#x5B83;&#x4EEC;&#x5404;&#x81EA;&#x7684;&#x89D2;&#x4E5F;&#x76F8;&#x7B49;&#x3002;&#x7279;&#x522B;&#x662F;&#xFF0C;&#x2220;B
          = &#x2220;C&#x3002;</p>
        <p>&#x7531;&#x4E8E;&#x5168;&#x7B49;&#xFF0C;&#x5B83;&#x4F7F;&#x5F97;&#x2220;BAM
          = &#x2220;CAM&#xFF0C;&#x6240;&#x4EE5;&#x7EBF;&#x6BB5;AM&#x4E5F;&#x662F;&#x89D2;&#x5E73;&#x5206;&#x7EBF;&#x3002;&#x6B64;&#x5916;&#xFF0C;&#x7531;&#x4E8E;&#x2220;BMA
          = &#x2220;CMA &#xFF0C;&#x4E14;&#x8FD9;&#x4E9B;&#x76F8;&#x7B49;&#x7684;&#x89D2;&#x4E4B;&#x548C;&#x4E3A;180&#xB0;&#xFF0C;&#x5B83;&#x4EEC;&#x90FD;&#x5FC5;&#x987B;&#x90FD;&#x662F;90&#xB0;&#x3002;&#x5728;&#x7B49;&#x8170;&#x4E09;&#x89D2;&#x5F62;&#x4E2D;&#xFF0C;&#x89D2;A&#x7684;&#x89D2;&#x5E73;&#x5206;&#x7EBF;&#x4E5F;&#x662F;BC&#x7684;&#x5782;&#x76F4;&#x5E73;&#x5206;&#x7EBF;&#x3002;</p>
        <p>&#x987A;&#x4FBF;&#x8BF4;&#x4E00;&#x4E0B;&#xFF0C;&#x7B49;&#x8170;&#x4E09;&#x89D2;&#x5F62;&#x5B9A;&#x7406;&#x7684;&#x9006;&#x547D;&#x9898;&#x4E5F;&#x6210;&#x7ACB;&#x3002;&#x4E5F;&#x5C31;&#x662F;&#x8BF4;&#xFF0C;&#x5982;&#x679C;&#x2220;B
          = &#x2220;C&#xFF0C;&#x90A3;&#x4E48; AB = AC&#x3002;&#x8FD9;&#x53EF;&#x4EE5;&#x901A;&#x8FC7;&#x4ECE;A&#x5230;&#x70B9;X&#x7684;&#x89D2;&#x5EA6;&#x6765;&#x8BC1;&#x660E;&#xFF0C;&#x5C31;&#x50CF;&#x539F;&#x6765;&#x7684;&#x8BC1;&#x660E;&#x4E00;&#x6837;&#x3002;&#x73B0;&#x5728;&#x6211;&#x4EEC;&#x8BF4;&#xFF0C;BAX
          &#x2245; CAX&#x3002;&#x6839;&#x636E;AAS&#x5B9A;&#x7406;&#xFF0C;&#x56E0;&#x4E3A;&#x2220;B
          = &#x2220;C (&#x5047;&#x8BBE;)&#x3001;&#x2220;BAX = &#x2220;CAX (&#x89D2;&#x5E73;&#x5206;&#x7EBF;)&#xFF0C;AX
          = AX&#x3002;&#x56E0;&#x6B64;&#xFF0C;AB = AC&#xFF0C;&#x6240;&#x4EE5;&#x4E09;&#x89D2;&#x5F62;&#x662F;&#x7B49;&#x8170;&#x7684;&#x3002;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

对各边都相等的等边三角形，我们可以把前面的定理应用到所有三条边，从而证明三个角都相等。由于这三个角必须是180°，我们有下面的推断：

**推论：**等边三角形中每个角都是60°。

根据SSS定理，如果两个三角形ABC和DEF有匹配的边\(AB = DE、BC = EF、CA = FD\)，那么它们也必须有匹配的角\(∠A = ∠D、∠B = ∠E、∠C = ∠F\)。如果ABC和DEF有匹配的角，那么它们必须有相等的边吗？当然不是，如下图所示。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image044.jpg)

相似三角形有匹配的角和等比例的边

对应内角都相等的两个三角形被称为相似三角形。如果两个三角形ABC和DEF是相似的\(表示ΔABC ~ ΔDEF或ABC ~ DEF\)，则∠A = ∠D、∠B= ∠E、∠C = ∠F。基本上，相似三角形之间是按比例缩放的。所以如果 ABC ~ DEF，那么对应的边必须被一正因子k缩放。也就是，DE = kAB、EF = kBC、and FD = kCA。

让我们把我们所学到的知识运用到这一章的开头，来回答问题2。回想一下，我们是从两条平行线开始的。我们的目标是在上面的直线上找到一个点P，这样三角形XYP就有最小的周长。我们声称下面的说法是正确的。

**定理:** 选取一点P，使得P在线段![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image046.png)的中心点正上方，此时所组成的三角形XYP的周长最小。

虽然这个问题可以用复杂的微积分来解决，但是我们将会看到几何是如何让我们用一点点的思考来解决这个问题的\(下面的证明很有趣，但有点长，所以你可以随意浏览或跳过它。\)。

**证明：**让P是上面一条直线上的任意一点，让Z表示上面直线上的点，它在Y的上方\(更准确地说，点Z被放置在包含Y的直线上，该直线垂直于相互平行的两条线。看下面的图\)。让Y′ 为垂直直线上的点，使Y′Z = ZY。换句话说，如果上方的线是一个大镜子，那么Y′就是Y通过点Z的影像。

我认为三角形PZY和PZY′是全等的。这是因为PZ = PZ、∠PZY = 90º ∠PZY′、ZY = ZY′，所以根据SAS，这些三角形全等。因此，PY = PY′，我们可以利用这一相等关系。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image048.jpg)

由于三角形 PZY和PZY′ 全等，因此肯定有PY = PY′。

三角形XYP的周长是三条边之和

YX + XP + PY

因为我们已经证明了 PY = PY′，所以周长等于

YX + XP + PY′

现在，长度YX不依赖于P，所以我们的问题是找到点P，使得XP + PY′最小化。

注意到线段![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image050.png)和![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image052.png)组成了一条从X到Y的弯曲路径。由于两点之间的最短距离是一条直线，所以可以通过从X到Y画一条直线来找到最优点P\*，P\*是这条线与上方直线线相交的点。请参阅下面的图。那么，我们为什么不这样做呢?为了完成这个证明，我们需要证明P\*恰恰在![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image046.png)中点之上。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image054.jpg)

三角形MXP\*和YXY′ 是缩放因子为2的相似三角形。

让M表示P\*点正下方\(![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image056.png)垂直于![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image058.png)\)的点。由于两条直线是平行的，所以![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image056.png)和![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image060.png)的长度必须相等\(这是直观的感觉，因为平行线之间有一个恒定的距离，但也可以通过绘制线段![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image062.png)和利用AAS验证三角形MYZ和ZP\*M全等来证明这一点\)。

为了证明m是![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image058.png)的中点，我们首先证明三角形MXP\*和YXY′是相似的。注意，∠MXP\*和∠YXY′是相同的角，∠P\*MX = ∠Y’YX是因为它们都是直角，一旦我们有两个相等的角，那么第三个角也必须相等，因为角度之和是180°。这些相似三角形之间的比例系数是多少?

YY′ = YZ + ZY′ = 2YZ = 2MP\*

所以比例是2。因此![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image064.png)的长度是![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image058.png)的一半。所以P\*是![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image058.png)的中点。

综上所述，我们已经证明了上面一条直线上的点P\*，当它位于![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image058.png)的中点正上方时，三角形XYP的周长最小。

□

有时几何问题可以用代数方法来解决。例如，假设线段![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image066.png)所在的平面上，点A有坐标\(a1、a2\)，点B有坐标\(b1、b2\)。然后中点M，在a和b正中间，有坐标。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image068.png)

如下图所示。例如A = \(1、2\)、B = \(3、4\)，则![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image024.png)的中点M = \(\(1 + 3\)/2、\(2 + 4\)/2\) = \(2、3\)。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image070.jpg)

线段的中点可以通过取其端点的平均值来找到。

让我们用这个想法来证明一个关于三角形的有用的事实。画一个三角形，然后用线段连接任何两边的中点。你注意到有什么有趣的事吗？答案在下面的定理中给出。

**三角形中位线定理：**给定任意三角形ABC，如果我们画一条线段连接![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image024.png)的中点与![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image040.png)的中点，那么线段将与第三边![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image072.png)平行。此外，如果![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image072.png)长度为b，那么连接中点的线段长度为b/2。

**证明：**将三角形ABC放在平面上，使点A在原点\(0，0\)，边![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image072.png)是水平的，所以点C在点\(b，0\)，如下图所示。假设点B位于\(x，y\)处，然后中点坐标\(x/2、y/2\)和中点的坐标\(\(x、b\)/2、y/2\)。因为中点都有相同的y坐标，所以连接它们的连线肯定是水平的，所以它和![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image072.png)是平行的。此外，这条线段的长度是![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image074.png)。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image076.jpg)

当三角形的两个边的中点被一条线段连接时，这个段与第三边平行，长度为第三条边的一半。

□

三角形中位线定理揭示了本章开头的魔术的秘密。我们把四边形ABCD各边中点相连接，形成第二个四边形的EFGH，它被证明总是一个平行四边形。让我们来看看为什么会这样。如果我们想象一条从顶点A到顶点C的对角线，那么它就会生成两个三角形ABC和ADC，就像下图所示。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image077.jpg)

根据三角形中位线定理，![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image079.png)和![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image081.png)与![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image083.png)平行。

将三角形中位线定理应用到三角形ABC和ADC中，我们发现![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image008.png)与![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image072.png)平行，![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image085.png)与![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image072.png)平行。这样![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image008.png)与![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image085.png)是平行的\(而且，长度相同，因为它们都是![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image072.png)长度的一半\)。按照同样的逻辑，通过想象从B到D的对角线，我们得到了![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image087.png)和![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image014.png)是平行的，并且长度相同。因此，EFGH是一个平行四边形。

之前的许多定理都与三角形有关。实际上，几何学习中，大量的时间是用来研究三角形。三角形是最简单的多边形，其次是四边形\(4边多边形\)、五边形\(5边多边形\)等等。有n边的多边形有时被称为n-gon。我们证明了任意三角形的角和是180度。三边以上的多边形有什么可说的呢？四边形，如正方形、长方形或平行四边形，有四个边。在一个矩形中，四个角都是90°，所以角度之和肯定是360°。

下一个定理表明对于任意四边形都成立。你可以把这称为一个4角结论。

**定理：**四边形内角和等于360°。

**证明：**像下图一样，令任意四边形以A、B、C、D 为顶点。通过画一条从A到C的线段，将四边形分成两个三角形。每个三角形的内角和为180°。因此，四边形内角和是2 × 180° = 360°。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image089.jpg)

四边形内角和为360°

□

另一个定理应该揭示一般的模式。

**定理：**五边形的内角和是540°。

**证明：**考虑以A、B、C、D、E为顶点的任意五边形。通过画一条从A到C的线段，五边形被分成一个三角形和一个四边形。我们知道三角形ABC内角和为180°，四边形ACDE的内角之和是360°。因此，五边形的内角之和是180° + 360° = 540°。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image091.jpg)

五边形内角和540°

□

通过归纳法或者通过一个顶点A其它所有顶点的连线来创建n - 2个三角形，我们得到了下面n边形的定理。

**定理：**n边形的内角之和是180 \(n − 2\) 度。

这是这个定理的一个神奇的应用。画一个八边形\(一个8边的多边形\)并在里面任意放置5个点。然后将顶点和点连接起来，注意八边形内的唯一允许出现的形状是三角形\(这被称为三角划分\)。下面是两个不同三角划分的例子，一个空的供你自己尝试。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image093.jpg)

在我的两个例子中，我们最终都得到了16个三角形。在第三个八边形中，无论你如何放置这5个点，如果一切都做得很好，你也应该有16个三角形。如果你没有得到16个三角形，仔细看看每个内部区域，确保它只有3个顶点。如果某区域有4个顶点，那么你需要增加一条线段来将其分割成两个三角形。

**定理：**通过在n边形内放置p个点，对n边形进行三角划分，可得到2p + n - 2个三角形。

前面的例子中，n = 8，p = 5，所以三角形的数量是10 + 8 − 2 = 16。

**证明：**假设划分的结果是T个三角形。我们通过用两种方法回答下面的问题来证明T = 2p + n − 2。

**问题：**所有三角形的内角之和是多少?

**答案1：**因为有T个三角形，每个三角形的内角和为180°，总和必须是180T度。

**答案2：**让我们把答案分成两种情况。每个内点周围的角构成一个圆，所以p个内点上的角之和为360p度。另一方面，根据我们之前的定理，我们知道n边形的内角和是180\(n - 2\)度。因此，所有角之和为360p + 180\(n - 2\)度。

两个答案是相等的，所以

180T = 360p + 180\(n − 2\)

T = 2p + n − 2

结论得证

□

周长和面积

多边形的周长是它的边长之和。例如，在一个长为b、高为h的矩形，它的周长是2b + 2h，因为它有两条长度为b的边和两条长度为h的边。矩形的面积是多少？我们定义1 × 1的正方形\(单位正方形\)面积为1。当b和h是正整数时，像下图一样，我们可以将这个区域分解为bh个1 × 1的正方形，所以它的面积是bh。一般来说，对于任何长为b和宽为h的矩形\(b和h是正的，但不一定是整数\)，我们定义它的面积是bh。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image095.jpg)

长为b高为h的矩形，周长 2b + 2h，面积bh

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p>&#x5728;&#x8FD9;&#x4E00;&#x7AE0;&#x4E2D;&#xFF0C;&#x6211;&#x4EEC;&#x4F7F;&#x7528;&#x4E86;&#x4EE3;&#x6570;&#x6765;&#x5E2E;&#x52A9;&#x6211;&#x4EEC;&#x89E3;&#x91CA;&#x51E0;&#x4F55;&#x3002;&#x4F46;&#x6709;&#x65F6;&#x51E0;&#x4F55;&#x5B66;&#x4E5F;&#x80FD;&#x5E2E;&#x52A9;&#x6211;&#x4EEC;&#x89E3;&#x91CA;&#x4EE3;&#x6570;&#x3002;&#x8003;&#x8651;&#x4E0B;&#x9762;&#x7684;&#x4EE3;&#x6570;&#x95EE;&#x9898;&#x3002;&#x8FD9;&#x4E2A;&#x91CF;&#x53EF;&#x4EE5;&#x6709;&#x591A;&#x5C0F;&#xFF0C;x&#x53EF;&#x4EE5;&#x662F;&#x6B63;&#x6570;&#x5417;?&#x5F53;x
          = 1&#x65F6;&#xFF0C;&#x5F97;&#x5230;2&#xFF1B;&#x5F53;x = 1.25&#x65F6;&#xFF0C;&#x5F97;&#x5230;1.25
          + 0.8 = 2.05&#xFF1B;&#x5F53;x = 2&#x65F6;&#xFF0C;&#x5F97;&#x5230;2.5&#x3002;&#x6570;&#x636E;&#x4F3C;&#x4E4E;&#x8868;&#x660E;&#xFF0C;&#x6211;&#x4EEC;&#x80FD;&#x5F97;&#x5230;&#x7684;&#x6700;&#x5C0F;&#x7B54;&#x6848;&#x662F;2&#x3002;&#x8FD9;&#x662F;&#x771F;&#x7684;&#xFF0C;&#x4F46;&#x6211;&#x4EEC;&#x600E;&#x4E48;&#x80FD;&#x786E;&#x5B9A;&#x5462;?&#x5728;&#x7B2C;11&#x7AE0;&#x4E2D;&#xFF0C;&#x6211;&#x4EEC;&#x4F1A;&#x627E;&#x5230;&#x4E00;&#x4E2A;&#x7B80;&#x5355;&#x660E;&#x4E86;&#x7684;&#x65B9;&#x6CD5;&#x6765;&#x56DE;&#x7B54;&#x8FD9;&#x4E2A;&#x95EE;&#x9898;&#xFF0C;&#x4F46;&#x662F;&#x6211;&#x4EEC;&#x53EF;&#x4EE5;&#x7528;&#x7B80;&#x5355;&#x7684;&#x51E0;&#x4F55;&#x6765;&#x89E3;&#x51B3;&#x8FD9;&#x4E2A;&#x95EE;&#x9898;&#x3002;</p>
        <p>&#x4E0B;&#x9762;&#x7684;&#x51E0;&#x4F55;&#x5BF9;&#x8C61;&#x662F;&#x7531;&#x56DB;&#x4E2A;&#x591A;&#x7C73;&#x8BFA;&#x6392;&#x7EC4;&#x6210;&#x7684;&#xFF0C;&#x6BCF;&#x4E00;&#x4E2A;&#x7684;&#x5C3A;&#x5BF8;&#x662F;x
          &#xD7; 1/x&#xFF0C;&#x8FDE;&#x63A5;&#x5728;&#x4E00;&#x8D77;&#x7EC4;&#x6210;&#x4E00;&#x4E2A;&#x6B63;&#x65B9;&#x5F62;&#xFF0C;&#x4E2D;&#x95F4;&#x6709;&#x4E00;&#x4E2A;&#x6D1E;&#x3002;&#x5305;&#x62EC;&#x8FD9;&#x4E2A;&#x6D1E;&#x5728;&#x5185;&#x7684;&#x6574;&#x4E2A;&#x533A;&#x57DF;&#x7684;&#x9762;&#x79EF;&#x662F;&#x591A;&#x5C11;?</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image097.jpg"
          alt/>
        </p>
        <p>&#x4E00;&#x65B9;&#x9762;,&#x7531;&#x4E8E;&#x8BE5;&#x533A;&#x57DF;&#x662F;&#x4E00;&#x4E2A;&#x8FB9;&#x957F;x
          + 1/x&#x7684;&#x6B63;&#x65B9;&#x5F62;&#xFF0C;&#x5B83;&#x7684;&#x9762;&#x79EF;&#x5FC5;&#x987B;(x
          + 1/x)&#xB2;&#x3002;&#x53E6;&#x4E00;&#x65B9;&#x9762;,&#x6BCF;&#x4E2A;&#x591A;&#x7C73;&#x8BFA;&#x7684;&#x9762;&#x79EF;&#x662F;1&#xFF0C;&#x6240;&#x4EE5;&#x8BE5;&#x533A;&#x57DF;&#x7684;&#x9762;&#x79EF;&#x81F3;&#x5C11;&#x662F;4&#x3002;&#x56E0;&#x6B64;</p>
        <p>(x + 1/x)2 &#x2265; 4</p>
        <p>&#x610F;&#x5473;&#x7740;x + 1/x &#x2265; 2&#x3002;</p>
        <p>&#x8BC1;&#x660E;&#x5B8C;&#x6BD5;</p>
        <p>&#x25A1;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

**定理：**底边长b、高h的三角形面积是½bh。

为了说明，下面所示的三个三角形的底长b和高度h都相同，因此它们都有相同的面积。这是本章开头的第三个问题，对很多人来说是一个惊喜。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image099.jpg)

以b为底，h为高的三角形的面积为½bh。不管三角形是直角、锐角还是钝角，这都是正确的。

有三种情况考虑，取决于底角∠A、∠B、∠C的大小。如果∠A或∠C是一个直角，那么我们可以复制三角形ABC，把两个三角形拼在一起形成一个面积为bh的矩形，如下所示。因为三角形ABC占据了矩形区域的一半，那么三角形就面积肯定是½bh。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image101.jpg)

两条边为b和h的直角三角形可以形成一个面积为bh矩形区。

当∠A和∠C是锐角时，我们提供了一个可爱的证明。从B到AC\(称为三角形ABC的高\)作垂线，它的长度h，相交于我们称为X的点，如下图所示。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image103.jpg)

AC被分成AX和XC两段，长度分别为 b1和b2、b1 + b2 = b。因为BXA和BXC 是直角三角形，则根据前面的例子，我们得它们的面积分别为½ b1h和½ b2h.这样三角形ABC的面积是

½ b1h + ½ b2h = ½ \(b1 + b2\)h = ½ bh

证明完毕

□

当角A或C是钝角时，我们得到下面类似的图形。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image105.jpg)

在锐角的情况下，我们将三角形ABC作为两个直角三角形的和。这里我们将ABC作为两个直角三角形ABY和CBY的差。大直角三角形ABY底的长度是b + c，所以它的面积是½\(b + c\)h。较小的直角三角形CBY的面积是½ch。三角形ABC的面积是

½\(b + c\)h - ½ch = ½bh

证明完毕

☺

毕达哥拉斯定理（勾股定理）

毕达哥拉斯定理，也许是最著名的几何定理，它也是数学中最著名的公式之一，应该有一个属于它的一节。在直角三角形中，直角边的对边叫做斜边（弦）。另外两条边被称为直角边（勾和股）。下面的直角三角形有直角边![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image072.png)、![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image040.png)和斜边![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image024.png)，长度分别为a、b和c。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image107.jpg)

**毕达哥拉斯定理（勾股定理）:**对于一个直角三角形，其直角边长度为a和b，斜边长度为c。

a2 + b2 = c2

据报道，毕达哥拉斯定理有三百多种证明，但我们将在这里给出最简单的证明。请随意跳过一些证明。我的目标是，至少有一种证明能让你微笑或说，这太酷了!

**证明1：**在下面的图片中，我们用四个直角三角形组装了一个巨大的正方形。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image109.jpg)

**问题：**大正方形的面积是多少？

**答案1：**正方形的边长是a + b，所以面积是\(a + b\)2 = a2 + 2ab + b2。

**答案2：**另一方面，这个大正方形由四个面积为ab/2三角形和一个倾斜的面积为c²正方形组成。为什么中间是正方形?我们知道，所有的四个边都是相等的，我们可以用对称来证明这四个角是相等的：如果我们旋转这个图90度，它是相同的，所以中间的正方形的每一个角都是相等的。因为四边形内角和是360度，所以我们知道每个角都是90度。所以，大正方形的面积是4\(ab\)/2 + c2 = 2ab + c2。

由于两个答案相等，我们得恒等式

a2 + 2ab + b2 = 2ab + c2

两边同时减去2ab

a2 + b2 = c2

定理得证

☺

**证明2：**使用与上面相同的图片，我们重新排列三角形，如下图所示。在第一张图中，没有被三角形占据的区域是c2。在新图片中，没有被三角形占据的区域是a2 + b2。因此c2 = a2 + b2。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image111.jpg)

**证明3：**这一次，让我们重新排列四个三角形形成一个更紧凑的面积c²的正方形（这个物体是正方形的一个原因是每个角都是由∠A和∠B组成的，它们的和是90°）。和以前一样，四个三角形的面积是4\(ab/2\) = 2ab。中间的倾斜正方形有面积\(a − b\)2 = a2 − 2ab + b2。因此，将两个面积合并等于2ab + \(a2 − 2ab + b2\) = a2 + b2。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image113.png)

☺

正方形的面积是c2和a2 + b2。

**证明4**：这里有一个类似的证明，我的意思是，让我们利用我们所知道的相似三角形的知识。在直角三角形ABC中，画出垂直于斜边的线，如下所示。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image115.png)

请注意两个相似的小三角形都和原来的大三角形相似。

三角形ADC包含一个直角和∠A，所以它的第三个角必须与∠B相等。同样地，三角形CDB有一个直角和∠B，所以它的第三个角必须与∠A相等。因此，这三个三角形相似：

ΔACB ~ ΔADC ~ ΔCDB

请注意，字母顺序很重要。我们有∠ACB = ∠ADC = ∠CDB = 90º，它们都是直角；同样的，∠A = ∠BAC = ∠CAD = ∠BCD and ∠B = ∠CBA = ∠DCA = ∠DBC。

比较三角形ACD和ABC的边长

AC / AB = AD / AC → AC² = AD × AB

比较三角形BCD和ABC的边长

CB / BA = DB / BC → BC² = DB × AB

将两个等式加起来，我们得到

AC2 + BC2 = AB × \(AD + DB\)

因为AD + DB = AB = c，我们得到想要的结果

b2 + a2 = c2

☺

下一个证明是纯几何的。它不使用代数，但它确实需要一些可视化技巧。

**证明5：**这次我们从两个并排放置的正方形开始，分别是a2和b2。如下所示，它们的组合面积是a2 + b2。我们可以把这个物体分解成两个直角三角形（边长a、b和斜边长度为c）和第三个奇形怪状的形状。注意，由于它被∠A和∠B包围，所以这个奇怪形状底部的角必须是90度。想象一下，在大正方形的左上角和小正方形的右上角各有一个铰链。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image117.png)

这两个面积为a2 + b2的方块可以转换成。

现在想象一下，左下角的三角形逆时针方向的90度，所以它位于大正方形的顶部。然后将另一个三角形顺时针旋转90度，这样直角就会匹配起来，它就会舒服地放在两个正方形的角上，如图所示。最终的结果是一个倾斜的面积c2的正方形。如同预期，a2 + b2 = c2。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image119.png)

面积为c²的正方形

我们可以用毕达哥拉斯定理来解释足球场上的问题。在这一章的开头，用一根长度为361英尺的绳子连接两个相距360英尺的球门柱。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image121.png)

根据毕达哥拉斯定理h² + 180² = 180.5²

从球门柱到场地中间的距离是180英尺。当绳子被提升到最高点h时，我们创造了一个直角三角形，如下所示，它的直角边长度是180和斜边180.5。因此，通过毕达哥拉斯定理和几行代数，我们得到

h² + 180² = 180.5²

h² + 32,400 = 32,580.25

h² = 182.25

h =

因此，绳子足够高，大多数卡车都能在它下面行驶！

几何魔术

让我们以一种基于几何的魔术来结束这一章。毕达哥拉斯定理的大部分证明都涉及到重新排列一个几何对象的片段，以获得相同区域的另一个几何对象。但请考虑以下悖论。从一个8 × 8的正方形开始，如下图所示，看起来我们可以把它分成4个部分（所有这些都有3、5或8的斐波那数的长度），然后重新组合这些部分来创建一个5 × 13的矩形\(自己试一试!\)。但这是不可能的，因为第一个图形的面积是8 × 8 = 64，而第二个图形的面积是5 × 13 = 65。怎么会这样？

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image123.png)

一个面积64的正方形可以通过重新组合来创建一个面积为65的矩形吗？

这个悖论的秘密在于，5 ×13矩形的“对角线”并不是一条直线。例如，三角形标记C斜边的斜率3/8 = 0.375（因为其y坐标增加3，x坐标增加8），然而。顶部的图形D\(梯形\)的斜率是2/5 = 0.4\(因为其y坐标增加2 x坐标增加5\)。因为斜率不同，“对角线”并不是一条直线。相同的现象发生在上部梯形和三角形的中。因此，如果我们仔细观察这个矩形，我们会看到两条“对角线”之间的额外空间。这个额外空间的面积正好是一个单位面积。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image125.png)

这个矩形包含一个额外区域的单位在对角线上展开

在这一章中，我们推导出了许多三角形、正方形、矩形和其他多边形的重要特性，它们都是用直线创建的。对圆和其他弯曲物体的研究需要通过三角学和微积分学来更复杂的几何思想，所有这些都将取决于这个神奇的数π。

