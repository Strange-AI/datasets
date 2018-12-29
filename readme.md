# Datasets

人工智能智能时代，依旧无法离开数据。奇异AI的工作者们收集了大量的数据来源，甚至在官网开辟了一块领域让大家方便的快速进入各大数据集入口。我们从以下领域出发收集来包含18大领域，近300种各类数据集。但其中有许多还无法完全包含进来，如果你有好的数据集来源，再可用的情况下可以给我们send PR。

本数据集由**奇异人工智能**整理发布，转载请注明出处：http://strangeai.pro 国内最大的人工智能算法交易平台。商业合作请联系：`jintianiloveu`.

**Updates**

- 2018.12.29: 新增几个图像分割数据集
- 2018.11.26: 新录入中文语音识别数据集
- 2018.11.6: 新录入文本生成数据集






## 图像数据集(分类检测分割)

- [COCO](): coco图像分类，分割数据集；

- KITTI: 自动驾驶的包含目标检测，激光雷达3D检查的数据集， http://www.cvlibs.net/datasets/kitti/eval_object.php 由于kitti数据集每次下载都要申请，为了简单，在本repo的scripts中包含了download kitti的一键下载脚本，可以直接下载;

- VOC： 用于图片分类目标检测与风格的公开数据集，不过年代比较老了， http://host.robots.ox.ac.uk/pascal/VOC/;

- 维基百科公式图片与文本：可以用来训练公式自动识别的AI，http://www.svcl.ucsd.edu/projects/crossmodal/;

- Face/HeadsSegmentation: 精准的头部分割数据集：
    <div style="align: center">
    <img src="https://s1.ax1x.com/2018/11/27/FEL1MV.png" align="center" width="300"/>
    </div>

- Color names dataset: 直接从图片生成颜色的名字（为什么不生成颜色，还能提取主题色）：http://lear.inrialpes.fr/people/vandeweijer/data.html;


- [FASSEG](http://massimomauro.github.io/FASSEG-repository/): faces segmentation datasets. 精准的脸部分割数据集。

  <div style="align:center"><img src="https://raw.githubusercontent.com/massimomauro/FASSEG-dataset/master/other/V1V2_diff.png" width="300"/></div>


该部分数据集可以直接在奇异AI官网首页快速进入: http://strangeai.pro





## 单(多)目标跟踪数据集

- DAVIS: 视频分割跟踪数据集 https://davischallenge.org/， 可以用来训练视频分割与跟踪模型;

  
  <div style="align:center"><img src="https://davischallenge.org/images/teaser/2017/choreography.jpg" width="400"/></div>

- IMDB WIKI： 分男女的人脸标注数据集;

  ![](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/static/img/imdb-wiki-teaser.png)

- Central Pedestrian： 带有3D框标注的行人追踪数据集;

  <div style="align:center"><img src="https://s1.ax1x.com/2018/11/27/FELDsK.png" width="300"/></div>









## 语音数据集

- [LJ](https://keithito.com/LJ-Speech-Dataset/): 语音识别合成数据集，英文，女声，质量高，2.6G左右
-  OpenSLR: An Open-Source Mandarin Speech Corpus and A Speech Recognition Baseline. 一个开源的中文语音数据集，下载地址：http://www.openslr.org/33/

- [VCTK](http://homepages.inf.ed.ac.uk/jyamagis/page3/page58/page58.html): English multi speaker datasets to train a TTS with multi sounds.

- [Nancy](http://www.cstr.ed.ac.uk/projects/blizzard/2011/lessac_blizzard2011/): Nancy datasets for
  text to speech system, this dataset more clear then LJ I think.






## 图像生成
- [CASIA Online and Offline Chinese Handwriting Databases](http://www.nlpr.ia.ac.cn/databases/handwriting/Online_database.html): 中文手写字体生成


 <div style="align:center"><img src="http://www.nlpr.ia.ac.cn/databases/handwriting/source/image11.jpg" width="400"/></div>








## Others

1. 金融

   [美国劳工部统计局官方发布数据](http://dataju.cn/Dataju/web/datasetInstanceDetail/139)
   [沪深股票除权除息、配股增发全量数据，截止 2016.12.31](http://dataju.cn/Dataju/web/datasetInstanceDetail/344)
   [上证主板日线数据，截止 2017.05.05，原始价、前复权价、后复权价，1260支股票](http://dataju.cn/Dataju/web/datasetInstanceDetail/340)
   [深证主板日线数据，截止 2017.05.05，原始价、前复权价、后复权价，466支股票](http://dataju.cn/Dataju/web/datasetInstanceDetail/341)

   [深证中小板日线数据，截止 2017.05.05，原始价、前复权价、后复权价，852支股票](http://dataju.cn/Dataju/web/datasetInstanceDetail/342)

   [深证创业板日线数据，截止 2017.05.05，原始价、前复权价、后复权价，636支股票](http://dataju.cn/Dataju/web/datasetInstanceDetail/343)

   [上证A股日线数据，1999.12.09 至 2016.06.08，前复权，1095支股票](http://dataju.cn/Dataju/web/datasetInstanceDetail/37)


2. 交通

   [2013年纽约出租车行驶数据](http://dataju.cn/Dataju/web/datasetInstanceDetail/76)

   [2013年芝加哥出租车行驶数据](http://dataju.cn/Dataju/web/datasetInstanceDetail/323)

   [Udacity自动驾驶数据](http://dataju.cn/Dataju/web/datasetInstanceDetail/86)

3. 商业

   [Airbnb 开放的民宿信息和住客评论数据](http://dataju.cn/Dataju/web/datasetInstanceDetail/309)

4. 推荐系统

   [Netflix 电影评价数据](http://dataju.cn/Dataju/web/datasetInstanceDetail/32)

   [MovieLens 20m 电影推荐数据集](http://dataju.cn/Dataju/web/datasetInstanceDetail/116)



## Copyright

本仓库由奇异AI在互联网基础上添加整理，感谢其他人的贡献。我们希望更多人通过学习AI知识，紧跟时代潮流，实现人生理想。**奇异AI是国内最大的Paas算法交易平台，欢迎学习者或企业合作者与我们进行深入的算法合作**.

```
关注【奇异人工智能】公众号
获取更多更有趣的AI教程
微信公众号：奇异人工智能
奇异官网：http://strangeai.pro
```

