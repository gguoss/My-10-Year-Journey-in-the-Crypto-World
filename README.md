# My-10-Year-Journey-in-the-Crypto-World
To achieve one thing: understand Bitcoin. By observing the design of this single, localized individual, Bitcoin, abstract the holistic equation of the Bitcoin paradigm to guide the crypto industry in realizing a variety of cryptos capable of forming Bitcoin-like distributed, closed-loop economies.

## 10年 奋斗过程积累的感悟总结
Bitcoin 范式的 ***关键主体对象是：Individual***， ***问题是：Individual的分布式信任安全问题***， ***解决方案是：Individual自治从而分布式涌现***。


### Bitcoin范式 的方程组
-  交易函数： f (compute) = TX (Input (Individual), Output ( Individual))；  实现Individual业务之间的分布式计算。
-  共识函数： f (concensus) = Concensus (hash, difficulty)； 解决 BFT容错的问题。
-  共识感知量化函数： f (Bitcoin) = F (f (Compute), f (concensus))；  通过融合交易函数和共识函数从而 分布式涌现出 能量守恒的分布式商业。

以上三个函数对 Bitcoin 的分析：
- Bitcoin 的个体对象是： 基于UTXO做载体的Coin。 
- Bitcoin的交易函数是： 基于 基于UTXO数据机构的 BTC transfer 。
- Bitcoin的共识函数：量化hash计算， 且以 nonce为个体 的分布式共识计算的 涌现。
- Bitcoin 的商业守恒函数： hash算力背后的电力能源 对应 BTC 这货币的 商业价值转换。

### Bitcoin 范式的 Individual到能量转换的 闭环分布式涌现商业 设计：
| ***Individual*** | ***Transaction function*** | ***Concensus function*** | ***Consensus-aware quantization function*** | ***Quantifiable Energy*** |
| ---------------- | -------------------------- | ------------------------ | ------------------------------------------- | --------------------------|
| 类UTXO分布式数据结构表达的事物 | 确切的函数式编程    | BFT 算法                  | 外部 能量 感知 算法                            | 能量输入 |

Bitcoin 之所以成功，而其他Crypto之所以不成功的原因是： 
只有 Bitcoin 完成了  ***BTC Individual*** 到 ***Quantifiable Energy*** 闭环能量守恒的分布式商业模式。
且在设计的 一切 原则接近 100% 的遵守 ***Individual分布式原则*** 。

### ***Individual分布式设计原则***
Individual分布式设计原则 是指 我们遵循自然规律的 ***个体自治涌现定律***。 
以 Bitcoin 和 Ethereum 的设计原则为例来对比分析。
| 对比类型/是否遵循Individual分布式设计原则 | Bitcoin | Ethereum |
| ------------------------------------ | ------- | -------- |
| Individual 的载体数据结构 | 是： 分布式的UTXO | 否：中心化的 状态树 |
| Transaction 计算函数 | 是： 分布式的无中间状态函数式编程 | 否： 中心化的EVM计算 |
| BFT 共识算法 | 是：不论POW 矿机Agent还是 nonce个体测试| 否： 中心化的POS 共识投票计算 |
| 能量守恒商业模式 | 是： BTC 对算力背后能源的 分布式映射 | 否： 可以忽略的各验证节点 中心化一致投票 BFT pos计算 的 电力能量 |

从上对比可以得出： Bitcoin 不管是从何逻辑设计都遵循着***Individual分布式设计原则***，而Ethereum 的设计 是一个极其粗燥肤浅的平台，Ethereum的一切设计都只是为了服务于图灵完备的EVM， 而这些肤浅的设计可以接受。
最不能闭环的是： 忽略不计的外部能量输入，导致系统成为了一个 封闭的墒增 无商业模式的系统。 而这是大部分 类 Ethereum 区块链模式失败的根本原因。

## 10年 奋斗路上的问题与思考迭代， SB和无知的10年
### 初入 Crypto行业 的2016。
被动接受了 Ethereum 针对 Bitcoin而设计改良的三大问题。
- 1， 解决 Bitcoin 的 图灵非完备的 VM 问题。
- 2， 绿色能源， POW 转 POS。
- 3， Sharding， 扩展账本计算能力，即提高TPS。

而这三大问题， 成为了整个 Blockchain 公链的 主叙事， 反反复复的在接下来的年代迭代出新的 改良产品， 但结果很显然， 没有一个是 超越Bitcoin 的设计模式的，因为没有公链创始人 看懂了 Bitcoin。

而我当然也是 没有看懂 Bitcoin 的人之一。
但不妨碍我 无知 的活着，所以有了接下来的一系列的折腾。 
2016年 8月左右， 用不到7天的时间， 把 Python版的 Ethereum客户端的POS 共识改成了 国家级需求的 POA 共识联盟链。 
同年9月， 因为 Python 版的 Ethereum 性能低下， 我用C++ 语法重写 Ethereum的 merkle 树和 RLP 等算法。 
同时， 因为 联盟链 有 隐私需求， 我从 BlockStream的 Elements （Bitcoin 的侧链）中 剥离出 ZKP 的 RangeProof 金额隐私算法，用于 金额隐私设计。 
此时， 不到3个月的时间， 让我从一个完全不懂区块链技术的程序员， 瞬间 成为了 区块链技术专家。 

但在我现在看来， 区块链 是一个骂人的词， 区块链指：没有看懂Bitcoin且自以为是的一群真无知者。

### 初露锋芒的 2017
为了要解决个人的生存问题， 在2017年初露锋芒，做了3件我觉得还很牛逼的事情。
- 其一， 建立了ChainX 社区，接待了 Gavin wood 来中国，认识了Gavin WOOD 和他们团队的3个创始人， 他们团队当时也只有3个人， 且他们也在生存问题边缘， Gavin到处站台顾问和写Rust Paritytech 客户端支持多种 小币种挖矿算法。
- 其二， 去巴比特 做了 Bytom， 用纳斯达克旗下的 Chain.com 公司的 UTXO 账户模型 融合了 tendermint 的 P2P 再加了创始人的科幻 AI梦想的挖矿算法。 其实这是一个无厘头的项目出发拼凑品。 但这是我当下认为最接近 Bitcoin 本质的一个项目，只是当时我们没有任何的抽象能力，无法去 抽象怎么来实现 更好的Bitcoin 范式。这说明：来自于 认知的局限性，就算 运气好，就算踩对了方向， 你也会 失败，且是找不到核心失败原因的失败。
- 其三， 通过ChainX 社区联系到 Cosmos 创始人，且接待了 Cosmos创始人 Jae Kwon， 然后花了3天时间， 把 Chain.com 的UTXO 模型融合 tendermint pos共识做了 Chainmint，然后获得 Jae Kwon 他们的2个BTC的奖金， 此时， Jae Kwon 想让我加入他们团队做核心开发， 当时他们也就2个核心开发， 我想， 韩国棒子再加英语的压力， 果断拒绝了。 但不后悔，因为那时就算去了 Cosmos，可能的我比现在更无知SB。

### 小有所成的 2018
再次为了突破自己一下， 这一年我准备 生两个孩子。一个事业的孩子，一个我生活的孩子。 说明只要你心诚，就能达到， 而在这一年我就实现了我的愿望。
- 事业的孩子， ChainPool， 因为 EOS的BM 鼓吹，我觉得可以做个 POS Staking 池是未来，所以我们准备做Staking 池挑战比特大陆，因为POW 老大 比特大陆当时最风光，比现在的Binance 还风光， 那我们做Chainpool那就是干 比特大陆， 这个可以。 然后一扑通进去 搞Chainpool 给EOS 做POS矿池， 然后一研究 EOS， 傻眼了， 这BM SB 是真拿着 Ethereum 的 blockchain的  Sharding 问题做 100万 TPS，还在自以为是的写 了一大堆 Sharding 代码，当时我一看， 这项目要完了， 因为 Sharding 代码逻辑狗屁不通， 然后 BM说要有缘人来起EOS， 我当时想： 你EOS 这是要黄了啊， 我的Chainpool也要黄， 那我去找个有缘人帮你来起 EOS， 我顺便帮你改改 EOS代码，删掉BM的逻辑不通 的sharding 代码，让代码跑起来。 而当我们 删掉 了EOS 的Sharding 的代码后， BM也接着把 sharding 的代码给删了。 而我们前后完成这个工作不到 2个月的时间， 这公链写代码是真挣钱， 说的是BM。 那代码都写了， 那就起个链吧， 这就和有缘人一起起了 EOSC 这个分叉EOS链，而当时链上的所有EOSC代码，是我1个多月时间删BM的代码删出来的， 这项目让我变现了点开发经费。给Chainpool 这个 Staking 池的故事有了闭环着落，不再去做 POS的 比特大陆了。
- 我自家的孩子， 有一天我正在写代码时，我旁边一个产品合伙人，跑过来和我炫耀他娃怀孕3个月的B超照片， 我当时就想， 这让我很爽， 我晚上回去也搞一个， 还真搞成了， 同年 11月份，我闺女出生了。 此时人生真感知到了生活的意义， 幸福感知之门开始。 幸福不是傻逼，

### 扩展 BTC 执念的开始 2019 ： ChainX 才是Substrate 第一链， Substrate 龙头链。
和VB，Jae Kwon，BM，Gavin Wood 接触后， 发现 Gavin Wood 的代码能力最强，所以当时 觉得 VB/Jae Kwon/BM 是SB，所以不再去关注Ehereum，Cosmos，EOS。 而去 和 Gavin Wood 写 Polkadot的未来。 
但我们SB的认为：
Polkadot 是为了解决万链 互联问题的项目。
所以 ChainX 设计为 Polkadot 的一个 跨链中枢或者叫 Bitcoin 跨链的 Hub。 
在此年，做了几个牛逼 的SB 事情。
其一： 实现了Bitcoin rust 版本的 SPV 轻客户端。
其二： 抢在 Polkadot/Kusama 上线前的2年左右， 最早代码上分割出来了Substrate，且实现了 Bitcoin SPV 轻节点融合  Substrate 的框架，使得ChainX 号称 Substrate 第一链。 而Kusama 是Substrate 第二链。 而 Polikadot是 Substrate 第三链。 ChainX 才是Substrate的 龙头。
其三： ChainX 上的 跨链BTC 数万个， ChainX 上被 lock 住的 BTC 有几十万个。
其四： ChainX 支持了 DOT的SDOT 跨链， 导致 Polkadot的 CEO拿着 他们基金会 没有卖掉 的30%的 DOT要跨到 ChainX 上来挖矿 PCX。 我直接给拒绝了， 这 SB的Polkadot基金会还想着 抢散户的PCX， ChainX 是完全 Bitcoin的 公平挖矿模式，不允许 polkadot 官方团队的DOT 代币进入网络来 白撸PCX 。

此年， 我们在玩 ChainX ，还是玩的很开心的， 很多乐呵。  但此时对行业很迷茫，因为认知到了 Gavin Wood 也是傻逼，  他所做的Polkadot 已经和我们之前想象的 万链互联概念有出入， 且不仅是出入的问题， 而是意识到了，好像币圈哪里都不对。 
此时的感知，也许是整个Crypto 对的反应。 也许不要出现意外， Crypto 行业也许在此时就能迎来 新的认知变革， 更早的颠覆 以太坊带来的区块链三大问题（图灵完备VM， Sharding高TPS， 绿色能源POS）。  
但意外就是在此时出现了， 后续的 Defi 这个 封闭梦境里的 自我能量 释放， 让这个 BlockChain 的叙事一直延续到现在。  
当下的大家才意识到了 以太坊 的区块链 三大问题 不是问题，或者是伪命题，其中：
- 绿色能源POS问题不符合能量守恒的商业模式。
- Sharding 高TPS 带来了 Layer2 这些 的快速崛起和衰落。
- 图灵完备的 Defi 虽然 带来了 去中心化的流动性体验， 但依然只能玩没有意义的 单机游戏。

而 以太坊 区块链 以及他这三个问题 都不成立的 统一本源问题是： 梦境割裂问题 导致的能量守恒的 商业不闭环问题。 
而为了认知到这个本源问题， 我从 2020到现在且 彻底搞明白。 

### 从恐惧 到心情开朗，好好生活的 2020年。 
此年， 是疫情的关键一年， 今年早些时候，大家封闭在家，无所事事，我让开发团队也都回家了， 大家大半年在家待着， 我也不做任何的管理和干预。 我准时每月给他们打钱发工资。
等不封控，可以开始办公时， 我问他们要不要再来一起办公， 而大家都过来了。 
此年，我自己没有去扎实的做过多的产品开发。 停留在 好好生活的反思。 

为了好好反思， 那首先要做的是人生的第一大项目： 造娃。
此时生了一个我想要的 和我 同一天生日且同时的娃， 我叫他为 小光华。 但人家从来不接受这个称呼，觉得我这个SB 在侮辱他。 

而在今年， 我们通过 Polkaworld 社区，孵化了很多Polkadot 项目， 因为是 Polkaworld 创始合伙人的原因， 所以我们都是最早轮投资了不少 Polkadot的 生态项目。 当然有亏有赚，投资一向如此。 但因为都投资一轮，所以收益还可以。
也在此年， 和我小时候一起生活长大的 表哥表姐 同时 去世了， 我震撼的感知到了，人生好好生活很重要。 我们要 真真切切的对待好每一天。 
但所有的反思和感悟， 是螺旋式的进展，时间一长， 如没外部输入， 内部的感悟函数就会 钝化。 
建议： 多换换城市， 多和人交流， 多各类输入反馈的变化， 会让 生活 更美好。

### 从虚向实的 2021： ComingChat： Individual 的 wechat。
在 Polkadot 生态的发展中，感知到了 来自于 EOS 和 ETH 时候的 匮乏商业的失望， 且Polkadot 更执着于我完全不理解的 Slot auction， 我在Polkadot 孵化投资了一堆项目：如Acala/Astar/Zenlink 后。 开始去解决我一直存在的疑问。 
为什么 Crypto 圈 不能像 wechat 的web2 圈一样 服务于现实？ 为什么 crypto 就不能 跳出炒空气的死循环？
我SB的认为， 那是币圈没有真实的用户涌入。 所以我 基于 椭圆曲线的 双齿轮算法设计 的 隐私聊天通信软件 ComingChat 上线， 不仅 支持了椭圆曲线的 聊天，而且把 Crypto 里的 账户系统和 聊天系统统一起来了。  
类似于 QQ 的设计， 一个 1到12位的 数字身份。 和QQ 的根本区别是， QQ的账户系统是一个中心化的 服务器统一管理着。
而我的ComingChat 是一个基于 Individual 的椭圆算法 衍生的 Individual 的crypto账户和通信账户。 这个 ComingChat 软件通信程度 达到了 Individual。
而此产品， 对外快速推广， 因为有 Crypto 的概念， 所以瞬速吸引了 1000万的 撸毛用户， 此产品在初始设计时， 没有去考虑消息服务转发的 P2P， 而消息转发的服务还在中心服务中。  导致每天要消耗大量的 服务费。 
此时不得不面对的问题是： 该产品的商业闭环的问题。 
人来了， 价值流通不正常， 这便成了 下一年我们要解决的问题。 


### 商业闭环的 2022: OmniBTC的 OmniSwap/OmniLending/Dolaprotol。 
从ComingChat 里吸引了人来了， 认识到了 Crypto  web3 圈 和web2圈不一样， web2圈是 以人或者 信息为中心做拓展。 而web3 crypto 圈 是以链上流动性为中心拓展。
基于我此时的SB 认知， 我快速进入迭代出了 OmniSwap， OmniSwap当时的灵感来源于我对Polkadot 要万链互联的想象，所以自然要解决万链互联的流动性， 而 Bitcoin 是我一直没搞明白且最牛逼的crypto， 类似于 老子的 道德经。
那我起这名字叫 OmniBTC 而不是单纯的叫 OmniSwap。 
然后我们 OmniSwap 后面快速的吸引了大量的用户进来， 用户进来的原因，是因为 ETH Layer2 撸毛的业务需求。

因为一直有  万链互联 的这个念头， 最早是对 Polkadot的 万念互联的期盼， 后面发现Gavin 这家伙压根做的不是这个，而是 以太坊 2.0 的另外一个版本。
而此时，机缘巧合，出来了一个 叫LayerZero的 协议，在搞 万链互联流动性协议， 所以我们第一个基于 LayerZero协议 实现了全链 流动性的 Swap。 
但实现了全链Swap 的同时， 我们已经不再局限于只做Swap，而是能否支持全链的借贷，甚至可以抽象一个最底层的全链聚合流动性协议， 所有的Defi Dapp都基于该全链流动性协议来拓展。 
而这些就是我们后面的集成在OmniBTC 里的产品， OmniLeding 和 Dolaprotocol。 
这些产品最早都只集成在ComingChat 移动端APP里。 
后面觉得ComingChat 的用户只通信，不花钱。 所以把OmniBTC 的产品拆出来了放到网页上，和浏览器插件 互动。 


###  迈上全球感知探索的2023年。
因为在做 ComingChat 和 OmniBTC 的时候， 认为SUI 很可以。
因为 ComingChat 要实现高并发的 朋友圈问题， 用 SUI 的Object 账户模型可以解决通信社交交流的并发的问题。 
且要做 OmniBTC 的Dola protocol 的全链流动性问题， 需要一个高TPS的链来做中枢管理，恰好 SUI解决了这些问题。 
所以此年， 我们在SUI 链上做了太多的应用， 包括 ComingChat 拿到了什么SUI 的第一社交的这种title，以及 给 Awesome-SUI 提交了 18个github代码仓库。 

在这一年，我们飞去新加坡 Jump 办公室待了 一个星期， 和 Jump 里面的顶级 哈佛本硕博连读（什么哲学，数学，计算机科学）等都拿了学位的些人好好聊了一下 dolaprotocol。 
此时，我认知到这些 高级算力很多时候都挺SB的。他们SB的原因是： 他们很容易局限在单一事物的局部最优解。 而不能跳出到全局来看事物。 大智若愚，也许描述的和这类人相反， 从整体来看事物，而不是用大脑计算能力去算局部。
当下的AI 计算能力很强了， 人已经无法去做计算， 而全局的抽象能力 反而成为了稀缺资源。 其实，此时，已经向我输入了， 学校不重要， 计算不重要， 真正的是感悟能力（即全局抽象能力），我不再执着于我孩子读哪所学校的问题了。 
当然，这些感悟不是2023年此时感知的，而是现在感悟得到的， 这中间有一个 反复的其他输入输出 的迭代期。
而这一年，应该飞的更多的地方，应该是 SUI开大会的地方， 和SUI项目方和生态团队一起来来回回飞 胡志明，香港。

在今年，另外一个惊喜是 Bitcoin 的铭文市场火爆， 因为 我去体验 打铭文， 让 个开发给我做了个打铭文工具， 创造了大量流量和热量。 我体会到这行情的火爆。

此时，我有了个想法， BEVM 把我以上所做的所有的事情都串起来了， 所以自然想到了 为什么 BTC 比 ETH 更需要 Layer2。
如何去设计 BEVM ，做一个真正落地像 Bitcoin 一样优秀的项目。 

### 2024年， 致力于 解决 BEVM的所有问题。
大体问题： 



