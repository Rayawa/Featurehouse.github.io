# Featurehouse.github.io

[English](README.md) | 简体中文

烤地瓜模组及相关联动资源的静态文档网站。

归档项目，保留用于参考。

## 项目概述

仓库包含模组介绍、画廊、百科及联动标准文档，英文与中文页面共用静态样式和素材。

## 技术栈与依赖

HTML、CSS，`_config.yml` 包含 GitHub Pages/Jekyll 配置。静态预览只需 HTTP 服务器，可选用 Python 3。

## 文件结构

- `index.html` — 默认首页
- `en/` — 英文页面
- `zh/` — 中文页面资源
- `spm/` — 模组介绍与百科
- `pigeonia-linkage-standard/` — 联动标准
- `static/` — 样式与素材

## 快速上手

在仓库根目录启动静态服务器，以正确加载绝对路径资源：

```bash
python3 -m http.server 8000
```

打开 `http://localhost:8000/`。直接编辑 HTML 和静态资源，无需前端构建。

访问 `/en/` 查看英文站点，也可通过 GitHub Pages 托管。
