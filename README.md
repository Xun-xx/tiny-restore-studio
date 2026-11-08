# 小小翻新工作室 · 官网

这是「小小翻新工作室 / Tiny Restore Studio」的静态单页官网，适合使用 GitHub Pages 免费部署。

官网包含：工作室介绍、正在制作的玻璃修复游戏介绍、简单的玻璃修复概念互动、开发中状态。页面兼容手机和电脑。站点无依赖，不需要 Docker、Node.js、后端服务器或数据库。

## 如何在 GitHub Pages 发布（推荐）

1. 登录 GitHub 账号 **Xun-xx**。
2. 打开 https://github.com/new ，创建一个名为 **tiny-restore-studio** 的新仓库（Repository name），选择 **Public**，再点 **Create repository**。
3. 打开仓库的 **Add file → Upload files**（若是刚建成的空仓库，则点击 **uploading an existing file**）。
4. 将解压后网站目录中的 `index.html`、`logo.webp`、`favicon.png` 以及 `README.md` 拖进上传区。注意：**不是直接上传 ZIP 压缩包**；`index.html` 必须放在仓库根目录，不能额外套一层文件夹。`TapTap厂商Logo_512x512.png` 可选，不是网站必需文件。
5. 点击 **Commit changes**。
6. 打开仓库 **Settings → Pages → Build and deployment**，`Source` 选择 **Deploy from a branch**；`Branch` 选择 **main**，目录选择 **/(root)**，点击 **Save**。
7. 等待 GitHub 发布完成（通常几分钟，有时最多约 10 分钟），打开：

   https://xun-xx.github.io/tiny-restore-studio/

8. 确认页面可正常访问，再将上述地址填写到 TapTap 厂商网址。

> 免费个人 GitHub 账户通过 GitHub Pages 发布时，需要一个公开仓库。不要把密码、密钥或未公开的游戏源代码上传到这个仓库。官网的静态文件会公开给任何人。

官方使用说明：https://docs.github.com/en/pages/quickstart

## 本地预览

直接双击 `index.html`，浏览器就能打开，无需安装任何软件。建议再用浏览器的手机模拟模式检查布局。

## 后续更新

- 修改网页文案或颜色：编辑 `index.html`。
- 更换工作室 Logo：替换 `logo.webp`，保持文件名不变。
- 更换小图标：替换 `favicon.png`。
- 每次修改后上传同名文件并提交到 GitHub，GitHub Pages 会自动重新发布。

## 重要说明

- 「玻璃修复站」为本次官网展示使用的暂定游戏名称；如果后续正式游戏名称不同，请在 `index.html` 中更改。
- 首页玻璃修复互动是 HTML/CSS/JavaScript 制作的品牌视觉演示，**不是游戏实机截图**。
- 尚未填写联系邮箱、TapTap 游戏详情页或发布日期，避免放入虚假信息。发布后可以逐步补充。
