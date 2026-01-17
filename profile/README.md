# Golutra

<p align="center">
  <a href="#en">English</a> | <a href="#zh">中文</a>
</p>

<a id="en"></a>
## English

> Golutra = A system that runs, flows, and transitions continuously.

Golutra is an engineering-first open-source organization focused on long-term evolution. We care about systems that run reliably, flow smoothly, and transition through verified change.

### Mission and Long-term Goals

- Mission: Build reusable, sustainable, and maintainable open-source systems and toolchains with engineering rigor.
- Vision: Enable systems to run continuously and evolve safely, while keeping collaboration and technology flowing.
- Long-term goals:
  - Deliver a stable, composable set of core components and platform capabilities.
  - Maintain a clear technical roadmap and cadence to reduce unplanned change.
  - Build a contribution system that is participatory, verifiable, and reviewable.

### Programming Orientation

> Intuitive thinking drives us. Users want things simple and usable; we take on the complex logic and heavy configuration.

### Technical Focus

Organized around Run / Flow / Transition:

- Run: runtimes, core libraries, performance and reliability engineering, system tooling.
- Flow: data pipelines, event-driven systems, messaging and stream processing, observability.
- Transition: architecture evolution, automated delivery, engineering efficiency, and platformization.

### Repository Naming

Use lowercase letters and hyphens. Names should reflect layer and domain, avoid vague abbreviations.

| Type | Prefix | Description | Example |
| --- | --- | --- | --- |
| Core components | core- | Base libraries and runtime capabilities | core-runtime |
| Platform | platform- | Platform and engineering infrastructure | platform-ci |
| Services | service- | Independent services or APIs | service-registry |
| Apps | app- | User- or developer-facing applications | app-console |
| Data/AI | data- / ai- | Data or AI-related projects | data-pipeline |
| Tooling | tooling- | CLI and developer tools | tooling-cli |
| Docs/Spec | docs- / spec- | Documentation, standards, and guides | docs-handbook |
| Experiments | playground- | Experimental projects | playground-raft |

### Project Layers and Evolution Strategy

#### Layers

- Core: Technical foundation with strong stability requirements.
- Platform: Build, delivery, and engineering capabilities.
- Services: Domain and platform services.
- Apps: User and developer experience.
- Tooling/Docs: Tooling and knowledge base.

#### Lifecycle

Each project should declare a lifecycle stage (repo tag or README label):

- Incubating: Validate direction; frequent changes expected.
- Active: Stable development; continuous improvement.
- Stable: Core capability established; compatibility first.
- Maintenance: Low change; fixes only.
- Deprecated: Migration planned with replacement and timeline.
- Archived: Read-only.

### Contribution Flow (Issue / PR / Review / Release)

1. Issue
   - Use templates; state background, goal, scope, and acceptance criteria.
   - Maintainers triage with labels and priority.
2. PR
   - Small, single-purpose changes; link to the issue.
   - Must include change summary and verification.
3. Review
   - At least one maintainer approval.
   - Focus on correctness, maintainability, security, and performance.
4. Release
   - Use SemVer.
   - Maintain clear release notes and changelog.

### Engineering Standards (Code, CI, Tests, Docs)

- Code: Consistent formatting and linting; readability and consistency first.
- CI: PRs must pass build, tests, and static checks; add security scans when needed.
- Tests: New features require tests; prioritize critical paths.
- Docs: README documents purpose, scope, and usage; significant changes include design notes or ADRs.

### Governance and Collaboration

- Maintainers own roadmap and technical direction; major changes are discussed openly.
- Use Issues/Discussions for public communication; record key decisions in docs.
- New projects must declare goals, scope, and lifecycle stage.

### License and Security

- License: AGPL-3.0.
- Provide SECURITY.md for reporting and response.

<a id="zh"></a>
## 中文

> Golutra = A system that runs, flows, and transitions continuously.  
> Golutra = 一个持续运行、持续流动、持续转变的系统。

Golutra 是一个面向长期演进的工程化开源组织。我们关注系统的“运行、流动、转变”：稳定运行的基础能力、持续流动的数据与协作、以及可验证的架构演进。

### 使命与长期目标

- 使命：以工程化方法构建可复用、可持续、可维护的开源系统与工具链。
- 愿景：让系统具备持续运行与可演进的能力，让协作与技术流动更自然。
- 长期目标：
  - 构建一组稳定、可组合的核心组件与平台能力。
  - 形成清晰的技术路线与演进节奏，减少偶发性和不可控变更。
  - 建立“可参与、可验证、可复盘”的开源协作体系。

### 编程导向

> 直觉性思考驱动我们。用户只要简单好用，复杂逻辑与繁琐配置由我们来承担。

### 技术方向

围绕“运行、流动、转变”三条主线布局：

- 运行（Run）：运行时、基础库、性能与可靠性工程、系统工具。
- 流动（Flow）：数据管道、事件驱动、消息与流处理、中间件与可观测性。
- 转变（Transition）：架构演进、自动化交付、工程效率与平台化能力。

### 仓库命名规范

统一使用小写字母与连字符，体现层级与领域，避免含糊缩写。

| 类型 | 命名前缀 | 说明 | 示例 |
| --- | --- | --- | --- |
| 核心组件 | core- | 基础库与运行时能力 | core-runtime |
| 平台能力 | platform- | 平台与工程基础设施 | platform-ci |
| 服务 | service- | 独立服务或 API | service-registry |
| 应用 | app- | 面向用户的应用 | app-console |
| 数据/AI | data- / ai- | 数据或 AI 相关项目 | data-pipeline |
| 工具 | tooling- | CLI、开发工具 | tooling-cli |
| 文档/规范 | docs- / spec- | 规范、文档、指南 | docs-handbook |
| 实验 | playground- | 试验性项目 | playground-raft |

### 项目分层与演进策略

#### 分层

- Core：组织的技术基座，强稳定性要求。
- Platform：构建与交付体系、工程化能力。
- Services：领域服务与平台服务。
- Apps：用户或开发者体验相关应用。
- Tooling/Docs：工具链与知识体系。

#### 演进阶段

每个项目都标注生命周期阶段（可作为仓库标签或 README 标记）：

- Incubating：验证方向，可能频繁调整。
- Active：稳定推进，功能持续完善。
- Stable：核心能力成型，兼容性为先。
- Maintenance：低频变更，修复为主。
- Deprecated：计划迁移，提供替代方案与时间表。
- Archived：停止维护，仅保留记录。

### 贡献流程（Issue / PR / Review / Release）

1. Issue
   - 使用模板，明确背景、目标、范围、验收标准。
   - 维护者进行标签与优先级归类。
2. PR
   - 小步提交、单一目标、关联 Issue。
   - 必须包含变更说明与验证方式。
3. Review
   - 至少 1 位维护者审查通过。
   - 关注正确性、可维护性、安全与性能。
4. Release
   - 采用语义化版本（SemVer）。
   - 维护清晰的 Release Notes 与变更记录。

### 工程规范（代码、CI、测试、文档）

- 代码规范：统一格式化与 lint；风格以可读性与一致性优先。
- CI：PR 必须通过构建、单测与静态检查；必要时引入安全扫描。
- 测试：新功能必须有对应测试，关键路径优先覆盖。
- 文档：README 说明用途、边界与使用方式；重大变更需补充设计说明或 ADR。

### 治理与协作

- 维护者负责 roadmap 与技术方向；重大变更需公开讨论。
- 对外沟通以 Issue/Discussion 为主，重要决策记录到 docs。
- 新项目需说明目标、边界与生命周期阶段。

### 许可证与安全

- 许可证：AGPL-3.0。
- 建议提供 SECURITY.md，明确安全问题反馈渠道与响应流程。
