# Platform Engineering Glossary

该仓库作为《平台工程洞察》的一部分，用于帮助对「平台工程」相关概念感兴趣的读者，建立对相关知识的基本了解。

如有兴趣协作编写，可以参考下方的术语模版，直接编辑以更新该内容。

## 术语模板

```markdown
## 术语名称（中文）

- **缩写**: 术语英文名称
- **英文名称**：术语英文名称
- **相关术语**：相关术语/需要区分的术语

### 定义

术语定义/概述/解释 (如引用第三方权威定义，直接注明出处)

### 参考资料

| 名称         | 作者 / 组织 | 简介                                 |
| ------------ | ----------- | ------------------------------------ |
| [标题](链接) | Gartner     | 一段简短的介绍，介绍该资料都讲了什么 |
```

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 平台工程

- **缩写**：PE
- **英文名称**：Platform Engineering
- **相关术语**：`软件工程`，`DevOps`，`平台`，`平台团队`，`平台工程师`

### 定义

Platform engineering is the discipline of building and operating self-service internal developer platforms (IDPs) for software delivery and life cycle management.
~ By Gartner

Platform engineering is the act of building tools and workflows that provide self-service capabilities to developers. Those tools and workflows are called an Internal Developer Platform (IDP).

The definition of platform engineering is the continuous development, building, and maintenance of infrastructure (like toolchains and workflows) in order to build self-service solutions. That enables value stream development teams to deliver quickly and provide consistency to the rest of the organization.
~ By Puppet

### 参考资料

| 名称                                                                                                                                               | 作者 / 组织                    | 简介 |
| -------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------ | ---- |
| [What is Platform Engineering？](https://www.gartner.com/en/articles/what-is-platform-engineering)                                                 | Gartner                        |      |
| [What is Platform Engineering？](https://www.puppet.com/blog/what-platform-engineering)                                                            | Puppet                         |      |
| [What is platform engineering?](https://platformengineering.org/blog/what-is-platform-engineering)                                                 | Platform Engineering Community |      |
| [What is platform engineering?](https://humanitec.com/platform-engineering)                                                                        | Humanitec                      |      |
| [What Is Platform Engineering? The Concept Behind the Term](https://www.liatrio.com/blog/what-is-platform-engineering-the-concept-behind-the-term) | Liatrio                        |      |
| [What is Platform Engineering?](https://www.pulumi.com/what-is/what-is-platform-engineering/)                                                      | Pulumi                         |      |
| [What is platform engineering? A quick introduction](https://circleci.com/blog/what-is-platform-engineering/)                                      | Circle CI                      |      |
| [CNCF Platforms White Paper](https://tag-app-delivery.cncf.io/whitepapers/platforms/)                                                              | CNCF                           |      |

## 内部开发者平台

- **缩写**：IDP
- **英文名称**：Internal Developer Platform

## 内部开发者门户

- **缩写**：IDP
- **英文名称**：Internal Developer Portal

## 自服务

- **英文名称**：Self-service

## 开发者体验

- **缩写**：DevEx
- **英文名称**：Developer Experience

## 运维人员体验

- **缩写**：OS
- **英文名称**：Operator Experience

### 参考资料

| 名称                                                                                                                                                     | 作者 / 组织                              | 简介 |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- | ---- |
| [Monoliths vs Microservices is Missing the Point—Start with Team Cognitive Load](https://itrevolution.com/articles/team-cognitive-load-team-topologies/) | Matthew Skelton, Manuel Pais             |      |
| [Designing for the Operator Experience](https://medium.com/statuscode/designing-for-the-operator-experience-21b63db8143)                                 | [Adam Hevenor](https://medium.com/@aHev) |      |

## 平台团队 |

- **英文名称**：Platform Team

## 平台工程团队

- **英文名称**：Platform Engineering Team

## 平台工程师

- **英文名称**：Platform Engineer

## 平台产品经理

- **英文名称**：Platform Product Manager

## 开发者控制面

- **缩写**：DCP
- **英文名称**：Developer Control Plane

## 基础设施即代码

- **缩写**：IaC
- **英文名称**：Infrastructure as Code

## 平台即产品

- **缩写**：PaaP
- **英文名称**： Platform as a Product

## 动态配置管理

- **缩写**：DCM
- **英文名称**：Dynamic Configuration Management

## 黄金路径

- **英文名称**：Golden Path

### 参考资料

| 名称                                                                                                                                                                                            | 作者 / 组织                                  | 简介 |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- | ---- |
| [Designing Golden Paths](https://cloud.redhat.com/blog/designing-golden-paths)                                                                                                                  | Raffaele Spazzoli / RedHat                   |      |
| [Golden Paths: Building process architectures for software](https://tanzu.vmware.com/golden-paths)                                                                                              | VMware                                       |      |
| [How We Use Golden Paths to Solve Fragmentation in Our Software Ecosystem](https://engineering.atspotify.com/2020/08/how-we-use-golden-paths-to-solve-fragmentation-in-our-software-ecosystem/) | Gary Niemen / Spotify                        |      |
| [Creating the Golden Path](https://medium.com/startup-by-design/goldenpath-156c1ff291ab)                                                                                                        | [Rana Chakrabarti](https://medium.com/@rana) |      |

## 团队拓扑

- **英文名称**：Team Topologies

## 认知负荷

- **英文名称**：Cognitive Load

## 知识迁移

- **英文名称**：Knowledge Transfer

## 最薄可行平台

- **缩写**：TVP
- **英文名称**：Thinnest viable platform

### 参考资料

| 名称                                                                                                                                                     | 作者 / 组织                  | 简介 |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------- | ---- |
| [What is a Thinnest Viable Platform (TVP)?](https://teamtopologies.com/key-concepts-content/what-is-a-thinnest-viable-platform-tvp)                      | Team Topologies              |      |
| [Monoliths vs Microservices is Missing the Point—Start with Team Cognitive Load](https://itrevolution.com/articles/team-cognitive-load-team-topologies/) | Matthew Skelton, Manuel Pais |      |

## 平台

- **英文名称**：Platform

### 参考资料

| 名称                                                                                            | 作者 / 组织                                                                           | 简介 |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ---- |
| [What Is a Platform, Anyway?](https://builtin.com/founders-entrepreneurship/what-is-a-platform) | [Mae Rice](https://builtin.com/authors/mae-rice) / Builtin                            |      |
| [What Is a Platform?](https://www.lifewire.com/what-is-a-platform-4155653)                      | [Stanley Goodner](https://www.lifewire.com/stanley-goodner-4035048)                   |      |
| [Platform](https://www.webopedia.com/definitions/platform/)                                     | [Siji Roy](https://www.webopedia.com/author/sroy/) / webopedia                        |      |
| [Platform](https://www.techopedia.com/definition/3411/platform-computing)                       | [Margaret Rouse](https://www.techopedia.com/contributors/margaret-rouse) / techopedia |      |
| [软件领域平台是什么](https://www.jianshu.com/p/0403dd74b092)                                    | [梅西爱骑车](https://www.jianshu.com/u/ea0462d5074c)                                  |      |

## 平台企业

- **英文名称**：Platform Company

### 参考资料

| 名称                                                                                                          | 作者 / 组织                                                            | 简介 |
| ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---- |
| [What is a Platform Company?](https://york.ie/blog/what-is-platform-company-moving-from-product-to-platform/) | [Kyle York](https://york.ie/blog/author/kyork/)                        |      |
| [What Is A Platform Company And Why It Matters](https://fourweekmba.com/platform-company/)                    | [Gennaro Cuofano](https://fourweekmba.com/author/thefourweekmbateam/)  |      |
| [Platform Business Model](https://www.applicoinc.com/blog/what-is-a-platform-business-model/)                 | [Alex Moazed](https://www.applicoinc.com/author/amoazed/)              |      |
| [Platform Business Models In A Nutshell](https://fourweekmba.com/platform-business-models/)                   | [Gennaro Cuofano ](https://fourweekmba.com/author/thefourweekmbateam/) |      |
| [The Platform Economy](https://innovator.news/the-platform-economy-3c09439b56)                                | [Jennifer L. Schenker](https://medium.com/@jennifer_45057)             |      |
