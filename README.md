# GameFramework

在此 Unity 工程中逐步完成一款可交付的游戏。用户与 Agent 对齐产品和方案，由 Agent 实现、验证并接受独立审查。当前玩法与首发平台尚待确定，见[项目定义](Docs/Project/01_项目定义.md)。

## 使用工程

使用 Unity `6000.0.60f1` 打开仓库根目录，场景入口为 `Assets/Scenes/Root.unity`。首次克隆后若子模块尚未初始化，在仓库根执行 `git submodule update --init --recursive`；已有工作区先检查并保留本地修改。启动前确认包解析与所需平台模块，具体配置见[工程现状](Docs/Project/02_工程现状.md)。

[GameInterface](Packages/GameInterface/README.md)、[GameSDK](Packages/GameSDK/README.md)、[GameHub](Packages/GameHub/README.md) 是独立子模块。包 README 说明定位，实际已提供能力以源码为准；模块边界与已有需求入口见[架构与模块](Docs/Project/03_架构与模块.md)。

## 开展工作

可以直接问：**“当前可以执行哪些任务？请按推荐顺序列出。”** 也可以直接点名工作或提出新需求。

| 需要了解什么 | 入口 |
|---|---|
| 怎样查询、启动或继续 | [任务使用指南](Docs/Project/04_任务使用指南.md) |
| 产品目标与近期推进 | [项目定义](Docs/Project/01_项目定义.md)、[近期工作](Docs/Project/08_近期工作.md) |
| 代码归属与模块入口 | [架构与模块](Docs/Project/03_架构与模块.md) |
| 需求、Task 和模块说明怎样维护 | [文档组织规范](Docs/Project/07_文档组织规范.md) |
| Agent 怎样协作和交付 | [Agent 协作协议](Docs/Project/05_Agent协作协议.md) |
| 工程修改和验证要求 | [工程实施与验收标准](Docs/Project/06_工程实施与验收标准.md) |

Agent 执行入口见 [AGENTS.md](AGENTS.md)。
