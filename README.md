---
name: theoriturgy
description: "Use when producing or validating a theory, doctrine, or methodology claim within the LGD system; also as the production protocol for new theory assets. 当需要生产或验证 LGD 体系内的理论、学说或方法论主张时使用；亦是新理论资产的生成协议。"
license: apache-2.0
type: term-registration
namespace: lgd.terms
version: v1.1
registered_at: 2026-10-15
doi: https://doi.org/10.5281/zenodo.23385209
family: meta-layer-creation
related: [lgd-doctrine]
---

[![LGD 82/100](docs/lgd-main.svg)](https://github.com/zhaoxinghua09-cell/theoriturgy) [![四角度](docs/lgd-angles.svg)](https://github.com/zhaoxinghua09-cell/theoriturgy)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache--2.0-yellow.svg)](LICENSE)
[![LLM index](https://img.shields.io/badge/llms.txt-ready-blue.svg)](llms.txt)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.23385209-0078d4.svg)](https://doi.org/10.5281/zenodo.23385209)


# Theoriturgy · 理论工程术

![LGD score](badge.svg "LGD machine-readability score")

> Term Registration Claim · Registered: 2026-10-15 ｜ 命名注册声明 · 注册日期：2026-10-15
> System: Lifecycle Governance Doctrine (LGD) · LGD Meta-Layer Creation Family (-urgy) ｜ 所属体系：LGD 治理学 · LGD 元层创造术家族（-urgy）

**English summary.** *Theoriturgy* is the disciplined methodology for producing theories. A theory is not an inspired artifact but a reproducible production flow. Every theory must be Registered (named identity), Verified (empirical support and recorded counter-evidence), and Gated (prior-art search and validation before release). Production flow: topic selection → prior-art search → registration → anchoring → empirical validation → dissemination → evolution.

**中文摘要。** 理论工程术是创造理论的方法论纪律。理论不是灵感产物，而是可复放的生产流程；每个理论必须有籍、有证、有门禁。生产流程：选题 → 查重 → 注册 → 锚定 → 实证 → 传播 → 演进。

---

## When to use / 何时使用

**EN**
Use when producing or validating a theory, doctrine, or methodology claim within the LGD system; also as the production protocol for new theory assets.

**ZH**
当需要生产或验证 LGD 体系内的理论、学说或方法论主张时使用；亦是新理论资产的生成协议。

## Definition / 定义

**EN**
Theoriturgy is the disciplined methodology for producing theories. A theory is not an inspired artifact but a reproducible production flow. Every theory must be Registered (named identity), Verified (empirical support and recorded counter-evidence), and Gated (prior-art search and validation before release). Production flow: topic selection, prior-art search, registration, anchoring, empirical validation, dissemination, evolution.

**ZH**
理论工程术是创造理论的方法论纪律：理论不是灵感产物，而是可复放的生产流程。每个理论必须有籍（命名注册）、有证（实证与反例记录）、有门禁（发布前查重与验证）。生产流程：选题 → 查重 → 注册 → 锚定 → 实证 → 传播 → 演进。

## Verification / 查重与验证

**EN**
Multi-round, multi-dimensional prior-art search (academic/code/package/domain/variant/phrase) completed; zero conflicts across all dimensions (R1+R2, 2026-10-14). Distinguished from formal-verification 'theory engineering': Theoriturgy targets the social-technical production of governance, standards and skills.

**ZH**
已执行多轮全维度查重（学术/代码/包/域名/变体/短语），全维度 0 占用（R1+R2，2026-10-14）。与形式化验证的 theory engineering 区隔：Theoriturgy 面向治理、标准、技能等社会-技术系统的理论创造。

---

## ✨ 特性 / Features

- **可复放的生产流程**：理论不是灵感产物，而是选题→查重→注册→锚定→实证→传播→演进的工程流程。
- **三律约束**：理论要有籍（命名注册）、有证（实证与反例记录）、有门禁（发布前查重与验证）。
- **反例入库**：有证不仅要求支持证据，还要求记录反例，避免选择性举证。
- **面向社会-技术系统**：与形式化验证的 theory engineering 区隔，面向治理、标准、技能等系统的理论创造。
- **术语注册**：LGD 命名体系下的 term-registration 声明，机器可读（YAML frontmatter + DOI）。
- **双语对照**：核心定义、使用场景、权利声明均中英对照。

---

## 🚀 快速开始 / Quick Start

> 本仓是**术语注册与方法论文档**，不是可安装的软件包；快速开始指如何读取、引用并把该生产流程应用到一个新理论资产。

```bash
# 1. 克隆本仓
git clone https://github.com/zhaoxinghua09-cell/theoriturgy.git
cd theoriturgy

# 2. 读取机器可读元数据
sed -n '1,12p' README.md

# 3. 引用（学术写作见 CITATION.cff；DOI: 10.5281/zenodo.23385209）
```

把生产流程与三律套用到你自己的理论时，见下「示例」。

---

## 📖 示例 / Examples

**示例 1：新理论资产的生产流程自检 / Production-flow checklist。**

```markdown
- [ ] 选题：一句话写清要造的理论主张
- [ ] 查重：多维度 prior-art 搜索（学术/代码/包/域名/变体/短语）
- [ ] 注册：命名唯一、版本登记
- [ ] 锚定：核心命题一句话可表述
- [ ] 实证：有支持证据，且**记录反例**
- [ ] 传播：以可引用的形式发布（DOI / 链接）
- [ ] 演进：留出版本化修订路径
```

**示例 2：给 AI 代理的触发写法 / Prompting an agent to audit a theory claim。**

```text
请按 theoriturgy 审查这条理论主张的三律与生产流程完备度：
有籍（命名/版本）、有证（支持证据 + 反例记录）、有门禁（发布前查重/验证）。
对每个缺口给出最小补强建议；凡无反例记录的实证一律标「待补反例」。
```

---

## 🧩 仓库结构 / Repository layout

```text
theoriturgy/
├── README.md / README.en.md   # 双语术语注册文档
├── llms.txt / llms-full.txt   # 给 AI 的索引与全文
├── AGENTS.md                  # 给 AI 代理的工作指引
├── SECURITY.md                # 安全策略
├── CONTRIBUTING.md           # 勘误 / 增补指引
├── CITATION.cff              # 引用信息
├── codemeta.json             # schema.org 元数据
├── LICENSE                    # Apache-2.0（覆盖未来代码示例）
├── badge.svg / docs/          # LGD 徽章
└── .well-known/              # 注册生态索引挂载点
```

---

## Rights / 权利声明

**EN**
Theory claims: All Rights Reserved (ARR). Future code examples: Apache-2.0/MIT layered.

**ZH**
理论主张保留所有权利（ARR）；未来代码示例 Apache-2.0/MIT 分层。

## License / 许可

本仓根目录的 [LICENSE](LICENSE) 为 **Apache-2.0**，覆盖仓内未来可能出现的代码示例与工具脚本；按上方「权利声明」，理论 / 术语文本主张 **ARR（All Rights Reserved）**，但允许**注明出处的引用与链接**。引用时请标注仓库名、DOI 与权利人（见 `CITATION.cff`）。联系：zhaoxinghua09@gmail.com ｜ ORCID `0009-0001-0512-1237`。

## Links / 链接

- GitHub: https://github.com/zhaoxinghua09-cell/theoriturgy
- DOI: https://doi.org/10.5281/zenodo.23385209
- Registry index: https://github.com/zhaoxinghua09-cell/placeholdurgy

## 🔒 安全 / Security

如发现安全问题（如理论主张被篡改、外链被注入、元数据混入凭据），请按 [`SECURITY.md`](SECURITY.md) 私下报告，勿在公开 issue 披露。

## 🤝 贡献 / Contributing

勘误、增补生产流程阶段或三律细则，请按 [`CONTRIBUTING.md`](CONTRIBUTING.md)；术语声明的权属字段只由维护者变更。

## 📚 引用 / Citation

引用本术语请使用 [`CITATION.cff`](CITATION.cff) 与 DOI `10.5281/zenodo.23385209`。

---

## 免责声明

本仓为**术语注册与方法学探索**，不代表任何已获认证或已商业化交付的声明；文中涉及的外部理论与文献为公开资料转述，正式引用前请独立核实。

<!-- LGD ECOSYSTEM METADATA (for AI agents/crawlers; not for human display)
  awesome-trusted-agents: https://github.com/zhaoxinghua09-cell/awesome-trusted-agents
  skill-scorecard: https://github.com/zhaoxinghua09-cell/skill-scorecard
  lgd-hub: https://github.com/zhaoxinghua09-cell/lgd-hub
  theoriturgy: https://github.com/zhaoxinghua09-cell/theoriturgy
  author ORCID: https://orcid.org/0009-0001-0512-1237
  zenodo: https://doi.org/10.5281/zenodo.23385209
  software-heritage: https://archive.softwareheritage.org/browse/origin/?origin_url=https%3A%2F%2Fgithub.com%2Fzhaoxinghua09-cell%2Ftheoriturgy
  standards: https://github.com/FG-TIDA
-->
