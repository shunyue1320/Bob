!> 注意：本文信息可能会过时，仅供参考，请以服务商最新官方文档为准。本文发布日期：2020 年 5 月 2 日。

?> 官方文档：https://cloud.baidu.com/doc/OCR/index.html

## 0. 收费模式

[查看详情](https://cloud.baidu.com/doc/OCR/s/9k3h7xuv6)

| 服务 | 免费额度 | 超出免费额度 | 并发请求数 |
| :-- | :-- | :-- | :-- |
| 通用文字识别（免费使用状态） | 每月1000次（认证后） 👍 | 直接禁止使用，不会扣费 | 2次/秒 |
| 通用文字识别（高精度版）（免费使用状态） | 每月1000次（认证后） 👍  | 直接禁止使用，不会扣费 | 2次/秒 |
| 通用文字识别（按量付费状态） | 每月1000次（认证后） 👍 | 0.0050元/次 | 10次/秒 |
| 通用文字识别（高精度版）（按量付费状态） | 每月1000次（认证后） 👍  | 0.030元/次 | 10次/秒 |

!> 2021年4月24日更新：如需使用**请尽快注册并实名认证**，百度官方在2021年5月24日开始将调低免费额度，具体看[这篇文章](blog/2021-04-26-baidu-ocr-news)

!> 2021年5月26日更新：如果你现在才准备注册百度，**上面显示的就是注册完并且身份认证之后的额度**

## 1. 注册登录

[点击此处跳转网页](https://cloud.baidu.com/)

![baidu_ocr_login](https://gitee.com/ripperhe/oss/raw/master/2020/0502/baidu_ocr_login.png)

## 2. 实名认证

实名认证之后会有更多的免费额度，不认证额度会少很多

[点击此处跳转网页](https://console.bce.baidu.com/qualify/#/qualify/index)

<img src="https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2021/0426/baidu_ocr_auth.png" alt="baidu_ocr_auth.png" width=1000 />

## 3. 创建新应用

登录成功后，点击左边「产品服务」

![baidu_ocr_app_1](https://gitee.com/ripperhe/oss/raw/master/2020/0502/baidu_ocr_app_1.png)

在展开的页面进入「全部产品」，搜索框中输入「文字识别」，点击搜索结果中的「文字识别」

![baidu_ocr_app_2](https://gitee.com/ripperhe/oss/raw/master/2020/0502/baidu_ocr_app_2.png)

进入「文字识别」页面后，点击「创建应用」

![baidu_ocr_app_3](https://gitee.com/ripperhe/oss/raw/master/2020/0502/baidu_ocr_app_3.png)

按照下图所示填写信息，点击立即创建

![baidu_ocr_app_4](https://gitee.com/ripperhe/oss/raw/master/2020/0502/baidu_ocr_app_4.png)

## 4. 领取资源包

无论是否实名认证，都需要在控制台领取免费资源才能继续正常使用。访问下面这个页面，点击底部的**「0元领取」**即可领取免费资源包：

[点击此处跳转网页](https://console.bce.baidu.com/ai/#/ai/ocr/overview/resource/getFree)

注意：
* **建议先完成实名认证，然后再去领资源包。**
    * 如果先领了资源包，之后来再完成实名认证，额度不会立即变更，而是会在一段时间后自动提升至实名认证后的额度（1000次/月）。
    * 如果很长时间之后也没有更新，可以提交工单给百度智能云的客服申请处理。
* **领取完后，需要等一段时间才能生效，页面上说 30 分钟内生效。**

更多的细节请查看 [这篇文章](blog/2021-06-23-baidu-ocr-error)。

## 5. 获取秘钥

!> 请妥善保管自己的秘钥，秘钥泄露可能会给你带来损失！

进入「文字识别」页面，进入「概览」，点击「管理应用」

![baidu_ocr_secret_1](https://gitee.com/ripperhe/oss/raw/master/2020/0502/baidu_ocr_secret_1.png)

下图所示即为需要的秘钥

![baidu_ocr_secret_2](https://gitee.com/ripperhe/oss/raw/master/2020/0502/baidu_ocr_secret_2.png)

## 6. 填写秘钥

在 Bob 的 偏好设置 > 服务 中，选中「文本识别」，点击 `+` 号，选中「百度智能云通用OCR」，然后将刚才获取到的秘钥填写到对应位置即可。

详细使用方法可查看 [服务](general/quickstart/service) 页面。