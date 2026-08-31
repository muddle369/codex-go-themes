# CodexGO Themes

CodexGO 的公开主题市场仓库。

当前收录 14 个主题：CodexGO Blue、ChannelerH 的 6 个原创主题、Codex Snow Skin、Glass Vision，以及 5 个程序化抽象预设。

## 目录结构

- `index.json`：主题市场清单
- `themes/<id>/theme.json`：主题配置
- `themes/<id>/image.*`：主题背景或主图
- `themes/<id>/preview.jpg`：预览图
- `themes/<id>/LICENSE.md`：主题授权与来源说明
- `themes/<id>/UPSTREAM_LICENSE`：上游许可证副本
- `ATTRIBUTIONS.md`：汇总署名和收录范围

主题应当明确标注作者、来源和许可证。禁止提交广告、密钥、远程脚本或未经授权的素材。主题包只能包含配置、图片、预览图和授权说明，不应包含可执行代码。CodexGO 不代表 OpenAI，也不拥有上游主题素材的权利。

## 收录与清洗规则

- 每个主题必须有唯一的 `id`、版本、作者、来源地址和许可证。
- `theme.json`、主图和预览图必须与 `index.json` 中记录的 SHA-256 一致。
- 主题目录必须同时包含 `LICENSE.md` 和上游许可证副本（如适用）。
- 主题不能包含脚本、远程代码、密钥、广告或未授权的第三方素材。
- 主题市场只展示通过完整资源校验的条目；清单异常时客户端不会安装主题。
