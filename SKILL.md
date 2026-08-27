---
name: amazon-aigc-product-visual-system
description: Build a controlled, compliant, and conversion-led Amazon visual system for Listing images and A+ Content. Uses AI for environmental assets only, integrates real product assets in Photoshop, and governs claims, QA, and performance iteration.
version: "5.0"
language: zh-CN
---

# Amazon AIGC Product Visual System V5.0

> **AI Asset Generation × Real Product Integration × Conversion Strategy × Claims Governance × Amazon Compliance**

## Operating Philosophy

**AI 负责生成“环境”，设计师负责生成“商业事实”，运营负责“转化与迭代”。**

| 角色 | 负责范围 |
| --- | --- |
| AI | 人、场景、光线、氛围、构图、情绪 |
| 设计师（PS） | 产品、尺寸、参数、结构、文字、图标、Claims、品牌资产、合规 |
| 运营 | 用户问题、卖点优先级、转化路径、数据反馈、迭代 |

## 使用边界

- 本系统适用于 Amazon Listing 图片与 A+ 内容的视觉生产；不将 AI 直接生成的产品、参数或文字作为最终商业素材。
- 平台、站点、类目和品牌政策会变化。发布前必须以目标站点 Seller Central 的当前要求、产品类目政策和实际证据为准。
- 不得编造产品参数、测试结果、认证、比较结论、评论、排名或用户反馈。

## 工作输入与交付物

### 必备输入

1. Target Market、Buyer Persona、Usage Scenario。
2. Competitor Visuals、Review/Q&A Mining、Return Reason 与 Search Term（如可获取）。
3. 真实产品白底 PNG：极光白、干净、无水印、已抠图。
4. 真实产品资料：尺寸、重量、电池容量、噪音、档位、配件和实际出货清单。
5. 人物母版图（按 Persona Localization 确定）。
6. Claims 证据表：每个卖点必须能追溯至规格、测试或认证材料。

### 应交付内容

- Listing 主图及副图方案。
- A+ 模块信息架构与对应成图。
- AI 场景底图与真实产品合成源文件。
- Claims Evidence Ladder 与 QA 记录。
- 上线后的 CTR、CVR、Session、Unit Session %、广告与评论反馈迭代记录。

---

## 01. Market Intelligence｜市场情报

### Persona Localization｜人物本地化原则

不强制规定种族。根据目标市场、产品定位和消费场景完成生活方式本地化。

**Localization ≠ Race。** 高质量海外视觉设计关注的是年龄、生活方式、穿搭气质、居住环境和使用场景，而非肤色标签。

| 市场 | 示例方向 |
| --- | --- |
| US Amazon | 25–35 岁城市年轻女性；办公室、通勤、户外与自然生活方式 |
| Japan Amazon | 小户型居家、桌面办公、通勤与极简生活 |
| Germany | 功能理性、参数、耐用和环保材料 |
| Middle East | 高温、室内空调环境与家庭场景 |

### Objection Mining｜用户异议挖掘

从 1–3 星 Review、Q&A、退货原因、Search Term 与竞品评论中提取真实痛点，并将每项痛点映射到对应图片或 A+ 模块。

示例：手持风扇用户问 “Is it loud?”，可规划“工作环境适用性”的性能证据；用户问 “Can I put it in my bag?”，可规划便携性与收纳场景。最终文案必须以证据强度决定，不得把用户问题本身写成未经证明的性能承诺。

---

## 02. Conversion Strategy｜转化策略

### System A：Listing Image Strategy｜Listing 图片策略

#### Main Image｜主图

- 纯白背景：RGB 255/255/255。
- 展示实际销售产品；严禁使用 AI 生成产品、mockup、插画或占位图。
- 产品至少占画面 85%，完整可见且不裁切。
- 不添加额外文字、图形、水印或色块；产品固有品牌标识应真实保留。
- 文件尺寸须满足 Amazon 当前技术要求；生产建议长边至少 1600 px，以支持清晰放大。
- 最终以目标站点、类目当前 Product Image Requirements 为准。

#### Secondary Images｜副图

- 构图与比例可灵活设计，推荐 1600 × 1600。
- 用于展示卖点、场景、功能与购买风险消除信息。
- 遵守一图一核心诉求：不堆叠无关信息。

#### 7-Image Decision Funnel｜七图决策漏斗

| 图片 | 阶段 | 核心问题 | 内容示例 |
| --- | --- | --- | --- |
| Image 1 | Identify | 我卖的是什么？ | 纯白底主图 |
| Image 2 | Value | 为什么我需要？ | 核心价值场景图 |
| Image 3 | Scenario | 我什么时候使用？ | 使用场景图 |
| Image 4 | Proof | 你凭什么这么说？ | 真实功能、结构或材质图 |
| Image 5 | Mechanism | 它为什么有效？ | 性能证据图 |
| Image 6 | Fit | 适不适合我的生活？ | 尺寸、重量或便携图 |
| Image 7 | Risk Removal | 买回来会不会踩坑？ | 包装清单、兼容性、使用/充电方式与必要注意事项 |

### System B：A+ Content Strategy｜A+ 内容策略

#### Eligibility Check｜资格检查

```text
是否具备 Premium A+ 资格？
├─ 是：Premium Module Planning
└─ 否：Basic A+ Planning
```

#### 图片尺寸

- Basic A+ 常见图片模块：970 × 300、970 × 600 等；具体以所选模块后台要求为准。
- Premium A+ 常见核心图片模块：1464 × 600 等；具体以所选模块后台要求为准。
- 不将上述尺寸视为所有 A+ 模块的统一规格。

#### Custom A+ Visual Module Library｜自定义 A+ 视觉模块库

> 这是自定义的设计系统，而非 Amazon 官方模块名称。它基于当前可用模块完成视觉策略映射。

| 编号 | 模块 | 设计核心 | 规则 |
| --- | --- | --- | --- |
| M01 | Hero Banner | 大图 + 大标题 | 聚焦品牌/产品核心主题 |
| M02 | Single Lifestyle | 单场景展示 | 强化使用代入感 |
| M03 | 3 Features | 一个视觉主题 + 三个相关证据点 | 不是 Listing 的“一图一卖点” |
| M04 | 4 Scenes | 使用场景扩充 | 场景须真实且本地化 |
| M05 | Exploded View | 爆炸图 | 严禁 AI 生成；仅用 CAD、实拍或工程图 |
| M06 | Detail | 材质细节 | 基于实际产品 |
| M07 | Dimension | 尺寸参数 | 真实数据 + PS 制作 |
| M08 | Brand Comparison | 同品牌比较 | 禁止竞品品牌、Logo、“Other Brands”及贬低竞品 |
| M09 | What's Included | 包装清单 | 以实际出货清单为准 |
| M10 | Brand Story | 品牌故事 | 使用已获授权的品牌资产 |
| M11 | FAQ / Objection Handling | 异议解决 | 基于 Review/Q&A 洞察与证据 |
| M12 | Usage Instruction | 操作说明 | 仅使用真实步骤与安全信息 |

**A+ 原则：一模块一核心主题，可包含多个相关证据点。**

---

## 03. Asset Production｜资产生产

### AI Restrictions｜AI 绝对禁区

1. AI 不承担最终商业文本生产职责。所有进入 Listing/A+ 的标题、卖点、参数、图标、引线与序号，均由设计师在可编辑环境完成，并通过 Claims QA。
2. 严禁 AI 生成最终产品。最终产品必须由真实产品素材合成；发现 AI 产品与真实产品不一致时，AI 产品部分必须删除并重做。
3. 爆炸图、尺寸图、结构图、认证材料与性能证据，必须来自真实资料、实拍、工程资料或经验证测试数据。

### 分离式工作流

#### 第一阶段：AI｜Pose First

AI 只解决人物、场景、姿势、光线与构图。手部必须处于可后期合成状态：

- 手自然张开或形成轻握姿势。
- 手掌朝向预期产品位置。
- 手指与手腕角度自然。
- 避免生成可识别的产品设计；如必须使用占位物，使用低细节、无品牌、无可识别设计的简化占位物，并以手部自然度为优先。

#### 第二阶段：PS｜Commercial Compositing

导入真实产品 PNG，完成：缩放、旋转、透视匹配、遮挡关系、接触阴影、环境光、色温、反射与景深。

#### 第三阶段：QA

核对 AI 产品与真实产品是否混淆。若结构、颜色、按键、网罩、手柄或配件不一致，删除 AI 生成产品区域并重新合成。

### AI Person Disclosure｜AI 人物披露

- 对于写实 AI 生成人物，发布前核对 Amazon 当前 Seller Central 对合成/AI 人物素材的披露和元数据要求。
- 若当前要求适用 `contains-synthetic-performer` XMP metadata，则在提交 Listing/A+ 前按要求写入。
- 真人、真人经 AI 编辑、无人物或非写实人物是否适用，须按当期政策与具体素材事实判断。

---

## 04. Commercial Compositing｜商业合成

### 三段式产品合成 SOP

1. **Level 1：Pose First** — 生成自然手势与场景底图。
2. **Level 2：Product Integration** — 合成真实产品 PNG，并校正透视、比例、旋转、遮挡、接触阴影、环境光、色温、景深与反射。
3. **Level 3：Occlusion Reconstruction** — 重建前后遮挡关系。

```text
人物背景
↓
真实产品
↓
前景手指
↓
接触阴影
↓
环境光修正
```

这构成真正的 **Commercial Product Integration**。

---

## 05. Information Design｜信息设计

- **Typography**：使用无衬线字体（如 Montserrat / Proxima Nova），并保持全案统一。
- **Icons**：使用极简线框图标。
- **Infographics**：Listing 副图遵循“一图一核心诉求”；A+ 遵循“一模块一核心主题”。
- **Data Visualization**：尺寸图、对比图和数据图必须有真实数据支持。

---

## 06. Claims Governance｜Claims 治理

### Claims Evidence Ladder｜卖点证据阶梯

| 等级 | Claim 类型 | 示例 | 所需证据 |
| --- | --- | --- | --- |
| Level 1 | 硬参数 | 5000mAh、180g、3 Speeds、USB-C | 规格书、产品实测或工程资料 |
| Level 2 | 功能描述 | Adjustable airflow、Foldable handle、Rechargeable | 产品结构与实际功能 |
| Level 3 | 性能 Claim | Quiet、Powerful、Long-lasting | 测试数据、测试方法、内部记录或第三方报告 |
| Level 4 | 比较 Claim | 50% quieter、2× stronger | 明确比较对象、测试条件与数据来源 |
| Level 5 | 权威/认证 Claim | Certified、Tested、Recommended | 认证机构、证书、年份与具体依据 |
| Level 6 | 高风险营销词 | #1、Best、No.1、Best-selling、Top-rated | 禁止或高风险，未经合法充分依据不得使用 |

“Powerful / Compact”并非天然禁止，但不得让文案暗示未经证据支持的客观性能事实。

---

## 07. Amazon Compliance｜Amazon 合规

### Main Image Policy

- 纯白背景。
- 真实产品。
- 无额外文字、Logo、水印或图形。
- 产品至少占画面 85%。

### A+ Policy

- 不进行竞品品牌比较。
- 比较图表仅限同品牌产品之间。
- 禁止 Competitor Brand、Logo、“Other Brands”及“Better than X”等贬低竞品表述。

### AI Person Disclosure

- 写实 AI 生成人物的 metadata/披露要求具有时效性；上线前必须再次核对。

---

## 08. QA｜四层 QA 检查

### QA-01：Product Accuracy｜产品准确性

核对型号、颜色、结构、按键、配件、尺寸与数量。确认全套素材中只出现同款极光白风扇，且按键、网罩、手柄均 100% 一致。

### QA-02：Claims Accuracy｜Claims 准确性

每个数字、性能词、比较词、认证词和品牌词都应能追溯到证据。

### QA-03：Amazon Compliance｜Amazon 合规

核对主图、A+、AI 人物元数据/披露、文案、图片尺寸、禁止内容与类目特殊规则。

### QA-04：Conversion QA｜转化 QA

- **3 秒识别**：用户能否在 3 秒内说出这张图卖什么？
- **Mobile Readability**：手机预览时标题是否可读、产品是否可识别？
- 复核信息层级、场景代入、卖点差异、用户异议与竞品差异。

---

## 09. Performance Optimization｜性能优化

```text
设计
↓
上线
↓
CTR / CVR / Session / Unit Session %
↓
广告数据 / 用户评论 / 竞品视觉
↓
A/B Test
↓
迭代图片
```

没有真实数据，绝不编造结果。该反馈闭环是作品集与普通 AI 设计展示的关键差异。

---

## Portfolio Showcase｜作品集展示

不要只展示成品；展示工业能力。

1. **AI Base**：AI 生成人物与场景底图。
2. **Product Integration**：真实产品 PNG 的透视、遮挡与光影合成过程。
3. **Final**：排版完成并通过合规检查的最终 Listing/A+ 页面。

核心卖点文案：

> AI负责视觉环境生成，设计师负责产品真实性、信息架构与商业合成。

---

## Reusability｜复用指南

适用于风扇、加湿器、榨汁杯、喂食器、香薰机等小家电。根据用户决策树调整卖点与场景：

| 产品 | 决策路径示例 |
| --- | --- |
| 加湿器 | 空气干 → 细雾量 → 噪音 → 水箱容量 → 卧室场景 |
| 喂食器 | 出差 → 卡粮风险 → 定时定量 → 手机查看 |
| 榨汁杯 | 鲜榨 → 榨汁效果 → 清洗难度 → 续航 |

人物、排版逻辑、出图参数与合规清单可复用；卖点、场景与证据必须按产品重新验证。

---

## V4 → V5 核心修正说明

| V4 内容 | V5 修正 | 修正原因 |
| --- | --- | --- |
| 产品占比 85% 以上 | 保留，并标注以目标站点/类目当前要求为准 | 避免写成跨站点永久模板 |
| AI 不能生成文字 | AI 不承担最终商业文本生产职责 | 更精准，不误写为平台硬规则 |
| 白色占位物思路 | 改为 Pose First | 优先保证手部自然与可合成性 |
| 单图只能 1 个产品 | 改为产品一致性原则 | 尺寸对比、包装清单和多角度图可合法出现多个同款产品 |
| 一图一卖点 | 一图一核心诉求 / 一模块一核心主题 | 与 M03 3 Features 不冲突 |
| 欧美白人女性 | Persona Localization | Localization ≠ Race |
| 角色库固定权重 | 改为测试参数 | 不同模型的权重含义不同 |
| A+ M01–M12 | 明确为自定义模块库 | 不与 Amazon 官方模块混淆 |
| M08 Comparison | Brand Comparison，仅限同品牌 | 避免竞品比较违规 |
| Claims Matrix | Claims Evidence Ladder，六级体系 | 区分性能、比较与认证 Claim |
| AI 人物 metadata | 标注时效性及发布前复核 | 政策可能更新 |
| QA | 四层 QA：产品 / Claims / 合规 / 转化 | 从设计视角升级为运营闭环 |
| Performance Feedback | 新增 | 补齐设计与运营迭代闭环 |
| Mobile QA | 新增 | 覆盖移动端浏览场景 |
| Objection Mining | 新增 | 以 Review/Q&A 发现真实异议 |

## 最终原则

**AI 负责生成“环境”，设计师负责生成“商业事实”，运营负责“转化与迭代”。**

