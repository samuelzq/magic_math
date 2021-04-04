# 第八章

  


3.141592653589…

## π的魔力

循环论证

我们以一些几何问题开始了上一章，这些问题旨在挑战你对矩形和三角形的几何直觉。上一章结束在将绳子拴在美式橄榄球场两端门柱上的问题。在这一章中，我们的重点将放在圆上，我们将从一个在地球上放置绳子的问题开始。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

**问题1：**想象一下，将一根绳子绑在地球的赤道上\(大约25000英里长\)。在把末端绑在一起之前，额外增加了10英尺的绳子。如果我们现在以某种方式举起绳子，让它在赤道的每一点上都保持同样的距离，绳子会有多高？

1.  离地面不到一英寸。

2.  只够从下面爬过去。

3.  可以从下面走过去。

4.  一辆卡车可以开过去。

**问题2：**两个点x和y固定在一个圆上，如下图所示。我们希望在主弧\(x和y之间的长圆弧，而不是短弧\)的某个点上选择第三点z。我们应该选择点z从而使得 ∠XZY最大化 ?

1.    点A（正对着X和Y的中点）

2.    点B（X通过圆心的对称点）

3.    点C（尽量靠近点X）

4.    弦上任意一点都行。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg)

图中哪个点与X、Y构成的角最大？∠XAY？ ∠XBY？∠XCY？或者一样大？

为了回答这些问题，我们需要加深对圆的理解（好吧，我猜你不需要朋友圈来读答案。答案分别是B和D。但是为了理解为什么这些答案是正确的，我们需要理解圆）。一个圆可以用一个点O和一个正数r来描述，这样圆上的每一个点都与O相距r。点O被称为圆心，距离r被称为半径。作为数学上的惯例，从O到P的线段被称为半径。

周长和面积

对于任何圆，它的直径D被定义为半径的两倍，它是两端点皆在[圆周](https://zh.wikipedia.org/wiki/%E5%9C%93%E5%91%A8)上长度最长的[线段](https://zh.wikipedia.org/wiki/%E7%BA%BF%E6%AE%B5)。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image006.jpg)

一个圆心O，半径r，直径D = 2r的圆

一个圆的周长用C表示（译注：英文中圆周长 **circumference**不同于多边形周长**perimeter**，作者原文是为了强调这一点）。从这幅图中,可以看出C大于2D，因为沿圆从P到Q的距离大于D，从Q回到P的距离也比D大。因此，C &gt; 2D。如果你盯着它看，你甚至可能会相信C比3D大一点（抱歉，但要清楚地看到，你可能需要戴3-D眼镜）。

现在，如果你想要把一个圆形物体的周长与它的直径进行比较，你可以把一根绳子绕在圆周上。然后除以直径的长度。你会发现，不管你是在测量一枚硬币，一个杯子的底部，一个餐盘，还是一个巨大的呼啦圈。

C/D ≈ 3.14

我们定义了精确的常数π（一个希腊字母发音‘pai’）以表示圆周长与直径的比值。

π = C/D

对所有的圆，π的值都是一样的。如果你喜欢，你可以把它写成任何圆的周长的公式。已知圆的直径D或半径r。

C = πD

或者

C = 2πr

π的小数表示为：

π = 3.14159 . . .

我们将在本章后续内容中，提供更多的关于π和它的一些属性的讨论。

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p>&#x6709;&#x8DA3;&#x7684;&#x662F;&#xFF0C;&#x4EBA;&#x7C7B;&#x7684;&#x773C;&#x775B;&#x5E76;&#x4E0D;&#x5584;&#x4E8E;&#x4F30;&#x7B97;&#x5468;&#x957F;&#x3002;&#x4F8B;&#x5982;&#xFF0C;&#x62FF;&#x4EFB;&#x4F55;&#x4E00;&#x4E2A;&#x5927;&#x9152;&#x676F;&#x3002;&#x4F60;&#x8BA4;&#x4E3A;&#x5B83;&#x7684;&#x9AD8;&#x548C;&#x5468;&#x957F;&#x54EA;&#x4E2A;&#x66F4;&#x5927;&#xFF1F;&#x5927;&#x591A;&#x6570;&#x4EBA;&#x8BA4;&#x4E3A;&#x5B83;&#x7684;&#x9AD8;&#x5EA6;&#x66F4;&#x5927;&#xFF0C;&#x4F46;&#x901A;&#x5E38;&#x662F;&#x5468;&#x957F;&#x66F4;&#x5927;&#x3002;&#x4E3A;&#x4E86;&#x8BF4;&#x670D;&#x81EA;&#x5DF1;&#xFF0C;&#x628A;&#x4F60;&#x7684;&#x62C7;&#x6307;&#x548C;&#x4E2D;&#x6307;&#x653E;&#x5728;&#x9152;&#x676F;&#x7684;&#x4E24;&#x8FB9;&#xFF0C;&#x4EE5;&#x786E;&#x5B9A;&#x5B83;&#x7684;&#x76F4;&#x5F84;&#x3002;&#x4F60;&#x53EF;&#x80FD;&#x4F1A;&#x53D1;&#x73B0;&#x9152;&#x676F;&#x7684;&#x9AD8;&#x5EA6;&#x5C0F;&#x4E8E;&#x76F4;&#x5F84;&#x7684;3&#x500D;&#x3002;</p>
        <p>&#x6211;&#x4EEC;&#x73B0;&#x5728;&#x53EF;&#x4EE5;&#x56DE;&#x7B54;&#x672C;&#x7AE0;&#x5F00;&#x59CB;&#x65F6;&#x7684;&#x95EE;&#x9898;1&#x4E86;&#x3002;&#x5982;&#x679C;&#x6211;&#x4EEC;&#x8BA4;&#x4E3A;&#x5730;&#x7403;&#x7684;&#x8D64;&#x9053;&#x662F;&#x4E00;&#x4E2A;&#x5468;&#x957F;&#x4E3A;C
          = 25,000&#x82F1;&#x91CC;&#x7684;&#x5B8C;&#x7F8E;&#x5706;&#xFF0C;&#x90A3;&#x4E48;&#x5B83;&#x7684;&#x534A;&#x5F84;&#x4E00;&#x5B9A;&#x662F;</p>
        <p>r = C/2&#x3C0; = 25,000/6.28 &#x2248; 4000&#x82F1;&#x91CC;</p>
        <p>&#x4F46;&#x5B9E;&#x9645;&#x4E0A;&#x6211;&#x4EEC;&#x4E0D;&#x9700;&#x8981;&#x77E5;&#x9053;&#x534A;&#x5F84;&#x7684;&#x503C;&#x6765;&#x56DE;&#x7B54;&#x8FD9;&#x4E2A;&#x95EE;&#x9898;&#x3002;&#x6211;&#x4EEC;&#x771F;&#x6B63;&#x9700;&#x8981;&#x77E5;&#x9053;&#x7684;&#x662F;&#xFF0C;&#x5982;&#x679C;&#x6211;&#x4EEC;&#x628A;&#x5468;&#x957F;&#x589E;&#x52A0;10&#x82F1;&#x5C3A;&#xFF0C;&#x534A;&#x5F84;&#x4F1A;&#x53D1;&#x751F;&#x591A;&#x5927;&#x7684;&#x53D8;&#x5316;&#x3002;&#x6DFB;&#x52A0;10&#x82F1;&#x5C3A;&#x5468;&#x957F;&#x5C06;&#x521B;&#x5EFA;&#x4E00;&#x4E2A;&#x7565;&#x5927;&#x7684;&#x5706;&#xFF0C;&#x534A;&#x5F84;&#x589E;&#x52A0;&#x7684;&#x786E;&#x5207;&#x503C;&#x4E3A;10/2&#x3C0;
          = 1.59&#x82F1;&#x5C3A;&#x3002;&#x56E0;&#x6B64;&#xFF0C;&#x5728;&#x7EF3;&#x5B50;&#x4E0B;&#x9762;&#x6709;&#x8DB3;&#x591F;&#x7684;&#x7A7A;&#x95F4;&#xFF0C;&#x4F60;&#x53EF;&#x4EE5;&#x5728;&#x5B83;&#x4E0B;&#x9762;&#x722C;&#x884C;(&#x4F46;&#x4E0D;&#x80FD;&#x5728;&#x5B83;&#x4E0B;&#x9762;&#x8D70;&#xFF0C;&#x9664;&#x975E;&#x4F60;&#x662F;&#x4E00;&#x4E2A;&#x6797;&#x6CE2;&#x821E;&#x8005;!)&#x3002;&#x8FD9;&#x4E2A;&#x95EE;&#x9898;&#x7279;&#x522B;&#x4EE4;&#x4EBA;&#x60CA;&#x8BB6;&#x7684;&#x662F;&#xFF0C;1.59&#x82F1;&#x5C3A;&#x7684;&#x7B54;&#x6848;&#x5B8C;&#x5168;&#x4E0D;&#x4F9D;&#x8D56;&#x4E8E;&#x5730;&#x7403;&#x7684;&#x5B9E;&#x9645;&#x5468;&#x957F;&#xFF1F;&#x5BF9;&#x4EFB;&#x4F55;&#x661F;&#x7403;&#xFF0C;&#x65E0;&#x8BBA;&#x5176;&#x5927;&#x5C0F;&#x5982;&#x4F55;&#xFF0C;&#x4F60;&#x90FD;&#x4F1A;&#x5F97;&#x5230;&#x76F8;&#x540C;&#x7684;&#x7B54;&#x6848;&#xFF01;&#x5047;&#x5982;&#x6211;&#x4EEC;&#x6709;&#x4E00;&#x5708;&#x5468;&#x957F;C
          = 50&#x82F1;&#x5C3A;&#xFF0C;&#x90A3;&#x4E48;&#x5B83;&#x7684;&#x534A;&#x5F84;&#x662F;50
          /(2&#x3C0;) = 7.96&#x3002;&#x5982;&#x679C;&#x6211;&#x4EEC;&#x589E;&#x52A0;&#x5468;&#x957F;10&#x82F1;&#x5C3A;,&#x90A3;&#x4E48;&#x65B0;&#x7684;&#x534A;&#x5F84;60
          /(2&#x3C0;) = 9.55&#xFF1B;&#x589E;&#x52A0;&#x4E86;&#x5927;&#x7EA6;1.59&#x82F1;&#x5C3A;&#x3002;</p>
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
        <p>&#x8FD9;&#x91CC;&#x6709;&#x5173;&#x4E8E;&#x5706;&#x7684;&#x53E6;&#x4E00;&#x4E2A;&#x91CD;&#x8981;&#x4E8B;&#x5B9E;&#x3002;</p>
        <p><b>&#x5B9A;&#x7406;&#xFF1A;</b>&#x8BA9;X&#x548C;Y&#x662F;&#x5706;&#x4E0A;&#x5BF9;&#x79F0;&#x7684;&#x4E24;&#x4E2A;&#x70B9;&#x3002;&#x5BF9;&#x4E8E;&#x5706;&#x4E0A;&#x7684;&#x4EFB;&#x610F;&#x70B9;P&#xFF0C;&#x2220;XPY
          = 90&#xBA;&#x3002;</p>
        <p>&#x4F8B;&#x5982;&#x4E0B;&#x56FE;&#x4E2D;&#xFF0C;&#x2220;XAY&#x3001;&#x2220;XBY&#x548C;&#x2220;XCY&#x90FD;&#x662F;&#x76F4;&#x89D2;&#x3002;
          <img
          src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image008.jpg"
          alt/>
        </p>
        <p><b>&#x8BC1;&#x660E;&#xFF1A;</b>&#x753B;&#x51FA;&#x4ECE;&#x5706;&#x5FC3;O&#x5230;P&#x7684;&#x534A;&#x5F84;&#xFF0C;&#x8BBE;
          &#x2220;XPO = x&#x3001;&#x2220;YPO = y&#x3002;&#x6211;&#x4EEC;&#x7684;&#x76EE;&#x6807;&#x662F;&#x8BC1;&#x660E;
          x + y = 90&#xB0;&#x3002;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image010.jpg"
          alt/>
        </p>
        <p>&#x65E2;&#x7136;OX&#x548C;OP&#x90FD;&#x662F;&#x5706;&#x7684;&#x534A;&#x5F84;&#xFF0C;&#x5B83;&#x4EEC;&#x5177;&#x6709;&#x76F8;&#x540C;&#x957F;&#x5EA6;r&#xFF0C;&#x8FD9;&#x6837;&#x4E09;&#x89D2;&#x5F62;XPO&#x662F;&#x7B49;&#x8FB9;&#x4E09;&#x89D2;&#x5F62;&#x3002;&#x6839;&#x636E;&#x7B49;&#x8FB9;&#x4E09;&#x89D2;&#x5F62;&#x5B9A;&#x7406;&#xFF0C;&#x2220;OXP
          = &#x2220;XPO = x&#x3002;&#x76F8;&#x4F3C;&#x7684;&#xFF0C;&#x6211;&#x4EEC;&#x53EF;&#x4EE5;&#x5F97;&#x5230;&#x2220;OYP
          = &#x2220;YPO = y&#x3002;&#x56E0;&#x4E3A;&#x4E09;&#x89D2;&#x5F62;XYP&#x5185;&#x89D2;&#x4E4B;&#x548C;&#x5FC5;&#x987B;&#x662F;180&#xB0;&#xFF0C;&#x6211;&#x4EEC;&#x5F97;&#x5230;2x
          + 2y = 180&#xB0;&#xFF0C;&#x6240;&#x4EE5;x + y = 90&#xB0;&#x3002;&#x5B9A;&#x7406;&#x5F97;&#x8BC1;&#x3002;</p>
        <p>&#x263A;</p>
        <p>&#x4E0A;&#x9762;&#x7684;&#x5B9A;&#x7406;&#x662F;&#x6211;&#x6700;&#x559C;&#x6B22;&#x7684;&#x51E0;&#x4F55;&#x5B9A;&#x7406;&#x7684;&#x4E00;&#x4E2A;&#x7279;&#x4F8B;&#x2014;&#x2014;&#x4E2D;&#x5FC3;&#x89D2;&#x5B9A;&#x7406;&#x3002;&#x6211;&#x5C06;&#x5728;&#x5728;&#x4E0B;&#x4E00;&#x8282;&#x4E2D;&#x4ECB;&#x7ECD;&#x5B83;&#x3002;</p>
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
        <p>&#x5706;&#x5FC3;&#x89D2;&#x5B9A;&#x7406;&#x53EF;&#x4EE5;&#x63ED;&#x793A;&#x672C;&#x7AE0;&#x5F00;&#x59CB;&#x65F6;&#x7684;&#x95EE;&#x9898;2&#x7684;&#x7B54;&#x6848;&#x3002;&#x4EE4;X&#x548C;Y&#x4E3A;&#x5706;&#x4E0A;&#x4EFB;&#x610F;&#x4E24;&#x4E2A;&#x70B9;&#x3002;&#x4F18;&#x5F27;&#x662F;&#x8FDE;&#x63A5;X&#x548C;Y&#x7684;&#x8F83;&#x957F;&#x7684;&#x5F27;&#xFF0C;&#x8F83;&#x77ED;&#x7684;&#x5F27;&#x88AB;&#x79F0;&#x4E3A;&#x52A3;&#x5F27;&#x3002;&#x5706;&#x5FC3;&#x89D2;&#x5B9A;&#x7406;&#x8BF4;&#xFF0C;&#x4F18;&#x5F27;&#x4E0A;&#x7684;&#x6BCF;&#x4E00;&#x70B9;P&#x6784;&#x6210;&#x7684;&#x2220;XPY&#x5177;&#x6709;&#x76F8;&#x540C;&#x7684;&#x89D2;&#x5EA6;&#xFF0C;&#x89D2;&#x2220;XPY&#x662F;&#x5706;&#x5FC3;&#x89D2;&#x7684;&#x4E00;&#x534A;&#x3002;&#x5982;&#x679C;Q&#x5728;&#x4ECE;X&#x5230;Y&#x7684;&#x52A3;&#x5F27;&#x4E0A;&#xFF0C;&#x90A3;&#x4E48;&#x2220;XQY
          = 180&#xBA; &#x2212; &#x2220;XPY&#x3002;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image012.jpg"
          alt/>
        </p>
        <p>&#x4F8B;&#x5982;&#xFF0C;&#x5F53;&#x2220;XOY = 100&#xBA;&#xFF0C;&#x5BF9;&#x4F18;&#x5F27;&#x4E0A;&#x4EFB;&#x610F;&#x4E00;&#x70B9;P&#xFF0C;&#x2220;XPY
          = 50&#xBA;&#x3002;&#x5BF9;&#x52A3;&#x5F27;&#x4E0A;&#x4EFB;&#x4E00;&#x70B9;Q&#xFF0C;&#x2220;XQY
          = 130&#xBA;&#x3002;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

一旦我们知道了圆的周长，我们就可以推导出圆面积的重要公式。

**定理：**半径为r的圆的面积是πr²。

这是一个你在学校里可能需要记住的公式，但更令人满意的是理解为什么它是正确的。一个完全严格的证明需要微积分，但没有它我们也可以给出一个很有说服力的论证。

**证明1：**将圆想象成由一系列同心环组成。如图所示，现在将圆从顶部切到中心，然后把圆环拉直，形成一个看起来像三角形的物体。这个三角形的面积是多少?

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image014.jpg)

以b为底，h为高的三角形的面积为½bh。对于我们得到的这个类三角形，它的底为2r\(圆的周长\)，高度为r\(从圆心到底部的距离\)。因为当我们使用越来越多的环时，圆变得越来越像三角形，所以圆有面积![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image016.png)。

☺

对于一个如此优雅的定理，让我们证明它两次！刚刚的证明像剥洋葱一样对待圆。这次我们把圆当作披萨。

**证明2：**将圆切成许多大小相等的薄片，然后将上半部分与下半部分分开，并将切片交织在一起。我们用8个切片来说明，然后是16个切片。

随着片数的增加，切片越来越像高r的三角形。将上下两部分切的三角形交错排列。给了我们一个很像矩形的对象，它的高为r，长基本等于周长的一半，即πr（为了让它看起来更像一个长方形，而不是平行四边形，我们可以把最左边的三角形劈成两半，然后把一半移动到最右边）。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image018.jpg)

随着图形越来越接近于矩形，我们可以得到圆的面积为：

bh = \(πr\)\(r\) = πr2

☺

我们经常想要描述平面上的圆。对于半径为r，圆心在\(0,0\)的圆，描述它的方程是这样的。

x2 + y2 = r2

为了证明这是正确的，让（x, y）为圆上任意一点，画一个直角三角形，它的长度是x、y，斜边r，然后根据勾股定理马上得到x2 + y2 = r2。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image020.jpg)

半径为r，圆心在\(0,0\)的圆，其对应的方程式为x2 + y2 = r2，面积是πr²。

r = 1时的圆被称为单位圆。当我们水平方向将单位圆放大a倍，垂直方向将单位圆放大b倍。我们得到一个椭圆。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image022.jpg)

椭圆的面积是 πab。

描述该椭圆的方程式为：

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image024.png)

椭圆面积为πab比较好理解，因为单位圆被放大了ab倍。注意当a = b = r时，我们得到的是一个半径为r的圆，公式πab给出面积 πr2。

这里有一些关于椭圆的有趣的事实。你可以用两个大头针，一根绳子和一支铅笔来创建一个椭圆。把两个大头针放在一张纸或纸板上，用一点松弛的方式把绳子绕在大头针上。把你的铅笔贴紧绳子，这样绳子就会形成一个三角形，如下图所示。然后把铅笔在两个大头针周围移动，一直保持绳子绷紧。这样便能够得到一个椭圆。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image026.jpg)

大头针的位置被称为椭圆的焦点，它们具有以下神奇的性质。如果你拿一个弹球或台球，把它放在一个焦点上，然后朝任何方向击球。当球在椭圆边缘反弹后，它会径直向另一个焦点滚去。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image028.jpg)

像行星和彗星这样的天体在椭圆轨道上绕太阳运行。我无法抗拒下面的韵文。

Even eclipses

Are based on ellipses!

<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p>&#x6709;&#x8DA3;&#x7684;&#x662F;&#xFF0C;&#x692D;&#x5706;&#x7684;&#x5468;&#x957F;&#x6CA1;&#x6709;&#x7B80;&#x5355;&#x7684;&#x516C;&#x5F0F;&#x3002;&#x4F46;&#x662F;&#x6570;&#x5B66;&#x5929;&#x624D;srinivasa
          ramanujan(1887 1920)&#x5EFA;&#x7ACB;&#x4E86;&#x4EE5;&#x4E0B;&#x6781;&#x597D;&#x7684;&#x8FD1;&#x4F3C;&#x3002;&#x6B63;&#x5982;&#x4E0A;&#x9762;&#x6240;&#x63CF;&#x8FF0;&#x7684;&#xFF0C;&#x692D;&#x5706;&#x7684;&#x5468;&#x957F;&#x8FD1;&#x4F3C;&#x4E3A;&#x3002;</p>
        <p>&#x3C0;
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image030.png"
          alt/>
        </p>
        <p>&#x6CE8;&#x610F;&#x5F53;a = b = r&#x65F6;&#xFF0C;&#x8FD9;&#x5C31;&#x53D8;&#x6210;&#x4E86;&#x4E00;&#x4E2A;&#x5706;&#x7684;&#x5468;&#x957F;&#x3002;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

π也会出现在三维物体。考虑一个圆柱体，比如一个罐头。对于半径为r和高度h的圆柱体，它的体积\(测量形状占用的空间\)为

Vcylinder = πr2h

这个公式比较好理解，因为我们可以认为圆柱体由面积πr²的圆堆叠起来\(就像餐馆里的一堆圆形杯垫\)，直到高度为h。

圆柱体的表面积是多少？换句话说，包括顶部和底部，表面刷漆需要多少油漆？你不需要记住答案，因为你可以通过把圆柱分成三部分来计算。圆柱体的顶部和底部各有一个面积πr2的圆，所以他们贡献2πr2的表面积。对于圆柱体其余的部分，我们可以通过将圆柱体从底部到顶部切开然后压平。这样将是一个高h和底2πr的矩形，因为底就是圆的周长。因为矩形面积是 2πrh，圆柱总面积是

Acylinder = 2πr2 + 2πrh

球体是所有的点和它的中心都有一个固定距离的三维物体。半径r的球，其体积是多少？这样的球体可以嵌在一个半径为r和高2r的圆柱体中，所以它的体积必须小于πr2 \(2r\)= 2πr3。如图\(和微积分\)巧合一般，球体正好占据了这个空间的三分之二。换句话说，球的体积是

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image032.png)

球的表面积有一个简单的公式，但它不是很容易推导出来的。

Asphere = 4πr2

让我们以出现在冰淇淋和披萨的π来结束本节。想象一下一个高度h的冰淇淋蛋筒，其顶端的圆半径为r，从圆锥尖到圆的任意点的斜高度为s，如下图所示。\(我们可以用勾股定理计算s，因为h2 + r2 = s2\)

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image034.jpg)

圆锥的体积为 πr2h/3 ，表面积为 πrs。

这样的圆锥体可以嵌入在半径为r和高度h的圆柱体内。所以锥体的体积小于 πr2h也就不足为奇了。但意外的是\(不使用微积分一点都看不出\)，锥体体积恰好是这个数的三分之一。换句话说

Vcone = ⅓πr2h

虽然我们可以不用微积分就推导出圆锥体的表面积，这一点都掩盖不住它的优雅和简单。圆锥体的表面积是。

Acone = πrs

最后，考虑一个半径为z和厚度a的披萨，如下所示。它的体积是多少?

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image036.jpg)

比萨可以被认为是一个形状不同的圆柱体，半径为z，高度为a，所以它的体积一定是。

V = πz2 a

但是答案一直都是盯着你的脸，因为如果我们更仔细地拼出答案的话，我们得到

V = pi z z a

.

π的一些惊人表象

看到π出现在常见圆形物体的面积和周长中，这并不奇怪。但π出现在许多貌似它并不应该出现的数学领域。举个例子，n!的总量。我们在第四章中探讨过。这个数有什么特别的圆。它主要用于计数离散量。我们知道它是一个增长极快的数字，但是没有有效的快捷方式来计算n！例如,计算100000！仍然需要成千上万的乘法。然而，有一种有用的方法（斯特林公式）可以估计它的值。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image038.png)

这里e = 2.71828 . . .（另一个重要的无理数，我们将在第10章学习它）。例如，计算机可以只用前4个最高有效位来计算，64! = 1.269 × 1089。

下图是著名的钟形曲线，它出现在统计学和所有的实验科学中。我们将在第十章中详细介绍这条曲线。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image040.jpg)

π也常常出现在无限项求和中。列昂哈德·欧拉首先证明了，当我们把正整数倒数的平方相加时，我们得到。

1 + 1/22 + 1/32 + 1/42 + · · · = 1 + 1/4 + 1/9 + 1/16 + · · · = π2/6

如果我们将以上各项再次平方，那么所有正整数四次方的倒数之和是。

1 + 1/16 + 1/81 + 1/256 + 1/625 + · · · = π4/90

事实上，所有偶数次幂的倒数之和是π2k乘以一个有理数。

奇数次幂的倒数之和是多少呢？我们将在第12章看到正整数倒数之和是无穷大。当指数是大于1的奇数时，比如下面的立方数倒数之和，

1 + 1/8 + 1/27 + 1/64 + 1/125 + · · · = ???

总和是有限的，但是还没有人总结出一个通用的求和公式。

矛盾的是，π出现在与概率有关的问题上。举个例子，如果你随机选择两个非常大的数字，它们没有相同质因子的概率是60%多一点。更准确地说,概率是6 /π2 = 0.6079。这不是巧合，它正是之前的一个无限倒数序列之和。

数字π

通过自己的精心测量，你可以通过试验确定π比3大一点，但两个问题很自然会出现。你能不使用物理测量证明π在3的附近是吗？有一个简单的分数或公式可以表示π吗？

我们可以通过画一个半径为1的圆来回答第一个问题。我们知道圆面积是π12 = π。在下面的图中，我们绘制了一个长度为2的正方形，它完全包含这个圆。由于圆的面积必须小于正方形的面积，这证明π&lt; 4。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image042.jpg)

3 &lt; π &lt; 4的几何证明

另一方面，圆周上的六个等距点构成一个六边形，该六边形被圆包含。内接六边形的周长是多少？六边形可以分成6个三角形，每个三角形的位于圆心的顶角为360° /6 = 60°。构成顶角的两边是半径为1的圆的半径，因此三角形为等腰三角形。根据等腰三角形定理，其他两个角相等，必须也是60°。因此，这些三角形都是边长为1的等边三角形。六边形的周长是6，它小于圆的周长2π。因此 π &gt; 3。综合以上结果，我们得到

3 &lt; π &lt; 4  


<table>
  <thead>
    <tr>
      <th style="text-align:left">
        <p><b>&#x65C1;&#x767D;</b>
        </p>
        <p>&#x901A;&#x8FC7;&#x4F7F;&#x7528;&#x66F4;&#x591A;&#x8FB9;&#x7684;&#x591A;&#x8FB9;&#x5F62;&#xFF0C;&#x6211;&#x4EEC;&#x53EF;&#x4EE5;&#x5C06;&#x3C0;&#x9650;&#x5236;&#x5728;&#x4E00;&#x4E2A;&#x8F83;&#x5C0F;&#x7684;&#x533A;&#x95F4;&#x3002;&#x4F8B;&#x5982;&#xFF0C;&#x5982;&#x679C;&#x6211;&#x4EEC;&#x7528;&#x516D;&#x8FB9;&#x5F62;&#x800C;&#x4E0D;&#x662F;&#x6B63;&#x65B9;&#x5F62;&#x6765;&#x5305;&#x56F4;&#x5355;&#x4F4D;&#x5706;&#xFF0C;&#x6211;&#x4EEC;&#x53EF;&#x4EE5;&#x8BC1;&#x660E;&#x2026;&#x2026;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image044.jpg"
          alt/>
        </p>
        <p>&#x518D;&#x4E00;&#x6B21;&#xFF0C;&#x516D;&#x8FB9;&#x5F62;&#x53EF;&#x4EE5;&#x88AB;&#x7EC6;&#x5206;&#x4E3A;&#x516D;&#x4E2A;&#x7B49;&#x8FB9;&#x4E09;&#x89D2;&#x5F62;&#x3002;&#x6BCF;&#x4E2A;&#x4E09;&#x89D2;&#x5F62;&#x53EF;&#x4EE5;&#x88AB;&#x7EC6;&#x5206;&#x6210;&#x4E24;&#x4E2A;&#x5168;&#x7B49;&#x7684;&#x76F4;&#x89D2;&#x4E09;&#x89D2;&#x5F62;&#x3002;&#x5982;&#x679C;&#x77ED;&#x76F4;&#x89D2;&#x8FB9;&#x7684;&#x957F;&#x5EA6;&#x662F;x&#xFF0C;&#x90A3;&#x4E48;&#x659C;&#x8FB9;&#x957F;&#x5EA6;&#x662F;2x&#xFF0C;&#x6839;&#x636E;&#x52FE;&#x80A1;&#x5B9A;&#x7406;&#xFF0C;x2
          + 1 = (2x)2&#x3002;&#x89E3;&#x51FA;x =
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image046.png"
          alt/>&#x3002;&#x56E0;&#x6B64;&#xFF0C;&#x516D;&#x8FB9;&#x5F62;&#x7684;&#x5468;&#x957F;&#x662F;12
          x =
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image048.png"
          alt/>&#xFF0C;&#x56E0;&#x4E3A;&#x5B83;&#x5927;&#x4E8E;&#x5706;&#x5468;&#x957F;2&#x3C0;&#xFF0C;&#x7531;&#x6B64;&#x53EF;&#x89C1;&#x3C0;
          &lt;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image050.png"
          alt/>&#x3002;(&#x6709;&#x8DA3;&#x7684;&#x662F;&#xFF0C;&#x6211;&#x4EEC;&#x901A;&#x8FC7;&#x5C06;&#x5706;&#x7684;&#x9762;&#x79EF;&#x4E0E;&#x516D;&#x8FB9;&#x5F62;&#x9762;&#x79EF;&#x8FDB;&#x884C;&#x6BD4;&#x8F83;&#x4E5F;&#x80FD;&#x5F97;&#x51FA;&#x76F8;&#x540C;&#x7684;&#x7ED3;&#x8BBA;&#x3002;)</p>
        <p>&#x4F1F;&#x5927;&#x7684;&#x53E4;&#x5E0C;&#x814A;&#x6570;&#x5B66;&#x5BB6;&#x963F;&#x57FA;&#x7C73;&#x5FB7;(&#x516C;&#x5143;&#x524D;287
          - 212&#x5E74;)&#x5728;&#x6B64;&#x57FA;&#x7840;&#x4E0A;&#x521B;&#x5EFA;&#x4E86;&#x6709;12&#x3001;24&#x3001;48&#x548C;96&#x4E2A;&#x8FB9;&#x7684;&#x5185;&#x63A5;&#x548C;&#x5916;&#x5207;&#x591A;&#x8FB9;&#x5F62;&#xFF0C;&#x63A8;&#x5BFC;&#x51FA;3.14103
          &lt; &#x3C0; &lt; 3.14271&#x548C;&#x770B;&#x8D77;&#x6765;&#x66F4;&#x7B80;&#x5355;&#x7684;&#x4E0D;&#x7B49;&#x5F0F;&#x3002;</p>
        <p>
          <img src="file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image052.png"
          alt/>
        </p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

将π近似写成分数的方式有很多种，比如：

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image054.jpg)

我特别喜欢最后一个近似。它不仅正确地给π小数点后六位，它还使用前三个奇数两次：两个1、两个3和两个5。

能发现π的精确的分数描述自然很有趣\(分子和分母都是整数;否则我们只能说\)。1768年，约翰·海因里希·兰伯特通过证明π是无理数，从而证明这样的搜索将是徒劳的。也许它可以用平方根或者简单数字的立方根来写？例如，……就相当接近。但在1882年,费迪南·冯·林德曼证明π不仅仅是无理数，而且是超越数。这意味着π不是任何整系数多项式的根。例如, ![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image056.png)是无理数但不是超越数，因为它是多项式x2 − 2的一个根。

尽管π不能被表示为一个分数，但它可以表示为无限个分数的和或积。例如，我们将在第12章中看到下面的等式

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image058.jpg)

上面的公式相当惊艳，但它不是一个非常实用的计算π的公式。300项之后，它仍然没有比22/7更接近π。还有另一个令人震惊的公式，被称为wallis s公式，它被表达为一个无限项的乘积，可是它也需要很长的时间才能收敛。

![](file:///C:/Users/samuel/AppData/Local/Temp/msohtmlclip1/01/clip_image060.jpg)

庆祝和记忆π

出于对π的迷恋\(作为一种测试超级计算机的速度和准确性的方法\)，π已被计算小数点后到万亿位。我们肯定不需要得到这个精度水平，只需小数点后四十位，你就可以测量已知宇宙的周长和氢原子的半径。

π几乎几乎拥有一大批的追随者。许多人将3月14日\(3/14\)设为特殊的纪念日π day，这一天也是爱因斯坦的生日。在π日，典型的活动有：展示和吃数学主题馅饼，打扮成爱因斯坦，还有π记忆比赛。学生通常记住π小数点后几十位的数字，经常有获胜者有记住超过一百位的数字。顺便说一下，目前的π记忆世界纪录属于一名叫吕超的中国人。他于1995年，花了将近24个小时无差错地背诵圆周率至小数点后67890位，并被收录进[吉尼斯世界纪录](https://baike.baidu.com/item/%E5%90%89%E5%B0%BC%E6%96%AF%E4%B8%96%E7%95%8C%E7%BA%AA%E5%BD%95)。

这是π的前100位

π = 3.141592653589793238462643383279502884197169399375

105820974944592307816406286208998628034825342117067 . . .

略过原文中关于π背诵的部分

所有的数学家都同意，π是数学中最重要的数字之一。但是如果你看看使用π的公式和应用程序，你会发现它们中的大多数是π乘以2。希腊字母τ来代表这个量

τ = 2π

许多人认为，如果我们能及时回到过去，三角学中的数学公式和关键概念将会由更简单的τ而不是π来表达。

这一想法已经在 Bob Palais 的文章\(“π is Wrong!”\) 和 Michael Hartl 的文章\(“The Tau Manifesto”\)中被优雅和令人愉快地表达了出来。这一想法的核心是：圆是由半径定义的。当我们将圆的周长除以半径时，我们得到 C/r = 2π = τ。一些教科书现在贴上τ-compliant表明其中的公式将同时使用π和τ（虽然在它们之间的切换并不比“吃派”简单，但是很多教师和学生认为τ 比π更简单）。看看接下来几十年里会发生什么将会非常有趣。τ的支持者们\(他自称tauists\)虔诚地相信真理在他们一边，但他们对传统符号持宽容的态度。正如他们喜欢说的，tauists从不pious。

这里是τ前一百位。注意，τ始于6和28，如第6章所述，这两个是完美数。这是巧合吗?当然是的！但不管怎样，这是一个有趣的小故事。

τ = 6.283185 30717958 64769252 867665 5900576 839433 8798750 211641949 8891846 15632 812572417 99725606 9650684 234135 . . .

2012年，十三岁的布朗伊桑创造了新的世界纪录，他背出了τ的前2012位。他使用了语音代码，但他没有创建长句子，而是创建了视觉图像，其中每个图像都包含一个主题、一个动作\(总是以ing结尾\)和一个被执行的对象。前7位数字，62 831 85，变成了一个“吐华夫饼的大海”。这里有他为τ的前一百位配的景象。

An ocean vomiting a waffle

A mask tugging on a bailiff

A shark chopping nylon

Fudge coaching a cello

Elbows selling a couch

Foam burying a mummy

Fog paving glass

A handout shredding a prop

FIFA beautifying the Irish

A doll shooing a minnow

A photon looking neurotic

A puppy acknowledging the sewage

A peach losing its chauffeur

Honey marrying oatmeal

为了使场景更容易记忆，布朗采用了记忆宫殿的方法，想象自己在学校里游荡。当他走入某些通道或进入不同的教室时，每个房间都会有3到5个物体在做傻事。最终，他有分布在60多个地点的272张图片。他花了4个月的时间准备背诵前2012位数字，最终而他在73分钟内背出了这2012位数字。

让我们以音乐庆祝的方式结束这一章。我写这篇文章是为了抒情，这是对 Larry Lesser 《American Pi》[http://www.math.utep.edu/Faculty/lesser/americanpi.html](http://www.math.utep.edu/Faculty/lesser/americanpi.html)的模仿。你应该只唱一次，因为π不会重复。

‘

A long, long, time ago,

I can still remember how my math class used to make me snore.

’Cause every number we would meet

Would terminate or just repeat,

But maybe there were numbers that did more.

But then my teacher said, “I dare ya

To try to find the circle’s area.”

Despite my every action,

I couldn’t find a fraction.

I can’t remember if I cried,

The more I tried or circumscribed,

But something touched me deep inside

The day I learned of pi!

Pi, pi, mathematical pi,

Twice eleven over seven is a mighty fine try.

A good old fraction you may hope to supply,

But the decimal expansion won’t die.

Decimal expansion won’t die.

Pi, pi, mathematical pi,

3.141592653589.

A good old fraction you may hope to define,

But the decimal expansion won’t die!

