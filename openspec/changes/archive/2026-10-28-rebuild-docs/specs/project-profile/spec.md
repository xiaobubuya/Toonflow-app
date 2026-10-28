## Purpose

登记 Toonflow 的项目身份与本工作区定位，作为进入该仓库的第一份结构化说明；
实现细节以上游文档为准，这里只写「是什么、归谁、在本工作区怎么用」。

## ADDED Requirements

### Requirement: 项目身份与许可
系统 SHALL 明确记录项目身份：开源 AI 短剧 / 漫剧 / 视频创作平台（Bun + Electron），上游仓库 `HBAI-Ltd/Toonflow-app`，许可 MIT。
本仓库是上游的 fork/镜像，SHALL 保留上游许可与归属声明，不得移除 `LICENSE*`、
`ATTRIBUTION.md` 等文件。

#### Scenario: 能查到项目身份
WHEN 新成员进入本仓库
THEN 从本 spec 得知项目是什么、上游在哪、许可是什么。

#### Scenario: 保留上游归属
WHEN 修改或分发本仓库
THEN 上游许可与归属文件保持完整。

### Requirement: 本工作区中的角色
**独立项目，不在 muyaya 相册系统的运行链路内**；本 fork 用于本地试用与上游同步。与相册系统无共享后端、无部署关系。

#### Scenario: 部署关系可查
WHEN 有人想知道这个仓库是否参与 muyaya 线上部署
THEN 本 spec 给出明确答案与部署真相所在位置。

### Requirement: 文档归属
文档权威来源 SHALL 以如下为准，本 `openspec/` 不得复制或替代上游文档：
上游 `README.md`、`AGENTS.md`、`CONTRIBUTING.md`、`docs/` 为权威来源。 上游是多平台镜像（GitHub/Gitee/AtomGit），fork 以 GitHub 为准。

#### Scenario: 不重复维护上游文档
WHEN 需要了解内部实现
THEN 去上游文档查，而不是在本 `openspec/` 里找（这里只记录工作区差异）。
