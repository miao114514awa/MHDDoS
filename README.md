<h1 align="center">MHDDoS - 支持56种攻击方法的DDoS脚本</h1>
<em><h5 align="center">(编程语言 - Python 3)</h5></em>

<p align="center">
<a href="#"><img alt="MH-DDoS forks" src="https://img.shields.io/github/forks/MatrixTM/MHDDoS?style=for-the-badge"></a>
<a href="#"><img alt="MH-DDoS last commit (main)" src="https://img.shields.io/github/last-commit/MatrixTM/MHDDoS/main?color=green&style=for-the-badge"></a>
<a href="#"><img alt="MH-DDoS Repo stars" src="https://img.shields.io/github/stars/MatrixTM/MHDDoS?style=for-the-badge&color=yellow"></a>
<a href="#"><img alt="MH-DDoS License" src="https://img.shields.io/github/license/MatrixTM/MHDDoS?color=orange&style=for-the-badge"></a>
<a href="https://github.com/MatrixTM/MHDDoS/issues"><img alt="MatrixTM issues" src="https://img.shields.io/github/issues/MatrixTM/MHDDoS?color=purple&style=for-the-badge"></a>
  
<p align="center">未经网站所有者同意，请勿发动攻击。</p>

<p align="center"><img src="https://i.imgur.com/aNrHJcA.png" width="1078" height="433" alt="POWER"></p>
<p align="center"><img src="https://i.imgur.com/4Q7v2wn.png" width="1078" height="296" alt="SCRIPT"></p>

## 功能与方法

 * 💣 第7层攻击

   * <img src="https://img.icons8.com/cotton/344/domain.png" width="16" height="16" alt="get"> GET | GET洪水攻击
   * <img src="https://cdn0.iconfinder.com/data/icons/database-storage-5/60/server__database__fire__burn__safety-512.png" width="16" height="16" alt="post"> POST | POST洪水攻击
   * <img src="https://static-00.iconduck.com/assets.00/ovh-icon-2048x2048-l4c3izvg.png" width="16" height="16" alt="ovh"> OVH | 绕过OVH防护
   * <img src="https://cdn-icons-png.flaticon.com/512/1691/1691948.png" width="16" height="16" alt="ovh"> RHEX | 随机HEX数据
   * <img src="https://cdn-icons-png.flaticon.com/512/4337/4337972.png" width="16" height="16" alt="ovh"> STOMP | 绕过验证码检测
   * <img src="https://cdn.iconscout.com/icon/premium/png-256-thumb/cyber-bullying-2557797-2152371.png" width="16" height="16" alt="stress"> STRESS | 发送高字节HTTP数据包 
   * <img src="https://pbs.twimg.com/profile_images/1351562987224641544/IKb4q_yd_400x400.jpg" width="16" height="16" alt="dyn"> DYN | 随机子域名的新型攻击方法
   * <img src="https://cdn-icons-png.flaticon.com/512/6991/6991643.png" width="16" height="16" alt="downloader"> DOWNLOADER | 缓慢读取数据的新型攻击方式
   * <img src="https://cdn2.iconfinder.com/data/icons/poison-and-venom-fill/160/loris2-512.png" width="16" height="16" alt="slow"> SLOW | Slowloris传统DDoS方法
   * <img src="https://lyrahosting.com/wp-content/uploads/2020/06/ddos-how-work-icon.png" width="16" height="16" alt="head"> HEAD | https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/HEAD
   * <img src="https://img.icons8.com/plasticine/2x/null-symbol.png" width="16" height="16" alt="null"> NULL | 空UserAgent及其他...
   * <img src="https://i.pinimg.com/originals/03/2e/7d/032e7d0755cd511c753bcb6035d44f68.png" width="16" height="16" alt="cookie"> COOKIE | 随机Cookie触发PHP'if (isset($_COOKIE))'
   * <img src="https://cdn0.iconfinder.com/data/icons/dicticons-files-folders/32/office_pps-512.png" width="16" height="16" alt="pps"> PPS |  仅发送'GET / HTTP/1.1\r\n\r\n'
   * <img src="https://cdn3.iconfinder.com/data/icons/internet-security-14/48/DDoS_website_webpage_bomb_virus_protection-512.png" width="16" height="16" alt="even"> EVEN | 带更多请求头的GET方法
   * <img src="https://iili.io/HU9BC74.png" width="16" height="16" alt="googleshield"> GSB | 绕过Google Project Shield防护
   * <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/DDoS-Guard_logo.svg/1200px-DDoS-Guard_logo.svg.png" width="16" height="16" alt="DDoSGuard"> DGB | 绕过DDoS Guard防护
   * <img src="https://i.imgur.com/bGL8qfw.png" width="16" height="16" alt="ArvanCloud"> AVB | 绕过Arvan Cloud防护
   * <img src="https://iili.io/HU9BC74.png" width="16" height="16" alt="Google bot"> BOT | 模拟Google爬虫
   * <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Apache_HTTP_Server_Logo_%282016%29.svg/1000px-Apache_HTTP_Server_Logo_%282016%29.svg.png" width="16" height="16" alt="Apache Webserver"> APACHE | Apache漏洞利用
   * <img src="https://icon-library.com/images/icon-for-wordpress/icon-for-wordpress-16.jpg" width="16" height="16" alt="wordpress expliot"> XMLRPC | WordPress XMLRPC漏洞利用(需添加/xmlrpc.php路径)
   * <img src="https://techcrunch.com/wp-content/uploads/2019/06/J2LlHqT3qJl0bG9Alpgc-1-730x438.png?w=730" width="16" height="16" alt="CloudFlare"> CFB | 绕过CloudFlare防护
   * <img src="https://techcrunch.com/wp-content/uploads/2019/06/J2LlHqT3qJl0bG9Alpgc-1-730x438.png?w=730" width="16" height="16" alt="CloudFlare UnderAttack Mode"> CFBUAM | 绕过CloudFlare"Under Attack"模式
   * <img src="http://iclouddnsbypass.com/wp-content/uploads/2015/02/iCloudDNSBypassServer.ico" width="16" height="16" alt="bypass"> BYPASS |  绕过常规AntiDDoS防护
   * <img src="https://cdn-icons-png.flaticon.com/512/905/905568.png" width="16" height="16" alt="bypass"> BOMB |  使用codesenberg/bombardier进行绕过
   * 🔪 KILLER | 启动多线程彻底瘫痪目标
   * 🧅 TOR | 绕过.onion网站防护


* 🧨 第4层攻击: 
  * <img src="https://raw.githubusercontent.com/kgretzky/pwndrop/master/media/pwndrop-logo-512.png" width="16" height="16" alt="tcp"> TCP | TCP洪水攻击绕过
  * <img src="https://styles.redditmedia.com/t5_2rxmiq/styles/profileIcon_snoob94cdb09-c26c-4c24-bd0c-66238623cc22-headshot.png" width="16" height="16" alt="udp"> UDP | UDP洪水攻击绕过
  * <img src="https://cdn-icons-png.flaticon.com/512/1918/1918576.png" width="16" height="16" alt="syn"> SYN | SYN洪水攻击
  * <img src="https://cdn-icons-png.flaticon.com/512/1017/1017466.png" width="16" height="16" alt="cps"> CPS | 通过代理快速建立关闭连接
  * <img src="https://icon-library.com/images/icon-ping/icon-ping-28.jpg" width="16" height="16" alt="icmp"> ICMP | ICMP回显请求洪水攻击(第3层)
  * <img src="https://s6.uupload.ir/files/1059643_g8hp.png" width="16" height="16" alt="connection"> CONNECTION | 通过代理保持持久连接
  * <img src="https://ia803109.us.archive.org/27/items/source-engine-video-projects/source-engine-video-projects_itemimage.png" width="16" height="16" alt="vse"> VSE | 发送Valve Source引擎协议
  * <img src="https://mycrackfree.com/wp-content/uploads/2018/08/TeamSpeak-Server-9.png" width="16" height="16" alt="teamspeak 3"> TS3 | 发送TeamSpeak 3状态ping协议
  * <img src="https://cdn2.downdetector.com/static/uploads/logo/75ef9fcabc1abea8fce0ebd0236a4132710fcb2e.png" width="16" height="16" alt="fivem"> FIVEM | 发送FiveM状态ping协议
  * <img src="https://cdn.iconscout.com/icon/free/png-512/redis-4-1175103.png" width="16" height="16" alt="mem"> MEM | Memcached放大攻击
  * <img src="https://lyrahosting.com/wp-content/uploads/2020/06/ddos-attack-icon.png" width="16" height="16" alt="ntp"> NTP | NTP放大攻击
  * <img src="https://cdn-icons-png.flaticon.com/512/4712/4712139.png" width="16" height="16" alt="mcbot"> MCBOT | Minecraft机器人攻击
  * <img src="https://cdn.worldvectorlogo.com/logos/minecraft-1.svg" width="16" height="16" alt="minecraft"> MINECRAFT | Minecraft状态ping协议
  * <img src="https://cdn.worldvectorlogo.com/logos/minecraft-1.svg" width="16" height="16" alt="minecraft pe"> MCPE | Minecraft PE状态ping协议
  * <img src="https://cdn-icons-png.flaticon.com/512/2653/2653461.png" width="16" height="16" alt="dns"> DNS | DNS放大攻击
  * <img src="https://lyrahosting.com/wp-content/uploads/2020/06/ddos-attack-icon.png" width="16" height="16" alt="chargen"> CHAR | Chargen放大攻击
  * <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRct5OvjSCpUftyRMm3evgdPOa-f8LbwJFO-A&usqp=CAU" width="16" height="16" alt="cldap"> CLDAP | Cldap放大攻击
  * <img src="https://help.apple.com/assets/6171BD2C588E52621824409D/6171BD2D588E5262182440A4/en_US/8b631353e070420f47530bf95f1a7fae.png" width="16" height="16" alt="ard"> ARD | Apple远程桌面放大攻击
  * <img src="https://www.tenforums.com/geek/gars/images/2/types/thumb__emote__esktop__onnection.png" width="16" height="16" alt="rdp"> RDP |  远程桌面协议放大攻击

* ⚙️ 工具 - 运行命令 
`
python3 start.py tools
`
  * 🌟 CFIP | 查找Cloudflare保护网站的真实IP
  * 🔪 DNS | 显示网站的DNS记录
  * 📍  TSSRV | TeamSpeak SRV记录解析
  * ⚠  PING | 服务器PING测试
  * 📌 CHECK | 检查网站状态
  * 😎 DSTAT | 显示接收/发送字节量统计

* 🎩 其他功能
  * ❌ STOP | 停止所有攻击
  * 🌠 TOOLS | 控制台工具集
  * 👑 HELP | 显示脚本使用帮助

  
<h1 align="center">
我们的社交平台💻
  
</h2> 

<h1 style="color:red;text-align: center;" style="text-align: center;" align="center">请不要在"Issues"板块提问！</h1>
<div align="center">
   <img src="https://icon-library.com/images/github-icon-vector/github-icon-vector-27.jpg" width="64" height="64"/>
   <img src="https://brandlogos.net/wp-content/uploads/2021/11/discord-logo.png"  width="64" height="64" alt="discord" />
   <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Telegram_logo.svg/2048px-Telegram_logo.svg.png" width="64" height="64" alt="telegram" />
</div>

 * [Matrix社区Telegram频道](https://t.me/Matrix_Development)
 * [Matrix团队Telegram群组](https://t.me/MatrixTMChat)
 * [GitHub](https://github.com/MatrixTM)
### 如果喜欢本项目，请在仓库点个Star！

## 下载

可从[GitHub Releases](https://github.com/MatrixTM/MHDDoS/releases)下载

### 快速开始

**环境要求**

* [dnspython](https://github.com/rthalley/dnspython)
* [cfscrape](https://github.com/Anorov/cloudflare-scrape)
* [impacket](https://github.com/SecureAuthCorp/impacket)
* [requests](https://github.com/psf/requests)
* [Python3][python3]
* [PyRoxy](https://github.com/MatrixTM/PyRoxy)
* [icmplib](https://github.com/ValentinBELYN/icmplib)
* [certifi](https://github.com/certifi/python-certifi)
* [psutil](https://github.com/giampaolo/psutil)
* [yarl](https://github.com/aio-libs/yarl)
---

## 文档

请参阅[GitHub Wiki](https://github.com/MatrixTM/MHDDoS/wiki)

**克隆并安装脚本**

```shell script
git clone https://github.com/MatrixTM/MHDDoS.git
cd MHDDoS
pip install -r requirements.txt
```

**全新VPS一键安装**

```shell script
apt -y update && apt -y install curl wget libcurl4 libssl-dev python3 python3-pip make cmake automake autoconf m4 build-essential git && git clone https://github.com/MatrixTM/MHDDoS.git && cd MH* && pip3 install -r requirements.txt
```

[python3]: https://python.org 'Python3'
[github issues]: https://github.com/MatrixTM/MHDDoS/issues 'enter'

---

## 需要便宜的按小时计费服务器？

<a href="https://aeza.net/?ref=375036"><img src="https://github.com/user-attachments/assets/f875428b-cb35-442d-8dce-cdc5ead4ffbd" width="728" height="90" alt="aeza"></a>

#### 您可以通过加密货币从[Aeza Hosting](https://aeza.net/?ref=375036)购买每小时10Gbps的服务器(100%匿名)。
