# HvvInfo

**一款在红蓝对抗中快速对目标单位进行资产探测和基本扫描的工具**

![image-20220901163642796](https://tva1.sinaimg.cn/large/e6c9d24egy1h5r6xw0tj8j214o0u0n0x.jpg)

----

## 使用注意

**注意使用sudo权限运行程序**

**Cookie只需要取auth_token字段即可**

<img width="1203" alt="image" src="https://user-images.githubusercontent.com/52586866/220052242-68db78e4-e482-454c-b18f-a0b204b6f47e.png">


## 基础用法

**对目标单位进行资产收集和子域名探测并进行存活探测**

> ./HvvInFo -n "百度" -c "天眼查的cookie"

**对多个目标单位进行资产收集和子域名探测并进行存活探测**

> ./HvvInFo -f "NameTarget.txt"

**对目标主域名进行子域名探测和存活检测**

> ./HvvInFo -df "1.txt"

## 进阶用法

**对目标单位进行信息搜集并对指定漏洞进行扫描**

> ./HvvInFo -n "百度" -c "天眼查的cookie" -pn "xxx.yaml"

**对目标单位进行信息搜集并进行多漏洞扫描**

> ./HvvInFo -n "百度" -c "天眼查的cookie" -pf "pocs/*"

**对多个目标单位进行信息搜集并对指定漏洞进行扫描**

> ./HvvInFo -f "NameTarget.txt" -pn "xxx.yaml"

**对多个目标单位进行信息搜集并进行多漏洞扫描**

> ./HvvInFo -f "NameTarget.txt" -pf "pocs/*"

**对目标主域名进行子域名探测和存活检测并对指定漏洞进行扫描**

> ./HvvInFo -f "NameTarget.txt" -pn "xxx.yaml"

**对目标主域名进行子域名探测和存活检测并进行多漏洞扫描**

> ./HvvInFo -f "NameTarget.txt" -pf "pocs/*"

**对指定Url进行指定漏洞扫描**

> ./HvvInFo -pu "http://127.0.0.1/" -pn "xxx.yaml"

**对指定Url进行多漏洞扫描**

> ./HvvInFo -pu "http://127.0.0.1/" -pf "pocs/*"

## 非盈利星球（免费）

- [**个人博客**](https://blog.yunjianxx.com/) **- 专注分享信息安全新技术、新领域的技术和知识的学习笔记，不时发布原创实用安全工具、安全脚本.**
- [**在线武器库**](https://link.yunjianxx.com/) **- 提供安全、渗透、社工等方面书签｜为广大网络安全爱好者提供网站导航,为小白提供黑客入门网站的安全站点收集.**
- 😄 I’m ExpLang [**Twitter**](https://twitter.com/ExpLang_Cn)、**Discord: explang**、**[Telegram](https://t.me/ExpLang)**

![image-20220822115559517](https://tva1.sinaimg.cn/large/e6c9d24egy1h5femrdq9zj20v90h6jsc.jpg)

### 感谢

感谢项目：
* [httpx](https://github.com/projectdiscovery/httpx)
* [subfinder](https://github.com/projectdiscovery/subfinder)
* [ENScan_GO](https://github.com/wgpsec/ENScan_GO)
