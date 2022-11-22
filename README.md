温度植被干旱指数TVDI(Temperature Vegetation Dryness Index)是一种基于光学与热红外遥感通道数据进行植被覆盖区域表层土壤水分反演的方法。
<!--more-->
## 1、原理
LST-NDVI特征空间[<sup>1</sup>](#refer-anchor-1)：
![TVDI](https://img-blog.csdnimg.cn/img_convert/f72ad880752043580320a9f846e28972.png)
温度植被干旱指数(TVDI)的计算方法为：  

$$TVDI = {LST - LST_{min} \over LST_{max} - LST_{min}}$$  

$$LST_{min} = {a + b \times NDVI}$$

$$LST_{max} = {c + d \times NDVI}$$  

其中$$a、b、c、d$$为干、湿边拟合系数
## 2、结果展示
LST-NDVI的散点图:  
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210224225022145.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzI2NjEwMjM5,size_16,color_FFFFFF,t_70#pic_center)  
TVDI展示：  
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210224225054877.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzI2NjEwMjM5,size_16,color_FFFFFF,t_70#pic_center)  
如果对您有用的话，别忘了给点个赞哦^_^ ！
## 3、参考文献
<div id="refer-anchor-1"></div>

- [1] [Du L, Song N, Liu K, et al. Comparison of Two Simulation Methods of the Temperature Vegetation Dryness Index (TVDI) for Drought Monitoring in Semi-Arid Regions of China[J]. Remote Sensing, 2017, 9(2): 177.](https://www.mdpi.com/181788)
