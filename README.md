# shadowrocket-config

个人 Shadowrocket 分流配置。仓库不含任何节点信息。

| 文件 | 作用 |
|---|---|
| shadowrocket.conf | 主配置 |
| rules/Ad.list | 广告与跟踪域名（约 5.2 万条），自动更新 |
| rules/Apple.list | 苹果直连，自动更新 |
| rules/China.list | 国内直连，自动更新 |
| rules/Binance.list | 币安走代理，手写 |
| rules/Exchanges.list | 其他交易所直连，手写 |
| .github/workflows/sync.yml | 每天自动更新规则 |

配置地址：https://raw.githubusercontent.com/你的用户名/shadowrocket-config/main/shadowrocket.conf
