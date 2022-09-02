# HvvInfo

**一款在红蓝对抗中快速对目标单位进行资产探测和基本扫描的工具**

![image-20220901163642796](https://tva1.sinaimg.cn/large/e6c9d24egy1h5r6xw0tj8j214o0u0n0x.jpg)

----

## 使用注意

**注意使用sudo权限运行程序**

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

![image-20220822115559517](https://tva1.sinaimg.cn/large/e6c9d24egy1h5femrdq9zj20v90h6jsc.jpg)

### 感谢

感谢项目：
* [httpx](https://github.com/projectdiscovery/httpx)
* [subfinder](https://github.com/projectdiscovery/subfinder)
* [ENScan_GO](https://github.com/wgpsec/ENScan_GO)
