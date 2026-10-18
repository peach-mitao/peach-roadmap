# Peach 开发规划

这里记录 Peach 维护者安排的项目开发任务。用户问题和功能建议请到[应用仓库的 Issues](https://github.com/peach-mitao/peach/issues)提交。

- [需求看板](https://github.com/orgs/peach-mitao/projects/7/views/1)：统一查看反馈和开发任务的处理状态。
- [路线图](https://github.com/orgs/peach-mitao/projects/7/views/3)：查看计划阶段、优先级和交付进度。
- [维护者待办](https://github.com/peach-mitao/peach-roadmap/issues)：本仓库的完整任务列表。
- [安装与下载](https://github.com/peach-mitao/peach#readme)：使用说明、安装包和反馈入口。

所有事项共用一个公开看板。P0 为紧急、P1 为优先、P2 为常规、P3 为低优先级；近期、后续、探索表示计划阶段，不构成交付日期承诺。个人馆藏、账号与设备操作保留在私有清单。

## 关联实现与验收

实现代码和 PR 放在 `peach-mitao/peach`。PR 正文使用独立关联行，例如 `Refs peach-mitao/peach-roadmap#1`。仓库名与编号共同标识任务，GitHub 的 Issue 关联和完整 Issue URL 也可使用。

PR 合入后，开放任务进入待验证；有下载制品的版本实际包含实现后，看板填写发布版本。完成验收再关闭 Issue。应用仓库事件触发同步，并每 6 小时检查两个仓库；本仓库不保存看板凭据。

任务类型、标签、优先级和验收范围见各 Issue；[同步规则](https://github.com/peach-mitao/peach/blob/master/docs/PROJECT_BOARD.md)见应用仓库文档。
