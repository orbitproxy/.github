# orbitproxy

**orbitproxy — 面向开发者/企业的多模态网关设施。**

一条可控链路，连接内网/本地服务、Webhook、MCP Agent 与 AI，从联调到生产都在同一套网关体系里快速达成。

- 官网：[orbitproxy.cc](https://orbitproxy.cc)
- 文档：[docs.orbitproxy.cc](https://docs.orbitproxy.cc/docs)
- 定价：[orbitproxy.cc/pricing](https://orbitproxy.cc/pricing)

## 产品

- [API 网关](https://docs.orbitproxy.cc/docs/gateway/overview)：把内网 / localhost 的 HTTP、TCP 服务分享到公网，叠加访问控制、限流和全链路观测。
- [Webhook 网关](https://docs.orbitproxy.cc/docs/gateway/webhook)：用固定公网域名接收微信支付等第三方回调，留存原文随时重放。
- [MCP 网关](https://docs.orbitproxy.cc/docs/mcp-gateway/overview)：聚合内网 MCP Server 暴露给 Cursor 等 Agent，监控拦截敏感调用。

## 开源仓库

- [orbitproxy-go](https://github.com/orbitproxy/orbitproxy-go)：orbitproxy 官方 Go SDK，[接入指南](https://docs.orbitproxy.cc/docs/client/overview)。
- [api-demo](https://github.com/orbitproxy/api-demo)：用于体验 orbitproxy API 网关的演示服务。

## 快速开始

阅读 [快速开始](https://docs.orbitproxy.cc/docs/start/quickstart)，几分钟内把你的本地服务接入 orbitproxy。
