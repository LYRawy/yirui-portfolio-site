# Yirui Portfolio

这是一个纯静态个人作品集网站，可直接部署到 GitHub Pages。

## 文件结构

- `index.html`：网站入口及页面样式、交互逻辑
- `assets/`：网站使用的全部图片素材
- `assets/experience/`：实习经历图片
- `assets/logos/`：公司 Logo

## 本地预览

在当前文件夹打开终端并运行：

```bash
python3 -m http.server 8000
```

然后在浏览器访问 `http://localhost:8000`。

## 上传 GitHub

1. 创建一个新的 GitHub 仓库。
2. 将本文件夹中的 `index.html`、`README.md` 和 `assets` 一起上传到仓库根目录。
3. 在仓库 `Settings → Pages` 中选择从主分支根目录部署。
4. 等待 GitHub Pages 生成访问链接。

请勿只上传 `index.html`，否则图片将无法显示。

## 后续修改

可直接在 GitHub 网页中编辑 `index.html`，也可以在本地修改后运行：

```bash
git add .
git commit -m "更新作品集"
git push
```

每次提交都会保留历史版本，改错时可以在 GitHub 中查看或恢复。
