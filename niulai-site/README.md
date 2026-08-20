# 牛来 · NIULAI GAMES

静态单页官网，可直接部署到 GitHub Pages。

## 本地预览

直接双击 `index.html` 即可，或在目录运行：

```bash
python -m http.server 8080
```

然后访问 `http://localhost:8080`。

## GitHub Pages 部署

1. 在 GitHub 新建公开仓库，例如 `niulai-games`
2. 上传本目录中的全部文件
3. 进入仓库 `Settings` → `Pages`
4. `Build and deployment` 选择 `Deploy from a branch`
5. Branch 选择 `main`，目录选择 `/ (root)`
6. 保存后等待 GitHub 生成页面地址

如果仓库名使用 `<你的GitHub用户名>.github.io`，网站地址会更短。
