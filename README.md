# Zhu Jiarui

**AI Agent · 数据工程 · 应用机器学习**

我关注可落地、可审计的 AI 与数据产品：让模型负责适合模型的判断与表达，让结构化数据、业务规则和测试保障关键结果的可靠性。

## 代表项目

| 项目 | 解决的问题 | 技术与验证 |
| --- | --- | --- |
| [China Fixed Income Lab](https://github.com/SuperrrrSpike/china-fixed-income-lab) | 中国债券晨报、一级发行跟踪、收益率曲线和利率风险分析 | Python、pandas、SciPy、Streamlit；可审计数据清单；50+ 项测试与多版本 CI |
| [Warehouse Agent](https://github.com/SuperrrrSpike/warehouse-agent) | 从真实拣选数据预测波次路线负荷，生成班前行动队列 | SQLite、scikit-learn、HistGradientBoosting；时间切分评估、漂移监控与回归门禁 |
| [FitCoach Agent](https://github.com/SuperrrrSpike/fitness-coach-agent) | 训练计划、饮食记录和食物图片识别的一体化健身助手 | Supabase、RLS、JavaScript、Deno Edge Function；服务端密钥隔离与配置注入回归 |
| [Charity Report Generator](https://github.com/SuperrrrSpike/charity-report-gen) | 将公益项目材料整理为内部审阅稿、捐赠人友好稿和结构化披露字段 | Python、LLM 结构化抽取、静态 Web；数字溯源、人工审批与只追加审计记录 |

## 工程原则

- 关键数值来自可追溯的数据管道，不让大模型直接编造或覆盖。
- 外部数据记录来源、许可证、校验值和处理口径。
- 密钥、个人数据、原始业务数据与代码仓库分离。
- 项目提供自动测试、CI、失败回退和明确的生产边界。

## 当前方向

- LLM Agent 编排、工具调用与状态管理
- 金融数据分析与决策支持
- 数据产品、机器学习评估与可解释输出
