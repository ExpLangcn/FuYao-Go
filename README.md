# FuYao - Go

[![Stargazers over time](https://starchart.cc/Bian-Sh/UniJoystick.svg)](https://starchart.cc/Bian-Sh/UniJoystick)

#### [Join Discord](https://discord.gg/GCZzJmzW3G) ｜[中文文档](README_CN.md)｜[issues](https://github.com/ExpLangcn/FuYao-Go/issues)

<img src="https://tva1.sinaimg.cn/large/e6c9d24egy1h17yaqtwb7j20uq0lwdim.jpg" alt="image-20220413114822870" style="zoom: 50%;" />

**Automate target asset detection and security vulnerability scanning | Suitable for bounty campaigns, SRC campaigns, mass usage, mass usage | Discover valid subdomains of websites by using passive online sources | Use custom templates with zero false positives The target sends a request, and can perform a quick scan of a large number of hosts at the same time. ｜Provide scanning of various protocols such as TCP, DNS, HTTP, FILE, etc., simulate various security checks through powerful and flexible templates**

----

### Current feature or future feature

- [x] Subdomain enumeration asset collection
- [x] Bulk subdomain enumeration asset collection
- [x] Chaos Asset Collection
- [x] Asset Survival Verification
- [x] Batch asset survival verification
- [x] Security Vulnerability Verification
- [x] Bulk Security Vulnerability Verification
- [x] Subdomain enumeration asset collection, asset survival verification, security vulnerability scanning linkage
- [ ] Subdomain Survival WebHook Notification
- [ ] WebHook notification of security vulnerability scan results
- [ ] Cyberspace Mapping Asset Collection
- [ ] Pending...

**If you need any functions, you can file them in [issues](https://github.com/ExpLangcn/FuYao-Go/issues)**

----

### Current POC list

Currently there are: **8980 POC templates**

![image-20220413112118120](https://tva1.sinaimg.cn/large/e6c9d24egy1h17yarsz5hj20em08yt90.jpg)

----

### Using help

````
./FuYao -h
  ███████╗██╗ ██╗██╗ ██╗ █████╗ ██████╗
  ██╔════╝██║ ██║╚██╗ ██╔╝██╔══██╗██╔═══██╗
  █████╗ ██║ ██║ ╚████╔╝ ███████║██║ ██║
  ██╔══╝ ██║ ██║ ╚██╔╝ ██╔══██║██║ ██║
  ██║ ╚██████╔╝ ██║ ██║ ██║╚██████╔╝ Discord:ExpLang#6666
  ╚═╝ ╚═════╝ ╚═╝ ╚═╝ ╚═╝ ╚═════╝ Author:ExpLang
     Github:github.com/ExpLangcn/FuYao-Go
 Please abide by local laws before using FuYao, FuYao is only provided for educational use

Usage: FuYao [-t xxx.com] [-l target.txt] [-poc]
  -l string
        Specify the target file for subdomain asset detection
  -poc
        Perform POC vulnerability detection on the results Scan result/subdomain_result.txt
  -t string
        Specify a single target for subdomain asset detection
````

**Scan a website**: `./FuYao -t xxx.com`

**Scan a website and scan for vulnerabilities**: `./FuYao -t xxx.com -poc`

**Scan a target file**: `./FuYao -l target.txt `

**Scan a target file and scan for vulnerabilities**: `./FuYao -l target.txt -poc`

----

### update record

````
2022.4.15 12:00
- Release v1.0 version
````

----

### Contact information

#### WeChat

<img src="https://tva1.sinaimg.cn/large/e6c9d24egy1h17yaq5zf6j20u012aq5x.jpg" alt="image-20220413113316684" style="zoom: 33%;" />

#### **[Join Discord](https://discord.gg/GCZzJmzW3G)**
