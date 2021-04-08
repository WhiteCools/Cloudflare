### ☁️ Cloudflare Firewall Rules To Prevent DDOS Attacks ☁️

Since Layer 7 Has Reached The Majority Of The Public Nowadays And Kids Sites Are Being Railed Best I Released This For Those Who Have Zero Idea What There Doing

## Firewall Rules

Rule Name | File Name | Action | What For
---- | ---- | ---- | ----
Countries | [common-country.rules](./common-country.rules) | Block | Only allow country's who wont pass much malicous traffic.<br>
ASN List | [bad-asn.rules](./bad-asn.rules) | Block | ASN List Of Most Known Proxyscraping Sites.<br>
Request Method | [request-method.rules](./request-method.rules) | Block | Block POST & HEAD Requests Only Allow GET Request's Unless Needed.<br>
useragents.rules | [useragents.rules](./useragents.rules) | Block | Block Checkhost & Golang Useragent Isnt Required And Mostly Pointless.<br>

![](https://media.discordapp.net/attachments/819747919581675530/829677841292460042/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678093706592276/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678478278000650/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678903131897906/unknown.png) 
