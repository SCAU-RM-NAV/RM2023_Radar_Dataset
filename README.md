# RM2023_Radar_Dataset
该仓库为RM2023雷达站所用到的yolo神经网络训练数据集，包含车和装甲板（上交格式）。同时有yolov5 6.0的训练环境，可以在本地进行训练和测试

## 数据集下载
1. [car] 53796张，来自包含RM官方开源图，视觉开源站，云南大学开源，沈阳航天航空大学开源，西交利物浦大学开源，上海科技大学开源，南京理工大学开源，以及由我们自己录制的一部分区域赛和训练视频进行抽帧组成。由于百度云上传大小限制，所以images拆开了几部分上传，统一解压后放在一起就可以使用，labels的txt文件都在一个压缩文件中。

链接: https://pan.baidu.com/s/1K8HiVKt4fvO4VwdtXJ58BA 提取码: 4xe7

2. [armor]31001张，由大图通过car网络抠图形成。
images和labels都在一个压缩包中。

链接: https://pan.baidu.com/s/1iCPs39cXOXAP-eYByadIag 提取码: zvet

## 雷达站原生视频
链接：https://pan.quark.cn/s/be322b92ff16  提取码：RvqG

## 使用说明

1. yolov5 6.0是用来训练网络的

2. yolov5 7.0是用来导出onnx格式


## 特别鸣谢
感谢 RM视觉开源站，上海交通大学，四川大学，云南大学，沈阳航天航空大学，西交利物浦大学，上海科技大学，南京理工大学的众多开源资料和雷达站视频

