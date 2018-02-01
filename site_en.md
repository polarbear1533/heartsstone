# Heartsstone being running since January 22, 2018 <img src="pic1.png" width="30" height="30" />
<h1>
  <span style="color: #0A0A0A; font-size: 160%; font-family:Comic Sans MS, cursive, sans-serif">Heart</span><span style="color: #f2cf4a; font-size: 160%; font-family:Comic Sans MS, cursive, sans-serif">SS</span><span style="color: #0A0A0A; font-size: 160%;font-family:Comic Sans MS, cursive, sans-serif">tone</span>  
  <span style="font-size: 14px; color: #989a9c; font-size: 50%; font-family: Helvetica Neue, Helvetica, Segoe UI;">A secure socks5 proxy service, SS stand for Shadowsocks(r).</span>
</h1>

English | Working on other language

## Introduction

### [*TL;DR -> Skip*](#tit3)

[Shadowsocks](https://shadowsocks.org/en/index.html) essentially is a socks proxy has encryption, Shadowsocksr is an improved version of shadowsocks, support authentication and obfuscation protocol that will harden your protection and anti-detection, also another advantage of socks proxy is the speed.

In most case, the proxy is just like lightweight VPN, secure your data, faster speed, save your battery, bypass region restriction.

 An apparent difference between proxy and VPN that is.
Proxy is running in [User space]((https://en.wikipedia.org/wiki/User_space)) as a process means more flexible for be programmed. As the disadvantage, not all applications support proxy, nevertheless, this problem can be solved by [Port forwarding](https://en.wikipedia.org/wiki/Port_forwarding).

Whereas VPN is running in [Kernel][1] as a module, all your network traffic will go through VPN without any supported by the developer, its cover your whole system naturally.

[1]: https://en.wikipedia.org/wiki/Kernel_(operating_system)

### Guide
* [How to config client](#tit1)
 1. [Add server information in the client](#config_1)
 2. [Select to apply the configuration you just created](#config_2)
 3. [Toggle on the proxy](#config_3)
* [Supported Platforms for client](#tit2)
 * [Mac OS](#macos_client)
 * [Windows](#windows_client)
 * [iOS](#ios_client)
 * [Android](#android_client)
 * [Linux](#linux_client)
* [Getting started with Shadowsocks](#tit3)
 * [Speed](#speed)
 * [Ping](#ping)
 * [Location](#location)
 * [Privacy Policy](#pp)
 * [Addition](#addt)
 * [Price](#price)
   * Trial
   * Small
   * Medium
   * Large
* [Accept payment methods and how to pay](#tit4)
 * [PayPal](#paypal)
 * [Crypto Currency](#cryptocurrency)
   * BitcoinCash
   * Litecoin
 * [After paid](#aftpaid)
* [Email address for order and contact](#tit5)
* [How to check how many days and data remains](#tit6)
* [Share with your friends](#tit6)
* [PGP Encryption (Optional)](#tit7)

## <a id="tit1"></a> How to config client
Shadowsocks support multiple platforms include popular desktop and mobile OS, client on all different platforms is easy to use.
You are able to use on different platforms in the mean time.

In order to apply the server information that I will send you later, basically, there's nothing more than three steps.

### <a id="config_1"></a> 1. Add server information in the client
You can find a similar window like below in all clients, to give an illustration of how to fill up with below server information:

Example server Information:
`48.7.198.45|1234|d8e5d682|chacha20|origin|tls1.2_ticket_auth`

<img src="mac1.png" width="200"/>
<img src="mac2.png" width="200"/>

The server information is what I will send to you, here is explanation of each part (You don't have to read or understand them):  
`48.7.198.45` is server domain or IP address.  
`1234` is the network port you will be access to.  
`d8e5d682` is the password for encryption.  
`chacha20` is the name of encryption algorithm will be use.    
`origin` represents the type of authentication protocol.     
`tls1.2_ticket_auth` represents the type of obfuscation protocol.  

### 2. <a id="config_2"></a> Select to apply the configuration you just created
You can save multiple server settings and switch between them. it's an awesome function available to all clients.

<img src="mac3.png" width="200"/>

### 3. <a id="config_3"></a> Toggle on the proxy
From now on, enjoy surfing the Internet through the proxy.  
You can toggle on/off the proxy at any time.  

<img src="mac4.png" width="200"/>

So hope you have sort of concept of how to use the client, now go download client that matches your platform, no problem with using multiple devices at the same time.

## <a id="tit2"> Supported Platforms for client
Generally, you only need an application, the icon is a circle with a paper plane within.

## <a id="macos_client"></a>Mac OS

You will need [ShadowsocksX-R](https://github.com/yichengchen/ShadowsocksX-R/releases/download/ssr_1.38_2/ShadowsocksX-R.app.zip) for under also include OS X Yosemite, [ShadowsocksX-NG-R8](https://github.com/qinyuhang/ShadowsocksX-NG-R/releases/download/1.4.3-R8-build2/ShadowsocksX-NG-R8.dmg) for above (Support High Sierra), their icon has slightly different but luckily easy to distinguish by the color, pink and green, respectively.

<img src="macos_client1.png" width="100"/>
<img src="macos_client2.png" width="100"/>

[*Download link is from Github, it's an open-source project*](https://github.com/qinyuhang/ShadowsocksX-NG-R)

## <a id="windows_client"></a>Windows

##### Download [shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases/download/4.0.7/Shadowsocks-4.0.7.zip)

<img src="windows_client.png" width="100"/>

Supports HTTP proxy  
Supports UDP relay  
[See more features and usage](https://github.com/shadowsocks/shadowsocks-windows/blob/master/README.md)

[*Download link is from Github, it's an open-source project*](https://github.com/shadowsocks/shadowsocks-windows)

## <a id="ios_client"></a>iOS
Download [shadowrocket in App Store](https://itunes.apple.com/us/app/shadowrocket/id932747118?mt=8)  

<img src="ios_client.png" width="100"/>

It's the best Shadowosocks client on the iOS, and it's not free, I can provide an account that already purchased for you to download it only when this app is not available in your Apple ID country(Ask me in the email).  
And please please please only downloading for yourself, do not share.

Recommend you to purchase by yourself, you won't be able to reinstall or update with my account. Its a wonderful proxy app for iOS anyway, it supports ordinary socks5 or HTTP(S) etc as well.

## <a id="android_client"></a>Android
##### Download [shadowsocksr-android](https://github.com/shadowsocksrr/shadowsocksr-android/releases/download/3.5.1.1/shadowsocksr-android-3.5.1.1.apk)

<img src="android_client.png" width="100"/>

[*Download link is from Github, it's an open-source project*](https://github.com/shadowsocksrr/shadowsocksr-android)

## <a id="linux_client"></a>Linux
I think as a Linux user, you probably already good at searching and be patient when package missing or compiling, so you deserve to have better environment support, Linux comes with a powerful CLI program `iptables` to configure rules of Linux kernel firewall, to implementing global proxy. (On Mac OS or Windows, you need additional application)

Require install a C-language client and need to compiling which does little hassle, contact me if you encountered problem, I will see if I can be of help.

## <a id="tit3"></a>Getting started with Shadowsocks

Alright, after introduced how to set up the client, I will introduce the service I will provide.

#### <a id="speed"></a>Speed
You will be able to watch Youtube in HD(720p) fluently, watch FHD(1080p) video take a little bit longer time to buffer, but it goes fluently as well since it starts playing, 1440p and 4K also can go fluently during the appropriate time.  
Well I mean, ***try yourself with the free trial***, it's better than I described.

#### <a id="ping"></a>Ping
Normally the ping is around 40ms - 200ms, its really depends on your ISP, ping represents latency, but not represents network speed of your internet neither server, so it's not that matter except for play video game.

#### <a id="location"></a>Location
Servers are located surrounding China, provides the best quality for people who living in China or need be in China.

Also provide server located in the US, especially for people who want to bypass region restriction, such as watch U.S. Netflix outside of United States.

Only Asia server available for free trial.

#### <a id="pp"></a>Privacy Policy
Heartsstone not recording or monitoring anything. Only keep follow information for each port:   

*`Port/Password/encryption/Protocol/Obfs`*: Necessary information for launch server.   
*`Data used/total`*: For to calculate date.  
*`Days remain/total`*: For to calculate time.  
*`Created date`*: For to calculate time.  
*`Email address`*: So I can know which port you are using.   
*`Your PGP public key`*: If you had sent to me.  
**And all these will be delete permanently once the port expire, no lasting records.**
You will be able to query all above information very soon, except email address and PGP public key to protecting your privacy. This function will available in a week ...

#### <a id="addt"></a>Addition

If you need server in US, then please mention it in the email, at default, I will send you server in Asia, because server in US does not provides the best speed.

**The automatic digital product delivery system still in building, so sorry that I cannot respond in seconds. I am available every day to review every email that you send me for question or order and will reply you asap.**

If you are in China, the speed may suddenly become extremely unstable, ping has over 50% packet loss, that's due to Chinese ISP try to interrupt it, despite I will check ping every day, but I still may miss, if this happens please contact me so I can fix it asap or send you alternate server. Its happen each every one or two months, you may not even realize, because I fixed it in time.

**I will try my best to make sure everything is working at anytime**

### <a id="price"></a>Price

All prices include payment fee, are the final prices.   
Your plan will expire when you spend all data or remains days is zero.  
(1GB = 1024MB, 1Month is 30days. )

#### Trial:  
2GB/End of day - Free

#### Small:  
20GB/Month - $4  
70GB/3Months - $11.99  
150GB/6Months - $23.99  

#### Medium:  
50GB/Month - $6  
180GB/3Months - $17.99  
350GB/6Months - $35.99  

#### Large:  
150GB/Month - $12  
500GB/3Months - $35.99   
1000GB/6Months - $71.99  

## <a id="tit4"></a>Accept payment methods and how to pay

### <a id="paypal"></a>PayPal
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="NKVC6VTGSRNMU">
<table>
<tr><td><input type="hidden" name="on0" value="Plans">Choose your plan</td></tr><tr><td><select name="os0">
	<option value="Small_20GB_1Month">Small_20GB_1Month $4.00 USD</option>
	<option value="Small_70GB_3Months">Small_70GB_3Months $11.99 USD</option>
	<option value="Small_150GB_6Months">Small_150GB_6Months $23.99 USD</option>
	<option value="Medium_50GB_1Month">Medium_50GB_1Month $6.00 USD</option>
	<option value="Medium_180GB_3Months">Medium_180GB_3Months $17.99 USD</option>
	<option value="Medium_350GB_6Months">Medium_350GB_6Months $35.99 USD</option>
	<option value="Large_150GB_1Month">Large_150GB_1Month $12.00 USD</option>
	<option value="Large_500GB_3Months">Large_500GB_3Months $35.99 USD</option>
	<option value="Large_1000GB_6Months">Large_1000GB_6Months $71.99 USD</option>
</select> </td></tr>
</table>
<input type="hidden" name="currency_code" value="USD">
<input type="image" src="https://www.paypalobjects.com/en_US/C2/i/btn/btn_buynowCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>

</br>
*1.* Choose your plan and click on the "Buy now" button, this will redirect to PayPal online payment, select ***Pay with debit or credit card.***  
****You don't need to have a PayPal account.****

*2.* To complete payment, PayPal will ask you some information include name and email address, what I only can get is your name and email address, I will send server information to that email address you entered. ***So be sure the email address is work***

*3.* It's done, follow my instruction on this site, ask me in the [email](#tit5) if you have the problem, PayPal is the easiest and fastest way.

### <a id="cryptocurrency"></a> Crypto Currency
<img src="bitcoincash_payment.png" width="150"/> &nbsp;&nbsp;  <img src="litecoin_payment.png" width="130" style="position:relative; top:5px;"/>

Crypto Currency isn't bad idea, the transaction fee of BitcoinCash and Litecoin is acceptable for most people, which around ***$0.1~$0.3***.  

*1.* Choose a plan and decide which Crypto Currency you would like to use, write it down in the email and [send to me](#tit5) so I can be able to reply you.  

*2.* I will reply you with the address and price of Crypto Currency you chose, after that, I will wait until you paid.  

*3.* After you paid, the transaction starts confirming, I will send server information to your email. Follow my instruction on this site, ask me in the email if you have problem.

### <a id="aftpaid"></a>After paid
**After you paid, I will send the server information like below to your email.**  
```
48.7.198.45|1234|d8e5d682|chacha20|origin|tls1.2_ticket_auth
```
**The instruction of how to configure the client is in the** **[How to config client](#tit1)** **section.**

## <a id="tit5"></a>Email address for order and contact
[hearts_of_stone@outlook.com ](mailto:hearts_of_stone@outlook.com)

## How to check how many days and data remains
You will be able to query all informations in [Privacy Policy](#pp) very soon, except email address to protecting your privacy.  
This function will available in a week ...

## <a id="tit6"></a>Share with your friends
Share with your friends tell them to add your email address in the order email and send to me, after your friend made order successfully, as reward you both will get extra 10GB data for use

## <a id="tit7"></a>PGP Encryption (Optional)
In order to level up security, I support to encrypt email with PGP. Well, this may be too much. But I believe some people like to keep their email content private, so be respect to them.  
**Remember to include your public key in the first email you send me.**

[My public key of PGP](pkey.txt)
