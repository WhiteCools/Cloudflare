### ☁️ Cloudflare Firewall Rules To Prevent DDOS Attacks ☁️

Since Layer 7 Has Reached The Majority Of The Public Thanks To Github And Kids Sites Are Being Railed Best I Released This For Those Who Have Zero Idea What There Doing. There NOT The Best By Any Means However It Will Stop Most Attacks.

## ☁️ Firewall Rules ☁️

Rule Name | File Name | Action | What For
---- | ---- | ---- | ----
General | [rules.ssl](./rules.ssl) | Manual ADD | Peformance, User Experience, DDOS Protection, Crawlers<br>
Countries | [common-country.rules](./common-country.rules) | Block | Only Allow Country's Who Wont Pass Much Malicous Traffic.<br>
ASN List | [bad-asn.rules](./bad-asn.rules) | Block | ASN List Of Most Known Proxyscraping Sites.<br>
Threat Score | [threatscore.rules](./threatscore.rules) | Block | Block Bad Threats Flagged By Cloudflare<br>
Request Method | [request-method.rules](./request-method.rules) | Block | Block POST & HEAD Request's Only Allow GET Request's Unless Needed.<br>

## ☁️ How To Basic ☁️
![](https://media.discordapp.net/attachments/819747919581675530/829677841292460042/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678093706592276/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678478278000650/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678903131897906/unknown.png) 
