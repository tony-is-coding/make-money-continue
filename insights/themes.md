# 持续追踪主题

> 主编维护，每周更新

## 活跃主题

### Agent 能力模块化（Skill Registry → 连接层生态）
- **首次发现**: 2026-05-18
- **热度**: ★★★★★（极高）↑
- **当前判断**: Agent 生态竞争焦点已从"模型能力"转向"连接层"——谁能让 Agent 接入更多系统，谁就赢得生态战
- **证据链**:
  - 2026-05-18: GitHub Trending agent-skills (+1,244 stars)、scientific-agent-skills (+610)、12-factor-agents (+359) 同时爆发
  - 2026-05-18: Anthropic 发布 10 个金融服务 Cowork/Claude Code 插件
  - 2026-05-19: Anthropic 收购 Stainless（API Spec → 多语言 SDK + MCP Server 的自动生成工具），补全 Agent 连接层
  - 2026-05-19: InsForge（开源 Agent 后端平台）在 Hacker News 热门，Agent-native PaaS 品类形成
- **周度评估（W20）**: 从社区爆发升级为平台方收购整合。Stainless 收购意味着 Anthropic 将 MCP 工具链纳入官方体系，生态标准化进入加速期。升级为极高热度。
- **下一步观察**: OpenAI/Google 如何应对 Stainless 被收购？开源 API-to-MCP 替代方案何时出现？

### AI 物理基础设施瓶颈
- **首次发现**: 2026-05-18
- **热度**: ★★★★★（极高）
- **当前判断**: 物理瓶颈仍在，但软件层开始找到绕过方案——Modal 的 40x 冷启动优化证明"算力效率"可以部分缓解硬件供给不足
- **证据链**:
  - 2026-05-18: NextEra Energy 668 亿美元收购 Dominion Energy
  - 2026-05-18: Anthropic 与 SpaceX 签署算力合作
  - 2026-05-19: Modal 发布 GPU 推理冷启动 40x 优化方案（LP + FUSE + C/R + CUDA-checkpoint），5000 万副本验证
  - 2026-05-19: Google + Blackstone 规划 50 亿美元 AI 云合资
- **周度评估（W20）**: 硬件层（能源并购、算力合作）和软件层（推理优化）同时推进。物理约束是真实的，但软件优化正在争取时间。维持极高热度。
- **下一步观察**: Nvidia 财报（5/21）是否确认算力需求仍在指数增长？Modal 类推理优化是否改变 GPU 采购节奏？

### Anthropic 平台化战略
- **首次发现**: 2026-05-18
- **热度**: ★★★★★（极高）
- **当前判断**: Anthropic 正在构建 AI 时代的"iOS"——模型 + 协议（MCP）+ 工具链（Stainless）+ 企业服务 + 算力 = 全栈 Agent 平台，护城河从"模型能力"转向"生态锁定"
- **证据链**:
  - 2026-05-04: 与 Blackstone/Hellman & Friedman/Goldman Sachs 成立企业 AI 服务合资公司
  - 2026-05-05: 发布 10 个金融服务插件 + Microsoft 365 集成
  - 2026-05-06: 与 SpaceX 签署算力合作
  - 2026-05-13: 推出 Claude for Small Business
  - 2026-05-14: PwC 部署 Claude Code/Cowork 给 3 万人
  - 2026-05-18: SandboxAQ 药物发现模型接入 Claude
  - 2026-05-19: 收购 Stainless，将 SDK/MCP 工具链纳入官方体系
  - 2026-05-19: Anthropic 联合创始人将在梵蒂冈与教皇 Leo XIV 共同发布 AI 通谕
- **周度评估（W20）**: 5 月内 7 个重大战略动作，收购 Stainless 是技术深度最高的一步——从"向外扩张"转向"向内加固"。生态锁定效应开始形成。维持极高热度。
- **下一步观察**: Stainless 收购后 OpenAI/Google 的 SDK 替代方案？企业 Agent 部署的实际 ROI 数据？

### 地缘冲突与 AI 投资的剪刀差
- **首次发现**: 2026-05-18
- **热度**: ★★★☆☆（中高）
- **当前判断**: 剪刀差持续——地缘风险暂时降温（Trump 叫停打击）但结构性通胀未解（10Y 反升），AI 投资继续加速
- **证据链**:
  - 2026-05-18: 10Y 国债收益率 4.6%，全球债券抛售
  - 2026-05-18: 伊朗战争担忧推高油价
  - 2026-05-19: Trump 叫停伊朗打击，油价 -1.85% 至 $102.45，但 10Y 反升至 4.623%
  - 2026-05-19: 伊朗推出比特币担保的霍尔木兹海峡航运保险（Bloomberg）
  - 2026-05-19: Google-Blackstone 50 亿 AI 合资 + Meta 7000 人 AI 重组，AI 投资不减反增
- **周度评估（W20）**: 地缘风险从"即时威胁"降级为"持续背景噪音"，但利率反升说明市场定价的是结构性通胀而非单一事件。剪刀差信号持续。维持中高热度。
- **下一步观察**: Nvidia 财报后 AI 板块是否出现分化？6 月美联储议息会议措辞？

### AI 编码代理生产化
- **首次发现**: 2026-05-18
- **热度**: ★★★★☆（高）
- **当前判断**: AI 编码代理已从"单 Agent 辅助"进化为"多 Agent 协作流水线"，安全领域率先验证规模化 ROI
- **证据链**:
  - 2026-05-18: Mozilla 用 Claude Mythos Preview 月修 423 个安全漏洞（常规 25 个），14 倍效率提升
  - 2026-05-18: PwC 3 万人部署 Claude Code
  - 2026-05-19: Cloudflare Project Glasswing——50 个并发 Agent 组成 8 阶段安全审计流水线
  - 2026-05-19: InsForge 为 Agent 提供完整后端操作能力
- **周度评估（W20）**: Cloudflare 的 50 并发 Agent 流水线是"多 Agent 协作"的生产级证据。从单 Agent 到多 Agent 协作是质变。维持高热度。
- **下一步观察**: 更多企业的多 Agent 部署案例？Agent 协作的标准化框架？

### AI 安全攻防军备竞赛（新）
- **首次发现**: 2026-05-19
- **热度**: ★★★★☆（高）
- **当前判断**: AI 已具备自主构建 exploit chain 的能力，攻防平衡正在倾斜，"AI 安全即服务"将成为新赛道
- **证据链**:
  - 2026-05-19: Cloudflare Project Glasswing 证明 Mythos 能自主构建漏洞利用链、编写/编译/执行 PoC
  - 2026-05-19: Cloudflare 结论——单 Agent 仅覆盖 0.1% 攻击面，需要多 Agent 并行架构
  - 2026-05-19: IEEE Spectrum 报道 Voice AI 系统易受隐藏音频攻击
  - 2026-05-19: Grafana Labs 遭客窃取代码（TechCrunch），开源基础设施成为攻击目标
- **周度评估（W20）**: 首次发现即有多个强证据点。AI 安全不是未来威胁，是当下现实。标记为高热度。
- **下一步观察**: 独立 AI 安全创业公司是否获得大额融资？Cloudflare 8 阶段架构是否被其他公司复制？

## 已归档主题

（暂无）
