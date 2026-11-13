空间观察 · Design Lens 2.0

【重要】此文件包是可安装网页应用（PWA），并非已上线的 App Store / 微信小程序。
需先将整个文件夹部署到支持 HTTPS 的静态网站，不能直接双击 HTML 就期待桌面安装与离线缓存。

最简方式（GitHub Pages）：创建 GitHub 仓库，上传 index.html、sw.js、manifest.webmanifest、icons/；在 Settings → Pages 选择 Deploy from a branch、main/root，等待 GitHub 给出 https://... 地址。

iPhone：用 Safari 打开该 HTTPS 网址 → 分享 → 添加到主屏幕。
Android：用 Chrome 打开 HTTPS 网址 → 菜单 → 安装应用 / 添加到主屏幕。

图文记录自动保存到本机 IndexedDB，按分析日期归档，可搜索、编辑、删除、导入导出 JSON 备份。
注意：更换手机、浏览器或网址不会自动同步。系统清理网站数据/卸载应用可能清空记录；务必定期在“档案”中导出备份并保存到云盘。
旧版本导出的 JSON 可通过“导入备份”功能恢复。
