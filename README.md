

# 前言

## 版本

版本 | 发表时间 | 发表人 | 主要修改内容
---- | ---- | ---- |----
V1.0 | 20200301 | PingCAP  UE team | 第一版，有错误修改请邮件给 support@pingcap.com

TiDB 作为一款新一代的分布式关系型数据库，在日常运维上会和传统的关系型数据库有一定的区别，用户生态团队给大量 TiDB 用户提供了社区技术支持，我们根据大家经常提问的一些运维问题，进行收敛，会逐步推出《TiDB 运维手册》，前期计划包括 SOP、POC、Case Study 三个系列。

本期是 SOP（`Standard Operation Procedure`） 系列，是第一个版本，一共包括 10 个主题，每个主题我们都会通过标准的 step by step 步骤，来完整实现对某一个常见运维目标的操作。希望对大家有用，如果在操作过程遇到什么问题、或者你有什么需求，可以通过邮件、或者 AskTUG 进行讨论与反馈（ https://asktug.com/t/topic/33145 ），我们会定期 review 、修正内容、增加新的主题，进行版本迭代。

> V1.0 目录: 

  * [【SOP 系列 01】 Release-2.1 升级到 Release-3.0 线上集群升级](upgradeto3.0.md)
  * [【SOP 系列 02】 Prometheus 等监控组件迁移](Prometheuemigrate.md)
  * [【SOP 系列 03】在线表结构变更（Online DDL）](onlineddl.md)
  * [【SOP 系列 04】现有集群 TiKV 如何从单实例部署调整为多实例部署](multi-tikv.md)
  * [【SOP 系列 05】现有集群如何从单机房调整为跨机房部署](multi-idc.md)
  * [【SOP 系列 06】临时关机维护某线上主机](maintenance.md)
  * [【SOP 系列 07】如何在线开启/关闭 TiDB Binlog](switch-binlog.md)
  * [【SOP 系列 08】线上集群扩缩容操作及要点](scale.md)
  * [【SOP 系列 09】现网如何修改 TiDB、TiKV、PD 的 ip 地址](modify-ip.md)
  * [【SOP 系列 10】现网如何修改 TiDB、TiKV、PD 的 port](modify-port.md)



> TODO

虽然我们有了以上 SOP，但我们知道，这些一定不能覆盖所有用户所需的运维操作场景，因此我们希望能依靠整个社区共同构建，如果你有其他好的主题，并愿意将相关经验分享给社区，欢迎您给该项目提交文档 pr（建议参考[SOP模板](template.md)）。

    目前我们想到的待完善的主题，期待您的参与：
    
* SOP 之 -- 中控机损坏该怎么修复 ansible
* SOP 之 -- 如何把多套集群的监控整合为一套 Grafana
* SOP 之 -- 报警阈值的修改

    如果您有哪些需求，或者想到哪些常用的主题，也可以通过邮箱`support@pingcap.com`，或者给该 Git 项目提交 issue，或者在 asktug 上留言（ https://asktug.com/t/topic/33145 ）来反馈您的想法。
 
 
 
 
 
 
 
