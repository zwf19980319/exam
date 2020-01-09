# 项目名称：車行
# Product Requirement（产品说明文档）

|Title|Content|
|-|------|
|Target release(发布日期)|2019\11|
|Name|車行|
|Belong|张玮锋|
|Designer|张玮锋|

# 目录
- [Part1 PRD价值主张设计](#Part1价值主张设计)
    - [加值宣言](#加值宣言)
    - [核心价值](#核心价值)
    - [目标](#目标客户)
    - [核心价值与用户痛点](#核心价值与用户痛点)
    - [人工智能概率性与用户痛点](#人工智能概率性与用户痛点)
    - [需求列表与人工智能API加值](#需求列表与人工智能API加值)
    - [框架图](#框架图)
- [Part2 原型](#Part2原型)
    - [交互及界面设计](#交互及界面设计)
    - [信息设计](#信息设计)
    - [原型文档](#原型文档)
- [Part3 API产品使用关键AI或机器学习之API的输出入展示](#Part3产品使用关键的api接口与api的输出、输入展示)
    - [API使用水平](#使用水平)
    - [API使用比较分析](#使用比较分析)
    - [API使用后风险报告](#使用后风险报告)
    - [API加分项](#加分项)
    - [API清单](#清单)
    



# 产品定位
本产品适宜年龄16+岁的人使用，是一款用于扫描车型，帮助人们识别车型的APP，人们可以用于扫描自己不懂得却感兴趣的车型，从而去了解价格、型号、购买区域。

# 背景
* 车辆是现代交通的首要手段，车是生活的必需品，是一个家庭都想拥有的交通工具。而有很多人对于车都是非常热爱的，尤其是中年男子。他们喜欢看车，买车。而当爱车人士们在外观察到好看的车时，可能不知道车的型号，未免有一点遗憾，我们这款APP会解决这个问题，他可以通过拍照识别车型，并且顺便进行价值的估算，让爱车人士更加了解车型。而且可以找到购买途径。
*  **对市场调查，尚未有搜索扫描车系的专业APP** 
* 只有售卖二手车的APP，但是只有购物功能，并没有扫描功能。

# Part1价值主张设计
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

## 产品框架图
![输入图片说明](https://images.gitee.com/uploads/images/2019/1215/205746_4a3aa272_1648159.png "框架图.png")
********


# Part2原型
* [原型](http://nfunm171013102.gitee.io/vehicle_prototype)
## 交互及界面设计
![输入图片说明](https://images.gitee.com/uploads/images/2019/1211/120556_3f3157f1_1648159.png "信息设计.png")

## 信息设计
![输入图片说明](https://images.gitee.com/uploads/images/2019/1211/123213_4fa5b60b_1648159.png "信息设计1.png")
![市场](https://images.gitee.com/uploads/images/2019/1211/120036_4c2efb79_1648159.png "界面设计2.png")
![信息设计2](https://images.gitee.com/uploads/images/2019/1211/123040_ebfdc222_1648159.png "信息设计2.png")
## 原型文档
* [原型](http://nfunm171013102.gitee.io/vehicle_prototype)
## 口头操作说明
********

# Part3产品使用关键的api接口与api的输出、输入展示
## 使用水平
* 百度车型识别API代码
``` python
# encoding:utf-8

import requests
import base64

'''
车型识别
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v1/car"
# 二进制方式打开图片文件
f = open('timg.jfif', 'rb')
img = base64.b64encode(f.read())

params = {"image":img,"top_num":5}
access_token = '[24.96bf3cd09ed0422fbf9744f27242e77c.2592000.1579533449.282335-18081637]'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
    
```
* 车型识别准确度（输出）
雪铁龙Survolt：准确度60%
```
{'log_id': 1693662610197928885, 'location_result': {'width': 1459.129516601562, 'top': 117.0717544555664, 'height': 796.3026733398438, 'left': 251.0002899169922}, 'result': [{'score': 0.5252830386161804, 'name': '雪铁龙Survolt', 'year': '2013'}, {'score': 0.09130119532346725, 'name': 'nanoFlowcellQUANTE', 'year': '2015'}, {'score': 0.02750954777002335, 'name': '标致VisionGranTurismo', 'year': '2015'}, {'score': 0.02313795313239098, 'name': '标致EX1', 'year': '2010'}, {'score': 0.01672195456922054, 'name': '丰田凯美瑞', 'year': '2018'}], 'color_result': '黑色'}
```

* 百度车辆检测API代码下载
```
# encoding:utf-8

import requests
import base64

'''
车辆检测
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v1/vehicle_detect"
# 二进制方式打开图片文件
f = open('多部车.jfif', 'rb')
img = base64.b64encode(f.read())

params = {"image":img}
access_token = '[24.3a8761586095cec2b117dcf2688200cb.2592000.1579534874.282335-18081637]'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())

```
* 百度车辆检测API输出结果
![输出车辆检测](https://images.gitee.com/uploads/images/2019/1222/230513_b5a27e10_1648159.png "屏幕截图.png")
* 百度语音合成API代码
``` python
import sys
import json

IS_PY3 = sys.version_info.major == 3
if IS_PY3:
    from urllib.request import urlopen
    from urllib.request import Request
    from urllib.error import URLError
    from urllib.parse import urlencode
    from urllib.parse import quote_plus
else:
    import urllib2
    from urllib import quote_plus
    from urllib2 import urlopen
    from urllib2 import Request
    from urllib2 import URLError
    from urllib import urlencode

API_KEY = 'zfNqZvwg7isWdaxGhrKLUoYb'
SECRET_KEY = '17ikGvyFdviAM53IvSkLBSbGSV638VGu'

TEXT = "Wu Ding, also known as Si Mu Wu Ding and Si Mu Wu Da Fang Ding, is a casting of the late Shang Dynasty (about the 14th century to the 11th century). It was unearthed in Wuguan "

# 发音人选择, 基础音库：0为度小美，1为度小宇，3为度逍遥，4为度丫丫，
# 精品音库：5为度小娇，103为度米朵，106为度博文，110为度小童，111为度小萌，默认为度小美 
PER = 4
# 语速，取值0-15，默认为5中语速
SPD = 5
# 音调，取值0-15，默认为5中语调
PIT = 5
# 音量，取值0-9，默认为5中音量
VOL = 5
# 下载的文件格式, 3：mp3(default) 4： pcm-16k 5： pcm-8k 6. wav
AUE = 3

FORMATS = {3: "mp3", 4: "pcm", 5: "pcm", 6: "wav"}
FORMAT = FORMATS[AUE]

CUID = "123456PYTHON"

TTS_URL = 'http://tsn.baidu.com/text2audio'


class DemoError(Exception):
    pass
"""  TOKEN start """

TOKEN_URL = 'http://openapi.baidu.com/oauth/2.0/token'
SCOPE = 'audio_tts_post'  # 有此scope表示有tts能力，没有请在网页里勾选


def fetch_token():
    print("fetch token begin")
    params = {'grant_type': 'client_credentials',
              'client_id': API_KEY,
              'client_secret': SECRET_KEY}
    post_data = urlencode(params)
    if (IS_PY3):
        post_data = post_data.encode('utf-8')
    req = Request(TOKEN_URL, post_data)
    try:
        f = urlopen(req, timeout=5)
        result_str = f.read()
    except URLError as err:
        print('token http response http code : ' + str(err.code))
        result_str = err.read()
    if (IS_PY3):
        result_str = result_str.decode()

    print(result_str)
    result = json.loads(result_str)
    print(result)
    if ('access_token' in result.keys() and 'scope' in result.keys()):
        if not SCOPE in result['scope'].split(' '):
            raise DemoError('scope is not correct')
        print('SUCCESS WITH TOKEN: %s ; EXPIRES IN SECONDS: %s' % (result['access_token'], result['expires_in']))
        return result['access_token']
    else:
        raise DemoError('MAYBE API_KEY or SECRET_KEY not correct: access_token or scope not found in token response')


"""  TOKEN end """

if __name__ == '__main__':
    token = fetch_token()
    tex = quote_plus(TEXT)  # 此处TEXT需要两次urlencode
    print(tex)
    params = {'tok': token, 'tex': tex, 'per': PER, 'spd': SPD, 'pit': PIT, 'vol': VOL, 'aue': AUE, 'cuid': CUID,
              'lan': 'zh', 'ctp': 1}  # lan ctp 固定参数

    data = urlencode(params)
    print('test on Web Browser' + TTS_URL + '?' + data)

    req = Request(TTS_URL, data.encode('utf-8'))
    has_error = False
    try:
        f = urlopen(req)
        result_str = f.read()

        headers = dict((name.lower(), value) for name, value in f.headers.items())

        has_error = ('content-type' not in headers.keys() or headers['content-type'].find('audio/') < 0)
    except  URLError as err:
        print('asr http response http code : ' + str(err.code))
        result_str = err.read()
        has_error = True

    save_file = "error.txt" if has_error else 'result.' + FORMAT
    with open(save_file, 'wb') as of:
        of.write(result_str)

    if has_error:
        if (IS_PY3):
            result_str = str(result_str, 'utf-8')
        print("tts api  error:" + result_str)

    print("result saved as :" + save_file)
 ```
   * 输出结果
   ![语音合成](https://images.gitee.com/uploads/images/2019/1222/155122_94ae0e12_1648159.png "屏幕截图.png")
    

## 使用比较分析
* 车型识别比较
    * [百度车型识别API](https://ai.baidu.com/ai-doc/VEHICLE/Ik3hb3lwt)
    ![车型价格](https://images.gitee.com/uploads/images/2019/1222/004456_20f3f437_1648159.png "车型识别价格百度AI.png")
    * [阿里车型识别API：](https://market.aliyun.com/products/57124001/cmapi032754.html?spm=5176.730005.productlist.d_cmapi032754.5afc3524lDp1C8&innerSource=search_%E8%BD%A6%E5%9E%8B%E8%AF%86%E5%88%AB#sku=yuncode2675400001)
    ![阿里云车型](https://images.gitee.com/uploads/images/2019/1222/005132_77cb822a_1648159.png "阿里云.png")
    
* 车辆检测比较
    * [百度车辆检测API](https://ai.baidu.com/ai-doc/VEHICLE/Ik3hb3lwt)
    ![前500侧](https://images.gitee.com/uploads/images/2019/1222/231244_1fa849e7_1648159.png "屏幕截图.png")
    ![输入图片说明](https://images.gitee.com/uploads/images/2019/1222/231328_fbb1283e_1648159.png "屏幕截图.png")
    
    * [阿里云车辆检测API]()
    
 * 语音合成比较
     * [百度语音合成API](https://ai.baidu.com/ai-doc/SPEECH/Nk38y8pjq)
     ![百度云 语音合成](https://images.gitee.com/uploads/images/2019/1222/232022_682239e4_1648159.png "屏幕截图.png")
     
     
     * [阿里云语音合成API](https://help.aliyun.com/document_detail/84881.html?spm=5176.12061040.1251723..1ed64779f0dI1F)
     ![阿里云语音合成](https://images.gitee.com/uploads/images/2019/1222/231852_029262aa_1648159.png "屏幕截图.png")
    
## 使用后风险报告
||百度车型识别|阿里云车型识别|腾讯云车型识别|
|-|------|------|-------|
|准确度|60%|80%|0%|
|价格|较低，每日体验500次|较高，只有100次免费|* |
|成熟度|一般|较为成熟，拥有多款结合为一体的车型识别|* |
|性价比|较为高|较高|* |
|优点|可以识别大量的车的种类，并且会返回识别结果的相似度|相似度较高80%|* |
|缺点|遇到车型种类多的图片，不能都准确识别出车型的种类|只能识别出是什么车，而不能给出多种结果相似度对比||

价格：百度>阿里云。百度车型识别API每天会提供500次免费调用额度。阿里云【图像识别】车型识别只有100次的免费调用额度，之后的收费都是在两者者中最贵的，性价比也是最低的。

||百度云语音合成|阿里云语音合成|
|-|------|------|
|准确度|100%|100%|
|价格|较低|较高|
|成熟度|一般|较为成熟，拥有多种声音，多种形式|
|性价比|较为高|较高|
|优点|支持中文、英文、中英文混读合成，提供基础音库和精品音库共9种音库供您选择，让您的应用拥有个性化的声音|有多种的不同声音选择，可以调节语速，声音大小、识别准确率高产品“能听、会说、懂你”式的智能人机交互体验。适用于多个应用场景中，包括智能问答、智能质检、法庭庭审实时记录、实时演讲字幕、访谈录音转写等场景，|
|缺点|只有普通话可以不接受粤语识别||


## 加分项
* [百度语音合成API代码片段](https://gitee.com/NFUNM171013102/car_app_prototype/blob/master/code/%E7%99%BE%E5%BA%A6%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90)
* [车辆识别API代码片段](https://gitee.com/NFUNM171013102/car_app_prototype/blob/master/code/%E8%BD%A6%E5%9E%8B%E8%AF%86%E5%88%AB.keep)
* [车辆检测API代码片段](https://gitee.com/NFUNM171013102/car_app_prototype/blob/master/code/%E8%BD%A6%E8%BE%86%E6%A3%80%E6%B5%8BAI)
* [原型](http://nfunm171013102.gitee.io/vehicle_prototype)

## 清单
* [百度语音合成API代码片段](https://gitee.com/NFUNM171013102/car_app_prototype/blob/master/code/%E7%99%BE%E5%BA%A6%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90)
* [车辆识别API代码片段](https://gitee.com/NFUNM171013102/car_app_prototype/blob/master/code/%E8%BD%A6%E5%9E%8B%E8%AF%86%E5%88%AB.keep)
* [车辆检测API代码片段](https://gitee.com/NFUNM171013102/car_app_prototype/blob/master/code/%E8%BD%A6%E8%BE%86%E6%A3%80%E6%B5%8BAI)
* [原型](http://nfunm171013102.gitee.io/vehicle_prototype)
#### 使用的api
* [百度语音合成API](https://ai.baidu.com/ai-doc/SPEECH/Nk38y8pjq)
* [百度车辆检测API](https://ai.baidu.com/ai-doc/VEHICLE/Ik3hb3lwt)
* [百度车型识别API](https://ai.baidu.com/ai-doc/VEHICLE/Ik3hb3lwt)









