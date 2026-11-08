# Free API Hunter — API Catalog Template

本文件用于人工登记 API 候选资源。它是空白模板，不代表其中任何 API 已通过核验。

## 使用规则

- 每个 API 单独建立一条记录。
- 只使用官方来源作为免费额度、计费和使用条款的最终证据。
- 证据不足时标记为 **E — Unverified**，不得推定免费。
- 只有 **A — Verified Free** 或 **B — Free with Conditions** 可进入零充值候选范围。
- **C** 和 **D** 排除；**E** 不测试；**F** 标记不可用。
- 不在本文件或任何公开文件中记录 API Key、密码、Token、Cookie 或请求头。
- 默认只做文档核验；未确认不会产生费用前，不发送真实 API 请求。

## 统一状态

| 代码 | 英文名称 | 中文含义 |
|---|---|---|
| A | Verified Free | 已核实零充值可用 |
| B | Free with Conditions | 有条件免费 |
| C | Card or Billing Required | 需要绑卡或启用账单 |
| D | Trial or Promotional Credits Only | 仅试用或活动额度 |
| E | Unverified | 尚未核实 |
| F | Unavailable | 已不可用 |

## API 资源登记表

复制以下表格，为每个候选 API 填写一份。未知信息填写 `Unknown`，不要猜测。

| 字段 | 填写内容 |
|---|---|
| name | API / 服务名称 |
| category | AI 视频 / AI 生图 / LLM / TTS / ASR / 搜索数据 / 文件处理 / 其他 |
| provider | 服务提供方 |
| official_homepage | 官方主页链接 |
| official_api_docs | 官方 API 文档链接 |
| official_pricing | 官方价格与免费额度链接 |
| official_terms | 官方服务条款链接 |
| authentication_required | 是否需要 API Key 或其他认证：Yes / No / Unknown |
| registration_required | 是否需要注册或审核：Yes / No / Unknown |
| payment_card_required | 是否需要绑卡：Yes / No / Unknown |
| billing_activation_required | 是否需要启用账单：Yes / No / Unknown |
| free_quota_and_period | 免费额度、计量单位、重置周期、适用模型或端点 |
| overage_behavior | 超额后拒绝 / 暂停 / 可能收费 / 不明确 |
| rate_limits | 请求频率、并发数及其他限制 |
| commercial_use | 商业用途许可及证据 |
| automation_allowed | 是否允许脚本、Agent、工作流或服务端自动调用 |
| data_policy | 数据留存、训练、隐私及处理规则 |
| region_restrictions | 地区、年龄、账户或组织限制 |
| verification_status | A / B / C / D / E / F |
| evidence_checked_at | YYYY-MM-DD |
| test_status | Not tested / Static review passed / Safe test passed / Failed |
| evidence_notes | 官方证据摘要、具体限制、未解决问题 |

## 单条资源记录（复制填写）

### [API 名称]

- **name**:
- **category**:
- **provider**:
- **official_homepage**:
- **official_api_docs**:
- **official_pricing**:
- **official_terms**:
- **authentication_required**:
- **registration_required**:
- **payment_card_required**:
- **billing_activation_required**:
- **free_quota_and_period**:
- **overage_behavior**:
- **rate_limits**:
- **commercial_use**:
- **automation_allowed**:
- **data_policy**:
- **region_restrictions**:
- **verification_status**: E — Unverified
- **evidence_checked_at**:
- **test_status**: Not tested
- **evidence_notes**:

## 核验检查清单

- [ ] 已找到官方 API 文档和实际端点
- [ ] 已找到官方价格及免费额度说明
- [ ] 已核实是否需要绑卡
- [ ] 已核实是否需要启用账单
- [ ] 已核实额度耗尽后的行为，不会自动扣费
- [ ] 已核实速率限制
- [ ] 已核实商业用途许可
- [ ] 已核实自动化调用许可
- [ ] 已核实数据处理和地域限制
- [ ] 已记录官方证据链接和核查日期
- [ ] 已按 A–F 统一标准分配状态
- [ ] 若未确认请求绝不会产生费用，保持 Not tested

## 明确禁止记录的内容

- API Key、Access Token、密码、Cookie
- Authorization 请求头或完整认证请求
- 个人身份信息及其他不必要的敏感数据
- 来源不明的共享密钥或账号
