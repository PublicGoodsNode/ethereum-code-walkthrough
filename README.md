# Ethereum-code-walkthrough 🚀

本仓库旨在帮助开发者系统性地学习以太坊协议的核心源码实现，适合对区块链底层原理、以太坊协议及其实现感兴趣的开发人员。

## 理论资料推荐 📚

在深入源码之前，建议先学习以下理论资料，了解以太坊协议相关的理论基础：

- [以太坊官方文档](https://ethereum.org/zh/developers/docs/)
- [EPF Wiki](https://epf.wiki/#/)
- [以太坊执行层规范](https://github.com/ethereum/execution-specs)
- [EIPs](https://eips.ethereum.org/)

## Geth 源码分析系列文章 🧩

本仓库包含了对 Geth（Go-Ethereum）核心模块的源码解读，帮助理解以太坊协议的实际工程实现。

- **[Geth 源码系列：Geth 整体架构](Geth源码系列：Geth整体架构.md)**
  - 介绍 Geth 的整体架构设计、主要模块划分及启动流程
- **[Geth 源码系列：存储设计及实现](Geth源码系列：存储设计及实现.md)**
  - 介绍以太坊底层存储方案、状态树、Trie 结构及数据持久化
- **[Geth 源码系列：p2p 网络设计及实现](Geth源码系列：p2p网络设计及实现.md)**
  - 分析以太坊节点间的 p2p 网络协议、节点发现、数据同步与消息传播机制
- **[Geth 源码系列：交易设计及实现](Geth源码系列：交易设计及实现.md)**
  - 解析以太坊交易的结构演进、交易池、费用机制及交易生命周期
- **[Geth 源码系列：EVM 设计及实现](Geth源码系列：EVM设计及实现.md)**
  - 讲解以太坊虚拟机（EVM）的架构、指令集、执行流程及合约调用机制
- **[Geth 源码系列：Blockchain 的设计及实现](Geth源码系列：Blockchain的设计及实现.md)**
  - 深入分析区块链模块的数据结构、区块同步、链管理等核心机制

## 贡献指南 🤝

如想为本仓库补充新的以太坊源码分析文章，请遵循以下流程：

1. 新建 markdown 文件，命名建议为 `Geth源码系列：xxx.md`
2. 图片请统一放在与文章同名的文件夹下，并在文中使用相对路径引用
3. 内容建议包括：理论背景、源码结构、关键流程、配图说明、参考资料等
4. 提交 Pull Request 前请确保图片链接可在本地正常预览
5. 在 PR 描述中简要说明文章内容

## License 📄

采用 [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html) 协议，任何人可以自由使用、修改和分发本仓库内容，但所有衍生作品必须继续以 [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html) 协议开源。
