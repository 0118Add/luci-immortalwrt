# 简介
- 用于 OpenWRT 路由器上进行 微信/Telegram 推送的插件
- 支持列表：
- 微信推送/Server酱    https://sct.ftqq.com/
- 企业微信/应用推送    https://work.weixin.qq.com/api/doc/90000/90135/90248
- 微信推送/WxPusher    https://wxpusher.zjiecode.com/docs
- 微信推送/推送加      http://www.pushplus.plus/
- Telegram/BotFather  https://t.me/BotFather
- 精力有限，如需要钉钉推送、飞书推送、Bark推送等请尝试 https://github.com/zzsj0928/luci-app-pushbot
- 依赖 iputils-arping + curl + jq 命令，安装前请 `opkg update`，小内存路由谨慎安装


#### 主要功能
- 路由 IP、IPv6 变动推送
- 设备 上线、离线 推送
- 设备在线列表及流量使用情况
- CPU 负载、温度监视、PVE 宿主机温度监控
- 路由运行状态定时推送
- 路由 Web、SSH 登录提示，自动拉黑、端口敲门
- 无人值守任务
