BiliLeupload
==========
Bilibili 乐视云上传(Beta)脚本，方便折腾黑科技的熊孩子们。
代替Biliupload。

Usage
--------
需要Python2.7+curl。

cookie文件名是./bilicookies  .

格式：`DedeUserID=123456;DedeUserID__ckMd5=****************;SESSDATA=*******************`

运行 `BiliLeupload.py [FILENAME1] [FILENAME2]` 开始上传. 

上传完毕后会自动进行检验。

具体使用：


          python bilileupload.py (-h/--help) (-e/--examine) (-c/--cookie ./cookiepath) 
          (-t/--proxy-type [h/s]) (-p/--proxy-address 127.0.0.1:8080)
          (-a/--curl-args -V)
          
          -h/help: Default: None
          Print this usage file.
          
          -e/examine: Default: 0
          If enabled, acupload will examine all the uploads via the API.
          May return 404 if the speed is too fast.
          
          -c/cookie: Default:'./accookies'
          Set the path of cookie.
          
          -t/proxy-type: Default: Blank
          Set the type of proxy, if you want to use.
          s: SOCKS
          h: HTTP
          
          -p/proxy-address: Default: Blank
          Set the proxy address, if enabled by -t.
          Format:
          127.0.0.1:8080
          
          -a/curl-args: Default: Blank
          Other arguments you want ot put on curl.


Misc
----
* 晚上写的，肚子饿了，有问题谅解，也没做PEP-8，随便看看吧。
* 禁止转载到**墙内**各种电子公告服务（包括但不限于百毒贴吧、AC 丧尸岛、各种论坛、微博等）。发现腿打折。之前不是没有过先例。

#### `vu` 的用法
* <http://yuntv.letv.com/bcloud.swf?uu=iamuseless&vu=cd09b2f515>
* `[localup]cd09b2f515[/localup]`
* 乐视云视频 - cd09b2f515