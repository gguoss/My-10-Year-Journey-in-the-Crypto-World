# My-10-Year-Journey-in-the-Crypto-World
To achieve one thing: understand Bitcoin. By observing the design of this single, localized individual, Bitcoin, abstract the holistic equation of the Bitcoin paradigm to guide the crypto industry in realizing a variety of cryptos capable of forming Bitcoin-like distributed, closed-loop economies.

## 10年 奋斗过程积累的感悟总结
Bitcoin 范式的 ***关键主体对象是：Individual***， ***问题是：Individual的分布式信任安全问题***， ***解决方案是：个体自治从而分布式涌现***。


### Bitcoin范式 的方程组
-  交易函数： f (compute) = TX (Input (Individual), Output ( Individual))；  实现个体业务之间的分布式计算。
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


