# last30days-skill — 让「选题」和「选品背调」变成一条命令

| | |
| --- | --- |
| 仓库 | https://github.com/mvanhorn/last30days-skill |
| Stars / Forks | 69,389 / 6,166 |
| 语言 · 许可 | Python · MIT |
| 最近推送 | 2026-11-17 |
| 收录日期 | 2026-11-18 |

## 一句话

跨 Reddit、X、TikTok、YouTube、Hacker News、Polymarket 搜近 30 天的真实讨论，按互动量排序后合成一份简报——不用再一个个帖子翻。

## 适合谁

做自媒体选题、跨境选品背调、竞品调研，以及接选题外包的人。

## 变现路径

1. **自媒体选题包**（启动 0 元 / 难度低）：每周给账号或团队出 5 个高热度选题 + 脚本角度，300–1500 元/单。
2. **跨境选品背调**（需 ScrapeCreators 或 Bright Data key，有免费额度 / 难度中）：交叉验证某品类在 Reddit、TikTok 的真实需求与差评，500–3000 元/份。
3. **竞品广告情报**（需 Meta / Bright Data 类凭证 / 难度中高）：抓在投广告 + 评论痛点，反推改良款，按项目报价。
4. **付费简报**（时间成本为主 / 难度低）：每周行业 30 天动态，卖给同行或卖家社群，49–199 元/月/人。

## 落地步骤

1. 安装：`npx skills add mvanhorn/last30days-skill -g`
2. 预检：`python3 skills/last30days/scripts/last30days.py --preflight`
3. 零 key 先跑通 Reddit + HN：`/last30days "宽脚跑鞋推荐"`
4. 补 key 解锁 TikTok / 小红书 / Amazon 评论，用于选品背调
5. 长期盯梢加 `--store` + `watchlist.py`，可接 Slack / Webhook

## 风险

- TikTok / X / Amazon 走第三方抓取服务，存在 ToS 与账号风险
- 输出质量取决于宿主 agent，结论是「信号」不是「事实」，爆款与差评仍需人工复核
