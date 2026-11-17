# Orange Personal Cloud 中文文库

OPC 中文白皮书、一文读懂和完整100问FAQ的公开源文件。站点内容位于 `docs/`，由 GitBook Git Sync 同步。

## 绑定 GitBook

1. 在 GitBook 中连接 GitHub，授权访问 `OrangePersonalCloud/whitepaper`。
2. 选择分支 `main`，项目目录保持仓库根目录。
3. `gitbook-docs.yaml` 将中文 space 映射到 `docs/`；`docs/.gitbook.yaml`指定首页和目录文件。
4. 第一次同步选择从 GitHub 导入内容。确认导航、配图及附件后，由站点所有者在 GitBook 发布。

`opc-docs-zh` 是固定的 space key，后续更新保持不变。GitBook双向同步后，本地编辑前先拉取远端更改，避免同时在两处改同一页。

## 文件

- `docs/overview.md`：一文读懂。
- `docs/whitepaper/`：中文白皮书。
- `docs/faq/`：100问，按8个主题组织。
- `docs/.gitbook/assets/`：图表的SVG、PNG及FAQ PDF。
- `docs/SUMMARY.md`：站点目录。

图表采用随仓库存放的文件，正文不依赖外部图片服务。FAQ的Q001–Q100编号在PDF和GitBook保持一致。
