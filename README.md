# Level

**Gy 的 GitHub 公开活动归档与项目导航。**

[个人主页](https://github.com/Gyziel) · [活动记录](activity.txt) · [工作流](https://github.com/Gyziel/Level/actions)

## 功能

每天自动读取 GitHub 公开事件，增量去重后更新记录；没有新事件时跳过提交，减少无效运行。

| 内容 | 说明 |
| --- | --- |
| [activity.txt](activity.txt) | 最新公开事件记录 |
| [daily_log.txt](daily_log.txt) | 有新活动时记录更新日期 |
| [update-activity.yml](.github/workflows/update-activity.yml) | 自动归档的 GitHub Actions 工作流 |

- **定时执行**：每天 02:17 UTC（北京时间 10:17，实际启动可能延迟）。
- **手动执行**：Actions → Refresh activity logs → Run workflow。
- **自动验证**：修改工作流配置时触发一次检查；没有新记录就不推送提交。
- **账户适配**：自动读取当前仓库所有者，不再依赖写死的用户名。

## 项目

[HyperMax](https://github.com/Gyziel/HyperMax) · [WeType Monet](https://github.com/Gyziel/WeType_Monet-Gy) · [ZEEHO Auto Gy](https://github.com/Gyziel/ZEEHO-Auto-Gy) · [GitHub 主页仓库](https://github.com/Gyziel/CnGyZzh)

<sub>公开事件快照不等于 GitHub 贡献统计，也不保证完整历史。</sub>
