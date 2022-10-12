# Scan4all_Pro
Scan4all Pro，Distributed, more optimized and faster


##  v2.8.4
```
1、fuzz、及所有请求输出限制为800k，避免被反制、进行内存攻击导致程序崩溃
2、修复naabu、nmap扫描后使用ip继续走后续流程，导致无法正确访问目标的bug，https通常是限定只能域名访问的 
3、file fuzz针对 aac、abw、...zip、3gp、3g2、7z 的Content-Type: 进行类型识别，跳过无用的fuzz,例如请求的是jpg，返回200的html
4、add dnsx
5、性能优化
6、add 
VMware/vCenter/CVE-2022-22954 
VMware/vCenter/CVE_2022_22972 
gitlab/CVE-2022-2185
go_poc_check jenkins/CVE_2016_0792 
ms/CVE-2021-26855_2 
ms/CVE_2021_26855 
ms/exchange/chkproxyshell 
ms/exchange/confirmtoken 
ms/exchange/proxyln 
ms/exchange/proxyln_test 
ms/exchange/proxytoken 
oracle/weblogic/CNVD-C-2019-48814 
shiro/CVE_2016_4437
CVE-2022-35914
7、增加了filefuzz时bywaf的功能
8、优化了fuzz，http2.0下测试18秒可以完成6万的扫描，同时合并、去除冗余的结果
9、优化：所有的web扫描前，均做有效检测，避免无效扫描，提升了效率 
10、add
vCenter/CVE_2021_21985
vCenter/c_21972
vCenter/c_21985
vCenter/c_22005
11、重构了webscan
12、add mychromedp 封装基于浏览器的爬虫，支持多tab，禁止图片、css加载 2022-09-29
```
