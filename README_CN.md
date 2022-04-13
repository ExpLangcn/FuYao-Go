# FuYao - Go 扶摇直上九万里

####  **[加入Discord](https://discord.gg/GCZzJmzW3G)** ｜ **[英文文档](README.md)**｜ **[问题反馈](https://github.com/ExpLangcn/FuYao-Go/issues)**

<img src="/Users/explang/HackTools/Mytools/go/FuYao/img/e6c9d24egy1h17y8fpf86j20uq0lwmzy.png" alt="image-20220413114822870" style="zoom: 50%;" />

**自动化进行目标资产探测和安全漏洞扫描｜适用于赏金活动、SRC活动、大规模使用、大范围使用|通过使用被动在线资源来发现网站的有效子域｜使用零误报的定制模板向目标发送请求，同时可以对大量主机进行快速扫描。｜提供TCP、DNS、HTTP、FILE等各类协议的扫描，通过强大且灵活的模板，模拟各种安全检查**

----

### 当前功能 or 未来功能

- [x] 子域名枚举资产收集
- [x] 批量子域名枚举资产收集
- [x] Chaos 资产收集
- [x] 资产存活验证
- [x] 批量资产存活验证
- [x] 安全漏洞验证
- [x] 批量安全漏洞验证
- [x] 子域名枚举资产收集、资产存活验证、安全漏洞扫描联动
- [ ] 子域名存活WebHook通知
- [ ] 安全漏洞扫描结果WebHook通知
- [ ] 网络空间测绘资产收集
- [ ] 待定...

**有需要什么功能的话可以在 [issues](https://github.com/ExpLangcn/FuYao-Go/issues) 提**

----

### 当前POC列表

当前总共有：**8980个POC模版**

![image-20220413112118120](/Users/explang/HackTools/Mytools/go/FuYao/img/e6c9d24egy1h17xgaun57j20em08yt90.png)

----

### 使用帮助

```
./FuYao -h                                                                                                                                                                                                      
  ███████╗██╗   ██╗██╗   ██╗ █████╗  ██████╗
  ██╔════╝██║   ██║╚██╗ ██╔╝██╔══██╗██╔═══██╗
  █████╗  ██║   ██║ ╚████╔╝ ███████║██║   ██║
  ██╔══╝  ██║   ██║  ╚██╔╝  ██╔══██║██║   ██║
  ██║     ╚██████╔╝   ██║   ██║  ██║╚██████╔╝  Discord:ExpLang#6666
  ╚═╝      ╚═════╝    ╚═╝   ╚═╝  ╚═╝ ╚═════╝   Author:ExpLang
     Github:github.com/ExpLangcn/FuYao-Go
 使用FuYao前请遵守当地法律,FuYao仅提供给教育行为使用

Usage: FuYao [-t xxx.com] [-l target.txt] [-poc]
  -l string
        指定目标文件进行子域名资产探测
  -poc
        对结果进行POC漏洞探测 扫描result/subdomain_result.txt
  -t string
        指定单个目标进行子域名资产探测
```

**扫描一个网站：**`./FuYao -t xxx.com`

**扫描一个网站并扫描漏洞：**`./FuYao -t xxx.com -poc`

**扫描一个目标文件：**`./FuYao -l target.txt `

**扫描一个目标文件并扫描漏洞：**`./FuYao -l target.txt -poc** `

----

### 更新记录

```
2022.4.13 11:40
	- 发布 v1.0版本
```

----

### 联系方式

#### WeChat

<img src="/Users/explang/HackTools/Mytools/go/FuYao/img/e6c9d24egy1h17xsrm1rej20u012agol.png" alt="image-20220413113316684" style="zoom: 33%;" />

#### **[加入Discord](https://discord.gg/GCZzJmzW3G)**