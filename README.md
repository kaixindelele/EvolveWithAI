## 独家信息-七日干碎美股9万亿-DeepSeek破圈时间线梳理
@[toc]
## 前言：
这个时间线梳理，我从2.1号就想做了，但工作量太大，很多数据源，比如外网的一些高热度帖子的获取和翻译，都需要从零构建工具链，才能拿到。
还有一些信息，比如一些外文帖子和原始的论文，必须要人工遍历一遍，才能确保这些信息理解是否有偏差。
最关键的是，信息太庞杂，我对于到底要写成一个什么样的帖子，一直难以确定。
现在Deep Research，R1+联网搜索虽然都比较强，但这种超长文本的输入输出的深度内容，我简单尝试了一下，仍然达不到我想要的标准。

但是，我自己的笔力也非常有限，也写不出一个非常精美的文章。

既然到这一步，先把想要写的东西写出来，期望能给大家提供一些有意的信息增量。

由于R1的破圈实属天时地利人和多方面因素叠加而成，所以我将尝试从多条线进行梳理。

1. 我比较兴奋的关键内容；
2. 几大搜索引擎的热度曲线整理；
3. 最关键性的几个事件-时间线梳理；
4. 我自己的信息渠道-时间线梳理；
5. 外网关于DeepSeek前七日、共110个破百万帖子的时间线梳理；
## 几大搜索引擎的热度曲线：

### 1. 微信指数：
>微信指数的数值和浏览量并不一致，微信指数每天更新昨日关键词指数，来自搜一搜、视频号、直播、公众号文章、网页及部分广告渠道的热度会对指数产生影响。

>由于原版的微信指数没有显示标注出数值，我特意将所有的数据重新绘制了一版。

![微信指数图](https://i-blog.csdnimg.cn/direct/5c1a4253554b4fc7974854ba67336f4c.png)

### 微信指数分析：
这个结果非常有趣，我估计这是全网第一个如此量化分析DeepSeek流量变化的帖子。

可以从图中看到，在1.20号R1发布之前，DeepSeek的微信指数并没有太高，相比于kimi，DS的热度要低一个量级。

- 北京时间2025年01月20日 20:10，[DeepSeek-R1 发布，性能对标 OpenAI o1 正式版](https://mp.weixin.qq.com/s/atKyfC5l-BaStje8-F3FGQ)在公众号正式发布；
- 北京时间2025年01月20日 20:23，Kimi的技术报告的第一次提交[Kimi k1.5：使用 LLM 扩展强化学习](https://github.com/MoonshotAI/Kimi-k1.5/commit/b6c2b5220d64521ef59292b0d56fb0ddb8078bb9)；
- 北京时间， 2025年01月20日 21:27，电信人工智能研究院的[TeleAI “复杂推理大模型”发布，评分超 o1-preview](https://mp.weixin.qq.com/s/duWvpGzknJ4qrbyZJUvc5w)，一时间热闹的跟过年一样。

相比而言，电信的只有一个通稿，没有看到详细的技术报告；Kimi发布了技术报告，但没有开源；而DS不仅开源，还完全开放商业使用，还发布了从1.5B到671B的全家族模型。

自此，命运的齿轮开始朝着不一样的方向，疯狂转动。

并且还有一个点值得关注，据新华社报道，1.20号下午，DS的梁文峰参加了一个重要的[座谈会](https://finance.eastmoney.com/a/202501203302513225.html)，并且CCTV13水印的截图在各大AI群聊内广泛传播。

在1.20发布的当天，kimi和DS的热度都有所提升，但DS的提升幅度更大一些，直到24号，形势出现了逆转，24-25号，DS的热度接近指数级提升，甚至于25号带动了chatgpt的热度（特朗普上台后，1.22号就已经发布了五千亿刀的星际之门计划，但并没有在中文社区带来明显的热度，不知道25号之后为啥chatgpt的热度又起来了）。更有趣的是，DS的热度一直没降，在2.05号开工日之后，热度更有所攀升。

### 2. 百度指数：
![百度指数](https://i-blog.csdnimg.cn/direct/9adb658694924e2baf785564d33e7bd6.png)
百度指数在1.20发布后，同样有缓慢上升，到1.26之后，开始猛增，等到2.05号开工，热度才有攀升。
同样的，可以看看谷歌的指数：
### 3. 谷歌指数：
![谷歌指数](https://i-blog.csdnimg.cn/direct/5ce74090d04c459b9f1c7101ce4ecf80.png)
从这两大搜索的数据可以看出来，在搜索端，DS的热度攀升，其实是稍微落后于微信指数的。

### 4. 推特热度：
> 这个热度的统计花了我最多的时间，我想知道到底是不是只有简中在讨论DS。由于我目前没法跑通对应的api，所以请了一位在日本的朋友帮我从网页上，半自动化的拿下了一些高热度帖子：从1.20到1.28号，浏览超过50万的所有帖子。由于推特的限制，25和28号的数据可能没有拿全，但大致趋势是符合整体热度的。
我们可以看下面两张图：


![推特热门贴趋势图](https://i-blog.csdnimg.cn/direct/863cff5b1d1948be984b92c33d04569e.png)
推特热门贴趋势图分析：

这张图里的信息非常多，我不仅标注了每日的浏览量，还有破百万帖子的数量，还有破千万贴子的数量。
除此之外，我还绘制了另外一张图：
![微信指数和推特热门贴流量对比曲线](https://i-blog.csdnimg.cn/direct/ce3db8befab14a3ea58d4b641aa261cb.png)
这张图可以看出来，其实这次DeepSeek的爆火，**国内外社交媒体的热度是接近同步的**。

>除了微信之外，我检索了B站的热门贴，发现高热度的视频也只有两百多万，并且数量并不多，所以这次我没有把B站当成是一个主要的破圈传播平台。然后我拿不到小红书和抖音的数据，所以就不管了。知乎我只能拿到整体的数据，二点几个亿的讨论度，也没有曲线，所以也没法用来对比。

>同样的，我们粗略检索了Kimi在推特上的热门贴，我统计到的不完全数据：1月份，从20号到31号，R1的推特总浏览量超过7.81亿，同期的kimi1.5的总热度在552W左右，1月23号发布的Doubao-1.5-pro的1月总热度在250w附近。


其实第一天，破百万的帖子就已经有四篇了，包括DS官方自己的一篇破千万的帖子（值得注意的是，这个浏览量是我在二月份统计的时候的累计播放，1.20当天的浏览量我已经无从获知了）。另外三篇都比较典型，一个是英伟达的推特大V，jim fan从学术创新角度、开源、民族角度赞扬了R1，一个是ollama在day0对R1的支持，一个是@alexocheema在DS发布后的2小时内，发了一个准备用M1本地部署满血版R1的帖子。从这四个博主的关系中可以看到，有一个共同关注的超大V，Marc Andreessen（尽管我不知道，是不是R1发布后，Marc才关注的他们），但从结果可以猜测，可能是因为这四个博主的某位，让Marc关注到了R1的发布。

1.25到1.27号，同样有一个猛增的流量曲线，我们事后诸葛亮可以找到，[上午1:43 · 2025年1月26日](https://x.com/omooretweets/status/1883209016261874010)，DeepSeek第一次登上苹果APP store的排行榜第十，这是我找到的最早的数据，从此一发不可收拾，新浪财经报道，北京时间1月26日15:45，DeepSeek在美区苹果App Store免费榜升至第六位，国内自媒体和专业媒体都开始报道这一关键性事件。

再然后就是1.26号晚上11.32，[冯骥的DeepSeek可能是国运级别成果](https://weibo.com/6603744955/5127209872004396)，他个人的经历和文笔，以及本身的话题性，将R1在微博社区彻底推向了高潮，27号占据好几个微博热搜。并且同时段，知乎的热榜几乎都是DeepSeek的话题:
![28号知乎的热榜截图-来自赵博](https://i-blog.csdnimg.cn/direct/7e50305e025e45279cfcf34f042c5c04.jpeg)
我查到最早的一个帖子是北京时间1.27号，凌晨2.33记录的reddit帖子：[DeepSeek登顶苹果APP store排行榜](https://www.reddit.com/r/singularity/comments/1iam94v/deepseek_officially_tops_the_appstore/)，这是一个标志性事件。

时间线发展到这一步，舆论以及积累了足够多的势能和共识，“源神”终于启动了。美股1月27日 09:30（ET）开盘，即北京时间1月27日 22:30，即将步入中国的除夕。并且，在1.27号上午6点，推特大V @KobeissiLetter就开始预测[纳斯达克会受到DeepSeek的登顶影响](https://x.com/KobeissiLetter/status/1883645592569593881)，七点，纳斯达克100期货下跌超过200点。

1.27号，最最重要的是英伟达，从下面的图中可以看到，英伟达的股票在开盘前，集合竞价阶段，就已经大跌了：
![1.27，英伟达股价大跌](https://i-blog.csdnimg.cn/direct/8db6d8500a514c54ab9d6d30d432d606.jpeg)
股价大跌的同时，中外舆论场同时沸腾，太多人等待这一时刻。推特非常多的人开始用英伟达股价大跌，来佐证DS的好，来diss美国AI公司的“技术懒惰”。
并且，值得注意的是，DS官方从1.20发布R1之后，几乎没有在任何场合做过直接的营销，只有少数几个辟谣，新年祝福和最近的官方教程。
但是，经过朋友[曾伊言](https://www.zhihu.com/people/ceng-yi-yan-8/posts)的提醒，我们可以发现，在**北京时间27号晚上11.46**，发布了一个性能不算太强的多模态模型[janus](https://github.com/deepseek-ai/Janus)。这个时间点把控的非常好，这个刚好在开盘后的很短时间，留出短暂的时间给 投资人验证消息真伪（但是不够时间去验证技术是否过硬），但又不留太长时间给 NVIDIA去应对。所以，DS的成本，会不会真有可能是牢黄买单了？

写到这里，终于点题了，从1.20到1.27，DS发布R1，经过一周时间，成功干碎奥特曼们的美国梦。


## 关键破圈事件分析：

第1次破圈的关键节点是，1月22日，微软CEO纳德拉在达沃斯一档访谈节目中表示，中国的Deepseek发展非常迅速，在推理时间上表现出色，计算效率极高。具体可以参考CNBC的[中国新 AI 模型 DeepSeek 如何威胁美国的主导地位](https://www.cnbc.com/2025/01/24/how-chinas-new-ai-model-deepseek-is-threatening-us-dominance.html)

2025 年 1 月 23 日星期四上午 9:25（美国东部标准时间）,CNBC 对 Scale AI 创始人兼首席执行官 Alexandr Wang 进行了采访，他的华裔身份，他的AI技术和商业背景，对DeepSeek-V3和R1性能的认可，声称DS拥有5万张H100显卡，他提出要加大对中国AI芯片制裁力度的观点，让这个采访视频得到了超多的争议。这个采访当天就在推特，公众号和知乎都引起了关注。

在此以后，下一个破圈的帖子就是1.24号，这位185万关注的Marc大佬的千万贴。这篇帖子正式把R1在推特社区中，从AI社群推向了大众。由于他本身对中国的态度并不算友好，这次如此正面的夸赞中国的AI，评论区引发了强烈的讨论，转发贴都有好几个超过百万的。
![1.27的时候，朋友就观察到了这个关键点。](https://i-blog.csdnimg.cn/direct/06fcce85f1524625a8e3e8b22b241b1d.png)
今天听到庄明浩老师的播客，[EP61 -期节目粉碎所有关于DeepSeek的谣言:训练成本600万、冲击英伟达、五万张H100、模型蒸馏、黑客攻击](https://www.xiaoyuzhoufm.com/episode/67a5867ad74435e4a396bf99)，Monica的张涛老师也提出同样的观点，认为Marc的帖子是R1破圈的关键事件：
![第一个破圈的千万贴](https://i-blog.csdnimg.cn/direct/c5f95d6b8cc645ad90c3e021941a77ce.png)




# 七日干碎美股9万亿-110个DeepSeek百万推特贴时间线梳理

## **2025/1/20**：正式发布，ollama支持本地部署，Jim fan夸赞技术过硬和开源
DeepSeek正式发布**DeepSeek R1**，展示了在性能、效率、**开源**以及与**OpenAI**产品对标等方面的技术亮点，迅速引起业界关注。当天的JimFan就开始夸赞技术创新和开源，ollama在day1就已经支持本地部署，有人期望能够用M1在本地部署满血版，在AI社群引起较大关注。

**12:29**：[ @alexocheema](https://x.com/alexocheema/status/1881348496172957922) - 浏览（140.4万）  
- 帖子内容：我将在家中运行**AGI**，或者尝试失败。**DeepSeek R1**在这些Mac上应该运行得很快。它们总共有896GB的**统一内存**，速度达3557GB/s。  
- 个人评价：本地部署，开源。

**12:29**：[ @deepseek_ai](https://x.com/deepseek_ai/status/1881318130334814301) - 浏览（**1.2千万**）  
- 帖子内容：**DeepSeek-R1**来了！性能与**OpenAI-o1**相当，**完全开源**的模型和技术报告，使用MIT许可证，允许**自由提炼与商业化**。网站和API现已上线，今日即可体验DeepThink。  
- 个人评价：性能强劲，对标O1，宽松开源，允许商业化。  

**14:48**：[ @DrJimFan](https://x.com/DrJimFan/status/1881343126210687089) - 浏览（136.6万）  
- 帖子内容：我们正处在一个非美公司延续**OpenAI**原始使命的时代——真正**开放**的前沿研究赋能所有人。**DeepSeek R1**不仅开源了一系列模型，还公开了全部训练秘密，展示了强化学习（**RL**）飞轮的持续增长。论文中强调：完全由RL驱动、使用硬编码奖励、模型思考时间随训练增加、自我反思与探索行为的涌现，以及使用GRPO代替PPO以降低内存使用。  
- 个人评价：与美国及OpenAI原先使命对比，突显了开放研究和新训练范式。  

**19:44**：[ @ollama](https://x.com/ollama/status/1881427522002506009) - 浏览（116.1万）  
- 帖子内容：**DeepSeek**第一代推理模型在数学、代码和推理任务上表现已达到与**OpenAI-o1**相当的水平。提供7B精简版，命令为“ollama run deepseek-r1:7b”，还有更多精简尺寸可选。  
- 个人评价：ollama推出开源可部署版本。  

---

## **2025/1/21**：小参数模型的本地部署和高性价比
这一日的帖子围绕**性价比**、家庭及低功耗设备部署、以及与**OpenAI**对标展开，进一步展示了**DeepSeek R1**在实际应用场景中的落地能力。  

**03:27**：[ @Saboo_Shubham_](https://x.com/Saboo_Shubham_/status/1881544014421447167) - 浏览（124.8万）  
- 帖子内容：**DeepSeek R1**完全**开源**，比**OpenAI-o1**便宜96.4%，但性能相当。对比价格：**OpenAI-o1**每百万输出令牌60刀，**DeepSeek R1** 仅为2.19刀。  
- 个人评价：对比o1，性价比高。  

**04:35**：[ @alexocheema](https://x.com/alexocheema/status/1881561143736664180) - 浏览（188.7万）  
- 帖子内容：家庭中的**AGI**。在7台M4 Pro Mac Mini和1台M4 Max MacBook Pro上运行**DeepSeek R1**，总统一体内存为496GB；采用@exolabs的分布式推理和4位量化，下一目标为fp8（需超过700GB）。  
- 个人评价：本地部署满血版方案。  

**08:30**：[ @nobody_qwert](https://x.com/nobody_qwert/status/1881620406710452535) - 浏览（100.4万）  
- 帖子内容：**ChatGPT o1 Pro** 与 **DeepSeek R1** 对比测试——要求实现内部带有红球的旋转三角形，左侧为**OpenAI**，右侧为**DeepSeek**。  
- 个人评价：与o1对比。  

**15:43**：[ @BrianRoemmele](https://x.com/BrianRoemmele/status/1882436734774043055) - 浏览（212.6万）  
- 帖子内容：各位，我们成功了！经过过夜测试，**OPEN SOURCE DeepSeek R1**已能在未联网的Raspberry Pi上达到每秒200个令牌；这意味着您可以在口袋中拥有一台比“OpenAI”更强大的前沿AI，一经测试完成，即提供Pi镜像，插入即用。  
- 个人评价：树莓派使用R1，本地开源部署。  

---

## **2025/1/22**：公开思维链引发好奇和自传播，端侧部署引起关注
当天讨论进一步聚焦于技术细节的探索、场景应用的扩展以及盈利模式的新疑问，尤其是作为第一个公开思维链的强推理模型，模型的思考引起了大家的关注和信任。并且，在手机等端侧设备的部署也吸引了很多人的讨论。

**00:00**：[ @skirano](https://x.com/skirano/status/1881854481304047656) - 浏览（130.3万）  
- 帖子内容：你可以仅提取**deepseek-reasoner**中的推理过程，将其发送给任意模型使用，就像将gpt-3.5 turbo变成绝对天才一样。  
- 个人评价：首个开源思考过程的模型，提取该思维过程助推其他模型性能。  

**07:37**：[ @ivanfioravanti](https://x.com/ivanfioravanti/status/1881969391547683031) - 浏览（210.3万）  
- 帖子内容：**DeepSeek R1**（右）在实现一个Python脚本，要求在正方形内使黄色弹跳球运动且处理碰撞检测和缓慢旋转方面，击败了**o1-pro**（左）。  
- 个人评价：拉踩OpenAI。  

**07:37**：[ @_akhaliq](https://x.com/_akhaliq/status/1882985442691437006) - 浏览（146.9万）  
- 帖子内容：使用**DeepSeek-R1**，编写p5.js脚本，使一个黄色弹跳球在一个菱形二十面体内运动，确保正确碰撞检测，并让菱形二十面体缓慢旋转。  
- 个人评价：转发，拉踩OpenAI。  

**15:11**：[ @minchoi](https://x.com/minchoi/status/1882083798650851839) - 浏览（120.5万）  
- 帖子内容：自**DeepSeek-R1**完全开源的推理模型发布仅48小时以来，人们的创造力不断迸发，分享了10个疯狂的应用实例。  
- 个人评价：对前2天应用的总结。  

**15:51**：[ @abacaj](https://x.com/abacaj/status/1882093734147301489) - 浏览（143.0万）  
- 帖子内容：**Deepseek**将如何实现营收？  
- 个人评价：盈利模式。  

**16:38**：[ @awnihannun](https://x.com/awnihannun/status/1882105560201617903) - 浏览（113.1万）  
- 帖子内容：精简后的**DeepSeek R1**（Qwen 1.5B）可在iPhone 16上通过MLX swift运行；展示了4位模型在设备上以近60令牌/秒的推理表现。  
- 个人评价：1.5B的苹果手机部署。  

--- 

## **2025/1/23**：DS的低成本对比下，美国AI公司开始慌了
这一日的帖子主要围绕**DeepSeek R1**的技术突破、极低成本和开源特性展开，同时也涉及中美科技竞争背景下的讨论，以DeepSeek的性价比，Diss OpenAI等美国AI公司。

**07:09**：[ @protosphinx](https://x.com/protosphinx/status/1882324677747781851) - 浏览（159.0万）  
- 帖子内容：**Deepseek** 是一个**副项目**。  
- 个人评价：其实也不算side project，他们还是很认真的。


**14:52**：[ @CodeByPoonam](https://x.com/CodeByPoonam/status/1882441160020676767) - 浏览（213.4万）  
- 帖子内容：自从 **Deepseek R1** 发布以来仅过去了 3 天，情况简直疯狂。剧透：**ChatGPT** 现在已经落后了。到目前为止有 13 个惊人的例子（不要错过第 5 个）。  
- 个人评价：总结过去3天的热门帖子，后面很多类似的帖子，不断的助长流量。


**15:43**：[ @RnaudBertrand](https://x.com/RnaudBertrand/status/1882600399657705725) - 浏览（172.9万）  
- 帖子内容：所有基准测试证实：**Deepseek** 的确与 **OpenAI** 的 **o1**（顶级产品）一样出色，但价格仅为其 3%。你可以选择为 API 付费，也可以使用它的**开源**版本（而 o1 做不到）。毫不夸张地说，这极大地改变了整个游戏规则。这不仅在人工智能方面，也是对美国试图阻止中国技术发展的错误尝试的强烈谴责，如果没有美国的努力，Deepseek 可能就不可能实现（俗话说，需要是发明之母）。
- 个人评价：强调DS的开源和极高性价比，并嘲讽美国的技术封锁。


**17:25**：[ @deedydas](https://x.com/deedydas/status/1882479771428544663) - 浏览（134.0万）  
- 帖子内容：中国刚发布一款**新模型**。字节跳动 **Doubao-1.5-pro** 在 **GPT 4o** 基准中表现相当，但价格便宜 50 倍；比 **DeepSeek** 便宜 5 倍，超出 **o1** 200 倍；支持 32k+256k上下文和稀疏 MoE 架构。人工智能的成本低得令人难以计量。  
- 个人评价：DS竟然被拿来与豆包比较，进一步突出低成本优势和火热程度。


**20:09**：[ @benhylak](https://x.com/benhylak/status/1882521144827531333) - 浏览（150.8万）  
- 帖子内容：**Deepseek R1** 正面临存在危机。  
- 个人评价：涉及一些敏感话题，推特很多人喜欢搞这些没意义的东西。

**20:21**：[ @sama](https://x.com/sama/status/1882478782059327666) - 浏览（886.7万）  
- 帖子内容：重大新闻：chatgpt 的免费套餐将获得 o3-mini！
（而且 plus 层将获得大量 o3-mini 使用量） 
- 个人评价：受到R1的冲击，奥特曼开始向免费用户提供o3-mini。这里用的是美国时间，所以会有点错乱。


**20:18**：[ @slow_developer](https://x.com/slow_developer/status/1882523264628731924) - 浏览（110.4万）  
- 帖子内容：事实——有趣的是，一家**中国**公司（**DeepSeek**）迫使**美国**公司（openAI）屈服，将其最新模型 **o3-mini** 免费提供给用户。同意吗？  
- 个人评价：认为R1的发布促使o3-mini免费提供。

---

## **2025/1/24**：开始讨论DS对美国AI公司和股市的冲击
当天的帖子从实际应用及技术复现到市场与经济层面（尤其是美国AI公司和英伟达公司）进行了全方位讨论。讨论焦点既有对**Deepseek**低成本、开源优势的赞誉，也涉及学术界采用、产业链冲击，以及一些有政治偏见的人开始破防。

**05:52**：[ @arithmoquine](https://x.com/arithmoquine/status/1882667756153368663) - 浏览（150.5万）  
- 帖子内容：在过去几个小时内，我向 **deepseek API** 发出了超过200,000个请求。没有速率限制，花费仅约50美分。感谢 **CCP**，**openai**绝对做不到。  
- 个人评价：强调DS的高性价比。

**05:57**：[ @AnjneyMidha](https://x.com/AnjneyMidha/status/1882669123492368586) - 浏览（307.8万）  
- 帖子内容：从斯坦福大学到麻省理工学院，**Deepseek R1** 凭借卓越性能几乎一夜间成为美国顶尖大学研究者的首选模型。  
- 个人评价：突出学术界对其性能的认可。

**09:19**：[ @Geiger_Capital](https://x.com/Geiger_Capital/status/1882844077324112193) - 浏览（211.2万）  
- 帖子内容：好的。**Deepseek** 和 **OpenAI** 一样出色甚至更好，价格仅为其3%……他们用2个月和不到600万美元构建，使用低性能芯片，而美国投入上百亿。**纳斯达克**会怎样？  
- 个人评价：虽然六百万不是完整的成本，但这个帖子算是引发，低成本研发对美股市场冲击的思考。

**09:19**：[ @yishan](https://x.com/yishan/status/1883143056393945289) - 浏览（160.2万）  
- 帖子内容：**R1**不是最终颠覆，而只是前奏。预测：3-6个月内，一家**美国**公司将复制这种成本节约的模式，随后**Deepseek**推出远超现有产品，才是真正颠覆。  
- 个人评价：我也很好奇，DS的这套低成本方案，对于拥有大量卡的美国AI公司来说，是糖还是砒霜？能不能让他们更充分的利用手里的卡？

**09:19**：[ @pmarca](https://x.com/pmarca/status/1882719769851474108) - 浏览（**1.1千万**）  
- 帖子内容：**Deepseek R1**是我见过最令人惊叹和印象深刻的突破之一——作为**开源**项目，它是对世界的深刻馈赠。  
- 个人评价：**破圈贴，极具影响力。**

**09:43**：[ @archiexzzz](https://x.com/archiexzzz/status/1882725829777740169) - 浏览（105.5万）  
- 帖子内容：深度搜索工程师  （贴了一张DS研发成员的图片）
- 个人评价：表达对中国工程师的认可？

**11:19**：[ @wzihanw](https://x.com/wzihanw/status/1882825861965152658) - 浏览（100.1万）  
- 帖子内容：**DEEPSEEK** 现在是**全球第一**。从未如此自豪工作于此，团队充满抱负、毅力、诚信和远见——这只是开始。  
- 个人评价：一个前DS员工对公司氛围的描述。


**12:17**：[ @katewillett](https://x.com/katewillett/status/1883038147912880588) - 浏览（322.4万）  
- 帖子内容：**中国**在这之后一天发布**Deepseek**，真是太搞笑了。  
- 个人评价：20发布的R1让22号的星际之门计划，显得有点小丑。


**13:31**：[ @TheShortBear](https://x.com/TheShortBear/status/1882783200998498542) - 浏览（155.3万）  
- 帖子内容：**DeepSeek**似乎在最大公司中引发恐慌，投资者需警惕。成本：2,048个Nvidia H800 GPU（\$40-50million）与训练成本（\$5million）。若击败**OpenAI**成本仅\$5500万，说明行业商品化速度超预期。  
- 个人评价：评论区讨论低成本对市场和GPU需求的冲击。

**16:15**：[ @kimmonismus](https://x.com/kimmonismus/status/1882824571281436713) - 浏览（531.8万）  
- 帖子内容：亿万富翁及Scale AI CEO Alexandr Wang：**DeepSeek** 拥有约50,000台 **NVIDIA H100**，但因**美国**出口管制无法讨论。  
- 个人评价：小黄毛的CNBC访谈，算是另外一个破圈事件。他说DS有5万张H100，评论区，马斯克说：明显的。但看张涛老师的说法，卡估计不少，但大概率不是H100。以及评论区很多人会阴阳怪气，小黄毛一个华裔，说这种话，并不能取信于美国人。


**17:14**：[ @jiayi_pirate](https://x.com/jiayi_pirate/status/1882839370505621655) - 浏览（158.2万）  
- 帖子内容：我们在 CountDown 游戏中复现了**DeepSeek R1-Zero**，运行良好。通过**强化学习**，3B基础语言模型自主发展了自我验证与搜索能力。只需不到30美元即可体验。  
- 个人评价：首次低成本复现R1-Zero，真卷啊，这个工作应该也是上了中文三大会。


**18:35**：[ @nealkhosla](https://x.com/nealkhosla/status/1882859736737194183) - 浏览（435.5万）  
- 帖子内容：**deepseek** 是一种**中国**心理战和经济战，旨在让**美国**的人工智能无利可图。他们虚构低成本以低价抢占市场，损害美国竞争力，不要上当。  
- 个人评价：一个对中国充满偏见的人。尽管评论区批评他的时候，他也承认DS模型性能好。


**18:39**：[ @A7mad_x07](https://x.com/A7mad_x07/status/1882860911104229515) - 浏览（521.1万）  
- 帖子内容：一种名为 **DeepSeek** 的**人工智能**产品由**中国**公司发布，引起巨大轰动和恐慌。体验后，我建议删除 **ChatGPT**，因其是一个强大、免费且**开源**的竞争者。  
- 个人评价：中东老哥对DS的开源表示兴奋。


**18:57**：[ @avichal](https://x.com/avichal/status/1882865234765058403) - 浏览（257.3万）  
- 帖子内容：更可能的情况是：1 - 一小组**DeepSeek**工程师作为副业击败全球顶尖研究人员；2 - **中国**政府拥有10万GPU，并发布600万美元成本的**开源模型**作为心理战。  
- 个人评价：又开始了，他们也开始阴谋论了。

**20:02**：[ @wongmjane](https://x.com/wongmjane/status/1882881778974937524) - 浏览（280.4万）  
- 帖子内容：**DeepSeek** 在提到特殊人名时会实时审查自己的回应。  
- 个人评价：这类帖子的热度相当高。

**20:39**：[ @itsPaulAi](https://x.com/itsPaulAi/status/1882891087754506522) - 浏览（187.1万）  
- 帖子内容：无需支付 \$200 使用 Operator。可创建一个使用网页浏览器的代理，无需编码。将 **DeepSeek R1** 与免费的**开源**浏览器代理结合即可。  
- 个人评价：用R1可以实现200刀的OpenAI operator类似的功能。


**21:26**：[ @MajestyRia](https://x.com/MajestyRia/status/1883211808238080011) - 浏览（640.0万）  
- 帖子内容：美国的科技兄弟忙得不可开交，因为一家来自**中国**的公司推出了新 **AI 模型**—**DeepSeek**，性能更优、更高效，研发成本仅600万美元，而美国则花费数十亿，且已**开源**。  
- 个人评价：diss美国公司，赞美开源和中国模式。


**21:49**：[ @Schuldensuehner](https://x.com/Schuldensuehner/status/1882908672952582477) - 浏览（454.8万）  
- 帖子内容：中国的**DeepSeek**可能对**美国股市**构成最大威胁，因为其以极低成本构建了突破性**人工智能**模型，且未使用尖端芯片，质疑数千亿资本的效用。  
- 个人评价：引用CNBC报道，讨论股市影响。

---

## **2025/1/25**：开始有更多的技术探讨和成本探讨，开始有人讨论对NV的冲击
当天的讨论进一步拓展至市场经济、产业链风险以及对未来生态的深远影响。从团队实力、开源精神、平台审查到对**NVIDIA**及其他科技巨头的影响，各角度观点纷呈，形成了对**DeepSeek**全方位的解读。

**00:20**：[ @Andr3jH](https://x.com/Andr3jH/status/1882946631668322620) - 浏览（119.8万）  
- 帖子内容：**OpenAI**工程师在浏览 **DeepSeek** 网站“我们的团队”时，认出了前女友。  
- 个人评价：内容略显抽象，我没看懂。



**00:36**：[ @amasad](https://x.com/amasad/status/1882950653666074761) - 浏览（253.9万）  
- 帖子内容：关于**DeepSeek**的讨论太多了。他们不仅推出了出色模型，还引入了突破性训练方法（**R1 Zero**）并已开始复现。即便成本有疑问，他们为世界带来了这份**伟大礼物**。  
- 个人评价：对成本有所质疑，但总体赞赏开源贡献。



**05:26**：[ @natfriedman](https://x.com/natfriedman/status/1883023712485839204) - 浏览（120.1万）  
- 帖子内容：**deepseek**团队显然非常出色。**中国**拥有众多优秀工程师。其他的都应付不过来。抱歉。
- 个人评价：夸赞DS的团队优秀，但其他的不太好理解。


**13:05**：[ @Dorialexander](https://x.com/Dorialexander/status/1883139251094814721) - 浏览（150.1万）  
- 帖子内容：**DeepSeek**情况总结：他们不是小团队，而是领先前沿实验室（全职研究人员超100人）；非新手，始于2023，通过重新训练一只**llama**逐步崛起，过程记录于16篇论文中。  
- 个人评价：评论区说，只有在LLM领域，2023开始的团队，才能被称作为“不是新手”。并且这个博主后续的帖子，详细介绍了他们过去的研究成果，是一个懂行的。



**13:45**：[ @hamptonism](https://x.com/hamptonism/status/1883149286088819029) - 浏览（124.6万）  
- 帖子内容：> 成为电气工程学生，与优秀同学组队，从事量化交易……购买数千Nvidia GPU，创建**DeepSeek**作为一个**副项目**。  
- 个人评价：开始有人描述DS创始人的成长路径。



**14:02**：[ @RnaudBertrand](https://x.com/RnaudBertrand/status/1883153432502214819) - 浏览（103.3万）  
- 帖子内容：所有关于 **Deepseek** “审查”的帖子完全误解重点：它在 MIT 许可证下**开源**，任何人可下载、微调，甚至用来输出一些不好的信息；在中国托管的版本因审查有限制，但开源版无此限制。因此，**Deepseek**比**OpenAI**更开放。  
- 个人评价：强调开源版无审查特性。

**15:31**：[ @CodeByPoonam](https://x.com/CodeByPoonam/status/1883175938613207134) - 浏览（**1.3千万**）  
- 帖子内容：再见，**ChatGPT**。自**Deepseek R1**发布仅5天，世界已被其潜力震撼。13个惊人例子（不要错过第5个）。  
- 个人评价：又一总结帖，强调短短5天内的影响力。



**15:49**：[ @signulll](https://x.com/signulll/status/1883180479643267463) - 浏览（195.6万）  
- 帖子内容：我在本地运行**DeepSeek**（高端Mac Studio配置）几日，性能媲美**o1**或**Sonnet**，编码等任务免费，仿佛一次彻底的范式转变。  
- 个人评价：部署的是70B的R1。

**16:22**：[ @minchoi](https://x.com/minchoi/status/1883188761854669147) - 浏览（310.1万）  
- 帖子内容：**DeepSeek R1**仅5天前便引起网络热潮。人们难以置信其强大和“**智能**”，开启了全新可能性。10个惊人例子。  
- 个人评价：又是总结贴。


**18:05**：[ @kakashiii111](https://x.com/kakashiii111/status/1883214597999808530) - 浏览（149.1万）  
- 帖子内容：**DeepSeek**或将导致购买数千NVIDIA芯片的AI初创公司破产，迫使大量二手**NVIDIA** GPU涌入市场，影响数据中心及新订单，整个NVIDIA生态或将解体。  
- 个人评价：评论区开始有人分析DS对GPU市场的冲击。

**18:16**：[ @TheJackForge](https://x.com/TheJackForge/status/1883217483294986668) - 浏览（216.9万）  
- 帖子内容：“这是一个副项目。我称之为 **DeepSeek**。”  
- 个人评价：老图新发，再次引发关注。

**20:19**：[ @TheShortBear](https://x.com/TheShortBear/status/1883248287077278129) - 浏览（115.3万）  
- 帖子内容：AI泡沫破灭？若**DeepSeek**结果属实，**NVIDIA**可能陷入与泡沫后**Cisco**类似的境地。  
- 个人评价：开始有人探讨DS对AI产业泡沫的冲击，及AI领域后续风险，尝试将英伟达和思科的历史联系起来。整片帖子是AI写的，逻辑不是很清晰，但也有人看。

**21:01**：[ @FinanceLancelot](https://x.com/FinanceLancelot/status/1883384721448611850) - 浏览（321.8万）  
- 帖子内容：这将是疯狂的一周。一旦媒体得知**DeepSeek**计算量减少97%但超过**OpenAI**，他们将开始将**NVDA**与**Cisco**对比。  
- 个人评价：上面的一个AI帖子，引发的另一轮讨论，开始有人讨论DS的发布，投资媒体可能的反应及市场的影响。

---

## **2025/1/26**：DS苹果登榜，越来越多人讨论对美股的冲击

26号破百万的帖子非常多，讨论的内容也很杂。已经有人开始夸中国的教育模式好，中国的stem人才多（确实多，我前几天还搜了一下，我们每年超过500万的stem毕业生），越来越多人开始讨论DS对美国AI的冲击，对美股的冲击了。以及，也有人发现，R1的写作能力有了显著的优势。

**00:01**：[ @RealAlexJones](https://x.com/RealAlexJones/status/1883304229726790011) - 浏览（**206.5万**）  
- 帖子内容：**中国的DeepSeek重磅消息震撼特朗普5000亿美元的人工智能项目**  
- 个人评价：**Diss** 星際之門，强调DeepSeek的技术突破对美国AI项目的影响。  

**00:09**：[ @JundeMorsenWu](https://x.com/JundeMorsenWu/status/1883306180287836491) - 浏览（**134.0万**）  
- 帖子内容：介绍DeepSeek在**AI训练效率、技术突破**以及**自主推理**方面的创新。特别指出其通过**outcome reward RL**实现的自我进化和反思能力。  
- 个人评价：总结DeepSeek的技术贡献，强调**GPT > deepseek > gemini > llama**。  

**00:59**：[ @zerohedge](https://x.com/zerohedge/status/1883318929025884322) - 浏览（**354.7万**）  
- 帖子内容：DeepSeek **最好不是真的**，暗示这一技术的不可思议性。  
- 个人评价：对DeepSeek的震惊和难以置信表示疑虑。  

**04:18**：[ @alexandr_wang](https://x.com/alexandr_wang/status/1883368885640102092) - 浏览（**262.0万**）  
- 帖子内容：**DeepSeek是对美国的警示，但美国依然需要在创新上超越对手。**  
- 个人评价：将DeepSeek的突破与美国的创新挑战联系，讨论**芯片出口管制**的必要性。  

**05:21**：[ @FinanceLancelot](https://x.com/FinanceLancelot/status/1883566609664823436) - 浏览（**407.5万**）  
- 帖子内容：**DeepSeek是OpenAI和Nvidia未曾预见的黑天鹅事件**，尤其是在**成本大幅降低**的背景下。  
- 个人评价：强调DeepSeek以低成本获得的惊人效果，突显其潜在的市场影响。  

**06:00**：[ @ArmenAgha](https://x.com/ArmenAgha/status/1883394495922004355) - 浏览（**110.4万**）  
- 帖子内容：**DeepSeek的应对方式让业界震惊，但R1几乎没有得到足够的正面关注。**  
- 个人评价：呼吁大家关注技术本身，而不是阴谋论，指出**资本滥用**的现象。  

**07:29**：[ @BeijingDai](https://x.com/BeijingDai/status/1883417049810313498) - 浏览（**156.0万**）  
- 帖子内容：**DeepSeek研发团队的背景**，展示中国在**大学教育质量**上的优势，并指出其对美国的挑战。  
- 个人评价：强调中国在AI和STEM领域的**优势**，尤其是在人才培养方面。  

**08:18**：[ @Rixhabh__](https://x.com/Rixhabh__/status/1883429287816315039) - 浏览（**166.9万**）  
- 帖子内容：**DeepSeek发布五天后**，展示了其强大的能力并列举了**12个令人惊讶的例子**。  
- 个人评价：总结发布后DeepSeek的强大表现，展示技术能力。  

**12:55**：[ @JulianGoldieSEO](https://x.com/JulianGoldieSEO/status/1883499097933680660) - 浏览（**337.7万**）  
- 帖子内容：展示如何使用DeepSeek R1构建**AI营销内容工作室**，无需编程经验。  
- 个人评价：展示DeepSeek的应用潜力，尤其是在**内容营销**方面的优势。  

**13:56**：[ @matthewstoller](https://x.com/matthewstoller/status/1883514294941421658) - 浏览（**309.7万**）  
- 帖子内容：**DeepSeek迫使硅谷承认Lina Khan是正确的**，即便硅谷不愿承认。  
- 个人评价：点明**DeepSeek**的破圈效应，对美国AI产业带来的挑战。  

**14:18**：[ @MathiasChu](https://x.com/MathiasChu/status/1883519899131367470) - 浏览（**136.2万**）  
- 帖子内容：**DeepSeek替代ChatGPT**，并且**完全免费**，无论在深度思考还是搜索方面都表现出色。  
- 个人评价：Diss OpenAI的高额收费。

**14:52**：[ @STEFisDOPE](https://x.com/STEFisDOPE/status/1883528390759838097) - 浏览（**101.6万**）  
- 帖子内容：硅谷是一个骗局。 DeepSeek 吃掉 ChatGPT 等的午餐应该会让你大开眼界。 他们在没有预算的情况下超越了美国的人工智能巨头，而且天知道他们的计算能力落后了多少。 因为我知道你需要流行文化的参考，所以基本上发生了以下事情：
- 个人评价：夸赞DS的努力，并Diss OpenAI。

**15:20**：[ @heyshrutimishra](https://x.com/heyshrutimishra/status/1883535509236089099) - 浏览（**208.2万**）  
- 帖子内容：RIP ChatGPT？ **DeepSeek R1发布**，展示了**18个令人震惊的应用例子**。  
- 个人评价：过去六天的总结帖，已经有十八个使用案例了。 

**16:37**：[ @7Alsabe](https://x.com/7Alsabe/status/1883554814623359066) - 浏览（**107.3万**）  
- 帖子内容：**为什么要为ChatGPT付费**，当你有**DeepSeek**这种免费服务时。  
- 个人评价：赞美DS的免费和对OpenAI付费模式的Diss。

**17:15**：[ @MrSaa3d](https://x.com/MrSaa3d/status/1883564549724610938) - 浏览（**109.8万**）  
- 帖子内容：**DeepSeek超越了ChatGPT**，并且支持阿拉伯语，且完全免费。  
- 个人评价：中东的兄弟们对免费的DS表示开心，并且祝贺DeepSeek进入苹果热榜。 

**17:44**：[ @jasminewsun](https://x.com/jasminewsun/status/1883571678938337359) - 浏览（**207.9万**）  
- 帖子内容：**DeepSeek R1写作能力**超越了**ChatGPT、Claude**等，展示了更具创意和风格的内容生成。  
- 个人评价：R1的文笔远超其他模型。

**18:14**：[ @chamath](https://x.com/chamath/status/1883579259769462819) - 浏览（**228.7万**）  
- 帖子内容：**DeepSeek通过R1破解了AI圣杯**——利用纯强化学习和巧妙奖励函数，促使模型自主生成长链思维及自我纠错，其技术突破在于构建了基于规则的奖励系统。  
- 个人评价：一篇分析师[详细论证高效率训练的DS](https://youtubetranscriptoptimizer.com/blog/05_the_short_case_for_nvda)，对NV股价的冲击。

**18:44**：[ @stocktalkweekly](https://x.com/stocktalkweekly/status/1883586839812218889) - 浏览（**124.8万**）  
- 帖子内容：**独家视频：Sam Altman与OpenAI团队讨论DeepSeek**，展示了暴怒的对话场面。  
- 个人评价：以玩梗视频讽刺OpenAI，反映出DeepSeek发布后对美系团队心理冲击明显。

**19:06**：[ @JulianGoldieSEO](https://x.com/JulianGoldieSEO/status/1883592246840467813) - 浏览（**125.3万**）  
- 帖子内容：**“这真是太疯狂了……”** 展示了如何用DeepSeek R1构建自动生成整个营销活动的内容工作室，无需编程经验。  
- 个人评价：突出DeepSeek在新产品和内容营销领域的应用潜力。

**19:21**：[ @Sentdex](https://x.com/Sentdex/status/1883656161778696247) - 浏览（**136.2万**）  
- 帖子内容：**“我现在可以确认：家中就有AGI”**，用DeepSeek R1在CPU与RAM上本地运行，展现出每秒大约3.4个令牌的推理速度。  
- 个人评价：全参数量化版，DeepSeek-R1-Q6_K在家中台式机上部署.

**19:32**：[ @Saboo_Shubham_](https://x.com/Saboo_Shubham_/status/1883599007760744503) - 浏览（**155.2万**）  
- 帖子内容：继 DeepSeek R1 之后，中国又推出了新的 OpenAI o1 级模型，其性能超越了 Claude Sonnet 3.5 和 GPT-4o。了解 Kimi 1.5 - 具有先进的思路链推理和实时网络搜索的多模式模型。而且它是 100% 免费的，聊天次数不限。让我们来感受一下吧。  
- 个人评价：在DS火了之后，开始有人主动关注中国AI的产品进展了（如果这不是Kimi的软广的话）。

**20:16**：[ @mattturck](https://x.com/mattturck/status/1883609972602548406) - 浏览（**123.8万**）  
- 帖子内容：对比美国大厂投资规模——**微软800亿美元、Meta650亿美元**，而DeepSeek只用**550万美元**，突显出其超低成本的优势。  
- 个人评价：以数字对比突显DeepSeek在低成本高效训练方面对美系AI公司的冲击，尽管不能用单次模型训练的成本和整个的项目投入成本对比，但数字对比下，确实显得美国AI公司太费了。这也让Dario Amodei在28号不得不写一篇[帖子](https://darioamodei.com/on-deepseek-and-export-controls)，详细的解释Claude的训练成本，也就几千万美元，因为V3的训练晚一点，便宜一些也正常（尽管有点嘴硬）

**21:07**：[ @islxlli](https://x.com/islxlli/status/1883622755272397209) - 浏览（**545.6万**）  
- 帖子内容：**“再见 ChatGPT”**——发布仅5天，DeepSeek R1展示了13个令人震惊的例子，预示着AI应用规则的变革。  
- 个人评价：又是一个总结帖，进一步强调DeepSeek在短时间内引发的技术与场景应用热潮。

**21:31**：[ @snowmaker](https://x.com/snowmaker/status/1883628838070149244) - 浏览（**126.3万**）  
- 帖子内容：总结讨论DeepSeek训练效率提升45倍的原因，提到**8位计算、键值索引93%压缩、多标记预测、专家混合模型**理念。  
- 个人评价：仍然是讨论那篇分析贴。

**21:34**：[ @thexcapitalist](https://x.com/thexcapitalist/status/1883629729644724276) - 浏览（**123.9万**）  
- 帖子内容：展示各大公司的H100芯片采购数据。如果你认为他们无法在没有更多芯片的情况下开发出更好的人工智能，而一些中国工程师却作为副项目做到了这一点，那么你就太天真了。据报道，Deepseek的训练使用了超过200,000个H100芯片。即使Deepseek在使用更少芯片的情况下达到了与OpenAI相匹配的水平，这对芯片制造商并没有任何看跌的影响，恰恰相反，这对他们来说是极其看涨的。如果Deepseek真的仅凭几千个芯片达到了这个水平，你能想象用一百万个芯片能做到什么吗？关于Deepseek的消息，无论真假，对芯片制造商来说都是极其看涨的，尤其是对$NVDA。
- 个人评价：越传越离谱，都已经20万H100了，我都以为我看0的个数了。有理由怀疑这人大量持有NV的股票。

**22:16**：[ @pmarca](https://x.com/pmarca/status/1883640142591853011) - 浏览（**572.1万**）  
- 帖子内容：一句话总结**DeepSeek R1是AI的“斯普特尼克时刻”**，标志着技术发力已令西方尤其是美国陷入焦虑与恐慌。  
- 个人评价：Marc大V的第二篇关于DS的破圈贴，他认为R1是堪比前苏联发射卫星一样的关键性事件，这次彻底让西方，尤其是美国焦虑和恐慌。

**22:24**：[ @ChrisJBakke](https://x.com/ChrisJBakke/status/1883642313777512494) - 浏览（**244.6万**）  
- 帖子内容：我在美国国防部担任软件工程实习生。这个周末，我将我们的代码库和我所有的工作文档上传到了一个叫做 DeepSeek 的新应用程序。它在帮助我完成工作方面非常有用！ 
- 个人评价：配图是DeepSeek登顶苹果排行榜，有人开始玩梗。

**22:38**：[ @KobeissiLetter](https://x.com/KobeissiLetter/status/1883645592569593881) - 浏览（**283.4万**）  
- 帖子内容：**让我们理清楚这一点： DeepSeek在不到2个月的时间内以不到1000万美元的成本开发完成，现在在App Store上排名第一。 此外，它是使用过时的芯片和不到200人的小团队开发的。 与此同时，美国正在向人工智能领域投入5000亿美元。 纳斯达克怎么会没有问题呢？**
- 个人评价：DS已经荣登榜一，有人开始提到纳斯达克会受到冲击。

**23:10**：[ @KobeissiLetter](https://x.com/KobeissiLetter/status/1883653721776861331) - 浏览（**340.6万**）  
- 帖子内容：突发消息，**纳斯达克100期货下跌超过200点**，市场直接对DeepSeek发布作出反应。  
- 个人评价：果然，美股终于要受到DS的冲击了。

**23:12**：[ @TicTocTick](https://x.com/TicTocTick/status/1883654228738207910) - 浏览（**749.8万**）  
- 帖子内容：分享安装DeepSeek后的感受，称“**无需安装其它任何东西**，这就是人工智能泡沫的终结”。  
- 个人评价：由知名交易员发布，极力赞美DeepSeek的全能特性，预示行业洗牌。

**23:18**：[ @garrytan](https://x.com/garrytan/status/1883655771067744441) - 浏览（**116.7万**）  
- 帖子内容：DeepSeek 搜索在进行几次查询后仍然显得更加吸引人，因为看到其推理过程（即使是对其所知和可能不知道的内容表现得多么诚恳）大大增强了用户的信任感。
- 个人评价：强调DeepSeek在公开思维链应用中对用户体验的正面影响。

**23:24**：[ @TKL_Adam](https://x.com/TKL_Adam/status/1883657200851362018) - 浏览（**218.1万**）  
- 帖子内容：OpenAI成立于10年前，拥有4,500名员工，已筹集了66亿美元的资金。DeepSeek成立不到2年前，拥有200名员工，开发成本不到1,000万美元。这两家公司现在是如何成为竞争对手的？
- 个人评价：虽然数据不对，但总归是Diss了OpenAI。

**23:25**：[ @TicTocTick](https://x.com/TicTocTick/status/1883657583195734217) - 浏览（**242.4万**）  
- 帖子内容：DeepSeek，就像邻居花1000万买下最贵的房子，而下个月一个人以20万买下了隔壁一栋类似的房子。很少有人理解这意味着什么，但他们很快就会感受到。
- 个人评价：DS的低成本对美国AI的冲击。

**23:53**：[ @TrungTPhan](https://x.com/TrungTPhan/status/1883664559384477985) - 浏览（**156.9万**）  
- 帖子内容：详细梳理DeepSeek创始人梁文峰的背景、团队构成、技术创新（如新型训练方法、出口限制下的应变策略）以及开源贡献，引用FT报道说明其转型之路。  
- 个人评价：DS登顶后，开始有人介绍梁文峰的来时路~

---

## **2025/1/27**：DS荣登苹果榜一，干崩纳斯达克1.2万亿刀
当天关于**DeepSeek**的推特讨论集中在该模型对美国股市及科技格局的冲击、与传统AI公司的对比、技术突破和低成本优势的展现，同时也涉及到数据隐私和国际政治等争议话题。讨论中既有对**DeepSeek**影响美股、英伟达股价的担忧，也有对其开源策略及技术实现细节的深入解读，这些成为当日破圈讨论的关键节点。

**02:51**：[ @TrungTPhan](https://x.com/TrungTPhan/status/1883733264294396277) - 浏览（153.9万）  
- 帖子内容：半导体基金经理在X平台上看到关于**DeepSeek**的4个表情包后  
- 个人评价：**DS对美股的冲击**  
  
**03:50**：[ @ParikPatelCFA](https://x.com/ParikPatelCFA/status/1883724137811890269) - 浏览（284.7万）  
- 帖子内容：是的，这个 **DeepSeek** 绝对安全，完全没有偏见。  
- 个人评价：**又在拿一些敏感词测试**  
  
**06:08**：[ @alljon12](https://x.com/alljon12/status/1883758980864118818) - 浏览（194.3万）  
- 帖子内容：在日美的应用排名中名列前茅的**DeepSeek**（中国制造的AI应用）关于**钓鱼岛**的调查结果就是这样。  
- 个人评价：**日本人惊叹DS对钓鱼岛的回答**  
  
**10:42**：[ @AlanDaitch](https://x.com/AlanDaitch/status/1883827944705187869) - 浏览（367.3万）  
- 帖子内容：Nvidia：“购买我们的40万美金的GPU”  
  **DeepSeek**：“朋友，你现在用的显卡已经可以训练AI了”  
  一家中国公司如何刚刚破解了游戏规则，并正在冲击美国股市  
- 个人评价：**DS对美股的冲击**  
  
**10:56**：[ @TKL_Adam](https://x.com/TKL_Adam/status/1883831333467934850) - 浏览（200.9万）  
- 帖子内容：**DeepSeek** 现在已经抹去了美国股票市场上价值 **2万亿美元** 的市值。  

  最大的市场逆风往往在你最不期待的时候出现。  
- 个人评价：**DS对美股的冲击，2万亿美元的降幅**  
  
**12:31**：[ @ChrisCamillo](https://x.com/ChrisCamillo/status/1883855442943844727) - 浏览（119.6万）  
- 帖子内容：DeepSeek 的 **70亿美元** 对冲基金母公司是否在做空 **$NVDA**，并在决定开源其模型时考虑了这一点，同时强调其 **500万美元** 的训练成本？  
- 个人评价：**DS对美股的冲击，并且有人怀疑幻方在发布时做空了NV**  
  
**12:44**：[ @KobeissiLetter](https://x.com/KobeissiLetter/status/1883858652727271527) - 浏览（164.7万）  
- 帖子内容：**DeepSeek** 正在重创美国股票：  

  **纳斯达克 100期货** 下跌 **-1,000点**，预计将创下自2022年9月以来的最大跌幅。  

  **英伟达** 今天预计将抹去超过 **4000亿美元** 的市值，成为历史上单日损失最大的股票。  

  发生了什么？让我们来解释一下。  

  （一个讨论串）  
- 个人评价：**DS对美股和英伟达造成了冲击**  
  
**12:55**：[ @CoderUday](https://x.com/CoderUday/status/1883861506632335477) - 浏览（262.7万）  
- 帖子内容：中国和印度的人口各为 **14亿**。  

  中国工程师开发了 **deepseek_ai**、**tiktok**、**比亚迪** 等。  

  我们连一个便宜的推特克隆都做不出来……

  问题出在哪里呢？是我们愚蠢，还是中国人聪明？  
- 个人评价：**印度人开始反思，评论区很有意思**  
  
**12:57**：[ @MichaelAArouet](https://x.com/MichaelAArouet/status/1883861901442187670) - 浏览（163.8万）  
- 帖子内容：欧洲用户观看 **DeepSeek** 超越 **ChatGPT** 在 Apple App Store 的表现  
- 个人评价：**欧洲人看到DS超越GPT，复杂的心情**  
  
**13:03**：[ @cegadede](https://x.com/cegadede/status/1883863433684406620) - 浏览（103.2万）  
- 帖子内容：对于那些不理解中国**深度搜索（deepseek）** 模型发布所引发的冲击的人来说。  

  人工智能公司的价值基于两个因素：1）其**数据中心的规模**；2）人工智能模型的**训练程度**。  
- 个人评价：**由于DS的冲击，向读者解释DS的价值：数据规模和训练能力**  
  
**13:06**：[ @farzyness](https://x.com/farzyness/status/1883864107134431462) - 浏览（176.0万）  
- 帖子内容：华尔街因**Deepseek**抛售人工智能，显示出公众对人工智能的理解有多么有限。  
- 个人评价：**他认为华尔街不懂AI，所以才会抛售AI股票。**  
  
**13:37**：[ @nic__carter](https://x.com/nic__carter/status/1883871974168142205) - 浏览（214.8万）  
- 帖子内容：**Deepseek** 刚刚将 **AGI** 的时间表提前了 **5年**。因此，专注于健身吧。**知识工作**已经过时。**肌肉**才是唯一剩下的。  
- 个人评价：**笑死，AI对人类的冲击，但看到宇树人形机器人的话，估计这个建议也废了**
  
**13:52**：[ @gabrielhaines](https://x.com/gabrielhaines/status/1883875841643589658) - 浏览（115.7万）  
- 帖子内容：你是因为一个中国的聊天GPT而出售的吗？  
  **@deepseek_ai**  
- 个人评价：**DS对美股的冲击**  
  
**13:57**：[ @benshapiro](https://x.com/benshapiro/status/1883876890227900559) - 浏览（154.3万）  
- 帖子内容：**DeepSeek** 的惊喜是一个极好的提醒，表明我们的敌人是有动机且具有攻击性的，而我们的**技术优势**并不是理所当然的。  
- 个人评价：**DS让精美慌了**  
  
**14:01**：[ @_KarenHao](https://x.com/_KarenHao/status/1883877986656825503) - 浏览（227.8万）  
- 帖子内容：作为一名报道人工智能已有7年的记者，同时也关注中国科技，我认为从**DeepSeek**中可以得出的最大教训是，它揭示了当前主导的人工智能发展范式存在的巨大**裂痕**。这是一个长篇讨论。1/  
- 个人评价：**DS的成功，让美国记者开始反思美国AI公司的发展模式**  
  
**14:06**：[ @marketmaker7](https://x.com/marketmaker7/status/1883879337688272902) - 浏览（116.0万）  
- 帖子内容：xxx
- 个人评价：**DS让小日本破防了**  
  
**14:17**：[ @svpino](https://x.com/svpino/status/1883881919328497870) - 浏览（120.9万）  
- 帖子内容：**DeepSeek R1** 是目前最好的模型。它处于 **o1** 级别，但你可以免费使用它，而且速度更快。这是一个没有人预见到的巨大飞跃。难怪这么多人在网上发脾气，试图抹黑开发这个模型的中国学生。你现在可以在 Visual Studio Code 中使用 **DeepSeek**：  
  1. 安装 Qodo Gen AI 扩展  
  2. 从他们的模型列表中选择 **DeepSeek R1**  

  Qodo 团队在他们的服务器上托管 **DeepSeek**，因此你的任何数据都不会流向中国。我一直在使用 **DeepSeek** 开发俄罗斯方块游戏，这是迄今为止我见过的最令人印象深刻的模型。  
- 个人评价：**39万关注的大V诚恳推荐R1**  
  
**14:29**：[ @KobeissiLetter](https://x.com/KobeissiLetter/status/1883885014431191471) - 浏览（115.3万）  
- 帖子内容：如果**DeepSeek** supposedly 拥有 **50,000** 个 **Nvidia, $NVDA, H100** 芯片，那么为什么股票下跌了 **-13%**？  

  这对 **Nvidia** 来说应该是利好消息，更不用说出现下滑了。

  这里面似乎有些不对劲。  
- 个人评价：**有人质疑ScaleAI说DS拥有5万H100，这样无法解释NV股价下跌**  
  
**14:30**：[ @MyLordBebo](https://x.com/MyLordBebo/status/1883885299131875397) - 浏览（469.4万）  
- 帖子内容：OpenAI：  
  - **10岁**  
  - **4500名员工**  
  - 融资**66亿美元**  

  **DeepSeek**：  
  - 不到**2岁**  
  - **200名员工**  
  - 使用的资本少于**1000万美元**

  **DeepSeek**开发并开源了一个相等或更好的产品，并免费提供，这可能会摧毁**OpenAI**的商业模式。  
- 个人评价：**虽然数据不对，但是用来diss OpenAI**  
  
**14:43**：[ @gregisenberg](https://x.com/gregisenberg/status/1883888629442830408) - 浏览（123.2万）  
- 帖子内容：**DeepSeek** 刚刚证明了那些“毫无价值”的**GPT包装**初创公司实际上才是拥有真正**护城河**的公司。

  一周前，作为一家“GPT包装”初创公司的地位极低，但他们早早进入了唯一重要的游戏。

  当**DeepSeek**、**Meta**、**Anthropic** 和**Microsoft**在基准分数上争斗时，这些“包装”公司却在悄然构建唯一重要的护城河：用户界面的**忠诚度**。

  由于拥有大型语言模型（**LLM**）对国家安全和经济的重要性，下一款突破性模型总是距离我们只有两周的时间。**DeepSeek**今天发布，明天就会有其他公司推出更好的模型。

  但让数百万人将你的产品融入他们的**日常工作流程**——这才是真正的进入壁垒。**ChatGPT**之所以获胜，并不是因为它拥有最好的模型，而是因为它使用起来极其简单。我认为正是因为这一点，它才具有持久的生命力。

  这就是为什么我们曾经忽视的所有AI初创公司实际上都处于有利位置的原因。他们并不是在竞争模型性能——而是在竞争成为人类与AI互动的默认方式。

  前沿模型正在变成商品，而用户习惯却不是。当每个人都在痴迷于下一个架构突破时，真正的游戏是在界面层面进行的。护城河不在于模型——而在于成为人们在不假思索的情况下选择的工具。

  技术优势是暂时的，而**界面锁定**是永恒的。

  继续推出那些**包装**产品吧，我的朋友们。  
- 个人评价：**DS的开源提高了AI应用产品的竞争力**  
  
**14:48**：[ @HanthlPro](https://x.com/HanthlPro/status/1883889861154800076) - 浏览（192.7万）  
- 帖子内容：今日最受关注的消息

  全球最大的公司**NVIDIA**遭遇了剧烈下跌，至今股价已下滑**16%**（约损失**4500亿美元**）。

  原因是（中国）成功开发了一款来自初创公司**DeepSeek**的超强人工智能模型。

  令人惊讶的是，该模型具备所有**ChatGPT**的付费功能，但**完全免费**，并且不依赖于之前已被禁止出售给中国的**NVIDIA**先进处理器！  
- 个人评价：**DS对NV的股价冲击**  
  
**14:54**：[ @GavinSBaker](https://x.com/GavinSBaker/status/1883891311473782995) - 浏览（331.4万）  
- 帖子内容：1) **DeepSeek r1** 是真实的，但有重要的细微差别。最重要的是，r1 比 **o1** 便宜得多，推理效率更高，这并不是从 **600万美元** 的训练数字来看的。r1 每个 API 的使用成本比 o1 低 **93%**，可以在高端工作站本地运行，而且似乎没有达到任何速率限制，这太疯狂了。简单的数学运算是，在 **FP8** 中每 **1b** 个活动参数需要 **1GB** 的 RAM，因此 r1 需要 **37GB** 的 RAM。批处理大大降低了成本，更多的计算增加了令牌/秒，因此在云端推理仍然具有优势。还要注意的是，这里有真正的地缘政治动态在起作用，我认为这款应用在《**星际之门**》之后立即推出并非巧合。**RIP，5000亿美元**——我们几乎不认识你。

  真实的：1) 它是/曾经是相关 App Store 类别中下载量第一的应用。显然领先于 **ChatGPT**；这是 **Gemini** 和 **Claude** 都无法完成的。2) 从质量角度来看，它与 o1 相当，尽管落后于 o3。3) 存在真正的算法突破，导致其在训练和推理方面都更加高效。**FP8**、**MLA** 和**多令牌预测**方面的训练非常重要。4) 很容易验证 r1 训练运行仅花费 **600万美元**。虽然这确实是事实，但它也*极具*误导性。5) 甚至他们的硬件架构也是新颖的，我要指出的是，他们使用 **PCI-Express** 进行扩展。

  细微差别：1) 根据技术论文，600万美元不包括“与架构、算法和数据的先前研究和消融实验相关的成本”。 “除此之外，林肯夫人，演出怎么样？” 这意味着，如果一个实验室已经在先前的研究上花费了数亿美元，并且可以访问更大的集群，那么就有可能通过 600万美元的运行来训练 r1 质量模型。 **Deepseek** 显然拥有远不止 **2048 H800s**；他们之前的一篇论文提到了一个由 **10k A100s** 组成的集群。一个同样聪明的团队不可能只用600万美元启动一个**2000 GPU** 集群并从头开始训练 r1。Nvidia 大约20%的收入来自新加坡。尽管他们尽了最大努力，但20%的 Nvidia GPU 可能不在新加坡。2) 有很多提炼——也就是说，如果没有不受阻碍地访问 **GPT-4o** 和 **o1**，他们不太可能训练这个。正如@altcap昨天有人向我指出，限制获取先进 GPU 的渠道，却不阻止中国开发先进美国型号的能力，这有点可笑——这显然违背了出口限制的目的。既然可以**免费获得牛奶**，为什么还要买牛呢？  
- 个人评价：**关于R1成本和性能的一些解释，终于有明白人了**  
  
**14:58**：[ @aubreystrobel](https://x.com/aubreystrobel/status/1883892424516501753) - 浏览（213.5万）  
- 帖子内容：深度搜索这个，深度搜索那个。你不如去寻求与一个女人的**深层连接**。  
- 个人评价：**哈哈，太脏了**  
  
**15:01**：[ @lukedepulford](https://x.com/lukedepulford/status/1883893208150937802) - 浏览（385.3万）  
- 帖子内容：仅供参考，  
  **@deepseek_ai** 收集您的**IP地址**、**击键模式**、**设备信息**等，并将其存储在中国，在那里所有这些数据都可能受到国家的任意征用。

  来自他们自己的**隐私政策**：  
- 个人评价：**截取了DS的隐私协议，并声称可能会被中国利用，但实际上它开源了，本地部署就可以了**  


# 总结：
这篇帖子的周期和内容实在是太长太长了，虽然写的不够好，但我真的写不下去了。

先发出来吧，如果有对完整Excel感兴趣的朋友，欢迎其他朋友探讨这里面的数据和细节。

也欢迎对这篇帖子进行润色和修改，我会把这篇帖子的Markdown文件传到Github上，再发布时，请注明原作者：
```
原作者：
[知乎-强化学徒](https://www.zhihu.com/people/heda-he-28)
[公众号-和AI一起进化](https://mp.weixin.qq.com/s/JM3q8j8mlQ5jAlDBf5mGtA)
[Github-kaixindelele](https://github.com/kaixindelele)
```



