# DEM数据

[toc]

## ALOS-2 PALSAR DEM数据 [12.5m]

**数据简介**

ALOS 12.5m DEM 数据，是使用ALOS（Advanced Land Observing Satellite）卫星相控阵型L波段合成孔径雷达（PALSAR）生产的高程数据。PALSAR传感器具有高分辨率、扫描式合成孔径雷达、极化三种观测模式。ALOS Dem高程数据水平及垂直精度可达12.5米。

ALOS是日本宇宙航空研究所（JAXA）的Advanced Land Observing Satellite-1（高级陆地观测卫星-1，ALOS）项目。ALOS卫星载有三个传感器：全色遥感立体测绘仪（PRISM），主要用于数字高程测绘；先进可见光与近红外辐射计－2（AVNIR－2），用于精确陆地观测；相控阵型L波段合成孔径雷达（PALSAR），用于全天时全天候陆地观测。卫星于2006年发射，于2011年突然失去电力供应，结束了使命。

**数据下载**

下载数据需要进入ASF Data Search：<https://search.asf.alaska.edu/#/>

下载方式可参考文章： [Alos PALSAR 12.5米免费DEM下载教程](https://blog.csdn.net/qq_27386899/article/details/127945443)

**注意事项**

- 下载的DEM有时候会有空缺值。需要自己使用GIS软件将这些空缺值填补上。

## Shuttle Radar Topography Mission (SRTM) [30m, 90m]

**数据简介**

Shuttle Radar Topography Mission（SRTM）于2000年2月11日至22日在奋进号航天飞机上飞行。美国国家航空航天局（NASA）和国家地理空间情报局（NGA）参加了一个获取雷达数据的国际项目，这些数据用于创建第一套近全球陆地高程。

SRTM任务期间使用的雷达实际上是在1994年两次奋进任务中开发和飞行的。

详细介绍：<https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-shuttle-radar-topography-mission-srtm-void>

**数据下载**

- 地理空间数据云：<https://www.gscloud.cn/search>
- USGS Earth Explorer：<https://earthexplorer.usgs.gov/>

**青藏高原SRTM DEM数据集（2012）**

青藏高原数据中心的处理好的青藏高原SRTM DEM数据集：
<https://data.tpdc.ac.cn/zh-hans/data/23e32e3e-8104-4798-b7a1-325df8fd1a95>

## Advanced Spaceborne Thermal Emission and Reflection Radiometer (ASTER) [30m]

**数据简介**

美国航天局和日本的联合行动是先进的星载热发射和反射辐射计（ASTER）的诞生。作为这个项目的一部分， ASTER Global Digital Elevation Model (GDEM) .

ASTER GDEM在全球拥有90米的分辨率和30米的分辨率。尽管它具有高分辨率和更大的覆盖范围（占地球的80％），但不满意的用户却常常在多云的地区表达其工件的问题。

ASTER GDEM采用立体对和数字图像相关方法。基于两幅不同角度的图像，采用立体对和摄影测量相结合的方法进行高程测量。然而，云量影响了ASTER的精度，而SRTM DEM的情况并非如此。因为 how passive and active sensors work 对DEM的质量影响最大。

改进的GDEM V3增加了额外的立体声对，提高了覆盖范围，减少了伪影的出现。改进的生产算法提高了空间分辨率，增加了水平和垂直精度。ASTER GDEM V3保留了GeoTIFF格式以及与V1和V2相同30米分辨率。

**数据下载**

- 地理空间数据云：<https://www.gscloud.cn/search>
- USGS Earth Explorer：<https://earthexplorer.usgs.gov/>

## USGS 30 ARC-second Global Elevation Data, GTOPO30

**数据简介**

GTOPO30是一种全球栅格数字高程模型(DEM)，提供水平网格间距为30弧秒(约1千米)的地形高程数据。GTOPO30源自地形信息的若干栅格和矢量来源。为了便于分发，GTOPO30被分成了多个分块。GTOPO30于1996年底完成，是在美国地质调查局地球资源观测和科学中心(EROS)工作人员的共同努力下历时三年开发的。

详细描述：
- <https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-global-30-arc-second-elevation-gtopo30>
- 论文：<https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/99EO00050>
- readme文件：<https://www.usgs.gov/media/files/gtopo30-readme>

**数据下载**

- USGS Earth Explorer：<https://earthexplorer.usgs.gov/>

**基于USGS30秒世界高程数据库的泛第三极地形数据集**

青藏高原数据中心的下载号的的泛第三极地区的GTOPO30数据集：
<https://data.tpdc.ac.cn/zh-hans/data/f2aab6ba-9b57-4d77-b64e-8422282316a8>

## 火星轨道器激光高度计（MOLA）

基于火星轨道器激光高度计（MOLA）仪器，可以查看火星崎岖的地形。例如，此链接中 <https://www.arcgis.com/home/webmap/viewer.html?webmap=71c5c7b5eac2453f990fe23a35940eef> 火星地形图的使用来自 MOLA 的数据。事实上，科学家们使用 MOLA 绘制了火星上的古老河流。那么在哪里可以下载火星的 MOLA DEM 呢？USGS 天体地质科学中心是火星的 DEM 数据中心。USGS 从火星重力场解决方案 GMM-2B 中发现了类面体上方的高程，总高程不确定性至少为 ±3m。
