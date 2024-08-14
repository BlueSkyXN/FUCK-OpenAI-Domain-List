# FUCK-OpenAI-Domain-List
为了避免错误地访问OPENAI、CHATGPT，可以屏蔽或调整部分域名的规则，以及重定向等操作

你可以在这里获得Hosts列表 [OpenAI.txt](OpenAI.txt)

另外你还可以用我的另外一个项目去广告和跟踪器 https://github.com/BlueSkyXN/AdGuardHomeRules

---


## OpenAI 官方域名

如果一个机器不在 OpenAI 的服务区，如中国大陆或香港，建议在本地设备和远程设备上设置以下规则：

```
# 127.0.0.1 chat.openai.com
# 127.0.0.1 ios.chat.openai.com
# 127.0.0.1 api.openai.com
# 127.0.0.1 platform.openai.com
# 127.0.0.1 oaistatic.com
# 127.0.0.1 oaiusercontent.com
# 20240814 Update
# 127.0.0.1 files.oaiusercontent.com
# 127.0.0.1 chatgpt.com
# 127.0.0.1 cdn.oaistatic.com
# 127.0.0.1 cdn.oaistatic.com
```

请注意，这些规则默认被注释掉了，如果你需要使用，你可以去掉 `#` 符号。

## 订阅管理器域名

这个域名和 iOS 有关。   [Review.md](Review.md)

实测发现，即使屏蔽了此域名，也不会影响 iOS PLUS 用户的功能。但我们无法确定是否会影响新购的用户，请根据自己的实际情况判断：

```
127.0.0.1 api.revenuecat.com
```

## 跟踪器

下列各类跟踪器的域名    [Review.md](Review.md)

可以根据需要进行屏蔽：


```
127.0.0.1 o33249.ingest.sentry.io
127.0.0.1 events.statsigapi.net
127.0.0.1 api.mixpanel.com
127.0.0.1 browser-intake-datadoghq.com
```

这些跟踪器通常用于收集使用情况数据，以便改善产品和服务。如果你选择屏蔽这些域名，那么这些服务将无法接收到你的数据。

---

请注意，修改你的设备上的 hosts 文件可能会影响你的网络连接和应用的正常运行，所以请确保你清楚你在做什么，如果有任何疑问，建议寻求专业的帮助。
