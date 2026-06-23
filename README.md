### Hi there 👋

**vibe coding工程师 | 智能合约工程师 | 3年经验 | 远程优先**

---

### 🛠 技术栈
`Solidity` `Foundry` `java`  `Node.js` `OpenZeppelin` `The Graph` `Chainlink`

### 👋个人简介
拥有多年软件开发基础，近两年专注智能合约与 DeFi 协议研发。独立设计并运行 BSC 链上跟单套利系统，实现稳定月收益 1000‑4000 U。
精通 Solidity、EVM 存储与 Gas 优化，熟悉主流 DeFi 协议和常见攻击防护。习惯 claude code 辅助编程，能通过清晰逻辑拆解问题，提升开发效率。
安全审计: Slither, Echidna, Foundry fuzz，Certora。

### 💼 工作经历
2014年-2017年，在惠州易隆软件担任研发工程师-参与电力公式，政府机构，装饰公司，建工集团等传统企业erp软件开发

2017开始参与web3领域，吃过2017年和2021年牛市红利

2022年开始关注学习web3相关开发技术

2023年-2024年，设计并实现一套基于PancakeSwap(UniV2)的链上自动化套利系统，持续运行超1年，月均盈利1000‑4000 U，零安全事故，技术包括本地节点搭建，
合约层（Solidity）：
· 开发专用 Router 合约，直接调用 Pair.swap() 执行底层交易，减少一层 Router 调用，有效降低Gas消耗并防止被三明治攻击轻易监测。
· 实现多跳路径价格冲击预估算法，支持买卖双向及精确输入/输出模式，结合链上储备量模拟交易后价格，为策略端提供滑点决策依据。
· 编写代币安全检测模块：通过模拟买入→模拟卖出→余额比对，自动计算实际买卖税率与转账税率，可识别高税率貔貅盘，降低打新/跟单风险。
· 采用 SafeERC20 及白名单+管理员权限设计，实现资金闭环管理，保证合约内滞留资产可安全提回。

链下层（nodejs+web3js）：最底层是mempool监听和交易解析，中间层是决策引擎（包含安全检测、风控、价格监控），最上层是交易执行与重试。
同时用Worker线程把安全检测和价格监控剥离，避免阻塞主线程的实时交易处理。

2025年牛市至今一直关注学习web3开发技术

2026年 claude code独立开发AI驱动的DeFi兑换聚合器


### 🛠 核心技能
智能合约：Solidity（精通），熟悉GAS优化技巧，熟悉ABI编码规则，熟悉EVM储存原理，熟悉合约升级UUPS / Transparent / Beacon Proxy 模式设计与实施

开发框架：Foundry、Remix、OpenZeppelin Contracts’

DeFi 协议：AMM（Uniswap V2/V3/V4）、借贷（Aave）、Vault、Staking、收益聚合、治理投票、Tokenomics 设计

前端/工具库：ethers.js、web3.js、The Graph、viem(了解)

后端语言：java、Node.js

独立完成链上套利系统全栈开发：从Solidity合约到底层mempool监听、安全检测、自动化交易执行与风控，具备将策略快速工程化落地的能力.

claude code开发。

教育背景
计算机网络技术 | 大专



### 📫 联系我
- Email: iszzm123@gmail.com
- Telegram: @Bgfmmt
- WX:iszzz666
