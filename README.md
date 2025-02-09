# Hollow 图片（视频）信息隐藏加解密软件 (Hollow Software for Picture Video Information Hiding Encryption and Decryption)

[![last-commit](https://img.shields.io/github/last-commit/HollowMan6/Hollow-Software-for-Picture-Video-Information-Hiding-Encryption-and-Decryption)](../../graphs/commit-activity)
[![release-date](https://img.shields.io/github/release-date/HollowMan6/Hollow-Software-for-Picture-Video-Information-Hiding-Encryption-and-Decryption)](../../releases)
![Python package](https://github.com/HollowMan6/Hollow-Software-for-Picture-Video-Information-Hiding-Encryption-and-Decryption/workflows/Python%20package/badge.svg)

[![Followers](https://img.shields.io/github/followers/HollowMan6?style=social)](https://github.com/HollowMan6?tab=followers)
[![watchers](https://img.shields.io/github/watchers/HollowMan6/Hollow-Software-for-Picture-Video-Information-Hiding-Encryption-and-Decryption?style=social)](../../watchers)
[![stars](https://img.shields.io/github/stars/HollowMan6/Hollow-Software-for-Picture-Video-Information-Hiding-Encryption-and-Decryption?style=social)](../../stargazers)
[![forks](https://img.shields.io/github/forks/HollowMan6/Hollow-Software-for-Picture-Video-Information-Hiding-Encryption-and-Decryption?style=social)](../../network/members)

[![Open Source Love](https://img.shields.io/badge/-%E2%9D%A4%20Open%20Source-Green?style=flat-square&logo=Github&logoColor=white&link=https://hollowman6.github.io/fund.html)](https://hollowman6.github.io/fund.html)
[![GPL Licence](https://img.shields.io/badge/license-GPL-blue)](https://opensource.org/licenses/GPL-3.0/)
[![Repo-Size](https://img.shields.io/github/repo-size/HollowMan6/Hollow-Software-for-Picture-Video-Information-Hiding-Encryption-and-Decryption.svg)](../../archive/master.zip)

[![Total alerts](https://img.shields.io/lgtm/alerts/g/HollowMan6/Hollow-Software-for-Picture-Video-Information-Hiding-Encryption-and-Decryption.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/HollowMan6/Hollow-Software-for-Picture-Video-Information-Hiding-Encryption-and-Decryption/alerts/)
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/HollowMan6/Hollow-Software-for-Picture-Video-Information-Hiding-Encryption-and-Decryption.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/HollowMan6/Hollow-Software-for-Picture-Video-Information-Hiding-Encryption-and-Decryption/context:python)

(All the documents and software are in Chinese)

***此软件申请了软件著作权。***

***This software has applied for software copyright.***

[Python库依赖(Python library dependency)](../../network/dependencies)

本软件部分参考了[蔡銘峯](https://github.com/parkmftsai)的[Digital Watermarking](https://github.com/parkmftsai/digital_watermarking)项目，并在其基础上做出了大量改进。本软件适用于视频和图片的信息隐藏加解密，具体设计说明原理和使用方法请参考[此说明文档](计算机软件著作权登记申请/设计说明书.pdf)

In the software part, I refer to [digital watermarking](https://github.com/parkmftsai/digital_watermarking) project of [Cai MingFeng](https://github.com/parkmftsai), and make a lot of improvements on the basis of it. This software is applicable to the encryption and decryption of video and picture information hiding. Please refer to [this instruction document（in Chinese）](计算机软件著作权登记申请/设计说明书.pdf) for the specific design description and user instruction.

[这里](qt-design)为QT Designer的UI设计和资源文件，要将UI文件转化为Python脚本，请使用以下命令：

[Here](qt-design) is the UI design and resource file of QT designer. To convert the UI file to Python script, use the following command:

```Shell
pyuic5 -o *.py *.ui
```

要将QRC文件转化为Python脚本，请使用以下命令：

To convert a QRC file to a python script, use the following command:

```Shell
pyrcc5 -o *.py *.qrc
```

[这里](code)为源代码和程序中用到的图片资源文件。

[here](code) is the source code and the image resource file used in the program.

[这里](test)为测试样例，我使用了7张[图片](test/raw-pic)进行效果测试：

[here](test) as a test sample, I used 7 [pictures](test/raw-pic) to test the effect:
![](test/raw-pic/1.jpg)
![](test/raw-pic/2.jpg)
![](test/raw-pic/3.jpg)
![](test/raw-pic/4.jpg)
![](test/raw-pic/5.jpg)
![](test/raw-pic/6.jpg)
![](test/raw-pic/Vincent_van_Gogh_-_Almond_blossom_-_Google_Art_Project.jpg)

这是要隐藏的[图片](test/hidden-pic.jpg)：

This is the [picture](test/hidden-pic.jpg) to hide:
![](test/hidden-pic.jpg)

[此文件夹](test/de-encrypted-pic)保存了图片加密还原过程中的一系列产物。

[this folder](test/de-encrypted-pic) stores a series of products in the process of image encryption and restoration.

这是经过加密后的图片,解密的辅助还原信息保存在文件夹下的npy文件：

This is the encrypted picture. The decrypted secondary restore information is saved in the NPY file under the folder:
![](test/de-encrypted-pic/ec1.png)
![](test/de-encrypted-pic/ec2.png)
![](test/de-encrypted-pic/ec3.png)
![](test/de-encrypted-pic/ec4.png)
![](test/de-encrypted-pic/ec5.png)
![](test/de-encrypted-pic/ec6.png)
![](test/de-encrypted-pic/ecVincent_van_Gogh_-_Almond_blossom_-_Google_Art_Project.png)

这是解密出的隐藏信息：

This is the decrypted hidden information:
![](test/de-encrypted-pic/deec1.png)
![](test/de-encrypted-pic/deec2.png)
![](test/de-encrypted-pic/deec3.png)
![](test/de-encrypted-pic/deec4.png)
![](test/de-encrypted-pic/deec5.png)
![](test/de-encrypted-pic/deec6.png)
![](test/de-encrypted-pic/deecVincent_van_Gogh_-_Almond_blossom_-_Google_Art_Project.png)

# 软件著作权证书(Software Copyright Certificate in China)

![](计算机软件著作权登记证书.jpg)

# 软件著作权申请(Applying for Software Copyright in China)

[计算机软件著作权登记申请](计算机软件著作权登记申请)文件夹下存放了此软件的有关申请文档，仅供参考。具体申请步骤请查看[官网](http://www.ccopyright.com/index.php?optionid=1033)。

我的申请经历：

我使用邮寄的方式于2019年10月28日按照要求将黑白单面打印未装订的申请材料按顺序摆放通过EMS寄出，申请材料有：[计算机软件著作权登记申请表](计算机软件著作权登记申请/计算机软件著作权登记申请表.pdf)，[源代码](计算机软件著作权登记申请/源代码.pdf)，[设计说明书](计算机软件著作权登记申请/设计说明书.pdf)。

2019年10月29日北京的中国版权保护中心签收了快件，随后就开始了漫长的等待。

2019年11月20日，因为申请文档存在缺陷，收到补正通知书邮件，隔日我将[补正材料](计算机软件著作权登记申请/补正材料.pdf)寄出。

2019年12月11日，收到中国版权保护中心计算机软件著作权登记申请受理通知书邮件。

2020年1月26日，被送信员电话通知，收到邮寄过来的证书。

The folder [计算机软件著作权登记申请](计算机软件著作权登记申请) stores the relevant application documents of this software for reference only. Please refer to [Official Website](http://www.ccopyright.com/index.php?optionid=1033) for specific application steps.

My application experience:

On October 28, 2019, I mailed out the application materials that were printed in black and white, single-sided and unbound in order and sent by EMS. The application materials include: [application form for computer software copyright registration](计算机软件著作权登记申请/计算机软件著作权登记申请表.pdf), [source code](计算机软件著作权登记申请/源代码.pdf), [design Design Specification](计算机软件著作权登记申请/设计说明书.pdf).

On October 29, 2019, the China Copyright Protection Center in Beijing signed for the express, and then I began a long wait.

On November 20, 2019, due to the defects in the application documents, I received the correction notice email, and I sent [correction materials](计算机软件著作权登记申请/补正材料.pdf) the next day.

On December 11, 2019, an email was received for the computer software copyright registration application acceptance notice of China Copyright Protection Center.

On January 26, 2020, I received the software copyright certificate by phone calling.

# 申请处理时间线(Timeline of application)

* 微信公众号查询详细版(WeChat public account query)：
![](Record-Wechat.jpg)
* 网站查询版(Website query)：
![](Record-Website.png)