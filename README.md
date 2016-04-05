# httpscan
httpscan是一个扫描指定CIDR网段的Web主机的小工具。和端口扫描器不一样，httpscan是以爬虫的方式进行Web主机发现，因此相对来说不容易被防火墙拦截。

httpscan会返回IP http状态码 Web容器版本 以及网站标题。
![demo][1]

**Usage**：`./httpscan IP/CIDR –t threads`

Example:`./httpscan.py 10.20.30.0/24 –t 10`


  [1]: https://raw.githubusercontent.com/zer0h/httpscan/master/log/demo.png
