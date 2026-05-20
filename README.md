# July 自动化状态页

这是个人自动化任务的远程脱敏状态页仓库。

## 远端入口

[https://july.nibajie.cc/](https://july.nibajie.cc/)

备用入口：

[https://julywa.github.io/automation-status-page/](https://julywa.github.io/automation-status-page/)

## 内容说明

- 展示自动化任务整体健康状态、更新时间、需要关注项和任务分组状态。
- 仅发布脱敏后的静态页面，不包含本机路径、PID、token、Keychain 名称或原始日志。
- 本地状态面板每 5 分钟刷新；远程 GitHub Pages 版本每日 09:20 和 18:10 自动发布。

## 文件

- `index.html`：GitHub Pages 状态页。
- `status.json`：脱敏后的结构化状态快照。
- `CNAME`：GitHub Pages 自定义域名配置。
- `.nojekyll`：确保 GitHub Pages 按静态文件直接发布。
