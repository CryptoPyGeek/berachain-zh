Berachain 的 V1 测试网（Artio）建立在 Polaris 之上，它将 EVM 执行与 Cosmos 共识紧密耦合。然而，生态系统在交易量和参与度方面的需求突显了这种架构的几个局限性。

Berachain 基金会对该框架进行了多次迭代和重新设计，最终形成了 BeaconKit。随着 Berachain 的 V2 测试网的推出，V1 期间遇到的初始问题已得到解决，从而实现了一个稳定且高性能的网络。

在 V1 中，验证者仅运行 Polaris 客户端，而在 V2 中，验证者将运行 BeaconKit 客户端（用于共识）以及任何 EVM 执行客户端（例如 Geth、Erigon）。这种模块化方法允许专门化关注点——执行层能够从 EVM 创新中受益，而 BeaconKit 提供高度可定制和高性能的共识层。

# 从 V1 到 V2 的主要变化

除了 BeaconKit 的技术变更，Berachain 原生代币的经济设计也有所演变。下表展示了 V1 和 V

从 V1 到 V2 的主要变化：

![v1-vs-v2](v1-vs-v2.png)

此表概述了 Berachain 从 V1 到 V2 的主要技术和经济变化。

一些要点：

- $BERA 被用于激活验证者，而不是 $BGT。
- $BGT 委托人不再面临削减风险。
- 执行环境现在与 EVM 完全相同。

# 主要优势

除了技术增强外，Berachain V2 中代币操作方式的经济变化还有以下几个好处：

- 提供了额外的 $BERA 实用性
- $BGT 采用纯经济角色，管理 PoL 和所有链激励
