# 第三方快照审计摘要

审计日期：2026-07-20

## 来源与版本

- Git 远程：`https://github.com/ffanglaili/awesome-niuma-skills.git`
- 本地提交：`f21ece0626345907ba25d2760cab52dc200b00f7`
- 提交日期：2026-04-12
- 许可证：MIT
- 版权：`Copyright (c) 2026 ffanglaili`

## 文件清点

- Markdown：181
- 标准命名的 `SKILL.md`：2
- Python 脚本：4
- Excalidraw 示例文件：8
- ZIP 压缩包：2
- 顶层岗位分类：7

两个 `SKILL.md` 位于：

- `图形处理/diagram-reports-generator/SKILL.md`
- `图形处理/excalidraw-diagram-generator/SKILL.md`

其余内容主要是岗位指南、提示词、工作流或模板，不应被宣传为 181 个可直接安装的 Codex Skills。

## 静态安全检查

四个 Python 脚本的初步静态扫描未发现主动联网、调用子进程或读取环境密钥的逻辑。

已知文件修改风险：

- `add-arrow.py`
- `add-icon-to-diagram.py`

上述脚本包含重命名、删除临时文件并覆盖 Excalidraw 目标文件的操作。运行前必须备份，并只在副本上测试。

部分 Markdown 文档提到 API Key、外部发布 API、ATS 写入权限、`yt-dlp`、`ffmpeg` 等工具或服务。这些属于第三方说明，使用者需要独立核验服务、权限和数据合规性。

## ZIP 处理

本地源目录中有两个 ZIP：

- `岗位skills.zip`：97 个归档条目，与当前岗位资料存在重复。
- `产品经理/Product-Manager-Skills-main.zip`：293 个归档条目，包含一个完整嵌套项目及其应用代码、依赖和独立许可证信息。

为避免重复分发和在未完成独立依赖/许可证审计前公开嵌套项目，本次快照不上传这两个 ZIP。遗漏记录保留在本审计中。

## 结论

该快照可作为第三方 MIT 岗位工作模板的研究来源，但不能整体视为已验证、可安装、可商用交付的 Codex Skills 包。后续整理版必须：

1. 逐项确定适用场景。
2. 为真正的 Skill 建立标准目录和 frontmatter。
3. 测试所有脚本。
4. 保留来源与 MIT 声明。
5. 将原始快照和修改版分开。
