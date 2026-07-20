# workmate-codex-skills

面向职场交付场景的 Codex Skills、工作流卡片与中文使用教程。

## 当前版本包含什么

- `third-party-mit/awesome-niuma-skills/`：第三方 MIT 内容的可追溯快照。
- `docs/安装与使用.md`：Codex Skills 与 Plugins 的安装、调用、验证和卸载说明。
- `THIRD_PARTY_NOTICES.md`：第三方来源、许可证和修改说明。
- `SECURITY.md`：安装第三方内容前的安全检查建议。

## 请先区分 Skill 与工作流文档

Codex 官方定义的 Skill 是一个至少含有 `SKILL.md` 的目录，`SKILL.md` 需要包含 `name` 和 `description`。本仓库导入的第三方素材虽然把 181 份 Markdown 统称为 Skills，但快照中只有 2 个标准命名的 `SKILL.md`；其余主要是岗位说明、提示词、工作流或参考模板。

因此，本仓库不会把这批内容宣传成“181 个可安装 Codex Skills”。它们统一标注为“第三方 MIT 岗位工作模板库”，待逐项整理、测试和改造成真正可安装的 Skill。

## 快速开始

如果只是浏览模板，直接进入：

`third-party-mit/awesome-niuma-skills/content/`

如果要安装 Skill，请先阅读：

`docs/安装与使用.md`

## 发布原则

- 保留第三方版权、许可证、来源和提交版本。
- 不把 OpenAI 内置 Skill、官方 Skill 或插件缓存复制进本仓库。
- 不上传密钥、Cookie、账号凭证或个人数据。
- 脚本默认视为未受信任代码，运行前先阅读并在副本上测试。
- 原始快照与后续整理版分开，避免误认作者或破坏追溯链。

## 来源

第三方快照来源于 `ffanglaili/awesome-niuma-skills` 的本地提交：

`f21ece0626345907ba25d2760cab52dc200b00f7`

详细信息见 `THIRD_PARTY_NOTICES.md` 和快照目录内的 `AUDIT.md`。
