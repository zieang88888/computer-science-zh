# 第三方声明（Third-Party Notices）

本仓库是开源项目的中文二次开发（汉化 / 课程体系整理）仓库。以下内容改编自对应的源项目，特此如实署名致谢。

## 源项目

- **项目名称**：Open Source Society University — Computer Science（OSSU 计算机科学课程体系，俗称「开源 CS 学位」）
- **仓库地址**：https://github.com/ossu/computer-science （默认分支 `master`）
- **作者 / 维护者**：
  - 创始人：Eric Douglas（@ericdouglas）
  - 首席技术维护：Josh Hanson（@joshmhanson）
  - 首席学术维护：Waciuma Wanjohi（@waciumawanjohi）
  - 全体全球社区贡献者
- **许可**：**MIT License**，源仓 LICENSE 原文为 `The MIT License (MIT) Copyright (c) 2015-2023 Open Source Society University`（见 https://raw.githubusercontent.com/ossu/computer-science/master/LICENSE ，2026-10-05 实测可访问）。
- **在线课程站**：https://cs.ossu.dev

## 数字与统计方式说明

- **星标数 151,638 ★**：2026-10-05 对源仓 `ossu/computer-science` 的实测值。
- **模块数 15**：对源 README `Curriculum` 章节下所有叶子课程小节（`## Intro CS`、Core CS 下 8 个 `###` 子模块、Advanced CS 下 5 个 `###` 子模块、`## Final project`）逐条统计。
- **课程 / 项目条目数 63**：用 Python 脚本统计源 README 各课程表格中以 Markdown 链接 `[课程名](链接)` 开头的行，逐行计数得到（含 Core Security 模块中「二选一」的两门备选课；实际必修要求略少于 63 门，详见源 README）。
- 统计脚本与源 README 原文留存于本批构建目录 `_src/`，可复跑核验。

## 本仓库做了什么

1. 将源 README 的课程体系整体**翻译 / 整理为中文**：15 个模块全部给出中文名 + 英文名，每门课程给出中文译名 + 英文原名 + 来源链接（见 [curriculum.md](curriculum.md)）。
2. 提炼「快速开始」上手指引（零基础起步、每周学时规划、毕业项目选择），内容均依据源 README 的 Summary / Process / Duration / Final project 原文建议，未虚构任何课程或学时要求。
3. 本仓库**不包含**源项目的课程视频、习题、教材原文或网站代码，仅做课程索引的中文呈现。

## 本仓库自身许可

- 本仓库代码与文档：**MIT License**（见 [LICENSE](LICENSE)，Copyright (c) 2026 zieang88888）。
- 课程链接指向的第三方课程（Coursera / edX / MIT OCW / 高校公开课等）版权归各开课机构所有，请以其各自条款为准。
