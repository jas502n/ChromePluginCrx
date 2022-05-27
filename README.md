

  # Chrome 插件离线下载备忘录

  ## 离线安装Chrome插件

  参考链接：https://mp.weixin.qq.com/s/cw3aq1uWyXUkyJFvMMmkdA

  Chrome网上应用店

  https://chrome.google.com/webstore/category/extensions?hl=en-US

  例如：下载插件 Proxy SwitchyOmega

  https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif?utm_source=chrome-ntp-icon

  从url中提取插件ID（ExtId），上面的插件id为 `gmmnidkpkgiohfdoenhpghbilmeeagjj`

  然后查看Chrome版本信息，`chrome://settings/help`

  `版本 101.0.4951.54（正式版本） (x86_64)`

  离线下载插件模板URL：

```bash
https://clients2.google.com/service/update2/crx?response=redirect&prodversion=`<ChromeVer>`&acceptformat=crx2%2Ccrx3&x=id%3D`<ExtId>`%26uc
```

  将**<ChromeVer>**、**<ExtId>**替换成正确值。

  例如:

  ```bash
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=`101.0.4951.54`&acceptformat=crx2%2Ccrx3&x=id%3D`padekgcemlokbadohgkifijomclgjgif`%26uc
  ```

  ## Proxy SwitchyOmega 2.5.21

  简介：轻松快捷地管理和切换多个代理设置。

  `chrome://extensions/`
  ![](https://pora-images-1251578175.cos.ap-shanghai.myqcloud.com/MacOs-a2d5a9a5cf564b518f3fe006c7293184/20220528002719.png)
  插件`ID：padekgcemlokbadohgkifijomclgjgif`
  ```bash
  #URL 编码后：
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dpadekgcemlokbadohgkifijomclgjgif%26uc

  #URL 解码后：
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2,crx3&x=id=padekgcemlokbadohgkifijomclgjgif&uc
  ```
  下载完成后：[extension_2_5_21_0.crx](https://clients2.googleusercontent.com/crx/blobs/Acy1k0Y7IFBaSHHT2CgFAwy1GWcGqozTRdkVQmSI86SW2BDd_u2mRCc8tlasqJL_9xG3m7N3AIr6LoNKOTo3tF5qVMJ04in-KbITo7goRUEUnXOgb89aAMZSmuUhJqwvX9_HsJfvjM6-nFupFyim_Q/extension_2_5_21_0.crx)
  ![](https://pora-images-1251578175.cos.ap-shanghai.myqcloud.com/MacOs-a2d5a9a5cf564b518f3fe006c7293184/20220528002825.png)



  为了后续方便知道是什么插件名字，需要重命名为  Proxy SwitchyOmega 2.5.21.crx



  ##  Proxy SwitchySharp 1.10.7

  简介：轻松快捷地管理和切换多个代理设置。基于 "Proxy Switchy!" 和 "SwitchyPlus" 开发。

  `ID：dpplabbmogkhghncfbfdeeokoefdjegm`

  ```bash
  # dpplabbmogkhghncfbfdeeokoefdjegm
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Ddpplabbmogkhghncfbfdeeokoefdjegm%26uc
  ```

  ## Anti-HoneyPot[By-4dogs.cn] 1.0.1

  Anti-HoneyPot 1.0.1 拦截蜜罐收集用户信息

  ID：mcgakjkooclpijbmfeglihcngmaoobnf

  ```bash
  # mcgakjkooclpijbmfeglihcngmaoobnf
  ```

  ## JSON Formatter 0.6.2

  格式化json，view 更直观。

  Makes JSON easy to read. Open source.

  ID：bcjindcccaagfpapjjmafapmmgkkhgoa

  ```bash
  # bcjindcccaagfpapjjmafapmmgkkhgoa
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dbcjindcccaagfpapjjmafapmmgkkhgoa%26uc
  ```

  ##  Shodan 1.1.0

  The Shodan plugin tells you where the website is hosted (country, city), who owns the IP and what other services/ ports are open.

  ID：jjalcfnidlmpjhdfepjhjbhnhkbgleap

  ```bash
  # jjalcfnidlmpjhdfepjhjbhnhkbgleap
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Djjalcfnidlmpjhdfepjhjbhnhkbgleap%26uc
  ```

  ## Charset 0.5.5

  修改网站的默认编码

  ID：oenllhgkiiljibhfagbfogdbchhdchml

  ```bash
  # oenllhgkiiljibhfagbfogdbchhdchml
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Doenllhgkiiljibhfagbfogdbchhdchml%26uc
  ```



  ## Adblock Plus - 3.13

  免费的广告拦截器，阻止 YouTube™ 广告、弹出窗口并抵御恶意软件！

  ID：cfhdojbkjhnklbpkdaibdccddilifddb

  ```bash
  # cfhdojbkjhnklbpkdaibdccddilifddb
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dcfhdojbkjhnklbpkdaibdccddilifddb%26uc
  ```

  ## EditThisCookie 1.6.3

  EditThisCookie是一个cookie管理器。您可以添加，删除，编辑，搜索，锁定和屏蔽cookies！

  ID：fngmhnnpilhplaeedifhccceomclgfbg

  ```bash
  # fngmhnnpilhplaeedifhccceomclgfbg
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dfngmhnnpilhplaeedifhccceomclgfbg%26uc
  ```

  ## Google Mail Checker 4.4.0

  显示 Google Mail 收件箱中的未读邮件数。点击该按钮还可以打开您的收件箱。

  ID：mihcahmgecmbnbcchbopgniflfhgnkff

  ```bash
  # mihcahmgecmbnbcchbopgniflfhgnkff
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dmihcahmgecmbnbcchbopgniflfhgnkff%26uc
  ```

  ## Google 翻译 2.0.12

  浏览网页时可轻松查看翻译版本。由Google翻译小组提供。

  ID：aapbdbdomjkkjkaonfhkkikfgjllcleb

  ```bash
  # aapbdbdomjkkjkaonfhkkikfgjllcleb
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Daapbdbdomjkkjkaonfhkkikfgjllcleb%26uc
  ```

  ## MEGA 4.14.1

  Secure Cloud Storage and Chat

  ID：bigefpfhnfcobdlfbedofhhaibnlghod

  ```bash
  # bigefpfhnfcobdlfbedofhhaibnlghod
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dbigefpfhnfcobdlfbedofhhaibnlghod%26uc
  ```

  ## Octotree - GitHub code tree 7.5.0

  GitHub on steroids

  ID：bkhaagjahfmjljalopjnoealnfndnagc

  ```bash
  # bkhaagjahfmjljalopjnoealnfndnagc
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dbkhaagjahfmjljalopjnoealnfndnagc%26uc
  ```

  ## Save as MHTML 0.3.7

  编辑并以MHTL/MHT(MIME HTML)存档格式保存活动标签或选定区域，以获得一个干净的单文件备份。

  ID：ahgakckdonjmnpnegjcamhagackmjpei

  ```bash
  # ahgakckdonjmnpnegjcamhagackmjpei
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dahgakckdonjmnpnegjcamhagackmjpei%26uc
  ```

  ## RSS Feed Reader 7.9.0

  Get a simple overview of your RSS and Atom feeds in the toolbar

  ID：pnjaodmkngahhkoihejjehlcdlnohgmp

  ```bash
  # pnjaodmkngahhkoihejjehlcdlnohgmp
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dpnjaodmkngahhkoihejjehlcdlnohgmp%26uc
  ```

  ## SuperCopy 超级复制 0.1.5

  一键破解禁止右键、破解禁止选择、破解禁止复制、破解禁止粘贴，启用复制，启用右键，启用选择，启用粘贴。

  ID：onepmapfbjohnegdmfhndpefjkppbjkm

  ```bash
  # onepmapfbjohnegdmfhndpefjkppbjkm
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Donepmapfbjohnegdmfhndpefjkppbjkm%26uc
  ```

  ## Tab Muter 1.4.2

  Re-enables the "Mute Tab" feature once found in Chrome itself.

  单个网页标签静音🔇。

  ID：bnclejfcblondkjliiblkojdeloomadd

  ```bash
  # bnclejfcblondkjliiblkojdeloomadd
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dbnclejfcblondkjliiblkojdeloomadd%26uc
  ```

  ## Wappalyzer - Technology profiler 6.10.24

  Identify web technologies 网站框架信息

  ID：gppongmhjkpfnbhagpmjfkannfbllamg

  ```bash
  # gppongmhjkpfnbhagpmjfkannfbllamg
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dgppongmhjkpfnbhagpmjfkannfbllamg%26uc
  ```

  ## Tampermonkey 4.16.1

  The world's most popular userscript manager

  ID：dhdgffkkebhmkfjojejmpbldmpobfkfo

  ```bash
  # dhdgffkkebhmkfjojejmpbldmpobfkfo
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Ddhdgffkkebhmkfjojejmpbldmpobfkfo%26uc
  ```

  ## Tabbed Postman - REST Client 0.8.4.22

  网页版postman，修改参数

  ID：coohjcphdfgbiolnekdpbcijmhambjff


  ```bash
  # coohjcphdfgbiolnekdpbcijmhambjff
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dcoohjcphdfgbiolnekdpbcijmhambjff%26uc
  ```

  ## WebSocket Test Client 0.2.0

  A Simple tool to help test WebSocket Service

  ID：fgponpodhbmadfljofbimhhlengambbn

  ```bash
  # fgponpodhbmadfljofbimhhlengambbn
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dfgponpodhbmadfljofbimhhlengambbn%26uc
  ```

  ## X-Forwarded-For Header 0.6.2

  This extension allows you quickly to set the X-Forwarded-For HTTP Header

  ID：hkghghbnihliadkabmlcmcgmffllglin

  ```bash
  # hkghghbnihliadkabmlcmcgmffllglin
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dhkghghbnihliadkabmlcmcgmffllglin%26uc
  ```

  ## XPath Helper 2.0.2

  Extract, edit, and evaluate XPath queries with ease.

  ID：hgimnogjllphhhkhlmebbmlgjoejdpjl

  ```bash
  # hgimnogjllphhhkhlmebbmlgjoejdpjl
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dhgimnogjllphhhkhlmebbmlgjoejdpjl%26uc
  ```

  ## 彩云小译 - 网页翻译插件 1.3.4

  彩云小译双语对照网页翻译插件，针对浏览器开发的一款网页翻译工具，一键高效获取母语阅读体验。

  ID：jmpepeebcbihafjjadogphmbgiffiajh

  ```bash
  # jmpepeebcbihafjjadogphmbgiffiajh
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Djmpepeebcbihafjjadogphmbgiffiajh%26uc
  ```

  ## GitZip for github 1.0.0

  It can make the sub-directories and files of github repository as zip and download it

  ID：ffabmkklhbepgcgfonabamgnfafbdlkn

  ```bash
  # ffabmkklhbepgcgfonabamgnfafbdlkn
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dffabmkklhbepgcgfonabamgnfafbdlkn%26uc
  ```



  ## FOFA Pro View 0.0.4

  FOFA Pro view

  ID：iadmijjfebdlnbinfghcgjlnepglmgih

  ```bash
  # iadmijjfebdlnbinfghcgjlnepglmgih
  ```

  ## Evernote Web Clipper 7.23.0

  使用Evernote扩展程序一键保存精彩网页内容到Evernote帐户。

  ID：pioclpoplcdbaefihamjohnefbikjilc

  ```bash
  # pioclpoplcdbaefihamjohnefbikjilc
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dpioclpoplcdbaefihamjohnefbikjilc%26uc
  ```

  ## WizClipper 4.0.10

  WizClipper 为知笔记插件：快速保存网页文章到笔记。

  ID：jfanfpmalehkemdiiebjljddhgojhfab

  ```bash
  # jfanfpmalehkemdiiebjljddhgojhfab
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Djfanfpmalehkemdiiebjljddhgojhfab%26uc
  ```

  ## DEPRECATED Secure Shell App 0.40

  (DEPRECATED: USE THE EXTENSION) Terminal emulator and SSH and SFTP client.

  ID：pnhechapfaindjhompbnflcldabbghjo

  ```bash
  # pnhechapfaindjhompbnflcldabbghjo
  https://clients2.google.com/service/update2/crx?response=redirect&prodversion=101.0.4951.54&acceptformat=crx2%2Ccrx3&x=id%3Dpnhechapfaindjhompbnflcldabbghjo%26uc
  ```
