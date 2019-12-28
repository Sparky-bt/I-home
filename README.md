# 项目名称：I-home

| 项目名称 | I-home |
| ------ | ------ | 
| 项目负责人 |黄舒婷 | 
| 项目状态 | 已完成|

### 价值主张写作练习
**一句话版本**：I-home基于用户对于自己家装的新定义，运用新技术形式帮助用户更快寻求自己需要的目标，把房子装扮成自己爱的样子。

**一分钟版本**:I-homeAPP可以了解您的兴趣爱好，为您推荐您感兴趣的家装风格，并为您定制逛家具店的路线，方便您更快寻找到目标家具。路线沿途经过的产品是系统根据用户喜欢的风格和需要购买的家具推荐家居装饰。app还有AR功能，只需要把您的家拍下来，到了家具店就可以在手机上看到家具放在家里的效果，方便选择心仪的家具。

### （一）加值宣言
I-home基于用户对于自己家装的新定义，运用新技术形式帮助用户更快寻求自己需要的目标，把房子装扮成自己爱的样子。

### （二）核心价值
I-homeAPP可以了解您的兴趣爱好，为您推荐您感兴趣的家装风格，并为您定制逛家具店的路线，方便您更快寻找到目标。app还有AR功能，只需要把您的家拍下来，到了家具店就可以在手机上看到家具放在家里的效果，方便选择心仪的家具。

### （三）用户痛点
**广泛性**
现今许多人对家居家装有了更多个性化需求，需要一个app来帮助他们更方便的实现自己的定制化需求。

**智能性**
只需要在新用户注册时花几分钟填写几个简单的问题，app可以立刻为您推荐您喜欢的装修风格，并且设计您逛家具店的路线，方便您快速且精准的找到目标；app的AR功能也能让您更方便的选择心仪的家具。

**便捷性**
因为家具普遍体积较大，用户若是买到自己不心仪的家具很可能因为退换麻烦而选择忍受自己并不喜欢的家具，而app的AR技术能让用户看到自己心仪的家具是否适合自己的家装风格而决定是否购买，方便了用户的同时，也让家居店少了退换货的烦恼。

### （四）APP功能设计（人工智能概率性）
- 新用户设置，了解用户基本信息，个人性格和兴趣爱好以便推荐相对应的家装风格。
- 用户输入想要购买的家具并且进入家具店。app生成路线告诉用户需要的家具在哪个区域，并且相对应的路线会设计路过可能与家具相配套的物品，给用户更多搭配家装的新奇想法。
- 用户遇到感兴趣的家具，打开手机app的AR功能，可以看到家具摆放在自己家里是怎样的效果，从而决定要不要购买。

### （五）产品使用场景

1、场景一：
一位时间很紧的用户使用此app并且输入了想要购买的家具，app在进入家居店时设计出直接到达目的地的路线，方便高效。
2、场景二：
一位不知道自己喜欢什么风格的用户，在初次注册app时回答的问题帮助她很快速的找到了自己喜欢的风格，并且在推荐里看到了自己喜欢的家装形式，按照推荐布置了自己的新家。
3、场景三：
一位很爱纠结的用户，在看到了两组同样喜爱的沙发后十分纠结要买哪一款，这时他打开了app的AR功能，将两组沙发都放进自己的虚拟家里看了看效果之后，不再纠结，果断地选择了第一组沙发，因为第二组沙发和他买的其他家具完全不搭。


### （六）产品原型
1、推荐页

![推荐页](https://github.com/Sparky-bt/I-home/blob/master/images/%E5%9B%BE%E7%89%875.png)

![推荐页](https://github.com/Sparky-bt/I-home/blob/master/images/%E5%9B%BE%E7%89%876.png)

2、路线页

![路线页](https://github.com/Sparky-bt/I-home/blob/master/images/%E5%9B%BE%E7%89%873.png)

![路线页](https://github.com/Sparky-bt/I-home/blob/master/images/%E5%9B%BE%E7%89%874.png)

3、AR页

![AR页](https://github.com/Sparky-bt/I-home/blob/master/images/%E5%9B%BE%E7%89%871.png)

![AR页](https://github.com/Sparky-bt/I-home/blob/master/images/%E5%9B%BE%E7%89%872.png)


### （七）产品流程图

![流程图](https://github.com/Sparky-bt/I-home/blob/master/images/%E6%B5%81%E7%A8%8B%E5%9B%BE.png)

### （八）口头操作说明
新用户注册APP时需要几分钟填写个人的兴趣爱好，喜欢的颜色等个性化问题，填完之后系统经过计算可以为用户推荐喜欢的家装风格。而用户在输入想要购买的家具时，系统会使用位置信息，规划直接到达目的的路线，省时省力，并且看到喜欢的家具还可以用AR功能看是否适合自己家。

### （九）API的使用

1、高德API——路径规划

- **价值主张**：路径规划API是一套以HTTP形式提供的步行、公交、驾车查询及行驶距离计算接口，返回JSON 或 XML格式的查询数据，用于实现路径规划功能的开发。

- **接口地址**：[高德API路径规划文档](https://lbs.amap.com/api/webservice/guide/api/direction)

- **请求方式**：GET

- **请求URL**：	https://restapi.amap.com/v3/direction/walking?parameters

- **代码示例**：

![路径api](https://github.com/Sparky-bt/I-home/blob/master/images/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92api01.png)

![路径api](https://github.com/Sparky-bt/I-home/blob/master/images/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92api02.png)

![路径api](https://github.com/Sparky-bt/I-home/blob/master/images/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92api03.png)

2、百度AR

- **适用场景**：AR技术的主要应用场景包括营销广告、教育培训、娱乐互动、商品展示、特效拍摄、美妆美颜、游戏互动、导航导览等。

- **接口地址**：[百度AR开发文档](https://ai.baidu.com/ai-doc/AR/lk3h7lyfx)

- **接入方式**：

![接入方式](https://github.com/Sparky-bt/I-home/blob/master/images/接入方式.png)


- **代码示例**：

![百度AR](https://github.com/Sparky-bt/I-home/blob/master/images/AR01.png)

![百度AR](https://github.com/Sparky-bt/I-home/blob/master/images/AR02.png)


### （十）需求列表与人工智能API加值
| 用户需求 | API接口 | 重要程度 |
| ------ | ------ | ------ |
| 用户需要节约逛家具店的时间成本，更快找到目标 | 路径规划API | 重要 |
| 用户需要使用AR技术看到家具摆放在自己家里的样子 | AR | 重要 |


### （十）API使用比较分析

| 平台 | 功能 | 使用原因 |
| ------ | ------ | ------ |
| 高德 | 路径规划 | 根据数据，三个地图平台的市场占有额分别是：百度29.5%、高德33.40%、腾讯12%。各自官方关于定位精度的说明分别是：百度：GPS=10M;WIFI=24M;基站=210M；高德：GPS+网路=25M;WIFI+网络+基站=29m；腾讯：GPS=20M;WIFI=30-180M;基站=150-800M。由市场占有额和定位精度综合因素考虑，使用高德API进行路径规划是最优选择。 |
| 百度 | AR | 百度AR的渠道优势是不仅拥有领先的AR技术，并且在用户辐射体量上也有着得天独厚的优势。目前，百度AR技术已经集成在手机百度、百度糯米等超级App上，并将业务扩展到如互动广告、游戏、教育、医疗、旅游等诸多领域。用户范围广，优势强，具体参照文章：[百度增强现实实验室成立，领先技术打造AR平台](https://ar.baidu.com/news25) |



### （十一）API使用风险评估

错误现象处理方法：

- 当路径规划没有出现用户的目标时，语音提示：“主人对不起，小爱又计算错误了，小爱已经把错误原因记下了”

- 当AR技术因网速不好难以加载时，提示：“哎哟~网速不好，小爱走丢了，已经上报给程序员哥哥啦！”

- 当推荐和用户喜好完全不符合的时候，提示：“对不起小主人，小爱计算错误了，您要不要再填一次兴趣表格，小爱重新算一次好么？”

### （十二）产品可行性
1、市面上的同类型产品较少，此app竞争力较强。
2、抓住了现今人们喜欢自我定制家装的需求，把握了用户的痛点。
3、AR技术能让用户买家具少踩雷，更方便省事的完成自己想要的家装风格。

### （十三）结果预期

上线初期，先通过对部分使用者的体验评价反馈进行不断迭代，再面向整个市场推出使用，到后期全面广泛应用，不断积攒用户。发展到一定阶段，app会接手广告业务获利，最终扎根市场，开启用户与企业双赢模式。

### （十四）完整产品原型

[I-HOME产品原型](http://nfunm030.gitee.io/i-home)
