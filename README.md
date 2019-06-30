# web_report
## 目录
- [策划档案和网站地图](#策划档案和网站地图)
- - [策划文档](#策划文档)
- - - [用户画像](#用户画像)
- - [网站地图](#网站地图)
- [图片使用](#图片使用)
- [架站文章](#架站文章)
- [设计](#设计)
- [云端网站管理](#云端网站管理)
- - [云端架站](#云端架站)
- - [网站安全监控](#网站安全监控)
- - [网站性能](#网站性能)
- - [网站备份](#网站备份)
- [站长工具](#站长工具)
- - [站长认证](#站长认证)
- - [SEO优化](#SEO优化)
- [用户研究](#用户研究)
- - [用户访谈](#用户访谈)
- - [A/B测试](#A/B测试)
- - [定制化](#定制化)
## 策划档案和网站地图
### 策划文档
- 该网站的内容主要是关于现在网络较流行的几款游戏的分析，目前已有《王者荣耀》、《地下城与勇士》、《英雄联盟》几款游戏的内容分析，目的在于通过这些分析，得出现在网络游戏的一个发展方向。文章内容的缺点在于部分数据缺失，收集量较大。
#### 用户画像
id | game |time | state | requirement
:--:|:--:|:--:|:--:|:--:
蓝叉|DNF|7年|已脱坑1年|对游戏本身失去了乐趣，想通过平台来发表自己对游戏本身的看法
我是小学ji|LOL|2年|未脱坑|享受游戏本身的团队配合机制，喜欢这种游戏模式，有时候需要有地方分享自己的游戏体验
### 网站地图
![image](https://github.com/WWWWp/web_report/blob/master/image/pic.jpg)
## 图片使用
- 除了架站教程，该网站的图片均来源于网络，并且在文章末尾有表明转载何处。
## 架站文章
- [教程 | 架站流程①：申请github education pack](http://wp115.me/2019/06/08/step1/)
- [教程 | 架站流程②：运用DigitalOcean申请IP地址](http://wp115.me/2019/06/08/step2/)
- [教程 | 架站流程③：用namecheap绑定域名](http://wp115.me/2019/06/08/step3/)
## 设计
- SiteOrigin
1. [页面布局采用SiteOrigin Post Carousel](http://wp115.me/page/)，轮播效果，方便查阅。
- Animate it!
1. [文章内容采用“淡入”效果](http://wp115.me/2019/06/27/dnf/)，方便读者阅读；
2. [文章图片以及段落采用“脉冲”效果](http://wp115.me/2019/06/26/game-king/)，提醒读者注意重点。
## 云端网站管理
### 云端架站
- 域名正常
![image](https://github.com/WWWWp/web_report/blob/master/image/web.jpg)
### 网站安全监控
- 使用Wordfence安全监控
![image](https://github.com/WWWWp/web_report/blob/master/image/wordfence%E7%9B%91%E6%8E%A7.jpg)
### 网站性能
- site27X4网站性能测试截图
![image](https://github.com/WWWWp/web_report/blob/master/image/xingneng.jpg)
### 网站备份
- 登录winSCP
![image](https://github.com/WWWWp/web_report/blob/master/image/php.jpg)
- wp-config本地截图&插件备份
![image](https://github.com/WWWWp/web_report/blob/master/image/php_download.jpg)
## 站长工具
### 站长认证
![image](https://github.com/WWWWp/web_report/blob/master/image/zhanzhang.jpg)
- 百度站长工具
![image](https://github.com/WWWWp/web_report/blob/master/image/baidu.jpg)
- bing站长工具
![image](https://github.com/WWWWp/web_report/blob/master/image/bing.jpg)
### SEO优化
#### 优化1：申请bing站长工具为例
- 申请bing站长工具
![image](https://github.com/WWWWp/web_SEO/blob/master/image/bing_03.jpg)
- 出现问题：网站在搜索引擎上被屏蔽
![image](https://github.com/WWWWp/web_SEO/blob/master/image/bing_01.jpg)
- 如何解决：在WordPress SEO仪表盘上修改,取消勾选【搜索引擎监视性】
![image](https://github.com/WWWWp/web_SEO/blob/master/image/bing_02.jpg)
#### 优化2：bing提交sitemap，索引量先上升后下降再上升
- 原因：可能是抓取错误导致索引量降低
![image](https://github.com/WWWWp/web_report/blob/master/image/bing_suoy.jpg)
#### 优化3：更改页面关键词，但索引量并没什么变化
- 原因：可能是更改时间较短，短时间内看不出效果；可能是关键词不够突出
![image](https://github.com/WWWWp/web_report/blob/master/image/SEO_key.jpg)

## 用户研究
- [录音文件](https://github.com/WWWWp/web_report/tree/master/record)
### 用户访谈
#### 问题设置
- 网站的颜色布局；
- 网站的页面布局；
- 文章排版是否需要改进；
#### 访谈结果
- 访谈人群选择中大南方在校生，涉及专业均为网络与新媒体。
- 颜色方面，该网站以黑色背景搭配白色字体，以及亮金色按钮，但100%的用户觉得**页面整体黑色，偏灰暗，让人看着不舒服。**
- 页面布局方面，80%的用户建议改善页面布局，其中用户Y建议**右侧小工具侧栏区域划分不明显，当文章内容文字内容较多时，易混淆（以首页为例），建议可用颜色区块划分。**
- 文章排版方面，大部分用户对**文字大小**提出了建议。
### A/B测试
#### A：“文章内容”页面不使用SiteOrigin布局排版
![image](https://github.com/WWWWp/web_report/blob/master/image/A.jpg)
#### B：“文章内容”页面使用SiteOrigin布局排版
![image](https://github.com/WWWWp/web_report/blob/master/image/B.jpg)
#### 测试结果
- 用户H测试的是A。内容布局**相对简单，没有特色。**
- 用户Y测试的是B。在A的基础上改进页面，添加SiteOrigin轮播效果，用户给出了**文章切换的交互按钮太小，希望可以调整样式，或选择其他轮播图小工具**的建议。
### 定制化
- 结合A/B测试结果，修改布局。**使用轮播，并且将内容放大。**
![image](https://github.com/WWWWp/web_report/blob/master/image/B_1.jpg)