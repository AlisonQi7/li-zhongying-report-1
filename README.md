# GitHub Pages 发布包

这个目录已经整理成可直接用于 GitHub Pages 的静态站点。

## 目录说明

- `index.html`：网页主文件
- `li-report-assets/intro.jpg`：测评介绍页长图
- `02 追逐者.png`、`事业02 .png` 等：页面实际引用的图片素材
- `.nojekyll`：避免 GitHub Pages 对静态文件做额外处理

## 发布方式

1. 在 GitHub 新建一个仓库。
2. 把这个目录里的文件上传到仓库根目录。
3. 打开仓库 `Settings` -> `Pages`。
4. 在 `Build and deployment` 里选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - Folder: `/ (root)`
5. 保存后，等待几分钟，GitHub 会生成公开链接。

如果后面要改内容，更新这个目录里的文件后重新上传即可。
