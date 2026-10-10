# wwbh 的博客 · 静态快照

《Web前端开发技术》国庆作业：**WordPress 站的静态化公网 git 上线 + 评论功能**。

- 本仓库的内容是由本机 WordPress（XAMPP，PHP + MySQL）导出的**静态快照**——页面在导出时从运行中的 WordPress 抓取生成，之后不再依赖 PHP 和数据库。
- 静态化路线对照课程「静态站点生成器」实训：WordPress 动态生成 → 导出后变成纯静态文件（html/css/js），任意静态服务器即可托管，此处托管在 **GitHub Pages**。
- 访问地址：<https://ggfhjbgynn.github.io/webcreat/>
- 评论功能：静态站没有自己的后端，评论区用 **giscus**，以本仓库的 Discussions 为"评论数据库"（浏览器直调平台 API 读写，serverless + 前后端分离）。

本地动态站（WordPress 原本的样子）：`http://localhost:8000/`（XAMPP，Apache 已移至 8000 端口）。
