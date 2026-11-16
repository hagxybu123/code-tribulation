# 代码渡劫模拟器 · C语言天劫实录

一款单文件的 C 语言「修行」文字冒险小游戏：以 `index.html` 承载全部内容，打开即玩，无需安装、无需后端。

## 玩法

- 以「天劫」为关卡骨架，在代码修行路上遭遇各类 C 语言报错与陷阱；
- **报错图鉴**：收集并解锁你踩过的坑；
- **知识点**：每次渡劫都会沉淀对应的 C 语言知识；
- **功德**系统与**隐藏结局**：不同选择走向不同终局。

## 技术

- 纯静态单文件：HTML + CSS + 原生 JavaScript，无外部依赖、无 CDN、无网络请求；
- 进度通过浏览器 `localStorage` 保存在本地；
- 适配桌面与移动端（含安全区适配），自带主题色。

## 本地运行

直接双击 `index.html`，或在目录下启动任意静态服务器：

```bash
python -m http.server 8000
# 打开 http://localhost:8000
```

## 部署

仓库根目录即站点根目录，`index.html` 同时作为 GitHub Pages 的入口页面（已放置 `.nojekyll`，避免 Jekyll 处理干扰）。

启用方式：仓库 **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`**，稍等片刻即可通过 `https://<用户名>.github.io/<仓库名>/` 访问。

## 许可

仅供学习与娱乐使用。
