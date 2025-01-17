## web安全前端利用
### Web利用漏洞工具
- https://github.com/hahwul/a2sv    //SSL漏洞扫描，包括OpenSSL心脏滴血漏洞\CSS注入\SSLv3 POODLE等
- https://github.com/Valve/fingerprintjs2    //JS.被动式浏览器全指纹库获取。8k。goodjob。Browser Fingerprinting via OS and Hardware Level Features。
- https://github.com/Song-Li/cross_browser    //JS.被动式跨浏览器指纹追踪识别，支持硬件特征（显卡、cpu核数等）识别。指纹追踪技术—跨浏览器指纹识别crossbrowsertracking_NDSS17.pdf。
- https://github.com/WMJonssen/Centcount-Analytics    //PHP.数据库mysql/redis，网站分析软件，支持浏览器指纹、事件追踪、鼠标轨迹
- https://github.com/ticarpi/jwt_tool    //PY.json web token的检测
- https://github.com/MagicZer0/fastjson-rce-exploit    //JAVA.阿里fastjson RCE, 绕过autotype机制，1.2.47以下版本。jndi利用方式。Github:fastjson-1.2.47-RCE。
- https://github.com/dienuet/crossdomain    //PY.CORS（Cross-Origin Resource Sharing, 跨域资源共享）漏洞扫描器，支持读取aquatone结果，绕过origin安全设置。
- https://github.com/chenjj/CORScanner    //PY.CORS域配置错误，跨域解析漏洞扫描器。
- https://www.jianjunchen.com/post/cors安全部署最佳实践/    //intro。CORScanner
- https://www.anquanke.com/post/id/152339    //JSONP和CORS跨站跨域读取资源的漏洞利用（附带EXP）。JSON Hijacking实战利用多种利用方式
- https://github.com/Bo0oM/PHP_imap_open_exploit    //利用imap_open绕过php exec函数禁用
- https://github.com/rudSarkar/crlf-injector    //CRLF注入漏洞批量扫描
- https://github.com/lietdai/doom    //thorn上实现的分布式任务分发的ip端口漏洞扫描器
- https://github.com/gh0stkey/PoCBox    //PHP.漏洞测试验证/报告生成平台。SONP劫持、CORS、Flash跨域资源读取、Google Hack语法生成、URL测试字典生成、JavaScript URL跳转、302 URL跳转
- https://github.com/utiso/dorkbot    //通过定制化的谷歌搜索引擎进行漏洞页面搜寻及扫描
- https://github.com/NullArray/DorkNet    //基于搜索引擎的漏洞网页搜寻
- https://github.com/m3liot/shcheck    //用于检查web服务的http header的安全性
- https://github.com/18F/domain-scan    //针对域名及其子域名的资产数据检测／扫描，包括http/https检测等
- https://github.com/commixproject/commix    //命令注入漏洞扫描
- https://github.com/jcesarstef/dotdotslash    //目录遍历漏洞测试
- https://github.com/m101/hsploit    //基于rust的 HEVD 漏洞利用程序
- https://github.com/coffeehb/SSTIF    //SSTI (服务器模板注入) 漏洞的半自动化工具
- https://github.com/tijme/angularjs-csti-scanner    //探测客户端AngularJS模板注入漏洞工具
- https://github.com/epinna/tplmap    //SSTI (服务器模板注入) 漏洞检测与利用工具
### CSRF跨站请求伪造利用
- https://www.owasp.org/index.php/File:CSRFTester-1.0.zip    //java.csrf验证工具
- https://github.com/d0nutptr/sic    //RUST.CSS注入，csrf攻击
- https://github.com/UltimateHackers/Blazy    //支持测试 CSRF， Clickjacking， Cloudflare and WAF的弱口令探测器
### SSRF服务端请求伪造
- http://blog.safebuff.com/2016/07/03/SSRF-Tips/    //ssrf漏洞利用手册
- https://github.com/swisskyrepo/SSRFmap    //PY.检测ssrf漏洞
- https://github.com/tarunkant/Gopherus    //PY.利用gopher协议生成ssrf payload执行rce。
### XSS跨站脚本检测利用
- https://github.com/UltimateHackers/AwesomeXSS    //XSS Awesome系列
- http://www.xss-payloads.com    //很全面的xss工具包与资料
- https://somdev.me/21-things-xss/    //XSS的21个扩展用途
- https://www.slideshare.net/GarethHeyes/xss-magic-tricks    //burpsuite团队总结xss知识点
- https://github.com/ismailtasdelen/xss-payload-list    //XSS 漏洞Payload列表
- https://github.com/NytroRST/XSSFuzzer    //根据特定标签生成xss payload
- https://github.com/evilcos/xssor2    //余弦写的xss利用辅助工具
- https://github.com/UltimateHackers/XSStrike    //可识别并绕过WAF的XSS扫描工具
- https://github.com/raz-varren/xsshell    //GO.利用xss返回js交互shell
- https://github.com/UltimateHackers/JShell    //利用xss返回js交互shell
- https://github.com/shawarkhanethicalhacker/BruteXSS    //一款XSS扫描器，可暴力注入参数
- https://github.com/1N3/XSSTracer    //小型XSS扫描器，也可检测CRLF、XSS、点击劫持的
- https://github.com/0x584A/fuzzXssPHP    //PHP版本的反射型xss扫描
- https://github.com/chuhades/xss_scan    //批量扫描XSS的python脚本
- https://github.com/BlackHole1/autoFindXssAndCsrf    //自动化检测页面是否存在XSS和CSRF漏洞的浏览器插件
- https://github.com/shogunlab/shuriken    //使用命令行进行XSS批量检测
- https://github.com/stamparm/DSXS    //支持GET、POST方式的高效XSS扫描器
- https://github.com/bsmali4/xssfork    //kali下无法使用的话，请下载正确的PhantomJS到目录thirdparty/phantomjs/Linux
- https://github.com/riusksk/FlashScanner    //flash xss扫描
- https://github.com/Damian89/xssfinder    //针对检测网站中的反射XSS
### XSS漏洞利用平台框架
- https://github.com/beefproject/beef    //JS,RUBY.BeEF跨平台Web浏览器渗透测试工具
- https://github.com/BlackHole1/WebRtcXSS    //PHP.基于thinkphp框架，利用webrtc进行自动化XSS入侵内网平台
- https://github.com/samdenty99/injectify    //TS,JS.利用xss在网站执行mitm攻击
- https://github.com/firesunCN/BlueLotus_XSSReceiver    //JS,PHP.蓝莲花战队XSS数据接收平台（无SQL版）.GOODJOB.
- https://github.com/euphrat1ca/XssPowerByTools    //PHP.XSS平台课程设计。simple。
- https://github.com/AntSwordProject/ant    //Nodejs.蚁逅@1.0，实时上线的 XSS 盲打平台
### 本地文件包含漏洞
- https://github.com/hvqzao/liffy    //本地文件包含漏洞利用工具
- https://github.com/D35m0nd142/Kadabra    //本地文件包含漏洞扫描和利用工具
- https://github.com/P0cL4bs/Kadimus    //本地文件包含漏洞扫描和利用工具
- https://github.com/D35m0nd142/LFISuite    //本地文件包含漏洞利用及扫描工具，支持反弹shell
- https://github.com/OsandaMalith/LFiFreak    //本地文件包含漏洞利用及扫描工具，支持反弹shell
### 上传漏洞利用
- https://github.com/UltimateHackers/Arjun    //扫描网页， 使用正则表达式爆破查找隐藏的GET/POST参数
- https://github.com/3xp10it/xupload    //用于自动测试上传功能是否可上传webshell的工具
- https://github.com/gunnerstahl/JQShell    //PY3.CVE-2018-9206 jQuery File Upload利用工具
- https://github.com/destine21/ZIPFileRaider    //burp插件，测试zip文件上传漏洞
- https://github.com/jpiechowka/zip-shotgun    //PY.测试zip文件上传漏洞
- https://github.com/almandin/fuxploider    //PY3.自判定网站类型与可被允许上传的文件格式类型。
### 数据库利用/扫描/爆破
- https://github.com/sqlmapproject/sqlmap    //PY.sql注入sqlmap.GREATJOB.15K.
- https://www.netsparker.com/blog/web-security/sql-injection-cheat-sheet/    //sql注入sheet表
- https://sqlwiki.netspi.com/    //你要的sql注入知识点都能找到
- https://github.com/aleenzz/MYSQL_SQL_BYPASS_WIKI    //mysql注入,bypass的一些心得
- https://github.com/kevins1022/SQLInjectionWiki    //一个专注于聚合和记录各种SQL注入方法的wiki
- https://sinister.ly/Thread-SQLi-Dumper-v-8-5-crack    //SQLi Dumper基于搜索引擎的自动化注入利用工具。GoodJob
- https://github.com/ron190/jsql-injection    //Java.SQL注入工具.GOODJOB
- https://github.com/shack2/SuperSQLInjectionV1    //C#.安恒航牛的超级SQL注入工具【SSQLInjection】.GOODJOB
- https://www.52pojie.cn/thread-80225-1-1.html    //Pangolin Professinal Edition 3.2.4.1132 CracKed By Hmily[LCG]。白帽汇NOSEC的注入工具，NoUpdate，历史感。
- https://www.52pojie.cn/forum.php?mod=viewthread&tid=103057    //Havij v1.151 Pro CracKed By Hmily[LCG]。印度ITSecTeam编写的sql注入工具，NoUpdate，历史感。
- https://github.com/codingo/NoSQLMap    //PY2.针对nosql数据库的注入工具。1k。
- https://github.com/torque59/Nosql-Exploitation-Framework    //NoSQL扫描/爆破工具
- https://github.com/se55i0n/DBScanner    //PY2.扫描常见sql、no-sql数据库资产，进行未授权访问和弱口令检测。simple。
- https://github.com/youngyangyang04/NoSQLAttack    //一款针对mongoDB的攻击工具
- https://github.com/jas502n/unauthorized-tools    //PY.用于快速探测MongoDB未授权数据库结构，取第一条内容，并统计数据数量。
- https://studio3t.com/download    //MongoDB扫描与连接工具
- https://github.com/Neohapsis/bbqsql    //SQL盲注利用框架
- https://github.com/m8r0wn/enumdb    //MySQL和MSSQL利用工具后期爆破、搜索数据库并提取敏感信息。
- https://github.com/NetSPI/PowerUpSQL    //Powershell.的sqlserver测试框架
- https://github.com/Mayter/mssql-command-tool    //GO.mssql连接工具，sqlserver利用
- http://www.4hou.com/system/14950.html    //INTRO.利用PowerUpSQL，渗透测试技巧：绕过SQL Server登录触发器限制
- https://github.com/stampery/mongoaudit    //MongoDB审计及渗透工具
- https://github.com/missDronio/blindy    //MySQL盲注爆破工具
- https://github.com/LoRexxar/Feigong    //针对各种情况自由变化的MySQL注入脚本
- https://github.com/JohnTroony/Blisqy    //PY.用于http header中的时间盲注爆破工具，仅针对MySQL/MariaDB
- https://github.com/Turr0n/firebase    //对没有正确配置的firebase数据库进行利用
- https://github.com/quentinhardy/odat    //针对Oracle注入渗透工具
- https://github.com/Hadesy2k/sqliv    //PY2.基于搜索引擎的批量SQL注入漏洞扫描器。simple。
- https://github.com/quadcoreside/QuadCore-Web-SQLi-Injecter-DB-Dumper    //PHP.sql注入辅助，数据脱取。
- https://github.com/bambish/ScanQLi    //PY3.SQLI漏洞探测工具，不包含利用。simple
### 网站管理WebShell
- https://github.com/AntSwordProject/antSword    //js.基于Electron中国蚁剑，插件式开发。1.5k。greatjob。
- https://github.com/AntSwordProject/AntSword-Labs    //antSword测试环境
- https://github.com/Chora10/Cknife/pulls    //JAVA.Github:SecQuanCknife;gitee.com/9199771/cknife。GOODJOB,2K。
- https://github.com/euphrat1ca/hatchet    //C++.中国大砍刀
- https://github.com/tengzhangchao/PyCmd    //PY.一句话木马客户端程序，目前支持php、jsp，CS端通信加密
- https://github.com/epinna/weevely3    //PY.利用特定的一句话脚本对网站进行管理
- https://github.com/nil0x42/phpsploit    //PY3.利用特定的一句话脚本对网站进行管理
- https://github.com/wonderqs/Blade    //PY.利用特定的一句话脚本对网站进行管理
- https://github.com/anestisb/WeBaCoo    //perl.利用特定的一句话脚本对网站进行管理
- https://github.com/keepwn/Altman    //.Net,mono.跨平台菜刀
- https://github.com/euphrat1ca/Behinder    //JAVA6.rebeyond“冰蝎”动态二进制加密网站管理客户端
- https://xz.aliyun.com/t/2744    //intro.“冰蝎”利用动态二进制加密实现新型一句话木马之Java篇，木马之.NET篇，木马之PHP篇,木马之客户端篇。
- https://github.com/yzddmr6/webshell-venom    //PY.免杀webshell无限生成工具。1k。Github:tennc/webshell。
- https://github.com/UltimateHackers/nano    //php.一句话，附带py编写的生成器
- https://github.com/antonioCoco/SharPyShell    //ASP.NET.webshell for C# web applications
- https://github.com/k4mpr3t/b4tm4n    //PHP.可以伪造邮件、ddos，bat.php的webshell，初始k4mpr3t
- https://github.com/dotcppfile/DAws    //PHP.过防火墙webshell，post pass=DAws
- https://github.com/b374k/b374k    //php.网站管理，默认密码b374k
- https://github.com/wso-shell/WSO    //PHP.webshell的文件管理，可以伪装为404界面
- https://github.com/rebeyond/memShell    //JAVA.一款可以写入java web server内存中的无文件webshell
- https://github.com/DXkite/freebuf-stream-shell    //PHP.使用流包装器实现WebShell。freebuf介绍。