# open-sourcetree-in-vscode-plugin

WIP - nothing to see here

```
npm install open-sourcetree-in-vscode-plugin
```

## Usage

``` js
const open-sourcetree-in-vscode-plugin = require('open-sourcetree-in-vscode-plugin')
```

## Continues Integration

```bash
npm install # 自动prepare -> npm run build，build前会清理，之后构建。
npm test    # npm测试
npm version {major|minor|patch}   # 自动管理package.json的 major.minor.patch 版本, 串行进行: 以及基于commit生成CHANGLOG, 基于commit发布release.
npm publish  # 发布当前npm为open-sourcetree-in-vscode-plugin
```

## github配置

`secrets.NPM_TOKEN`

`.github\workflows\release.yml`

```bash
env:
  node_version: 14
  email: 1062670898@qq.com
```

## License

MIT



refer to

https://github.com/mafintosh/templates

https://github.com/mafintosh/create-project