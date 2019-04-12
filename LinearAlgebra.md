
##标量、向量、矩阵、和张量

+ 标量（scalar）:一个标量就是一个单独的数，它不同于线性代数中研究的其他大部分对象(通常是对个数的数组)。

>表示：用斜体表示，标量通常被赋予小写的变量名称。</br>
 >>  示例:</br>
	 1. 定义实数标量，令![s属于集合R的斜率](https://s2.ax1x.com/2019/03/30/ADNbb4.png)表示一条线的斜率。</br>
	 2. 定义自然数标量，令[![n属于集合N](https://s2.ax1x.com/2019/03/30/ADUPqe.png)](https://imgchr.com/i/ADUPqe)表示元素的数目。

+ 向量（vector）：一个向量是一列数。这些数是有序排列的。并且可以通过索引可以得到其中的某一个数。
>***表示：***通常赋予向量粗体的小写变量名称，比如![——x——](https://s2.ax1x.com/2019/03/31/ADvba6.png)。向量中的元素可以通过带脚标的斜体表示。向量![——x——](https://s2.ax1x.com/2019/03/31/ADvba6.png)的第一个元素是![——x1——](https://s2.ax1x.com/2019/03/31/ADxPdP.png)，第二个元素是![——x2——](https://s2.ax1x.com/2019/03/31/ADxERg.png)，等等。</br>
>	注：通常也会注明储存在向量中的元素是什么类型。</br>
>	示例：</br>
> 如果每一个元素都属于![——R——](https://s2.ax1x.com/2019/03/31/ADxmss.png)并且该向量有![——n——](https://s2.ax1x.com/2019/03/31/ADxcyd.png)个级元素，那么该向量属于实数集![R](https://s2.ax1x.com/2019/03/31/ADxmss.png)的![——n——](https://s2.ax1x.com/2019/03/31/ADxcyd.png)次笛卡尔乘积构成的集合，记为[![——R^n——](https://s2.ax1x.com/2019/03/31/ADx4Ff.png)](https://imgchr.com/i/ADx4Ff)。当我们需要明确表示向量中的元素时，我们会将元素排列成一个方括号包围的纵列：
<div align=center>![——R^n次笛卡尔乘积构成的集合——](https://s2.ax1x.com/2019/03/31/ADz9l4.png)</br>
<div align=left>把向量看做看做空间中的点，每个元素是不同坐标轴上的坐标。	</br>
如需要索引向量中的元素。此时需要定义一个包含这些元素索引的集合，然后将该集合写在脚标处。比如，指定![——x1——](https://s2.ax1x.com/2019/03/31/ADxPdP.png)，![x3](https://s2.ax1x.com/2019/03/31/ArpERO.png)，![x6.png](https://s2.ax1x.com/2019/03/31/ArpDYV.png)，定义集合为![Ar991S.png](https://s2.ax1x.com/2019/03/31/Ar991S.png)，写作![——xS——](https://s2.ax1x.com/2019/03/31/Ar9Jtx.png)。用符号—表示集合的补集中的索引。
![——x_1——](https://s2.ax1x.com/2019/04/01/AyKfA0.png)中除![——x1——](https://s2.ax1x.com/2019/03/31/ADxPdP.png)外的所有元素，![x_S](https://s2.ax1x.com/2019/04/01/AyKa7t.png)表示![——x——](https://s2.ax1x.com/2019/03/31/ADvba6.png)中除![——x1——](https://s2.ax1x.com/2019/03/31/ADxPdP.png)，![——x3——](https://s2.ax1x.com/2019/03/31/ArpERO.png)，![——x6——](https://s2.ax1x.com/2019/03/31/ArpDYV.png)外所有元素构成的向量。

+ 矩阵（matrix）：矩阵是一个二维数组，其中的每一个元素被两个索引确定，
>***表示：***通常会赋予矩阵粗体的大写变量表示，例如：![——矩阵A——](https://s2.ax1x.com/2019/04/01/Ayl90A.png)。如果一个实数矩阵高度为![——m——](https://s2.ax1x.com/2019/04/01/AylZ6g.png)，宽度为![——n——](https://s2.ax1x.com/2019/04/01/AyleXQ.png)，那么![AylzCV.png](https://s2.ax1x.com/2019/04/01/AylzCV.png)。在表示矩阵元素时，通常以不加粗的斜体形式使用其名称，索引用逗号间隔。
>>![Ay1hqJ.png](https://s2.ax1x.com/2019/04/01/Ay1hqJ.png)，表示![——矩阵A——](https://s2.ax1x.com/2019/04/01/Ayl90A.png)左上的元素；![Ay1zdA.png](https://s2.ax1x.com/2019/04/01/Ay1zdA.png)表示![——矩阵A——](https://s2.ax1x.com/2019/04/01/Ayl90A.png)的右下的元素。</br>
>
用“：”表示水平坐标,以表示垂直坐标![——i——](https://s2.ax1x.com/2019/04/01/Ay33yF.png)中的所有元素。<br>
>>例：![——A_i——](https://s2.ax1x.com/2019/04/01/Ay3DyD.png)表示![——矩阵A——](https://s2.ax1x.com/2019/04/01/Ayl90A.png)中垂直坐标![——i——](https://s2.ax1x.com/2019/04/01/Ay33yF.png)上的一横排元素，又称为![——矩阵A——](https://s2.ax1x.com/2019/04/01/Ayl90A.png)的第![——i——](https://s2.ax1x.com/2019/04/01/Ay33yF.png)**行（row）**。</br>
>同上，![Ay8G1f.png](https://s2.ax1x.com/2019/04/01/Ay8G1f.png)表示![——矩阵A——](https://s2.ax1x.com/2019/04/01/Ayl90A.png)的第![——i——](https://s2.ax1x.com/2019/04/01/Ay33yF.png)**列（column）**</br>
如需明确表示矩阵中的元素时，将其写在用方括号包围起来的数组中：<br/>
<div align=center>![——明确的矩阵A——](https://s2.ax1x.com/2019/04/01/AyGm80.png)</br>

><div align=left>如需矩阵值表达的索引，而不是单个元素时，在表达式后面接下标，但不必将矩阵的变量名称小写化。</br>
>>如：![——函数f——](https://s2.ax1x.com/2019/04/01/AyGHGq.png)表示函数![——f——](https://s2.ax1x.com/2019/04/02/AyJCJ1.png)作用在![——矩阵A——](https://s2.ax1x.com/2019/04/01/Ayl90A.png)上输出的矩阵的第![——i——](https://s2.ax1x.com/2019/04/01/Ay33yF.png)行第![AyJuFA.png](https://s2.ax1x.com/2019/04/02/AyJuFA.png)列元素。

+ 张量（tensor）:一个数组中的元素分布在若干维坐标的规则网格中，称为张量。
> ***表示：***使用字体**A**来表示张量“A”。张量A中坐标![——i,j,k——](https://s2.ax1x.com/2019/04/12/Aqtart.png)，记作![——矩阵A_{i,j,k}——](https://s2.ax1x.com/2019/04/12/Aqt2Mn.png)。

> **转置（transpose）:**矩阵的转置是以对角线为轴的镜像,这条左上角到右下角的对角线被称为**主对角线（main diagonal）**。
> 
> ***表示：***矩阵![——矩阵A——](https://s2.ax1x.com/2019/04/01/Ayl90A.png)的转置表示为![——矩阵A的转置——](https://s2.ax1x.com/2019/04/12/AqaUM9.png)，定义为

> <div align=center>![——矩阵A的转置定义——](https://s2.ax1x.com/2019/04/12/AqahZt.png)
> <div align=left>　向量可以看做是只有一列的矩阵。向量的转置可以看做是只有一行的矩阵。

>　　例如：通过将向量元素作为行矩阵写在文本中，然后使用转置操作将其变为标准的列向量，来定义一个向量，如：![向量矩阵的转置](https://s2.ax1x.com/2019/04/13/Aqgf5d.png)

>　标量可以看做是只有一个元素的矩阵。所以标量的转置等于他本身，![标量的转置](https://s2.ax1x.com/2019/04/13/AqgxGn.png)。

> <div align=center> ![张量转置示意图](https://s2.ax1x.com/2019/04/12/AqgpHe.md.png)