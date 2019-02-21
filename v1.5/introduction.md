# ASCH v1.5.0 文档指引

## 1. v1.5.0 更新日志

### 1.1. 新功能

#### 1.1.1. 智能合约平台

- 详见智能合约介绍文档

#### 1.1.2. 跨链网关

- 新增网关防作恶机制；
- 新增网关候选人申请页和列表页；
- 新增网关储备金机制（追加/退回）；
- 新增网关储备金展示；

#### 1.1.3. 提案系统

- 新增"网关清算"提案类型；
- 新增“资源租赁比例调整”提案类型；
- 新增“每日免费NET额度调整”提案类型；
- 新增“Gas_Price调整“提案类型；

#### 1.1.4. 理事会

- 新增网关资产列表的多资产类型展示；
- 新增了理事会资产转账记录列表展示；

#### 1.1.5. 资源租赁机制（燃料费策略）

- 新增抵押XAS换取Asch Chain网络资源使用权策略；
- 新增Net Point (NET）作为普通交易手续费；
- 新增Energy Point （EP）作为智能合约平台燃料费；

#### 1.1.6. 其他

- 新增个人中心“查看公钥“的功能；
- 新增个人中心“查看主密钥二维码”的功能；
- 新增登录页面“根据浏览器语言调整默认语言“的功能；

### 1.2. Bug 修复及优化

#### 1.2.1. P2P通讯优化

- 优化了交易的广播机制；
- 优化了节点发现机制；

#### 1.2.2. 其他

- 优化了移动端转账记录中的交易ID不可点击的问题；
- 优化了区块浏览频道列表区块高度不可点击的问题；
- 优化锁仓换取投票权的展示样式；

## 2. v1.5 客户端用户手册

  点击下载[v1.5用户手册](./manual.pdf)

## 3. 智能合约开发指南

### 3.1. 智能合约开发环境准备

#### 3.1.1. 安装ASCH智能合约开发工具

为了帮助开发人员方便快速的开发智能合约，ASCH平台提供了一个基于vscode的开发工具。具体使用方法参见[智能合约开发工具](./asch-contract/dev-tools.md)

#### 3.1.2. 安装ASCH本地测试节点v1.5版

节点安装方式请参见[节点安装](../install/zh-cn.md)，需要注意的是，**v1.5使用的Node版本不能低于`v10.14`**,

#### 3.2. 智能合约编写

请参见[智能合约开发入门](./asch-contract/contract-introduction.md)

#### 3.3. 本地测试合约

使用编写合约单元测试用例，对合约代码进行基本测试。然后在本地节点上注册合约，并在本地节点上调用合约进行测试。在节点注册合约的，方法请参见《用户手册》中注册合约章节

#### 3.4. 在测试网上测试合约

在测试网上对智能合约进行测试，过程同本地节点测试。

## 4. 常见问题

- 测试网地址是什么？
  [1.5测试网址](http://testnet.asch.cn/)

- 如何获取测试用的XAS？
  请通过[水龙头](http://www.asch.io:3000/faucet/index.html/)领取

- bug反馈及建议
  请联系开发群(QQ群: 472708713 )管理员