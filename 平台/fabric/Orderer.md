### 什么是ordering

公链系统是不需要认证的，采用的都是概率共识，容易出现分叉

fabric采用ordering node和确定性共识算法，来防止分叉，每一个被peer验证过的
节点是最终和正确的

### Orderer nodes和Channel配置

Orderer节点不仅做排序的功能，它还保存了可以创建channel的组织，
