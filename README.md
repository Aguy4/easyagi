# 通用智能（EasyAGI）演示视频

[![官网](https://img.shields.io/badge/官网-easyagi.com.cn-blue)](https://easyagi.com.cn/)
[![文档](https://img.shields.io/badge/文档-easyagi.com.cn%2Fdoc-green)](https://easyagi.com.cn/doc/)

本仓库收录 **通用智能** 平台的官方演示视频合集，用于在 GitHub 上展示平台能力、典型开发流程与实战案例。视频按主题分目录存放，每个目录配有文字说明（详见各目录下的 `README.md`）。

---

## 关于通用智能平台

**通用智能** 是一款高效、灵活的低代码 / 无代码智能体开发平台，以**数据、模型、流程设计**为核心，提供从数据标注、模型训练到智能体构建、部署的一站式解决方案。

### 核心功能模块

| 模块 | 说明 |
|------|------|
| 🎯 **工作流设计** | 可视化拖拽构建智能体逻辑流，支持多种节点、多模态数据、条件分支与一键部署 |
| 📝 **数据标注** | 基于 CVAT 的专业标注工具，支持 2D/3D 图像、视频等格式 |
| 🎨 **页面设计** | 可视化界面设计，快速构建智能体交互页面 |

- **官网**：[https://easyagi.com.cn/](https://easyagi.com.cn/)
- **文档**：[https://easyagi.com.cn/doc/](https://easyagi.com.cn/doc/)

---

## 目录结构

```
easyagi/
├── README.md                          # 本文件：项目总览与视频索引
├── model-mcp-skill-knowladge/         # 平台基础模块：模型、MCP、Skill、知识库、Token 统计
├── node/                              # 工作流节点与开发规则（3 集）
├── machine-vision-tokenuse/           # 机器视觉与应用部署
├── single-agent/                      # 单 Agent 实战：官网截图发飞书
├── multi-agent/                       # 多 Agent 协调演示
├── skill/                             # Skill 相关演示
├── deploy/                            # 应用部署演示
└── demo/                              # 综合案例演示
    ├── 1/                             # 案例 1：单 Agent 开发全流程（飞书任务）
    ├── 2/                             # 案例 2：四 Agent 股票交易建议系统
    ├── 3/                             # 案例 3：多 Agent 消息路由（公司角色）
    └── 4/                             # 案例 4：纯视觉方案操作桌面（微信自动回复）
```

---

## 视频索引

> 所有演示视频统一在抖音观看：[https://v.douyin.com/t2NNhW0EwUQ/](https://v.douyin.com/t2NNhW0EwUQ/)

### 平台基础

| 目录 | 标题 | 视频文件 | 视频地址 | 说明文档 |
|------|------|----------|----------|----------|
| [model-mcp-skill-knowladge](./model-mcp-skill-knowladge/) | 大模型提供商、MCP、Skill、知识库与 Token 统计 | `video.mp4` | [观看](https://v.douyin.com/t2NNhW0EwUQ/) | [README](./model-mcp-skill-knowladge/README.md) |
| [node](./node/) | 工作流节点与开发规则 | `1.mp4` `2.mp4` `3.mp4` | [观看](https://v.douyin.com/t2NNhW0EwUQ/) | [README](./node/README.md) |
| [machine-vision-tokenuse](./machine-vision-tokenuse/) | 机器视觉与应用部署 | `video.mp4` | [观看](https://v.douyin.com/t2NNhW0EwUQ/) | [README](./machine-vision-tokenuse/README.md) |

### 智能体开发

| 目录 | 标题 | 视频文件 | 视频地址 | 说明文档 |
|------|------|----------|----------|----------|
| [single-agent](./single-agent/) | 单 Agent：查找官网并截图发飞书 | `video.mp4` | [观看](https://v.douyin.com/t2NNhW0EwUQ/) | [README](./single-agent/README.md) |
| [multi-agent](./multi-agent/) | 多 Agent 协调演示 | `1.mp4` | [观看](https://v.douyin.com/t2NNhW0EwUQ/) | [README](./multi-agent/README.md) |
| [skill](./skill/) | Skill 功能演示 | `video.mp4` | [观看](https://v.douyin.com/t2NNhW0EwUQ/) | [README](./skill/README.md) |
| [deploy](./deploy/) | 应用部署演示 | `video.mp4` | [观看](https://v.douyin.com/t2NNhW0EwUQ/) | [README](./deploy/README.md) |

### 综合案例（demo）

| 目录 | 标题 | 视频文件 | 视频地址 | 说明文档 |
|------|------|----------|----------|----------|
| [demo/1](./demo/1/) | 单 Agent 应用开发：飞书下达研究任务 | `video.mp4` | [观看](https://v.douyin.com/t2NNhW0EwUQ/) | [README](./demo/1/README.md) |
| [demo/2](./demo/2/) | 四 Agent 股票交易建议系统 | `video.mp4` | [观看](https://v.douyin.com/t2NNhW0EwUQ/) | [README](./demo/2/README.md) |
| [demo/3](./demo/3/) | 多 Agent 消息路由：公司经理与下属 | `video.mp4` | [观看](https://v.douyin.com/t2NNhW0EwUQ/) | [README](./demo/3/README.md) |
| [demo/4](./demo/4/) | 纯视觉桌面自动化：微信自动回复 | `video.mp4` | [观看](https://v.douyin.com/t2NNhW0EwUQ/) | [README](./demo/4/README.md) |

---

## 推荐观看顺序

适合从零了解平台的观看路径：

1. **[model-mcp-skill-knowladge](./model-mcp-skill-knowladge/)** — 先配置大模型、MCP、Skill、知识库等基础能力  
2. **[node](./node/)** — 熟悉工作流节点类型与连接规则  
3. **[machine-vision-tokenuse](./machine-vision-tokenuse/)** — 了解机器视觉模块与应用部署  
4. **[demo/1](./demo/1/)** — 跟随案例完成第一个单 Agent 应用  
5. **[single-agent](./single-agent/)** / **[demo/3](./demo/3/)** / **[demo/2](./demo/2/)** / **[demo/4](./demo/4/)** — 按兴趣深入单 Agent、多 Agent、金融案例或视觉操控场景  

---

## 相关链接

- 平台官网：[https://easyagi.com.cn/](https://easyagi.com.cn/)
- 使用文档：[https://easyagi.com.cn/doc/](https://easyagi.com.cn/doc/)
- 工作流节点说明：[文档 - 节点说明](https://easyagi.com.cn/doc/)
- 快速开始：[文档 - 快速开始](https://easyagi.com.cn/doc/)

---

## 贡献与反馈

欢迎通过 Issue 反馈视频说明问题或补充观看链接。各目录 `desc.txt` 为原始说明素材（已加入 `.gitignore`，不会上传），经整理后的可读版本见对应目录 `README.md`。
