# data-crawling-filter


**运行环境**

+ Ubuntu 16.04
+ Python 3.7.9
+ Pytorch: 1.4.0
+ torchvision: 0.5.0
+ CUDA: 10.0

**依赖库**

+ umap-learn == 0.5.2
+ numpy <= 1.20
+ matplotlib == 3.3.4
+ opencv-python 4.5.1.48

依赖库安装

```pip install -r requirements.txt```

**任务报告**
+ **任务目标**
 爬取人脸图片

+ **数据源**
百度

+ **爬取方式**
[Image-Downloader](https://github.com/sczhengyabin/Image-Downloader) 

+ **数据观察结果**
  + 包含需要的图片
  + 同时包含人脸相关的非真实人脸图片
  + 包含与人脸完全不相关的图片
  
  ![need](https://github.com/LKatrina/data-crawling-filter/blob/main/img/需要的人脸.png)
  
+ **筛选目标**
  + 剔除一张图中包含很多人脸的图片
  + 剔除人脸模型的图片
  + 剔除虚拟及卡通人脸
  + 剔除有遮挡的人脸
  + 剔除采集设备中较小的人脸
  + 剔除与人脸毫不相关的图片
  [no_need](https://github.com/LKatrina/data-crawling-filter/blob/main/img/不需要的人脸.png)
  
  

