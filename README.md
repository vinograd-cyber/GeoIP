⛑️🛡️帮助用户屏蔽网络广告和欺诈钓鱼，为用户带来安全舒适的上网体验！
🌈使用
- 打开 https://github.com/vinograd-cyber/GeoIP 看到的都是最新版本。
- 下载 [h1y.dat](https://raw.githubusercontent.com/vinograd-cyber/GeoIP/main/geoip.dat) 域名文件放到 v2ray或xray的资源目录中，域名文件的标签支持cn/gfw/rej三种，在 v2ray或xray 配置文件中按标签设定路由规则，所有的域名均以子域名的形式进行匹配。
- [v2ray路由配置示例](https://github.com/vinograd-cyber/GeoIP/blob/main/routing.json)

🌈下载
- [h1y.dat](https://raw.githubusercontent.com/vinograd-cyber/GeoIP/main/h1y.dat)
- [geoip.dat](https://raw.githubusercontent.com/vinograd-cyber/GeoIP/main/geoip.dat)

🌈说明：
- 💡域名文件-h1y.dat：
  - ext:h1y.dat:cn 直连中国（国内）的网站（domain）【域名总数：> 66126，更新日期：07/07/22 10:55:22】
  - ext:h1y.dat:gfw 代理被GFW屏蔽的网站（domain）【域名总数：> 27442，更新日期：07/07/22 10:55:22】
  - ext:h1y.dat:rej 屏蔽广告和欺诈性网站（domain）【域名总数：> 610773，更新日期：07/07/22 10:55:22】
- 💡IP 文件-geoip.dat：
  - geoip:cn 直连中国（国内）的网站（ip）【ip总数：> 343305866，更新日期：07/07/22 10:55:22】
  - geoip:rej 屏蔽广告和欺诈性网站（ip）【ip总数：> 140573，更新日期：07/07/22 10:55:22】
