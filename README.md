# shadowrocket-rules

基于 [Johnshall 的 sr_top500_banlist_ad.conf](https://johnshall.github.io/Shadowrocket-ADBlock-Rules-Forever/sr_top500_banlist_ad.conf) 建立的个人维护仓库。

## 文件说明

- sr_top500_banlist_ad.base.conf：当前下载的原始基线规则，便于对照上游变化。
- sr_top500_banlist_ad.custom.conf：你后续自己维护、修改和增删规则的版本。

## 建议维护方式

1. 定期重新下载上游规则，覆盖 sr_top500_banlist_ad.base.conf
2. 将你自己的修改只保留在 sr_top500_banlist_ad.custom.conf
3. 对比这两个文件，决定是否同步上游变更

## 当前上游来源

- 上游地址：<https://johnshall.github.io/Shadowrocket-ADBlock-Rules-Forever/sr_top500_banlist_ad.conf>
- 上游项目：<https://github.com/Johnshall/Shadowrocket-ADBlock-Rules-Forever>
