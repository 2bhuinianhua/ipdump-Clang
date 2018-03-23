# Ipdump

Linux抓包程序
-------
<br>
* 使用Linux发行版本<br>
    Ubuntu(Debian)
<br>
* 编程语言<br>
    C语言
<br><br>
使用说明
<br><br>
  * 语法
   <br>usage: ./ipdump [-aedht] [-p protocols] [-i ifrname] [-f filters]
   <br>protocols: arp ip icmp tcp udp 
   <br>filters: ip <IP addr> port <PORT number>
   <br>default: ./ipdump -p arp ip icmp tcp udp
<br>
  * 示例<br>
    sudo ./ipdump -p arp -e -d
<br>
  * 停止抓包<br>
    ctrl+c
<br>
<br>
* 问题说明<br>
    过滤，抓指定IP地址还有问题，代码更改无限延期

