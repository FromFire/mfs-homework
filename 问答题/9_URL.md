## 1. 什么是 URL？
   
> URL是统一资源定位符的英文简写，也就是网址。它的内容是一个网页的地址，对应了一个唯一的页面。

## 2. URL 有哪些常见的 Schemes？他们各是什么含义？

> * http：http协议，用来发送网页等各种文件。
> * https：http加上安全保护，所有数据采用加密传输。
> * ftp：ftp协议，用来传文件。
> * file：本地文件。

## 3. URL 有哪些约束？

> url格式是scheme://host:port/path/filename。
> * scheme是服务类型，例如http和https。
> * host是网站域名或ip地址。
> * port是服务器接受信息的端口，例如80和8080，http不写默认80。
> * path是请求的文件所在服务器中的路径，省略表示在根目录下。
> * filename是请求的文件名称，可以不写后缀名。

## 4. 请将以下 URL 转换成合法的 URL: `baidu.com/s?wd=码蜂社 前端`

> `https://www.baidu.com/s?wd=%E7%A0%81%E8%9C%82%E7%A4%BE%20%E5%89%8D%E7%AB%AF`

## 5. 请提取以下 URL 的 scheme，host，port，path，filename:
`https://www.mafengshe.com/course/fe-senior/ad`, 
`http://127.0.0.1:3000/course/fe-senior/ad`

> | URL | scheme | host | port | path | filename |
> | --- | ------ | ---- | ---- | ---- | -------- |
> | `https://www.mafengshe.com/course/fe-senior/ad` | https | `www.mafengshe.com` | 80 | course/fe-senior | ad |
> | `http://127.0.0.1:3000/course/fe-senior/ad` | http | `127.0.0.1` | 3000 | course/fe-senior | ad