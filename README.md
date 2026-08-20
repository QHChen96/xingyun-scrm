# 星云 SCRM

企业微信私域经营操作系统。围绕客户关系、获客、客户运营、营销触达、服务和合规构建的商业化平台。

公开产品说明与官网真源。核心工程仓库为私有仓库 `iscrm`。

## 产品定位

星云 SCRM 服务三类客户：

- 使用企业微信开展私域经营的中小商家
- 需要白标、代运营或渠道分销的代理商
- 需要本地数据、独立部署和 License 控制的中大型企业

交付形态：

| 形态 | 部署 | 品牌 | 权益 |
| --- | --- | --- | --- |
| SaaS 标准版 | 平台多租户云 | 默认品牌 | Subscription |
| 白标 OEM 版 | 平台多租户云 | Partner / Brand | Subscription + Brand |
| 私有化部署版 | 客户 DeploymentInstance | 客户品牌 | License |

明确不做：自营商城与支付收银台、智能外呼、个人微信协议 / 群控 / 自动加人。

## 能力范围

- 企微凭证接入与服务商授权双模式
- 活码、线索、客户、标签、公海、群与客户继承
- OneID、客户同意、营销偏好与数据主体请求
- 群发、SOP、旅程、朋友圈、短信与互动雷达
- 可重算多触点归因、营销实验
- 客服、会话存档、质检、审批与审计
- 会员、积分账本、外部订单镜像与 RFM
- OpenAPI、Webhook、导入迁移、白标与私有化

## 工程结构

```
apps/server          Java 后端（com.chenqinhao.iscrm）
apps/tenant-web      租户管理端
apps/platform-web    平台运营端
contracts/openapi    HTTP 机器契约
功能设计/            产品规格与页面矩阵
```

界限上下文：Tenancy、Identity & Access、Entitlement、Channel、Acquisition、Customer、Engagement、Conversation、Customer Value、Governance、Analytics、Data Exchange。

## License

私有软件。未授权不得复制或再分发。
