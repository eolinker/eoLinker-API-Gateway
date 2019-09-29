![](https://data.eolinker.com/6IvqUL3cb40efeca8cf4fdc034286bd946b130b45d50bd8.jpg)

[![Gitter](https://badges.gitter.im/goku-api-gateway/community.svg)](https://gitter.im/goku-api-gateway/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) [![Go Report Card](https://goreportcard.com/badge/github.com/eolinker/goku-api-gateway)](https://goreportcard.com/report/github.com/eolinker/goku-api-gateway) [![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/3214/badge)](https://bestpractices.coreinfrastructure.org/projects/3214) ![](https://img.shields.io/badge/license-GPL3.0-blue.svg)

Goku API Gateway （中文名：悟空 API 网关）是一个基于 Golang 开发的微服务网关，能够实现高性能 HTTP API 转发、多租户管理、API 访问权限控制等目的，拥有强大的自定义插件系统可以自行扩展，并且提供友好的图形化配置界面，能够快速帮助企业进行 API 服务治理、提高 API 服务的稳定性和安全性。

# 概况

- [为什么要使用Goku](#为什么要使用Goku "为什么要使用Goku")
- [产品特性](#产品特性 "产品特性")
- [基准测试](#基准测试 "基准测试")
- [产品截图](#产品截图 "产品截图")
- [安装使用](#安装使用 "安装使用")
- [企业支持](#企业支持 "企业支持")
- [关于我们](#关于我们 "关于我们")
- [授权协议](#授权协议 "授权协议")

# 为什么要使用Goku
Goku API Gateway （悟空 API 网关）是运行在企业系统服务边界上的微服务网关。当您构建网站、App、IOT甚至是开放API交易时，Goku API Gateway 能够帮你将内部系统中重复的组件抽取出来并放置在Goku网关上运行，如进行用户授权、访问控制、流量监控、防火墙、静态数据缓存、数据转换等。

Goku API Gateway 的社区版本（CE）拥有完善的使用指南和二次开发指南，代码使用纯 Go 语言编写，拥有良好的性能和扩展性，并且内置的插件系统能够让企业针对自身业务进行定制开发。

并且 Goku API Gateway 支持与 EOLINKER 旗下的 API Studio 接口管理平台结合，对 API 进行全面的管理、自动化测试、监控和运维。

总而言之，Goku API Gateway 能让业务开发团队更加专注地实现业务。

[![Stargazers over time](https://starchart.cc/eolinker/goku-api-gateway.svg)](#)

# 产品特性
- **集群管理**：多个 Goku API Gateway 节点，配置信息自动同步，支持多集群部署。
- **界面管理后台**：通过清晰的UI界面对网关的各项配置进行管理。
- **负载均衡**：对后端服务器进行负载均衡。
- **服务发现**：从 Consul、Eureka 等注册中心发现后端服务器。
- **转发代理**：通过转发请求来隐藏真实后端服务，支持 Rest API、Webservice。
- **多租户管理**：根据不同的访问终端或用户来判断。
- **访问鉴权**：Basic、API Key等。
- **API监控**：请求数据统计。
- **API告警**：支持通过API、邮件方式对异常的服务进行告警。
- **健康检查**：动态发现异常的网关节点以及后端节点，自动切断转发流量并转到其他正常后端服务。
- **异常自动重启**：网关节点异常时会自动尝试重载重启。
- **灵活的转发规则**：支持模糊匹配请求路径，支持改写转发路径等。
- **插件系统**：基于 Go 语言的插件系统，可以快速开发高性能的插件。
- **性能扩展**：网关节点拥有良好的处理性能，支持水平扩展节点数量满足不同的性能需求。
- **日志**：详细的系统日志、请求日志等。
- **Open API**：提供 API 对网关进行操作，便于集成。
- ...

# 基准测试
![](https://data.eolinker.com/p7NFG6lb4c73b26cc880e838fe45aa31bc037b7415e3770.jpg)

[基准测试详情](https://help.eolinker.com/#/tutorial/?groupID=c-362&productID=19#tip7 "Benchmark Detail")

# 产品截图

[查看产品截图](https://github.com/eolinker/goku-api-gateway/blob/master/docs/CONSOLE_PREVIEW_CN.md "查看产品截图")

# 安装使用
* [部署教程](https://help.eolinker.com/#/tutorial/?groupID=c-351&productID=19 "部署教程")
* [快速入门教程](https://help.eolinker.com/#/tutorial/?groupID=c-307&productID=19 "快速入门教程")
* [源码编译教程](https://help.eolinker.com/#/tutorial/?groupID=c-350&productID=19 "源码编译")

# 企业支持
Goku API Gateway EE（企业版本）拥有更强大的功能、插件库以及专业的技术支持服务，如您需要了解可以通过以下方式联系我们。
- **中国大陆服务支持电话**：400-616-0330 法定工作日（9:30-18:00）
- **申请企业版免费试用及演示**：[预约试用](https://wj.qq.com/s2/2150032/4b5e "预约试用")
- **市场合作邮箱**：market@eolinker.com
- **购买咨询邮箱**：sales@eolinker.com
- **帮助文档**：[help.eolinker.com](help.eolinker.com "help.eolinker.com")
- **QQ群**: 725853895

# 关于我们
EOLINKER 是领先的 API 管理服务供应商，为全球超过3000家企业提供专业的 API 研发管理、API自动化测试、API监控、API网关等服务。是首家为ITSS（中国电子工业标准化技术协会）制定API研发管理行业规范的企业。

官方网站：[https://www.eolinker.com](https://www.eolinker.com "EOLINKER官方网站")
免费下载PC桌面端：[https://www.eolinker.com/pc/](https://www.eolinker.com/pc/ "免费下载PC客户端")

# 授权协议
```
Copyright 2017-2019 Eolinker Inc.

Licensed under the GNU General Public License v3.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at http://www.gnu.org/licenses/gpl-3.0.html

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS,WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and limitations under the License.
```