# GitHub Pages 发布文件

把本目录内的全部文件上传或提交到 GitHub 仓库 `tt` 的根目录（覆盖旧文件），然后等待 GitHub Pages 从 `main / (root)` 重新部署。

- 页面入口：`index.html`
- 利润看板：`profit_dashboard/index.html`
- 选品工作台：`selection_workbench/index.html`
- 默认选品数据：`selection_workbench/selection_workbench.json`

GitHub Pages 是静态托管：选品协作数据由 Supabase 保存；“同步订单、面单、结算”“更新本地看板”只能在运行本机服务的电脑上执行。
