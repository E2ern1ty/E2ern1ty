# Hi, I'm E2ern1ty

## 开源贡献 · Pull Requests

<div align="center">

[![PRs](https://img.shields.io/badge/Total_PRs-28-0969da?style=for-the-badge&logo=github)](https://github.com/search?type=pullrequests&q=is%3Apr+author%3AE2ern1ty)
[![Merged](https://img.shields.io/badge/Merged-13-success?style=for-the-badge)](https://github.com/search?type=pullrequests&q=is%3Apr+is%3Amerged+author%3AE2ern1ty)
[![Repos](https://img.shields.io/badge/Upstream_Repos-12-8957e5?style=for-the-badge)](https://github.com/search?type=pullrequests&q=is%3Apr+author%3AE2ern1ty)
[![Apache](https://img.shields.io/badge/Apache_Projects-2-d2218f?style=for-the-badge)](https://github.com/apache/geaflow)

</div>

### [Apache GeaFlow](https://github.com/apache/geaflow) — 流图计算 + AI 检索 `8 PRs · 5 merged`

GeaFlow **AI 检索模块**的活跃贡献者，方向集中在 embedding 索引、向量/关键词检索与 DSL 连接器：

- merged · [#878](https://github.com/apache/geaflow/pull/878) · `feat(ai)` NearestNeighborIndex contract with linear default adapter
- merged · [#877](https://github.com/apache/geaflow/pull/877) · `test(ai)` golden tests for keyword index tokenization, serialization and lifecycle
- merged · [#832](https://github.com/apache/geaflow/pull/832) · `fix(ai)` inverted embedding value filter that dropped digit-free text
- merged · [#819](https://github.com/apache/geaflow/pull/819) · `feat` geaflow-dsl-connector-doris（Stream Load sink + partitioned source）
- merged · [#879](https://github.com/apache/geaflow/pull/879) · `fix(ci)` remove duplicate geaflow-cluster dependency in geaflow-mcp pom
- open · [#825](https://github.com/apache/geaflow/pull/825) · `feat(ai)` make the keyword search index resident and incremental
- open · [#858](https://github.com/apache/geaflow/pull/858) · `fix(ai)` invalidate an embedding vector when its text changes
- open · [#843](https://github.com/apache/geaflow/pull/843) · `feat` provenance model for facts, chunks, and evidence

### [NebulaGraph](https://github.com/vesoft-inc/nebula) — 分布式图数据库 C++ 核心 `5 PRs · 3 merged`

- merged · [nebula#5940](https://github.com/vesoft-inc/nebula/pull/5940) · `feat` Add Monitoring Metrics to NebulaGraph
- merged · [nebula#5958](https://github.com/vesoft-inc/nebula/pull/5958) · `feat` build-in log rotation leveraging glog
- merged · [nebula#5955](https://github.com/vesoft-inc/nebula/pull/5955) · `fix` cmake error in pr #5846
- open · [nebula#6101](https://github.com/vesoft-inc/nebula/pull/6101) · `feat` process_uptime_seconds metrics
- open · [nebula#5963](https://github.com/vesoft-inc/nebula/pull/5963) · `feat` transfer leader cmd
- open · [nebula-studio#818](https://github.com/vesoft-inc/nebula-studio/pull/818) · `feat` 图探索功能 — 节点扩展与智能磁力布局

### [Apache Maka](https://github.com/apache/maka) — Agent Runtime 性能优化 `4 PRs · 1 merged`

- merged · [#5096](https://github.com/apache/maka/pull/5096) · `perf(storage)` parallelize Claude Code transcript listing
- closed · [#5785](https://github.com/apache/maka/pull/5785) · `perf(storage)` serialize each AgentRun event once on append
- closed · [#5097](https://github.com/apache/maka/pull/5097) · `perf(runtime)` compile raw-text closing tags once in WebFetch
- closed · [#5098](https://github.com/apache/maka/pull/5098) · `chore` remove unreferenced private methods

### AI Agent 生态

- open · [camel-ai/camel#3829](https://github.com/camel-ai/camel/pull/3829) · `feat` MCP Code Execution support
- open · [langchain4j#4029](https://github.com/langchain4j/langchain4j/pull/4029) · `feat` Bedrock API timeout improvements
- open · [agentscope#1889](https://github.com/agentscope-ai/agentscope/pull/1889) · `perf` iteration extension events & general-purpose status events
- open · [oceanbase/powercontext#2000](https://github.com/oceanbase/powercontext/pull/2000) · `fix(desktop)` refresh contract manifests

### 其他

- merged · [jackwener/OpenCLI](https://github.com/jackwener/OpenCLI) × 3 — ChatGPT 本地图片上传、小红书话题/图片发布修复
- open · [MorvanZhou/zhongjie#2](https://github.com/MorvanZhou/zhongjie/pull/2) · `feat` map search city configurable via `AMAP_CITY`

<details>
<summary>全部 28 个 PR 一览（点击展开）</summary>

| 日期 | 项目 | PR | 状态 |
|---|---|---|---|
| 2026-10 | apache/geaflow | [#879](https://github.com/apache/geaflow/pull/879) fix(ci): remove duplicate dependency in geaflow-mcp pom | merged |
| 2026-10 | apache/geaflow | [#878](https://github.com/apache/geaflow/pull/878) feat(ai): NearestNeighborIndex contract | merged |
| 2026-10 | apache/geaflow | [#877](https://github.com/apache/geaflow/pull/877) test(ai): golden tests for keyword index | merged |
| 2026-10 | oceanbase/powercontext | [#2000](https://github.com/oceanbase/powercontext/pull/2000) fix(desktop): refresh contract manifests | closed |
| 2026-09 | apache/maka | [#5785](https://github.com/apache/maka/pull/5785) perf(storage): serialize AgentRun event once | closed |
| 2026-09 | apache/maka | [#5098](https://github.com/apache/maka/pull/5098) chore: remove unreferenced private methods | closed |
| 2026-09 | apache/maka | [#5097](https://github.com/apache/maka/pull/5097) perf(runtime): compile closing tags once | closed |
| 2026-09 | apache/maka | [#5096](https://github.com/apache/maka/pull/5096) perf(storage): parallelize transcript listing | merged |
| 2026-08 | apache/geaflow | [#858](https://github.com/apache/geaflow/pull/858) fix(ai): invalidate embedding on text change | open |
| 2026-08 | apache/geaflow | [#843](https://github.com/apache/geaflow/pull/843) feat: provenance model for facts/chunks/evidence | open |
| 2026-08 | apache/geaflow | [#832](https://github.com/apache/geaflow/pull/832) fix(ai): inverted embedding value filter | merged |
| 2026-08 | apache/geaflow | [#825](https://github.com/apache/geaflow/pull/825) feat(ai): resident & incremental keyword index | open |
| 2026-07 | apache/geaflow | [#819](https://github.com/apache/geaflow/pull/819) feat: dsl-connector-doris | merged |
| 2026-06 | agentscope-ai/agentscope | [#1889](https://github.com/agentscope-ai/agentscope/pull/1889) perf(event): iteration & status events | open |
| 2026-05 | jackwener/OpenCLI | [#1779](https://github.com/jackwener/OpenCLI/pull/1779) fix(xiaohongshu): attach real topics | merged |
| 2026-05 | jackwener/OpenCLI | [#1476](https://github.com/jackwener/OpenCLI/pull/1476) feat(chatgpt): local image uploads | merged |
| 2026-05 | jackwener/OpenCLI | [#1380](https://github.com/jackwener/OpenCLI/pull/1380) fix(xiaohongshu): improve image publishing | merged |
| 2026-03 | MorvanZhou/zhongjie | [#2](https://github.com/MorvanZhou/zhongjie/pull/2) feat: AMAP_CITY env var | open |
| 2026-02 | camel-ai/camel | [#3829](https://github.com/camel-ai/camel/pull/3829) feat: MCP Code Execution support | open |
| 2025-11 | langchain4j/langchain4j | [#4029](https://github.com/langchain4j/langchain4j/pull/4029) feat: Bedrock API timeout improvements | open |
| 2025-09 | vesoft-inc/nebula | [#6101](https://github.com/vesoft-inc/nebula/pull/6101) feat: process_uptime_seconds metrics | open |
| 2025-08 | vesoft-inc/nebula-studio | [#818](https://github.com/vesoft-inc/nebula-studio/pull/818) feat: 图探索 - 节点扩展与磁力布局 | open |
| 2024-10 | vesoft-inc/nebula | [#5963](https://github.com/vesoft-inc/nebula/pull/5963) feat: transfer leader cmd | open |
| 2024-10 | vesoft-inc/nebula | [#5958](https://github.com/vesoft-inc/nebula/pull/5958) feat: build-in log rotation via glog | merged |
| 2024-09 | vesoft-inc/nebula | [#5955](https://github.com/vesoft-inc/nebula/pull/5955) fix: cmake error | merged |
| 2024-09 | vesoft-inc/nebula | [#5940](https://github.com/vesoft-inc/nebula/pull/5940) feat: Monitoring Metrics | merged |
| 2023-12 | vesoft-inc/nebula-docs | [#2397](https://github.com/vesoft-inc/nebula-docs/pull/2397) Update 6.find-path.md | merged |
| 2017-08 | qlcoder-oreo/welcome2git | [#859](https://github.com/qlcoder-oreo/welcome2git/pull/859) first PR | open |

</details>

---

## 工作经历

- **哈啰** · Infra · ing
- **小红书** · 数据库研发工程师 · 2023 – 2025 —— 图数据库核心功能与性能优化、分布式存储架构
- **星环信息科技** · 数据库研发工程师 · 2021 – 2023 —— 分布式数据库关键组件、查询引擎性能优化

## 技术栈

![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Graph](https://img.shields.io/badge/-Graph_Database-217346?style=flat-square&logo=neo4j&logoColor=white)
![Distributed](https://img.shields.io/badge/-Distributed_Systems-6296f5?style=flat-square&logo=cloudflare&logoColor=white)

## 学术成果

- [ACM Digital Library Publication](https://dl.acm.org/doi/10.1145/3722212.3724449)

## 联系我

[![Email](https://img.shields.io/badge/Email-1144902127@qq.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:1144902127@qq.com)
[![GitHub](https://img.shields.io/badge/GitHub-E2ern1ty-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/E2ern1ty)
![Profile views](https://komarev.com/ghpvc/?username=E2ern1ty&color=blueviolet&style=flat-square)

---

<div align="center">
  <i>水边等鱼咬钩，仓库等 CI 跑绿 —— 都是好钓鱼佬</i>
</div>
