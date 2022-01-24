# heroku-vmess
Deploy VLESS server to heroku

**由于 Heroku 有可能会封本项目，且用切珍惜，也可以 Fork 本项目后，修改 README.md 中的部署链接为自己的用户名后，再进行部署。**

**Heroku 为我们提供了免费的容器服务，我们不应该滥用它，所以本项目不宜做为长期翻墙使用。**

**Heroku 的网络并不稳定，部署前请三思。**

## 镜像


[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/louyour/dan-vmess)

## ENV 设定


* 代理协议(类型)：vmess 
* 地址(Address)：appname.herokuapp.com
* 端口(Port)：443
* 默认UUID：ad806487-2d26-4636-98b6-ab85cc8521f7
* 额外(AlterID): 64
* 加密方式(encryption)：auto
* 传输协议(Transport)：ws
* 伪装类型：none
* 路径：/
* 底层传输安全：tls


V2Ray 将在部署时自动安装最新版本。

**出于安全考量，除非使用 CDN，否则请不要使用自定义域名，而使用 Heroku 分配的二级域名，以实现 V2Ray Websocket + TLS。**
