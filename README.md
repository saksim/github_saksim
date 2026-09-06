<p align="center">
  <img src="assets/profile-banner.svg" alt="saksim — From market data to working systems. 5,005 commit records, 387 PRs opened, 86 GitHub Releases, 143 of 144 days with commits. 2026-04-15 to 2026-09-05 UTC, public and private repositories." width="100%" />
</p>

<p align="center">
  <b>电力市场 × Python 工程 × AI 协作</b><br />
  把复杂数据与算法，做成可回测、可追溯、可交付的工具。
</p>

<p align="center">
  <a href="https://github.com/saksim?tab=repositories">公开项目</a>
  ·
  <a href="https://github.com/saksim/omni_skill_pipeline">Omni Skill Pipeline</a>
  ·
  <a href="https://github.com/saksim/prompt_workflow">Prompt Workflow</a>
</p>

---

## ⚡ Hi, I'm saksim

我用 Python 和 AI 协作开发，长期关注**电力市场中的数据、预测、策略与收益计算**。

我喜欢把事情接完整：数据如何进入模型，预测如何进入业务，结果如何被核对，以及软件如何在另一台机器上可靠地运行。除了算法实现，我也持续投入数据同步、离线安装、旧环境兼容、权限、版本发布和回滚。

我的很多业务开发发生在私有仓库；这里用可公开的作品和固定区间统计，介绍我正在做的事。

## 🧭 What I build

| 方向 | 我反复解决的问题 |
| --- | --- |
| ⚡ **电力算法与决策工具** | 电价、负荷、价差信号，策略回测、收益口径，以及模型到 callable 的交付 |
| 🧱 **Python 工程与数据平台** | 增量同步、检查点、数据契约、离线依赖、旧运行环境和安装验证 |
| 🤖 **AI 协作工具** | 把任务拆解、Prompt、个人偏好和多模态证据组织成可复用的工作流 |
| 🔍 **可追溯的运行过程** | 明确输入、版本、权限和结果归属，让失败可定位、结果可核对 |

我也在探索法律工作台和双人互动产品，将工程能力用到更贴近日常的场景中。

## 🚀 Public work

### [Omni Skill Pipeline](https://github.com/saksim/omni_skill_pipeline)

把文本、音频、图像、视频和表格证据，整理成可复用、可审核的 Skill 工件。

覆盖证据结构、SkillGraph、人工审核、工件导出、安装包与发布验证。观察期内发布了 **7 个 internal 版本**；当前定位为内部试用与验证，外部上线仍有明确条件。

[查看内部版本 v0.2.6-internal.3 →](https://github.com/saksim/omni_skill_pipeline/releases/tag/v0.2.6-internal.3)

### [Prompt Workflow](https://github.com/saksim/prompt_workflow)

把一次模糊需求，逐步变成有范围、有约束、有验收标准的实施任务。

~~~text
decompose  →  optimize  →  implement
拆解问题       优化任务       生成实施 Prompt
~~~

提供 Python API、CLI、个人偏好和显式历史导入；运行时仅依赖 Python 3.11+ 标准库。**v1.0.0 已发布。**

[查看 v1.0.0 →](https://github.com/saksim/prompt_workflow/releases/tag/v1.0.0)

### [Law Helper · prototype](https://github.com/saksim/law_helper/tree/dev)

面向律师团队的工作台原型，探索材料解析、主体识别、线索报告、提醒、权限与审计。实现位于 dev 分支，仍以原型阶段介绍。

## 📊 A snapshot of my building rhythm

**2026-04-15—2026-09-05 · UTC · 144 天**

| 提交记录 | 创建 / 合并 PR | GitHub Release | 有提交记录的日期 |
| :---: | :---: | :---: | :---: |
| **5,005** | **387 / 335** | **86** | **143 / 144** |

<p align="center">
  <img src="assets/monthly-activity.svg" alt="Monthly non-merge commits: 199, 272, 882, 860, 1893, 553. PRs opened: 8, 11, 113, 41, 95, 119. Releases: 0, 4, 34, 16, 28, 4. April and September are partial months." width="100%" />
</p>

<details>
<summary>展开月度数字与统计口径</summary>

| 覆盖月份 | 非合并提交 | 创建 PR | 合并 PR | Release |
| --- | ---: | ---: | ---: | ---: |
| 4 月 15—30 日 | 199 | 8 | 4 | 0 |
| 5 月 | 272 | 11 | 8 | 4 |
| 6 月 | 882 | 113 | 106 | 34 |
| 7 月 | 860 | 41 | 42 | 16 |
| 8 月 | 1,893 | 95 | 59 | 28 |
| 9 月 1—5 日 | 553 | 119 | 116 | 4 |
| **合计** | **4,659** | **387** | **335** | **86** |

统计包含公开与私有仓库中可恢复的本人提交，涵盖默认分支、其他分支及 PR 历史，按完整 SHA 去重、按 UTC committer date 分月。5,005 条中含 346 条合并提交；另有 9 条作者、作者时间、消息及内容快照一致的重放记录。

PR 创建与合并分别按各自事件日期计算，335 个合并中有 2 个创建于区间之前。86 次 Release 包含 10 个 GitHub 预发布及内部版本，不等于 86 次生产部署。

这些数字反映开发活动，包含小步迭代、文档、测试和未合并工作，不能换算为独立功能数或工作小时数。4 月和 9 月只统计上述部分日期；这组数字也不是 GitHub 公开贡献图的口径。

</details>

## 🤝 How I work with AI

AI 协作已经进入我的日常开发流程：**明确问题 → 拆分任务 → 实现 → 验证 → 评审修复 → 交付**。

在上述区间，**2,575 条非合并提交带有 Codex 自标记**，另有 **156 个使用 codex 分支名的 PR**、**61 个通过 Codex 连接器创建的 PR**。这些是可观察的协作留痕，彼此可能重叠，不等于 AI 使用时长或 AI 生成代码占比。

我重视任务范围、可核对的证据、失败记录和清晰的发布阶段，也把这些习惯做进了自己的 Prompt 与 Skill 工具里。

## 🛠️ Tools & interests

**常用技术与工程场景**

<code>Python</code> · <code>SQL / MySQL</code> · <code>TypeScript</code> · <code>FastAPI / Django</code> · <code>Git</code> · <code>Windows / Linux</code>

**持续投入**

<code>Time-series forecasting</code> · <code>Energy markets</code> · <code>Data engineering</code> · <code>AI workflows</code> · <code>Reproducible delivery</code>

**正在探索**

多市场适配、离线强化学习、证据化决策，以及有明确隐私边界的 AI 交互产品。

---

<p align="center">
  <b>Build with AI. Verify with evidence. Deliver for use.</b><br />
  <sub>用 AI 协作，用证据验证，把工具交到使用者手中。</sub>
</p>

<p align="center">
  <sub><a href="https://github.com/saksim/github_saksim/blob/main/README.md">README 维护仓库与源文件</a></sub>
</p>
