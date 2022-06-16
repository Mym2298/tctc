# tctc
//作者QQ2298755276 TG@CoZhiJun。资源搜集于网络
[general]
server_check_url=http://cp.cloudflare.com/generate_204
dns_exclusion_list=*.cmpassport.com, *.jegotrip.com.cn, *.icitymobile.mobi, id6.me, *.pingan.com.cn, *.cmbchina.com
geo_location_checker=http://ip-api.com/json/?lang=zh-CN, https://raw.githubusercontent.com/Orz-3/Orz-3/master/QuantumultX/IP.js
resource_parser_url=https://cdn.jsdelivr.net/gh/KOP-XIAO/QuantumultX@master/Scripts/resource-parser.js
excluded_routes=239.255.255.250/32, 24.105.30.129/32, 185.60.112.157/32, 185.60.112.158/32, 182.162.132.1/32
udp_whitelist=1-442, 444-65535

[dns]
no-ipv6
server=/aaplimg.com/119.29.29.29
address=/mtalk.google.com/108.177.125.188
server=/dl.google.com/119.29.29.29
server=/dl.l.google.com/119.29.29.29
server=/update.googleapis.com/119.29.29.29
server=/*.dl.playstation.net/119.29.29.29
server=/amplifi.lan/system
server=/router.synology.com/system
server=/sila.razer.com/system
server=/router.asus.com/system
server=/routerlogin.net/system
server=/orbilogin.com/system
server=/www.LinksysSmartWiFi.com/system
server=/LinksysSmartWiFi.com/system
server=/myrouter.local/system
server=/www.miwifi.com/system
server=/miwifi.com/system
server=/mediarouter.home/system
server=/tplogin.cn/system
server=/tplinklogin.net/system
server=/melogin.cn/system
server=/falogin.cn/system

[policy]
static=StreamingSE, direct, proxy, reject, 香港节点, 台湾节点, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/niconico_1.png
static=WeChat, direct, proxy, img-url=https://raw.githubusercontent.com/tugepaopao/Image-Storage/master/cartoon/Cute/%23.png
static=其余加速, proxy, 香港节点, 台湾节点, 日本节点, 美国节点, reject, direct, 狮城, img-url=https://raw.githubusercontent.com/tugepaopao/Image-Storage/master/cartoon/Cute1/2921096.png
static=油管, proxy, 台湾节点, 香港节点, 日本节点, 狮城, img-url=https://raw.githubusercontent.com/tugepaopao/Image-Storage/master/cartoon/Cute/1icon.png
static=TikTok, direct, proxy, 日本节点, img-url=https://raw.githubusercontent.com/tugepaopao/Image-Storage/master/cartoon/Cute/hat.png
static=Google, 美国节点, proxy, img-url=https://raw.githubusercontent.com/tugepaopao/Image-Storage/master/cartoon/Cute/google.png
static=Facebook, proxy, 其余加速, 台湾节点, 日本节点, img-url=https://raw.githubusercontent.com/tugepaopao/Image-Storage/master/cartoon/Cute1/1644015.png
static=Spotify, direct, proxy, 日本节点, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Alpha/FRANXX.png
static=Twitter, reject, 日本节点, direct, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Alpha/Muchang.png
static=想不到的网站, direct, 香港节点, 台湾节点, 日本节点, 美国节点, proxy, reject, 其余加速, img-url=https://raw.githubusercontent.com/tugepaopao/Image-Storage/master/cartoon/Cute1/1814229.png
static=其他国外媒体, proxy, 香港节点, 台湾节点, 日本节点, 美国节点, img-url=https://raw.githubusercontent.com/tugepaopao/Image-Storage/master/cartoon/Cute/youtube.png
static=网易云, direct, 网易云音乐, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Netease_Music_Unlock.png
available=网易云音乐, server-tag-regex=网易|网易云|music|Music|音乐, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Netease_Music.png
url-latency-benchmark=狮城, server-tag-regex=(?=.*(新|新加坡|狮城|🇸🇬))^((?!(台|日|美|港)).)*$, check-interval=600, tolerance=0, alive-checking=false, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Singapore.png
static=香港节点, server-tag-regex=(?=.*(港|HK|(?i)Hong))^((?!(台|日|韩|新|美)).)*$, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/HK.png
static=台湾节点, server-tag-regex=(?=.*(台|TW|(?i)Taiwan))^((?!(日|韩|新|美)).)*$, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/TW.png
static=日本节点, server-tag-regex=(?=.*(日|JP|(?i)Japan))^((?!(港|台|韩|新|美|俄)).)*$, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/JP.png
static=美国节点, server-tag-regex=(?=.*(美|US|(?i)States|American))^((?!(港|台|日| 韩|新|下载|流)).)*$, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/US.png
[server_remote]
https://xn--4gq62f52gdss.com/api/v1/client/subscribe?token=7e89fb0b006b06dc679c0a6e20ec626f#一元#regex=港|日&regout=直连&npt=2&info=1, tag=一, update-interval=172800, opt-parser=true, enabled=true
https://sub.store/download/%E6%AC%A1%E5%85%83#次元, tag=Tag-1655038898, update-interval=172800, opt-parser=false, enabled=true
https://ssssv2.xyz/api/v1/client/subscribe?token=d52f6542b3d472c3401c7a53854d8adc#regex=港|HK|美|US|台|TW|日|JP|新&sort=日>港>美>台&emoji=-1&delreg=加速|【极速】, tag=Tag-1654822568, img-url=applelogo.system, update-interval=172800, opt-parser=true, enabled=true
https://fanqiang.eu/api/v1/client/subscribe?token=ba6540e09a90909ac384e3e5bc9b7bfa#regex=港|HK|法|美|US|台|TW|日|JP|澳|德|印&sort=日>港>美>台&emoji=-1, tag=Tag-1654754651, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Available.png, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/yyn618/QuantumultX-Script/main/UnlockNetease.list, tag=wyy, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Netease_Music.png, update-interval=172800, opt-parser=true, enabled=true
[filter_remote]
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Steam/Steam.list, tag=Steam, force-policy=proxy, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/StreamingMedia/StreamingSE.list, tag=b站换区, force-policy=StreamingSE, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/WeChat/WeChat.list, tag=微信, force-policy=WeChat, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Google/Google.list, tag=谷歌Google, force-policy=Google, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/WSL33099/QuantumultX/main/NetEaseMusic/NetEaseMusic.list, tag=网易云, force-policy=网易云, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Twitter/Twitter.list, tag=Twitter, force-policy=Twitter, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Facebook/Facebook.list, tag=Facebook, force-policy=Facebook, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/Alcc9238/ios_rule_script/master/rule/QuantumultX/YouTube/YouTube.list, tag=YouTube, force-policy=油管, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontents.com/Hedilict/QuantumultX/master/Filter/Media/Spotify.list, tag=sp破解, force-policy=Spotify, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Video/TikTok.list, tag=海外抖音, force-policy=其他国外媒体, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Unbreak.list, tag=规则修正, force-policy=direct, update-interval=172800, opt-parser=true, enabled=true

https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/HK.list, tag=流媒体HK, force-policy=香港节点, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/TW.list, tag=流媒体TW, force-policy=台湾节点, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/JP.list, tag=流媒体JP, force-policy=日本节点, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/US.list, tag=流媒体US, force-policy=美国节点, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Streaming.list, tag=其他国外媒体, force-policy=其他国外媒体, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Global.list, tag=其余加速, force-policy=其余加速, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/Apple.list, tag=Apple, force-policy=direct, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/China.list, tag=国内网站, force-policy=direct, update-interval=172800, opt-parser=true, enabled=true
[rewrite_remote]
https://github.com/DualSubs/DualSubs/blob/main/qxrewrite/DualSubs.YouTube.qxrewrite?raw=true, tag=YouTube字幕, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/WSL33099/QuantumultX/main/Conf/Sub-Store.snippet, tag=sub订阅, update-interval=172800, opt-parser=false, enabled=true
https://github.com/VirgilClyne/iRingo/blob/beta/qxrewrite/Weather.beta.qxrewrite?raw=true, tag=雨, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/githubdulong/Script/master/jd_price2.sgmodule, tag=京东比价, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Rewrite/Function/Bilibili_CC.conf, tag=B站台区繁体字幕转简体, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/Block/YouTubeAds.conf, tag=YouTube去广, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/WSL33099/QuantumultX/main/Conf/Readdle.conf, tag=d解锁, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/chavyleung/scripts/master/box/rewrite/boxjs.rewrite.quanx.conf, tag=BoxJS, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/WSL33099/QuantumultX/main/Conf/Ps.conf, tag=ps解锁, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/WSL33099/QuantumultX/main/Conf/Picsart.conf, tag=美易解锁, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/WSL33099/QuantumultX/main/Conf/Picsew.conf, tag=picsew解锁, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/TestFlightDownload.conf, tag=TestFlight解锁, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/app2smile/rules/master/module/spotify.conf, tag=Spotify解锁, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/TikTok.conf, tag=Tiktok解锁, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/General.conf, tag=神机重定向, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/zwf234/rules/master/QuantumultX/qxrules.conf, update-interval=172800, opt-parser=false, enabled=false

[server_local]




















[filter_local]
host-suffix, m.speedtest.cn, 其余加速
host-keyword, *paopaoyun*, direct
host-suffix, ip168.com, 其余加速
host-suffix, paypal.com, 美国节点
host-suffix, jsdelivr.net, 其余加速
host-suffix, y.music.163.com, 网易云
host-suffix, facebook.net, Facebook
host-suffix, facebook.com, Facebook
host-suffix, facebookmail.com, Facebook
host-keyword, .facebook., Facebook
host-suffix, twitter.com, Twitter
host-suffix, zhenbuka3.com, direct
host-suffix, zh.hk1lib.org, 其余加速
host-suffix, www.wechat.com, direct
host-suffix, local, direct
ip-cidr, 192.168.0.0/16, direct
ip-cidr, 10.0.0.0/8, direct
ip-cidr, 172.16.0.0/12, direct
ip-cidr, 127.0.0.0/8, direct
ip-cidr, 100.64.0.0/10, direct
ip-cidr, 224.0.0.0/4, direct
ip6-cidr, fe80::/10, direct
ip-cidr, 203.107.1.1/24, direct
ip-cidr, 183.240.197.130/32, direct
final, 想不到的网站
ip-cidr, 203.107.1.1/24, reject
[rewrite_local]
# 京东比价
^https?://api\.m\.jd\.com/(client\.action|api)\?functionId=(wareBusiness|serverConfig|basicConfig|lite_wareBusiness|pingou_item) url script-response-body https://raw.githubusercontent.com/Tartarus2014/Script/master/jd_price_lite.js
#哔哩哔哩番剧监控cookie
https?:\/\/app.bilibili.com\/x\/v2\/space\/bangumi url script-request-header https://raw.githubusercontent.com/lowking/Scripts/master/bilibili/bangumiMonitor.js
#哔哩哔哩大会员特权领取cookie
https:\/\/api.bilibili.com\/x\/vip\/privilege\/receive url script-request-header https://raw.githubusercontent.com/lowking/Scripts/master/bilibili/privilegeReceive.js
^https:\/\/ap(p|i)\.bili(bili|api)\.(com|net)\/(pgc\/view\/v\d\/app\/season|x\/v\d\/search\/defaultwords)\?access_key url script-response-body https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/Bili_Auto_Regions.js

#比价
#^https:\/\/ap(p|i)\.bili(bili|api)\.(com|net)\/x\/v\d\/search(\/type)?\?.+?%20(%E6%B8%AF|%E5%8F%B0|%E4%B8%AD)& url script-request-header https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/Bili_Auto_Regions.js
# 获取京东Cookie. 
//^https:\/\/(api\.m|me-api)\.jd\.com\/(client\.action\?functionId=signBean|user_new\/info\/GetJDUserInfoUnion\?) url script-request-header https://raw.githubusercontent.com/NobyDa/Script/master/JD-DailyBonus/JD_DailyBonus.js
[task_local]
event-interaction https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/streaming-ui-check.js, tag=流媒体解锁查询, img-url=arrowtriangle.right.square.system, enabled=true
event-interaction https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/TaskLocal/NeteaseMusicUnlockCheck.js, tag=网易音乐查询, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Netease_Music_Unlock.png, enabled=false
0 0 0,1 * * ? https://raw.githubusercontent.com/lowking/Scripts/master/bilibili/bangumiMonitor.js, tag=bilibili, enabled=false
// GeoIP查询 - ip.sb
event-interaction https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/geo_location.js, tag=GeoIP 查询, img-url=location.fill.viewfinder.system
event-interaction https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/switch-check-google.js, tag=送中 查询, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Google.png, enabled=true
//YouTube Premium 查询
event-interaction https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/ytb-ui-check.js, tag=YouTube 解锁查询, img-url=text.magnifyingglass.system, enabled=true
event-interaction https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/TaskLocal/NodeLinkCheck.js, tag=代理链路检测, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Stack.png, enabled=true
[http_backend]

[mitm]

hostname = *.bilibili.com,me-api.jd.com,*.jd.com,ap?.bili*i.com, ap?.bili*i.net,%INSERT% api.m.jd.com
passphrase = 5A0B6C67
p12 = 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
skip_validating_cert = true
