# Design for Trust: An Exploration of the Chanllenges and Opportunities of Bitcoin Users
The Infrastructure of Trust

CHI 2017

## ABSTARCT
比特币很火，但是我们对人们使用比特币的动机和体验了解甚少。本文采访了马来西亚的20个比特币使用者，结果显示比特币更多的被用作投机性投资和财富储备。本文通过发现比特币主要的特点和对信任的影响，加强了HCI中的信任理论。本文提出了一些设计启示，包括双向交易的透明度，实质化信任的工具，支持不可逆转的交易的工具。

## INTRODUCTION
初步研究，采访了9个用户，得出了三个使用比特币的动机。
- 比特币在货币革命中的角色
- 用户的权利很大由于开放的反监管的科技
- 比特币的价值上涨

另一方面，比特币作为一个去中心化和伪匿名的平台，又对比特币用户提出了重要的信任挑战，比如非法使用和黑客攻击。所以，由于以上特点，我们认为区块链为信任的探索提供了一个独特的case study。这与大多数HCI的信任模型形成对比，那些模型是传统的中心化的、受监管的和非匿名的电子商务或电子支付系统。因此用这些模型来理论化比特币中用户的信任是值得研究的。

相关的HCI工作刚刚开始兴起，我们对比特币用户和他们的体验，**区块链的特征怎么影响信任**还了解的很少。**本文通过采访20个比特币用户他们使用比特币的动机和体验，他们对于信任相关的问题来解决这个gap。**
我们设计了以下问题：
- 用户早期采纳和使用比特币的动机是什么？人们怎么学习比特币和他们用比特币来干什么。
- 比特币的不同特征怎么影响信任的不同维度。
- 主要的信任问题是什么，人们怎么解决它们。

**本文的主要贡献是加强了HCI中的信任的理论阐述，并且延申到区块链这样的去中心化和匿名的系统。并且提出了三个用于支撑用户信任的设计启示。**

## RELATED WORK
信任的话题已经讨论的很多了，我们主要选择有关电子支付和电子商务的理论。

### Trust in HCI
HCI中主要有两个概念化信任的方向：
- 人与科技之间的信任
- 人与人之间的信任（通过科技交互）

关于人们对比特币技术的信任的研究正在兴起，（在他们自己的前一篇文章中[Exploring Trust in Bitcoin Technology: A Framework for HCI Research](https://dl.acm.org/citation.cfm?id=2838821)）提出了三个维度的信任：
- 技术（用户对比特币技术的信任）
- 社会（比特币中所有利益相关者之间的信任，矿工、用户、交易所、庄家）
- 制度（政府对比特币技术的信任）

两个流行的HCI信任模型是：
- the model of online trust
[On-line trust: concepts, evolving themes, a model](https://www.sciencedirect.com/science/article/pii/S1071581903000417)
阐述了三个信任因素包括用户对该技术感觉可不可靠、该技术的易用性和风险。（credibility、ease of use、 risk）
其中可靠性主要包括四个维度：
    1. honesty（好的意图，诚实的，无偏见的行为）
    2. expertise （专业的知识和能力）
    3. predictability （基于过去该技术的行为是一致的）
    4. reputation （基于过去的名声）

    这个模型被广泛用于电子商务电子银行网站的设计。但是它对于区块链的价值乏善可陈。


- the framework on mechanics of trust
[The mechanics of trust: A framework for research and design](https://www.sciencedirect.com/science/article/pii/S1071581905000121)
这个框架提出了两个关键的担保交易双方的因素：Contextual和Intrinsic properties。
其中情境因素又分为三点:

    1. Temporal embeddedness（交易双方长期交易的潜力，关系的长期维持）
    2. Social embeddedness （激励交易人完成交易保持信誉）
    3. Institutional embeddedness （法律保护交易） 

而本质属性大概就是交易双方自己的道德品质。

总结一下，HCI的信任模型指出了用户信任科技或者用户之间通过科技信任的影响因素。然而对于这些模型是否能适用于区块链科技，调查还很少。

### Alternative Crypto Currency
介绍了人类代币的发展历史，目前代币主要作为一种反监管的数字货币，并且为局部地区和虚拟社区所用。 

### Bitcoin Technology
介绍了下比特币和区块链，比特币背后的技术故意被设计为去中心化和安全的、反监管的和透明的、伪匿名的。这些独特的区块链的优势也带来一些信任挑战比如非法使用和损坏名誉。然而目前对于**区块链属性和用户的信任的关系**的研究还很有限。

## METHOD
招募了20个比特币用户（年龄range: 21-50）介绍了他们的使用时长、教育背景和职业。
还介绍了一下马来西亚在加密货币领域走在前列。
招募广告不仅公开Post, 也私信给社区group中最活跃的用户。我们也应用了Snowball Sampling，六个人被介绍到实验中来。
采用Semi-structed interviews(开放式访谈，不严格按照既定的问题与答案格式)来采访。
问了问题：
- 你为什么对比特币感兴趣？
- 你如何学习比特币知识的？
- 使用比特币的好处和挑战是什么？
- 你对比特币的信任程度有多少？
- 你经历过诈骗吗？
- 你会采取任何行动去防止诈骗吗？

采访通过Skype或者电话的形式。
混合方法，使用deductive coding来验证HCI已有的信任概念，新的概念对inductive coding做贡献。

## Results
我们列出了用户使用比特币的动机，比特币的关键特性和他们如何影响用户的信任。特别地，我们着重关注了不安全的交易和风险。我们还描述了应对不诚实交易者的风险，提供了缓和它们的策略。

### Motivation for the Use of Bitcoin Currency
早期使用比特币的人的动机和感知可以使用Davis' technology acceptance model来分析。
[ Perceived Usefulness,Perceived Ease of Use, and User Acceptance of Information Technology](https://www.jstor.org/stable/pdf/249008.pdf)

*Economic Rationale (经济原因)*
主要三点：
- 塞浦路斯危机让人们看到，政府可以随时拿走你账户里的钱，所以比特币更安全。
- 经济现在不景气，钱投资比特币更好。
- 人们相信比特币价格未来会上升。

*Social Learning (通过社会学习)*
调查显示很多人通过社交网络来学习比特币。大多数人从网上社区（比如reddit）听说比特币。并且比特币价格上涨后，人们主动的去自己学习更多。“我一开始听说比特币在2009年，后来2013年大涨，我就开始去学习更多。”
另一个消息来源是同辈和朋友。“朋友告诉我关于钱包、使用过程和比特币怎样避免银行的交易。”。这些信息显示早期采用者如何看重比特币相比国家法定货币的优点。

*Uses of Bitcoins (比特币的使用)*
大多数受访者将比特币作为财产储备。7个人用他们作为偶尔的投资，5个人是专业比特币投资者。这是有趣的，因为比特币的高波动性使得比特币并不是一个长期的可信赖的价值储备。这显示了人们更偏爱于自己可以完全控制的储蓄，而不是波动更小、但是自己更少控制权的法币。
另一个惊讶的发现就是尽管接收比特币支付的商家越来越多，但是还是很少人用比特币来真正的购买东西。但是有一个参与者有着丰富的比特币线上和线下使用经验。“我在网上用比特币买香烟，在餐馆用比特币付账...”。这个用户的行为是异于常人的，我们很难再发现任何采访者有这样丰富的使用经验。
有趣的是，我们发现一个用户用比特币在暗网买了一个不受限制的Spotify账号。

### Blockchain's Characteristics and their impact on Trust
我们现在描述比特币的主要特点，和它们如何对信任做出贡献。比如去中心化、反监管、需要专业的知识和透明、低花费、简单和不安全的交易。

*Decentralized Blockchain*
大多数参与者喜欢比特币不需要任何来自金融机构的第三方即可交易的特性，“如果没有第三方管理我的资产，我自己管理是更安全的。” 去中心化也提供了规避不诚实的中心化金融机构的自信，这也支持了前面提到的model of online trust中的honesty这个维度。
人们不喜欢银行复杂的交易认证过程，在银行需要三个工作日完成交易的同时，比特币可以做到即时的快速转账。

*Unregulated Blockchain*
参与者也表达了对比特币反监管特性的赞许，他们把这个看作重新夺回自己财产控制权的机会。“所有的政府都喜欢控制人民，但是他们不能控制比特币，所以他们不接受比特币。比特币给予人民金融自由。” 这是一个好战的举动，联系到最初使用比特币的动机：金融机构和政府随着经济危机已经失去人民的信任。

并且人们认为使用比特币可以方便的全球交易，不受到任何机构的限制。并且因为匿名性，政府不能冻结他们的钱包。

*Blockchain's Embedded Expertise*
另一个人们赞赏的是挖矿和验证需要很专业的知识。“挖矿很难，需要专门的方法和昂贵的设备”。大约四分之一的受访者提及了挖矿的复杂度和高昂的成本。他们对矿工的专业性的赞赏支持了比特币交易的可信度。
**这也呼应了online model of trust 的credibility维度。**

*Blockchain's Reputation*
区块链科技的名声由于非法的活动变得很差，四个参与者提及了网络犯罪的问题。然而有趣的是，区块链为非法活动提供的便利并没有很大的影响人们心中的地位。反而人们认为区块链有着光明的未来，很多大公司对区块链的研究正在提供一种合法化和提高区块链可靠度的方法。
除了区块链的信任，参与者也提到了比特币交易的信任。我们现在讨论比特币的交易特点，和它们如何支持和阻碍信任。

*Transparent Transactions*
用户可以追踪任何比特币交易直到最初的来源。这是非常透明的，人们可以在一个公开的帐本中看到比特币的流动。
**透明性呼应了model of online trust的credibility维度和honesty维度。**

*Easy and Quick Transactions*
另一个特点是比特币的简单易用和交易的速度。“转账从一个国家到另一个国家如此简单，就像发送一条信息一样。”
*这呼应了model of online trust*的ease of use因素。

*Low Cost Transaction*
比特币的交易费用很低，能够减少人们在交易中感觉到的风险，因为人们不用担心隐藏的或者更高的花费。
**risk是model of online trust的第三个因素。** 

### Insecure Transactions
尽管以上特点支持了区块链技术中的信任，参与者还是表达了对于不安全的交易风险的担忧。但是没有人对矿工的加密算法担心，而是strong trust in miners' expertise and in the predictability of the protocol.(原文表述)。我们下面指出四种不安全交易的类型，其中三种与人相关，一种与技术相关。

*Risk Due to Users' Challenges of Handling Passwords*
六个受访者提到了丢失钱包密码的风险。“确保你不要忘记自己的密码，因为区块链不能恢复你的密码，你将丢失所有的比特币。”

第二个风险是不能很好的保护密码，一个用户提到自己设置email密码和钱包密码相同，被盗走了30个比特币。

为了解决这些风险，一些用户提到了安全地存储和保护密码的责任和重要性。一些用户甚至安装了额外的安全应用作为双重保障。“系统是安全的，安全责任落在用户身上，如果任何人丢了比特币，首先他们应该责怪自己!”（我很doubt用户有这么高的觉悟.....）

*Risks Due to Hackers Malicious Attacks*
三个受访者提到了黑客的恶意攻击的问题。

*Risks Due to Failure to Recover from Human Error or Malice*
尽管三分之一的受访者觉得自己应该担起责任保护自己的密码，但是还是有很多人认为比特币的提供的安全支持有限。主要的问题是交易是不可逆转的，“黑客一旦转走你的钱，你不知道钱到了那里也不能逆转交易。”
这是一个有趣的发现，显示了比特币的一个缺点。

*Risk Related to Dishonest Partner of Transaction*
研究显示一个值得考虑的因素是不诚实的交易伙伴。“我转了比特币但是买家不付我钱。”阐述了了解交易伙伴的重要性。

### Strategies for Mitigating the Risks of Dishonest Traders
我们提出五个应对不诚实交易者的策略。这些策略主要有两种形式的交易：直接和另一个人交易、通过交易所交易。

*Trade with Authorized Exchanges*
网上交易所现在是用户最喜欢的交易方式，可能因为它的监管支撑了用户的信任。尽管比特币和加密协议是反监管的，交易所却需要金融机构的批准。五个受访者提及了他们会评估交易所的信用程度。“我会看他们的背景，和长期的条款，从这些里面我信任交易所。”
这也扩展了之前HCI网站价值对于信任的研究，扩展到了加密货币交易的场景。另一个信任的来源是用户可以直接与交易所的客服对话，这使用户感到更放心，有什么问题都可以问。交易所也建立了交易双方的信任，他们需要卖家和买家都注册并且验证身份。
**这些研究为the framework on mechanics of trust提供了支持**
- 根据用户的诚信表现和期待他们未来会保持一致的行为（temporal embeddedness）
- 交易所的名声（social embeddedness）
- 交易所的合法授权服务（institutional embeddedness）

又说为the framework on mechanics of trust的Intrinsic properties提供了支持。

*Trade with Socially Authorized Traders*
与社会上权威的非匿名的人交易很放心，这些人一般被社区管理员加到可以信赖的交易者的名单里。这个结果显示了非匿名性对于信任有着巨大的作用。
**这些研究为the framework on mechanics of trust提供了支持**
（temporal embeddedness, social embeddedness）

*Trade with Reputable Individual Traders*
如果不能发现权威的交易者，就只能与风险大一点的良好声誉者交易。这些人往往是通过介绍认识的，超过半成的受访者提到了他们更喜欢与过去交易成功过的人交易。这也显示了善意和名声的重要性。
**这些研究为the framework on mechanics of trust提供了支持**
（social embeddedness and credibility）

*Trade with De-anonymized Individual Traders*
很多受访者表示他们仅仅跟愿意不匿名的人交易，主要有两种方式：
- 面对面交易
- 亮出自己的personal ID.
用户尝试去通过去匿名来引入institutional embeddedness（身份证政府担保）,或者减少不同步交易的风险- 面对面交易。

*Regulating Bitcoin*
许多用户表示希望比特币被监管。？？？（这不是自相矛盾吗）这是一个重要的一个高级的策略，不解决交易本身，解决区块链没有监管的生态。

## THEORETICAL IMPLICATIONS
我们用这些研究的价值来加强HCI中的信任理论。我们也讨论了反监管和伪匿名性对于信任特殊的价值。

### Towards a Model of Trust among Bitcoin Users
我们考虑了HCI理论对于区块链特点支持用户信任的可行性，对于比特币用户的主要挑战是不安全的交易风险，特别是与不诚实的人交易。
我们从Sas的比特币信任框架开始（就是他们之前的文章）。我们的研究显示比特币用户对比特币技术的信任还是很强的，特别是安全的加密协议。
研究依然显示了新的对于社会维度的信任的视角。这里主要的问题是不诚实的交易者。另外很少的用户使用比特币买东西，更多的是财产储备。同时我们也看到了政府信任的丢失如何使用户采纳比特币。

更深入的考察技术信任，我们运用the model of online trust去指出区块链的特点对于信任的影响。

交易的时候，如果有关对方名声的信息越少，就越需要去证实他们的身份。（de-anonymize）。

### The paradox of Unregulation
比特币的反监管和伪匿名性是关键的区块链的优势。但是有趣的是，比特币用户渴望监管，因为不诚实的交易者的存在。
我们认为用户还受限于传统的中心化的法币的思维，我们需要新的支持比特币科技的思维模型。这需要新的支持用户学习数字知识的能力，也需要创新的技术来在保持匿名的同时限制不诚实的交易者。

### The Challenge of Pseudo-anonymous Transaction
在the framework on mechanics of trust中，三种形式（temporal embeddedness, social embeddedness, institutional embeddedness）都变得不起作用。

这是一个失败，区块链不能用contextual properties激励用户。这意味着用户只能依赖自己的Intrinsic properties。
然而我们发现用户不相信对方的道德品质，想要通过去掉对方的匿名性来保护自己。

这也确认了人们当碰到完全不认识的交易方时，只愿意承担很小的风险。

## DESIGN IMPLICATIONS
现在我们讨论设计方面的启示。

### Supporting Transparency of Two-way Transaction
大多数交易是双向的，序列化和异步的。比如一方发送了法币，当另一方收到之后，发送比特币。然而人们只能追踪比特币的移动，而不能确保法币的交易。（法币可以伪造通过诈骗的方式发送）
可以使用新的方法来捕捉交易的非比特币内容，使其变成在链上可以验证的。其实早已存在，比如Colored coin.（好像就是用比特币交易的脚本来发行代币的东西）

### Tools for Materializing Trust in Bitcoin
研究显示由于缺乏稳定的和认识的身份机制，用户往往会寻求social embeddedness来产生信任（搜集对方名声相关的信息、从亲近的朋友、网上小组）。

更好的方式是捕捉和可视化声誉作为钱包地址的元数据，**建立一套区块链之上的信誉系统能够大幅度增加social embeddedness。同时，会促进用户不用新的地址来交易，而是用相同的地址来积累积分。

### Tools to support Reversible Transactions
还是像之前所说的，不可逆转的交易是一个问题。比特币能被追踪，但是对应的现金转账或者商品交易不行。由于区块链的机制，逆转交易是不可能的。一种解决办法是使用户确保能联系上对方，但是又不丢失用户的隐私性。
另一种办法是多签名系统，支付一定的费用给第三方，钱被放在一个联合地址里，3方中只有两方同意才能操作。这与中介系统也不同，因为仲裁方自己不能做主，还需要另一方的签名，从而防止了仲裁方的欺诈。
奇怪的是，没有受访者提到多签名系统，可能因为他们觉得难用，或者不知道这类工具。未来还需要做更多的探索。

## CONCLUSIONS
本研究调查了比特币哪些特点支撑用户的信任，和它们激励用户去使用的动机。我们想要建立一个比特币科技的信任模型，并且对于这些特点提供启示。研究产生了很多能够使用户增加彼此信任的启示，包括双向透明交易、物化信任的工具、支持可逆转交易的工具。

### 我的总结
这篇文章引用了两个HCI古老的引用量巨高的信任模型，把区块链和比特币的特点往上套。这篇文章就像高歌老师说的一样，是完全依靠用户采访的内容写的文章。然后还提出了应对不诚实交易者的策略、比特币中不安全交易的问题，当然主要还是围绕信任方面的问题，最后提出了理论上的启示和设计上的启示。
主要内容是讨论比特币的特点和这些特点对信任的影响。






















