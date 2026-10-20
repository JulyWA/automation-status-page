# 多机工作台公开看板

手机查看用的公开脱敏看板，2026-10-20 起替换原来的自动化 / 期权套利状态页。

## 入口

[https://july.nibajie.cc/](https://july.nibajie.cc/)（备用 [https://julywa.github.io/automation-status-page/](https://julywa.github.io/automation-status-page/)）

## 内容说明

- 由 1 号电脑每 30 分钟发布一次，数据来自各电脑上报的任务状态。
- 只发布脱敏后的静态页面：不含文件路径、钥匙串或密钥名称、链接、IP、原始报错和技术细节；不允许搜索引擎收录。
- 生成脚本在私有项目 ai-workbench 的 tools/publish_public_page.py。

## 文件

- `index.html`：看板页面。
- `CNAME`：自定义域名配置。
- `.nojekyll`：按静态文件直接发布。
