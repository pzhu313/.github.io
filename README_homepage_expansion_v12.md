# Maison Atlas · Homepage Expansion v12

这版是在你上传的 `maison_atlas_seeded_v11_package` 上直接扩出来的，没有推倒重做。

## 这次新增
- `index.html`：新的个人主页入口，适合作为 GitHub Pages 首页
- `research_atelier.html`：科研面板
- `career_hq.html`：2026 GS / MS 量化研究社招作战板
- `application_atlas.html`：Princeton / Statistics / FE 长期申请规划
- `index_calendar_seeded_v11.html`：保留原执行总控台，并新增个人主页 / 科研 / 跳槽 / 申请入口
- 其余私密页保留原交互逻辑，并补上新入口

## 推荐部署方式
### 公开到 GitHub Pages
适合公开：
- `index.html`
- `research_atelier.html`
- `career_hq.html`
- `application_atlas.html`

### 本地私密保留
建议只本地使用：
- `index_calendar_seeded_v11.html`
- 财务 / 日志 / 显化 / 占卜 / 照片墙 / 健身打卡 等页面

## 注意
科研面板里的 PDF 建议登记为：
- 仓库内相对路径，例如 `papers/xxx.pdf`
- 或在线链接

直接把大型 PDF 二进制塞进浏览器本地存储并不合适；更稳的是把 PDF 文件放到仓库目录，再在页面里登记路径。
