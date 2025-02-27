# Mirror-Web

## 一个由IPFS支持的镜像站

---

## 🚀 项目结构

在 VitePress 项目中，将看到以下文件夹和文件：

```
.
├─ docs
│  ├─ .vitepress
│  │  └─ config.js
│  ├─ windows
│  │  ├─ 11
│  │  ├─ 10
│  │  └─ XP
│  ├─ index.md
│  └─ mirror.md
└─ package.json
```

VitePress 在 `docs/` 目录中查找 `.md` 文件。

每个文件都基于其文件名显示为一条路径。

静态资产，例如图标、图片可以添加到 `docs/public/assets/image` 并通过相对链接嵌入到 Markdown 中。

## 🧞 指令

所有命令都是从项目根目录的终端运行的：

| 命令                  | 运行                            |
|:--------------------|:------------------------------|
| `yarn install`      | 安装依赖项                         |
| `yarn docs:dev`     | 在 `localhost:5173` 上启动本地开发服务器 |
| `yarn docs:build`   | 构建站点到 `./dist/` 目录            |
| `yarn docs:preview` | 在部署之前在本地预览构建                  |

## 贡献者
<a href="https://github.com/winx-ipfs/Mirror-Web/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=winx-ipfs/Mirror-Web" />
</a>