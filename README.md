# 氯化钠溶解 · 3D 水合实验室

完整静态网页，无需安装依赖、无需构建。包含水分子结构、离子水合及持续运动演示。

## 发布到 GitHub Pages

1. 在 GitHub 新建 Public 仓库，建议名称 `salt-hydration`，勾选 Add README。
2. 解压发布包，将 `index.html` 上传至仓库根目录（不要上传 ZIP，也不要放入额外一层文件夹）。如愿意也可上传本 README 和 `.nojekyll`。
3. 点击 Commit changes。
4. 打开 Settings → Pages。
5. Source 选择 Deploy from a branch；Branch 选择 main；目录选择 / (root)，点击 Save。
6. 等待发布后，使用 Pages 设置页显示的网址。项目地址通常为 https://你的用户名.github.io/salt-hydration/ 。

首页必须命名为 index.html。整个应用已合并到该文件，无外部脚本或字体依赖。
可在电脑上使用支持 WebGL 的浏览器直接打开 index.html；无需联网。
GitHub Pages 的实际可达性仍取决于访问设备和网络。
