# 产品简介



## 私有网络简介

私有网络 VPC（Virtual Private
Cloud）是属于用户的、逻辑隔离的网络环境。在私有网络中，可以创建指定网段的VPC，在VPC中创建子网并自主管理云资源，同时通过网络ACL实现安全防护。私有网络VPC为用户提供以下能力：

  - 通过规划VPC网段管理云上资源，并提供灵活扩容能力。
  - 通过绑定弹性IP、NAT网关，为云资源提供灵活访问 Internet能力。
  - 通过VPC网络互通，实现不同VPC之间的互通需求。
  - 通过VPC网络互通和高速通道，实现跨地域容灾。
  - 通过VPC网络互通和专线接入，实现数据中心无缝对接云上网络。
  - 通过绑定网络ACL，提供云资源间安全隔离和访问控制能力。 

## 私有网络组件

包含VPC、子网、NAT网关和网络ACL等组件：

**VPC**：私有网络 VPC（Virtual Private
Cloud）是属于用户的、逻辑隔离的网络环境。在私有网络中，可以创建指定网段的VPC，在VPC中创建子网并自主管理云资源。

**子网**：为了科学有效地划分VPC内的地址空间，将其划分为更细粒度的网络段。这些独立的网络段叫做子网（Subnet）。

**NAT网关**：NAT网关是一款企业级的VPC公网网关，可以让子网中未绑定EIP的云资源访问外网，也可配置端口转发规则使云资源对外提供服务。

**网络ACL**：是子网级别的安全策略，用于控制进出子网的数据流。用户可以通过设置出站规则和入站规则，对进出子网的流量进行精确控制
