广告过滤规则来自：
https://anti-ad.net/
anti-AD致力于成为中文区命中率最高的广告过滤列表，实现精确的广告屏蔽和隐私保护。现已支持AdGuardHome，dnsmasq，Surge，Pi-Hole，Clash，smartdns，sing-box等网络组件。

使用anti-AD能够屏蔽广告域名，能屏蔽电视盒子广告，屏蔽app内置广告，同时屏蔽了一些日志收集、大数据统计等涉及个人隐私信息的站点，能够保护个人隐私不被偷偷上传。

本工具是通过域名解析层（DNS服务）来屏蔽广告和保护隐私的，其将各大著名的hosts，ad filter lists，adblock list等的列表进行合并去重，再进行一系列的抽象化，例如主动剔除失效域名、easylist优化模糊匹配、增强的黑白名单机制等措施，最终生成期望的高命中率列表。

不同格式的过滤列表文件会定期自动更新，其分别用于不同服务中的广告过滤规则:
https://anti-ad.net/anti-ad-for-dnsmasq.conf
https://anti-ad.net/easylist.txt（AdGuardHome）
https://anti-ad.net/adguard.txt（AdGuard专用规则）
https://anti-ad.net/domains.txt
https://anti-ad.net/surge.txt
https://anti-ad.net/surge2.txt（据说更节省内存）
https://anti-ad.net/clash.yaml
https://anti-ad.net/anti-ad-for-smartdns.conf
https://anti-ad.net/anti-ad-sing-box.srs
