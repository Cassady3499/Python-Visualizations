# Python-Visualizations
There are 50 Visualizations which can you to finish 7 different purposes of data analysis. 

一共有50组图，可以实现7种不同的数据分析的目的。

 ## 1. Correlation
 ### 1.1 Scatter plot（散点图）
   
   Scatteplot is a classic and fundamental plot used to study the relationship between two variables. If you have multiple groups in your data you may want to visualise each group in a different color. In matplotlib, you can conveniently do this using plt.scatterplot().
   
   散点图是用于研究两个变量之间关系的经典的和基本的图表。 如果数据中有多个组，则可能需要以不同颜色可视化每个组。 在 matplotlib 中，您可以使用 plt.scatterplot（） 方便地执行此操作。
   
   ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Image/Scatter%20plot.png)
   Code (代码): [Scatter plot.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Code/Scatter%20plot.py)
    
 ### 1.2 Bubble plot with Encircling （带边界的气泡图）
    
   Sometimes you want to show a group of points within a boundary to emphasize their importance. In this example, you get the records from the dataframe that should be encircled and pass it to the encircle() described in the code below.
    
   有时，您希望在边界内显示一组点以强调其重要性。 在这个例子中，你从数据框中获取记录，并用下面代码中描述的 encircle（） 来使边界显示出来。
   
   ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Image/Bubble%20plot%20with%20Encircling.png)
   Code(代码)：[Bubble plot with Encircling.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Code/Bubble%20plot%20with%20Encircling.py)
    
 ### 1.3 Regression plot （回归拟合）  
 #### 1.3.1 Scatter plot with line of best fit （带线性回归最佳拟合线的散点图）
   
   If you want to understand how two variables change with respect to each other, the line of best fit is the way to go. The below plot shows how the line of best fit differs amongst various groups in the data. To disable the groupings and to just draw one line-of-best-fit for the entire dataset, remove the hue='cyl' parameter from the sns.lmplot() call below.
   
   如果你想了解两个变量如何相互改变，那么最佳拟合线就是常用的方法。 下图显示了数据中各组之间最佳拟合线的差异。 要禁用分组并仅为整个数据集绘制一条最佳拟合线，请从下面的 sns.lmplot（）调用中删除 hue ='cyl'参数。
 
 ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Image/Scatter%20plot%20with%20line%20of%20best%20fit.png)
 Code(代码)：[Scatter plot with line of best fit.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Code/Scatter%20plot%20with%20linear%20regression%20line%20of%20best%20fit.py)
 #### 1.3.2 Each regression line in its own column（针对每列绘制线性回归线）
 
   Alternately, you can show the best fit line for each group in its own column. You cando this by setting the col=groupingcolumn parameter inside the sns.lmplot().
   
   或者，可以在其每列中显示每个组的最佳拟合线。 可以通过在 sns.lmplot() 中设置 col=groupingcolumn 参数来实现。
   
 ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Image/Each%20regression%20line%20in%20its%20own%20column.png)
 Code(代码)：[Each regression line in its own column.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Code/Each%20regression%20line%20in%20its%20own%20column.py)
 ### 1.4 Jittering with stripplot （抖动图）
   
   Often multiple datapoints have exactly the same X and Y values. As a result, multiple points get plotted over each other and hide. To avoid this, jitter the points slightly so you can visually see them. This is convenient to do using seaborn’s stripplot().
 
   通常，多个数据点具有完全相同的 X 和 Y 值。 结果，多个点绘制会重叠并隐藏。 为避免这种情况，请将数据点稍微抖动，以便您可以直观地看到它们。 使用 seaborn 的 stripplot（） 很方便实现这个功能。
 
 ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Image/Jittering%20with%20stripplot.png)
 Code(代码)：[Jittering with stripplot](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Code/Jittering%20with%20stripplot.py)
 
 ### 1.5 Counts Plot（计数图）
 
   Another option to avoid the problem of points overlap is the increase the size of the dot depending on how many points lie in that spot. So, larger the size of the point more is the concentration of points around that.
 
   避免点重叠问题的另一个选择是增加点的大小，这取决于该点中有多少点。 因此，点的大小越大，其周围的点的集中度越高。
    
   ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Image/Counts%20Plot.png)
 Code(代码)：[Counts Plot.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Code/Counts%20Plot.py)
 ### 1.6 Marginal Histogram（边缘直方图）
 
   Marginal histograms have a histogram along the X and Y axis variables. This is used to visualize the relationship between the X and Y along with the univariate distribution of the X and the Y individually. This plot if often used in exploratory data analysis (EDA).
   
   边缘直方图具有沿 X 和 Y 轴变量的直方图。 这用于可视化 X 和 Y 之间的关系以及单独的 X 和 Y 的单变量分布。 这种图经常用于探索性数据分析（EDA）。
   
 ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Image/Marginal%20Histogram.png)
 Code(代码)：[Marginal Histogram.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Code/Marginal%20Histogram.py)
 ### 1.7 Marginal Boxplot（边缘箱形图）
 
   Marginal boxplot serves a similar purpose as marginal histogram. However, the boxplot helps to pinpoint the median, 25th and 75th percentiles of the X and the Y.
   
   边缘箱图与边缘直方图具有相似的用途。 然而，箱线图有助于精确定位 X 和 Y 的中位数、第25和第75百分位数。
   
   ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Image/Marginal%20Boxplot.png)
   Code (代码):[Marginal Boxplot.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Code/Marginal%20Boxplot.py)
 
 ### 1.8 Correlogram（相关图）
   
   Correlogram is used to visually see the correlation metric between all possible pairs of numeric variables in a given dataframe (or 2D array).
   
   相关图用于直观地查看给定数据框（或二维数组）中所有可能的数值变量对之间的相关度量。
  
  ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Image/Correlogram.png)
 Code(代码)：[Correlogram.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Code/Correllogram.py)
 ### 1.9 Pairwise Plot（矩阵图）
 
   Pairwise plot is a favorite in exploratory analysis to understand the relationship between all possible pairs of numeric variables. It is a must have tool for bivariate analysis.
   
   矩阵图是探索性分析中的最爱，用于理解所有可能的数值变量对之间的关系。 它是双变量分析的必备工具。
  
  ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Image/Pairwise%20Plot.png)
  ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Image/Pairwise%20Plot2.png)
 Code(代码)：[Pairwise Plot.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Correlation_Code/Pairwise%20Plot.py)
 
 ## 2. Deviation（偏差）
 ### 2.1 Diverging Bars（发散型条形图）
 
   If you want to see how the items are varying based on a single metric and visualize the order and amount of this variance, the diverging bars is a great tool. It helps to quickly differentiate the performance of groups in your data and is quite intuitive and instantly conveys the point.
   
   如果您想根据单个指标查看项目的变化情况，并可视化此差异的顺序和数量，那么散型条形图 （Diverging Bars） 是一个很好的工具。 它有助于快速区分数据中组的性能，并且非常直观，并且可以立即传达这一点。
   
  ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Deviation_Image/Diverging%20Bars.png)
  Code (代码): [Diverging Bars.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Deviation_Code/Diverging%20Bars.py)
  
 ### 2.2 Diverging Texts（发散型文本）
   
   Diverging texts is similar to diverging bars and it preferred if you want to show the value of each items within the chart in a nice and presentable way.
 
   发散型文本 （Diverging Texts）与发散型条形图 （Diverging Bars）相似，如果你想以一种漂亮和可呈现的方式显示图表中每个项目的价值，就可以使用这种方法。
 
 ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Deviation_Image/Diverging%20Texts.png)
  Code (代码): [Diverging Texts.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Deviation_Code/Diverging%20Texts.py)
 ### 2.3 Diverging Dot Plot（发散型包点图）
 
   Divering dot plot is also similar to the diverging bars. However compared to diverging bars, the absence of bars reduces the amount of contrast and disparity between the groups.
 
   发散型包点图 （Diverging Dot Plot）也类似于发散型条形图 （Diverging Bars）。 然而，与发散型条形图 （Diverging Bars）相比，条的缺失减少了组之间的对比度和差异。
  
  ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Deviation_Image/Diverging%20Dot%20Plot.png)
  Code (代码): [Diverging Dot Plot.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Deviation_Code/Diverging%20Dot%20Plot.py)
 ### 2.4 Diverging Lollipop Chart with Markers（带标记的发散型棒棒糖图）
 
   Lollipop with markers provides a flexible way of visualizing the divergence by laying emphasis on any significant datapoints you want to bring attention to and give reasoning within the chart appropriately.
 
   带标记的棒棒糖图通过强调您想要引起注意的任何重要数据点并在图表中适当地给出推理，提供了一种对差异进行可视化的灵活方式。
  
  ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Deviation_Image/Diverging%20Lollipop%20Chart%20with%20Markers.png)
  Code (代码): [Diverging Lollipop Chart with Markers.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Deviation_Code/Diverging%20Lollipop%20Chart%20with%20Markers.py)
 ### 2.5 Area Chart（面积图）
 
   By coloring the area between the axis and the lines, the area chart throws more emphasis not just on the peaks and troughs but also the duration of the highs and lows. The longer the duration of the highs, the larger is the area under the line.

   通过对轴和线之间的区域进行着色，面积图不仅强调峰和谷，而且还强调高点和低点的持续时间。 高点持续时间越长，线下面积越大。
  
  ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Deviation_Image/Area%20Chart.png)
  Code (代码): [Area Chart.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Deviation_Code/Area%20Chart.py)
  
  ## 3. Ranking（排序）
  ### 3.1 Ordered Bar Chart（有序条形图）
  
   Ordered bar chart conveys the rank order of the items effectively. But adding the value of the metric above the chart, the user gets the precise information from the chart itself.
   
   有序条形图有效地传达了项目的排名顺序。 但是，在图表上方添加度量标准的值，用户可以从图表本身获取精确信息。
   
   ![](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Ranking_Image/Ordered%20Bar%20Chart.png)
   Code(代码)：[Ordered Bar Chart.py](https://github.com/WilliamCHW/Python-Visualizations/blob/master/Ranking_Code/Ordered%20Bar%20Chart.py)
   
  ### 3.2 Lollipop Chart （棒棒糖图）
  
   棒棒糖图表以一种视觉上令人愉悦的方式提供与有序条形图类似的目的。
 
 ![]()
  Code（代码）:[Lollipop Chart.py]()
  ### 3.3 Dot Plot （包点图）
  
    包点图表传达了项目的排名顺序，并且由于它沿水平轴对齐，因此您可以更容易地看到点彼此之间的距离。
  
  ![]()
  Code（代码）:[ Dot Plot.py]()
  ### 3.4 Slope Chart （坡度图）
  
    坡度图最适合比较给定人/项目的“前”和“后”位置。
  
  ![]()
  Code（代码）:[ Slope Chart.py]()
  ### 3.5 Dumbbell Plot （哑铃图）
  
    哑铃图表传达了各种项目的“前”和“后”位置以及项目的等级排序。 如果您想要将特定项目/计划对不同对象的影响可视化，那么它非常有用。

   ![]()
  Code（代码）:[ Dumbbell Plot.py]()
  
  ## 4.Distribution
  
  ### 4.1 Histogram for Continuous Variable （连续变量的直方图）
  
    直方图显示给定变量的频率分布。 下面的图表示基于类型变量对频率条进行分组，从而更好地了解连续变量和类型变量。
  
   ![]()
  Code（代码）:[ Histogram for Continuous Variable.py]()
  ### 4.2 Histogram for Categorical Variable （类型变量的直方图）
  
    类型变量的直方图显示该变量的频率分布。 通过对条形图进行着色，可以将分布与表示颜色的另一个类型变量相关联。
  
   ![]()
  Code（代码）:[ Histogram for Categorical Variable.py]()
  ### 4.3 Density Plot （密度图）
  
    密度图是一种常用工具，用于可视化连续变量的分布。 通过“响应”变量对它们进行分组，您可以检查 X 和 Y 之间的关系。以下情况用于表示目的，以描述城市里程的分布如何随着汽缸数的变化而变化。
  
   ![]()
  Code（代码）:[ Density Plot.py]()
  ### 4.4 Density Curves with Histogram （直方密度线图）
  
    带有直方图的密度曲线汇集了两个图所传达的集体信息，因此您可以将它们放在一个图中而不是两个图中。
  
  ![]()
  Code（代码）:[ Density Curves with Histogram.py]()
  ### 4.5 Joy Plot （连续变量的直方图）
  
   Joy Plot允许不同组的密度曲线重叠，这是一种可视化大量分组数据的彼此关系分布的好方法。 它看起来很悦目，并清楚地传达了正确的信息。 它可以使用基于 matplotlib 的 joypy 包轻松构建。 （注：需要安装 joypy 库）
   
   ![]()
  Code（代码）:[ Joy Plot.py]()
  ### 4.6 Distributed Dot Plot （分布式包点图）
  
   分布式包点图显示按组分割的点的单变量分布。 点数越暗，该区域的数据点集中度越高。 通过对中位数进行不同着色，组的真实定位立即变得明显。
   
   ![]()
  Code（代码）:[ Distributed Dot Plot.py]()
  
  ### 4.7 Box Plot （分布式包点图）
  
   箱形图是一种可视化分布的好方法，记住中位数、第25个第45个四分位数和异常值。 但是，您需要注意解释可能会扭曲该组中包含的点数的框的大小。 因此，手动提供每个框中的观察数量可以帮助克服这个缺点。例如，左边的前两个框具有相同大小的框，即使它们的值分别是5和47。 因此，写入该组中的观察数量是必要的。

![]()
  Code（代码）:[ Box Plot.py]()
  ### 4.8 Dot and Box Plot （包点和箱形图）
  
  包点+箱形图 （Dot and Box Plot）传达类似于分组的箱形图信息。 此外，这些点可以了解每组中有多少数据点。

![]()
  Code（代码）:[ Dot and Box Plot.py]()
  ### 4.9 Violin Plot （小提琴图）
  
    小提琴图是箱形图在视觉上令人愉悦的替代品。 小提琴的形状或面积取决于它所持有的观察次数。 但是，小提琴图可能更难以阅读，并且在专业设置中不常用。
  
  ![]()
  Code（代码）:[ Violin Plot.py]()
  ### 4.10 Population Pyramid （人口金字塔）
  
  人口金字塔可用于显示由数量排序的组的分布。 或者它也可以用于显示人口的逐级过滤，因为它在下面用于显示有多少人通过营销渠道的每个阶段。
  
  
  ![]()
  Code（代码）:[Population Pyramid.py]()
  
  ### 4.11 Categorical Plots （分类图）
  
  由 seaborn库 提供的分类图可用于可视化彼此相关的2个或更多分类变量的计数分布。
  
   ![]()
  Code（代码）:[Categorical Plots.py]()
## 5. Composition （组成）
### 5.1 Waffle Chart （华夫饼图）

  可以使用 pywaffle包 创建华夫饼图，并用于显示更大群体中的组的组成。（注：需要安装 pywaffle 库）

   ![]()
  Code（代码）:[Waffle Chart.py]()
### 5.2 Pie Chart （饼图）

  饼图是显示组成的经典方式。 然而，现在通常不建议使用它，因为馅饼部分的面积有时会变得误导。 因此，如果您要使用饼图，强烈建议明确记下饼图每个部分的百分比或数字。
  
  ![]()
  Code（代码）:[Pie Chart.py]()
### 5.3 Treemap （树形图）

树形图类似于饼图，它可以更好地完成工作而不会误导每个组的贡献。（注：需要安装 squarify 库）

![]()
  Code（代码）:[Treemap.py]()
### 5.4 Bar Chart （条形图）

条形图是基于计数或任何给定指标可视化项目的经典方式。 在下面的图表中，我为每个项目使用了不同的颜色，但您通常可能希望为所有项目选择一种颜色，除非您按组对其进行着色。 颜色名称存储在下面代码中的all_colors中。 您可以通过在 plt.plot（）中设置颜色参数来更改条的颜色。

![]()
  Code（代码）:[Bar Chart.py]()
## 6. Change（变化）

### 6.1 Time Series Plott （时间序列图）

  时间序列图用于显示给定度量随时间变化的方式。 在这里，您可以看到 1949年 至 1969年间航空客运量的变化情况。
  
  ![]()
  Code（代码）:[Time Series Plott.py]()
### 6.2 Time Series with Peaks and Troughs Annotated （带波峰波谷标记的时序图）

  下面的时间序列绘制了所有峰值和低谷，并注释了所选特殊事件的发生。

![]()
  Code（代码）:[Time Series with Peaks and Troughs Annotated.py]()
### 6.3 Autocorrelation (ACF) and Partial Autocorrelation (PACF) Plot （自相关和部分自相关图）

  自相关图（ACF图）显示时间序列与其自身滞后的相关性。 每条垂直线（在自相关图上）表示系列与滞后0之间的滞后之间的相关性。图中的蓝色阴影区域是显着性水平。 那些位于蓝线之上的滞后是显着的滞后。那么如何解读呢？对于空乘旅客，我们看到多达14个滞后跨越蓝线，因此非常重要。 这意味着，14年前的航空旅客交通量对今天的交通状况有影响。PACF在另一方面显示了任何给定滞后（时间序列）与当前序列的自相关，但是删除了滞后的贡献。

![]()
  Code（代码）:[ACF and PACF Plot.py]()


### 6.4 Cross Correlation plot （交叉相关图）

交叉相关图显示了两个时间序列相互之间的滞后。

![]()
  Code（代码）:[Cross Correlation plot.py]()
### 6.5 Time Series Decomposition Plot （时间序列分解图）
 
  时间序列分解图显示时间序列分解为趋势，季节和残差分量。

![]()
  Code（代码）:[Time Series Decomposition Plot.py]()
### 6.6 Multiple Time Series （多个时间序列）

  您可以绘制多个时间序列，在同一图表上测量相同的值，如下所示。

![]()
  Code（代码）:[Multiple Time Series.py]()
### 6.7 Plotting with different scales using secondary Y axis （使用辅助 Y 轴来绘制不同范围的图形）

  如果要显示在同一时间点测量两个不同数量的两个时间序列，则可以在右侧的辅助Y轴上再绘制第二个系列。
  
  ![]()
  Code（代码）:[Plotting with different scales using secondary Y axis.py]()
### 6.8 Time Series with Error Bands （带有误差带的时间序列）

  如果您有一个时间序列数据集，每个时间点（日期/时间戳）有多个观测值，则可以构建带有误差带的时间序列。 您可以在下面看到一些基于每天不同时间订单的示例。 另一个关于45天持续到达的订单数量的例子。在该方法中，订单数量的平均值由白线表示。 并且计算95％置信区间并围绕均值绘制。
  
  ![]()
  Code（代码）:[Time Series with Error Bands.py]()
### 6.9 Stacked Area Chart （堆积面积图）

堆积面积图可以直观地显示多个时间序列的贡献程度，因此很容易相互比较。

![]()
  Code（代码）:[Stacked Area Chart.py]()
### 6.10 Area Chart UnStacked （未堆积的面积图）  

  未堆积面积图用于可视化两个或更多个系列相对于彼此的进度（起伏）。 在下面的图表中，您可以清楚地看到随着失业中位数持续时间的增加，个人储蓄率会下降。 未堆积面积图表很好地展示了这种现象。
  
 ![]()
  Code（代码）:[Area Chart UnStacked.py]()
### 6.11 Calendar Heat Map （日历热力图）

  与时间序列相比，日历地图是可视化基于时间的数据的备选和不太优选的选项。 虽然可以在视觉上吸引人，但数值并不十分明显。 然而，它可以很好地描绘极端值和假日效果。（注：需要安装 calmap 库）

![]()
  Code（代码）:[Calendar Heat Map.py]()
### 6.12 Seasonal Plot （季节图）

  季节图可用于比较上一季中同一天（年/月/周等）的时间序列。
  
  ![]()
  Code（代码）:[Seasonal Plot.py]()
## 7. Groups （分组）

### 7.1 Dendrogram （树状图）

  树形图基于给定的距离度量将相似的点组合在一起，并基于点的相似性将它们组织在树状链接中。
  
  ![]()
  Code（代码）:[Dendrogram.py]()
### 7.2 Cluster Plot （簇状图） 

  簇状图可用于划分属于同一群集的点。 下面是根据USArrests数据集将美国各州分为5组的代表性示例。 此图使用“谋杀”和“攻击”列作为X和Y轴。 或者，您可以将第一个到主要组件用作X轴和Y轴。
  
  ![]()
  Code（代码）:[Cluster Plot.py]()
  
 ### 7.3 Andrews Curve （安德鲁斯曲线） 
 
   安德鲁斯曲线有助于可视化是否存在基于给定分组的数字特征的固有分组。 如果要素（数据集中的列）无法区分组（cyl），那么这些线将不会很好地隔离，如下所示。
   
  ![]()
  Code（代码）:[Cluster Plot.py]()
 ### 7.4 Parallel Coordinates （平行坐标）
 
   平行坐标有助于可视化特征是否有助于有效地隔离组。 如果实现隔离，则该特征可能在预测该组时非常有用。
   
   ![]()
  Code（代码）:[Parallel Coordinates.py]()





  
  
  
  
  
  
  
