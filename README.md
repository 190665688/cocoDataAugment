# cocoDataAugment
用该文件可以实现以下功能:
用labelme工具打1张图片的标签,生成1.png和1.json
在终端中运行命令python a.py生成20张数据增强后的图片及其对应的json文件,包括翻转,加噪,模糊,加减曝光等图片
在终端中运行python labelme2COCO.py生成COCO格式数据集,可以进行mask-rcnn 和faster-rcnn 等的输入数据集
