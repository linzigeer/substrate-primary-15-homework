

比特币的UTXO（未花费交易输出）模型尤其引人注目。在比特币系统中，每一笔交易都会消耗一个或多个之前交易的输出，生成新的输出。这些新的输出成为新的UTXO，等待被未来的交易使用。UTXO模型是比特币区块链的核心，它确保了交易的可追溯性和不可双重支付性。每个UTXO都相当于一个“硬币”，可以被分割和重新组合，以满足不同金额的交易需求。

此外，白皮书还详细描述了工作量证明（Proof of Work）机制，这是比特币网络达成共识的关键技术。通过要求节点解决一个计算难题来创建新区块，不仅保证了区块链的安全性，也实现了一种去中心化的货币发行机制。

阅读了比特币白皮书后，感觉比特币本质就是一个分布式数据库。网络节点类似p2p，account内容分发存储验证，Hash函数防止篡改。比较疑问的是，比特币花费大量节点算力和时间，算出区块。人们与现实货币体系挂钩，是否有更好的方式，而无需浪费这些算力。