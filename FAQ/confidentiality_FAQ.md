## 保密性
&nbsp;

##### 如何实现事务和业务逻辑的保密性？

安全模块与成员服务模块一起工作以向部署在链网络上的任何数据记录和业务逻辑提供访问控制服务。

当在链网络上部署代码时，无论其是用于定义业务合同还是资产，其创建者都可以对其进行访问控制，使得只有由授权实体发出的交易才会由链验证者处理和验证。

原始交易记录永久存储在分类帐中。虽然非机密交易的内容对所有参与者开放，但是机密交易的内容使用仅为其发起者，验证者和授权审计员知道的秘密密钥加密。只有秘密密钥的持有者才能解释交易内容。



##### 如果商业合同的所有利益相关者都不是验证者怎么办？

在一些业务场景中，可能需要合同逻辑的完全保密性 - 从而只有合同交易对手和审计师可以访问和解释其链码。在这些情况下，反对方将需要分离一个只有自己作为验证者的新子链。