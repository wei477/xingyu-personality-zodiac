# 星语 · 性格星座分析

一个可以在 PyCharm 或任何文本编辑器中打开的纯 HTML/CSS/JavaScript 单页网页。

## 本地运行
1. 解压 ZIP 文件。
2. 在 PyCharm 里选择 **File → Open**，打开 `xingyu_personality_zodiac` 文件夹。
3. 打开 `index.html`。
4. 可以直接在文件管理器双击 `index.html` 用浏览器运行；修改后保存并刷新浏览器即可。
5. 不需要安装 Node.js、Python 包、数据库或 API key。

## Jupyter Notebook 怎么用
Jupyter 适合实验 Python、数据分析和 AI 逻辑；这个项目本身是前端网页，最简单的方式是把 `index.html` 放在 Jupyter 能访问的目录中，然后在文件管理器或浏览器打开它。Jupyter 不是网站托管平台。

## 免费发布到网上（GitHub Pages）
1. 登录 GitHub，创建一个 **Public** 仓库。
2. 上传 `index.html` 到仓库根目录。
3. 打开仓库 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选 `main`，目录选 `/(root)`，点击 **Save**。
6. 等待 Pages 发布完成，打开页面显示的网址测试。以后更新 `index.html` 并提交，网站会自动更新。

## 说明
- 本项目不需要服务器，不收集或上传生日。
- 星座和性格文字是娱乐与自我探索参考，不是科学测评、心理诊断或未来预测。
- 目前是静态单页；如果以后想增加用户账号、云端存档或 AI 对话，需要另外设计后端与隐私保护。
