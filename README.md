# 项目名称：車行
# Product Requirement（产品说明文档）

|Title|Content|
|-|------|
|Target release(发布日期)|2019\11|
|Name|車行|
|Belong|张玮锋|
|Designer|张玮锋|

# 目录

# 产品定位
本产品适宜年龄16+岁的人使用，是一款用于扫描车型，帮助车主安全驾驶的APP

# 背景
* 车辆是现代交通的首要手段，车是生活的必需品，是一个家庭都想拥有的交通工具。而有很多人对于车都是非常热爱的，尤其是中年男子。他们喜欢看车，买车。而当爱车人士们在外观察到好看的车时，可能不知道车的型号，未免有一点遗憾，我们这款APP会解决这个问题，他可以通过拍照识别车型，并且顺便进行价值的估算，让爱车人士更加了解车型。
*  **对市场调查，尚未有搜索扫描车系的专业APP** 

# PART1 PRD价值主张设计
## 加值宣言
*  **对市场调查，尚未有搜索扫描车系的专业APP** 
本产品皆在通过使用人工智能的部分功能（车辆分析、）
* (核心)百度AI车型识别，拍下任意车照片并输入，输出照片车型对应名称、种类以及详细信息和价格资料。
* (核心)百度AI的车辆检测，通过拍照，在一张照片如果出现很多车，会在输出的结果栏提示选择哪一部车。
* 百度AI语音合成API：在介绍车中使用到，并且添加了语速以及声音可选项。 
* (辅佐)百度AI图像效果增强，图像去雾和图像清晰度增强
   
## 核心价值
# 核心价值与用户痛点
* 着眼与爱车人士和购车人士的基本需求，解决用户及时获得车辆介绍信息的问题。

## 目标
1. 拍下或上传车照片，提取车的信息，输出该车种类、名称及跳转相关的购买信息。

## 目标用户
* 在外的客户看到感兴趣的车型，无法得知信息。
* 想要购车客户通过车型搜索，车型扫描，得知信息需要购车

## 核心价值与用户痛点
|加值|痛点|
|-|------|
|车型识别功能可以通过拍摄车的照片得到车名称、型号|车类太多了，几乎没有人可以记下很多车型|
|车型识别功能可以通过拍摄动物照片得到车详细信息、购买的价格指标|对于想购车的人们，可以满足用户的购买喜好需求|
|车的详细信息较多，用户不想要看字，更想要用语言去听|减少用户的烦燥，|


## 需求列表与人工智能API加值
|用户案例|对应api|重要程度|
|-|------|------|
|用户想知道当前看到的车的名字信息、价格列表|车型识别|非常重要|
|用户拍下一张图片有很多车|车辆检测|非常重要|
|图片模糊不清楚|图像效果增强|次重要|
|用户不想看字|语音合成|次重要|

## 人工智能概率性与用户痛点
* 百度AI中的车型识别api:
识别近八千种车型，接口返回车辆名称，支持自定义返回结果数
支持获取识别结果的百科信息，接口返回百科词条URL、图片和描述，支持自定义返回词条数
综上可得出，用户在使用车型识别时可识别车型种类多，基本能满足客户识别车型的使用，识别车型基本能返回百科词条信息。但在拍摄和上传图片极为模糊时或网络断连和卡顿的情况下，会影响该功能的使用，但正常情况的手机拍摄和网络下不会影响使用，对用户基本影响不大。
* 百度AI中的车辆检测api:
在一张图的诸多的车辆中，可以扫描多种车辆，然后给用户作为筛选，选择自己想要识别的车辆，就不会造成识别API的误区
********
# 原型
## 交互及界面设计
![输入图片说明](https://images.gitee.com/uploads/images/2019/1211/120556_3f3157f1_1648159.png "信息设计.png")
![输入图片说明](https://images.gitee.com/uploads/images/2019/1211/110158_ec5660e2_1648159.png "界面设计.png")

## 信息设计
![输入图片说明](https://images.gitee.com/uploads/images/2019/1211/123213_4fa5b60b_1648159.png "信息设计1.png")
![市场](https://images.gitee.com/uploads/images/2019/1211/120036_4c2efb79_1648159.png "界面设计2.png")
![信息设计2](https://images.gitee.com/uploads/images/2019/1211/123040_ebfdc222_1648159.png "信息设计2.png")
## 原型文档
## 口头操作说明
********
# 产品使用关键的api接口与api的输出、输入展示
## 使用水平
## 使用比较分析
## 使用后风险报告
## 加分项


