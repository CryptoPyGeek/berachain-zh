# BERA

$BERA 是 Berachain 生态系统的本地燃气代币，用于初期验证器质押以保护网络，并用于支付交易费用。详细了解请参阅 Tokens > $BERA。

# BGT

$BGT是Berachain的质押和治理代币，不可转让，只能通过参与Proof of Liquidity来获得，可以兑换为$BERA，用于提出和/或投票治理提案，以及委托给验证者以增加其权重以被选为提出区块。详细了解请参阅 Tokens > $BGT。

# 区块

一个数据单元，包含一系列交易，按顺序永久添加到区块链中。

# Bend

Berachain 的本地借贷协议，从 Lend 改名为 Bend。详细了解请参阅 Native dApps > Bend。

# BEX

Berachain 的本地去中心化交易所，从 DEX 改名为 BEX。详细了解请参阅 Native dApps > BEX。

# Berps

Berachain 的本地永续合约交易所，从 Perps 改名为 Berps。详细了解请参阅 Native dApps > Berps。

# 区块时间

创建新区块所需的时间。Berachain 的平均区块时间为 < 3 秒。请注意，区块时间可能会因网络拥堵而增加。

# CometBFT

Berachain 使用的通用区块链共识引擎，用于实现高吞吐量和快速交易最终性。详细了解请访问 Cometbft.com。

# 共识客户端

共识客户端（有时称为共识层）是负责在网络节点之间达成关于区块链当前状态的协议的软件。它处理验证交易和区块的过程，确保它们符合网络规则，并决定哪些区块添加到区块链中。共识客户端专注于网络范围的规则和交易顺序。它通常与执行客户端配对使用。

EVM 共识客户端：

- Lighthouse：基于 Rust 的官方客户端，采用 Apache-2.0 许可证。
- Lodestar：使用 Typescript 编写的生产就绪共识客户端实现，采用 LGPL-3.0 许可证。
- Nimbus：使用 Nim 编写，采用 Apache-2.0 许可证。
- Prysm：使用 Go 编写的功能齐全的开源共识客户端，采用 GPL-3.0 许可证。
- Teku：最初的 Beacon Chain 创世客户端之一，使用 Java 编写，采用 Apache-2.0 许可证。
- BeaconKit：基于 Cosmos SDK 构建的模块化共识客户端。

# 共识机制

Berachain 网络节点就区块链状态达成一致的协议。Berachain 使用 Proof-of-Liquidity 基于验证者提供的流动性来选择验证者。

# 委托

令牌持有者授予另一参与者在网络中的投票或验证权力的过程。

# DEX（去中心化交易所）

在区块链上直接进行代币买卖的平台，没有中心化的中介。所有流动性都由智能合约拥有。

# 执行客户端

EVM（以太坊虚拟机）执行客户端（有时称为执行层）是负责实际计算区块内交易的软件应用程序。它使用 EVM 解释和执行智能合约的代码，管理状态变更，并执行交易逻辑。该客户端确保根据智能合约的代码和 EVM 协议正确执行所有操作。

EVM 执行客户端：

- Geth：以太坊协议的官方 Go 实现。
- Erigon：性能更高，功能丰富的客户端，从 go-ethereum 分叉。
- Nethermind：基于.NET 的客户端，完全支持以太坊协议。
- Besu：企业级客户端，采用 Apache 2.0 许可证，使用 Java 编写。
- Reth：专注于性能和可靠性的基于 Rust 的客户端。
- Ethereumjs：由以太坊基金会管理的基于 JavaScript 的客户端。

# 最终性

确保一旦在区块链上确认交易，就无法更改或撤销的保证。Berachain 提供交易的即时最终性。

# 治理

在 Berachain 生态系统内做出决策的系统。治理涉及提案、投票和实施更改，通常使用 BGT 代币进行参与。

# HONEY

$HONEY 是 Berachain 生态系统的本地稳定币，与 1 美元等值。它在整个 Berachain 生态系统中使用，并涉及铸造和销毁费用。详细了解请参阅 Tokens > $HONEY。

# 流动性

在 Berachain 网络上用于促进交易的流动资产的可用性。用户通常通过流动性池提供流动性。

# 流动性池

锁定在智能合约中的一组资金，用于为去中心化交易所和其他 DeFi 服务提供流动性。Berachain 的流动性池可以包含 2-8 种代币。

# 流动性提供者

将代币存入流动性池的用户，从池中交易产生的费用中获得一部分奖励。

# Mainnet

Berachain 区块链上实际发生真实交易的主要网络，与用于开发的测试网络相对。

# Polaris EVM

Berachain 的工程团队使用的以太坊虚拟机实现，提供与 Cosmos 的 CometBFT 上构建的基于以太坊智能合约的兼容性。

# Proof of Liquidity

Berachain 使用的共识机制，根据验证者提供的流动性来选择验证者。

# 质押

锁定代币以支持区块链网络运作的过程。在 Berachain 中，质押用于网络安全和参与治理。

# 交换

在去中心化交易所上交换一种代币为另一种代币的过程。交换涉及费用，费率根据池子的设置而异。
