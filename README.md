# System Analysis Documenter Skill

这是一个专门用于协助用户创建高质量系统分析文档的Claude Code技能。它使用先进的领域驱动设计（DDD）思想，结合PlantUML图形化展示，帮助用户完成从需求分析到文档输出的全过程。

## 🌟 功能特点

- **结构化流程**：按照5个步骤完成系统分析文档（模板确认 → 需求确认 → 文档撰写 → 质量评估 → 文档修订与导出）
- **智能对话**：遇到不确定的技术术语或需求时主动向用户确认
- **质量保证**：按照6个维度对文档进行自动化质量评估（总分100分）
- **基于DDD的先进模板**：使用领域驱动设计思想，结合PlantUML图形化展示的专业模板
- **语雀导出支持**：支持将生成的文档导出到语雀，充分利用PlantUML图表渲染功能

## 🛠️ 安装方法

要使用这个技能，请按照以下步骤操作：

1. 下载 `.skill` 文件：
   - 从 Releases 页面下载最新版本的 `.skill` 文件
   - 或直接复制整个项目文件夹到您的Claude技能目录

2. 安装技能：
   ```bash
   # 如果您有技能安装工具
   claude skill install system-analysis-documenter.skill
   ```

## 📋 使用方法

在Claude Code会话中，当需要创建系统分析文档时，直接提出您的需求。例如：

- "我需要为电商平台订单管理系统写一份系分文档"
- "帮我创建一个微服务架构的系统分析文档"
- "为用户权限系统重构写一份详细的系分文档"

技能将按照既定流程与您交互，最终输出一份高质量的系统分析文档。

## 📊 质量评估维度

文档将按照以下六个维度进行评估：
1. **完整性** (20%) - 是否覆盖所有必要内容
2. **合理性** (25%) - 技术方案和业务逻辑是否合理
3. **逻辑完整性** (15%) - 各部分之间逻辑关系是否清晰
4. **可实施性** (20%) - 技术方案是否切实可行
5. **图表质量** (10%) - 架构图和流程图质量
6. **标准化** (10%) - 符合文档编写标准

## 📁 文件结构

```
system-analysis-documenter/
├── SKILL.md                 # 主技能定义文件
├── templates/               # 文档模板
│   └── default-system-analysis-template.md
├── references/              # 参考文档
│   ├── user-guide.md        # 用户使用指南
│   ├── template-guide.md    # 模板使用指南
│   └── yuque-export.md      # 语雀导出功能说明
├── evals/                   # 评估用例
│   └── evals.json
└── workspace/               # 工作区配置
    └── trigger_eval.json
```

## 🎯 适用场景

- 新系统架构设计
- 现有系统重构分析
- 微服务架构设计
- 高并发系统设计
- 数据处理系统分析
- 权限管理系统设计

## 🌱 贡献指南

我们欢迎各种形式的贡献！无论是报告bug、提交改进，还是增加新功能。

1. Fork 仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 LICENSE 文件了解详情。

## 💬 支持

如果您有任何问题、建议或想法，欢迎开启一个 Issue 进行讨论。