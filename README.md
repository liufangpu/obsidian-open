# Obsidian PARA Starter Kit

这是一个开箱即用的 [Obsidian](https://obsidian.md/) 个人知识库模板，基于 Tiago Forte 的 **PARA 方法** 构建。

它不仅仅是一组文件夹，更是一套配置完整的**生产力系统**，内置了自动化的工作流、模板和核心插件配置，帮助你直接开始高效记录，而无需从零折腾配置。

## ✨ 特性 (Features)

*   **📚 预置 PARA 结构**：Projects, Areas, Resources, Archives 标准目录体系。
*   **🤖 自动化模板 (Templater)**：
    *   **Daily Note**：一键生成每日日记，包含任务列表。
    *   **Project Note**：自动管理项目状态和截止日期。
    *   **Meeting Note**：标准会议记录模板。
    *   **Dynamic Title**：所有笔记自动使用文件名作为标题（`= this.file.name`），修改文件名自动同步。
*   **✅ 任务管理 (Tasks)**：预装 Tasks 插件配置，支持全库任务聚合查询。
*   **📊 数据视图 (Dataview)**：预置基础查询语法，支持动态展示项目列表。
*   **🎨 极简美学**：推荐并配置了 Minimal 主题（如已包含），专注内容创作。

## 📂 目录结构

```text
.
├── 00-Inbox/        # 📥 收集箱：快速捕捉灵感，定期清空
├── 10-Projects/     # 🚀 项目：有截止日期的短期任务
├── 20-Areas/        # 🏠 领域：长期维护的责任（如健康、财务）
├── 30-Resources/    # 📚 资源：感兴趣的主题和参考资料
├── 40-Archives/     # 🗄️ 归档：已完成的项目和旧资料
├── 90-Journal/      # 📅 日记：每日记录与复盘
├── 99-Templates/    # 🛠️ 模板：核心系统模板（不要随意删除）
└── 99-Attachments/  # 📎 附件：图片和文件自动存放处
```

## 🚀 快速开始 (Quick Start)

### 方法一：直接克隆 (推荐)
```bash
git clone https://github.com/liufangpu/obsidian-open.git MyKnowledgeBase
```
然后打开 Obsidian，选择 **"Open folder as vault"**，指向 `MyKnowledgeBase` 文件夹。

### 方法二：下载 ZIP
点击右上角的 **Code** -> **Download ZIP**，解压后用 Obsidian 打开即可。

## 🛠️ 推荐工作流

1.  **日常捕捉**：按 `Ctrl+N` 新建笔记（自动进入 Inbox），记录想法。
2.  **开始一天**：点击侧边栏日历图标，创建今日日记，规划任务。
3.  **新建项目**：在 `10-Projects` 目录右键新建笔记，自动应用项目模板。
4.  **每周回顾**：清空 Inbox，检查进行中的项目，归档已完成内容。

## 🔌 包含的插件配置
本仓库已包含以下核心插件的配置文件（`data.json`），无需重新配置：
*   **Templater**：强大的模板引擎。
*   **Dataview**：将知识库转化为数据库。
*   **Tasks**：全库任务管理。
*   **Calendar**：侧边栏日历导航。

## 📄 License
MIT License. 
你可以自由使用、修改和分发此模板。
