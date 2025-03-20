# DocBase 官方插件仓库

欢迎来到 DocBase 官方插件仓库！本仓库包含两个重要的配置文件：`docloader.json` 和 `docsplitter.json`。以下是对这两个文件的简要说明：

## 文件说明

### docloader.json

文档加载器插件列表，文档加载器用于从不同的数据格式中加载文档数据。

### docsplitter.json

文档分割器插件列表，文档分割器用于将加载的文档分割成更小的块，以便后续处理。

### 插件格式说明

所有插件均以 npm 包的形式存在，每个插件在配置文件中通过 `name` 和 `version` 字段来指定：
- `name`: npm 包的名称。
- `version`: npm 包的版本号。

增加、更新插件请向本仓库提交PR
