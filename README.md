# FuYao - Go

#### [Join Discord](https://discord.gg/GCZzJmzW3G)｜[中文文档](README_CN.md)｜[Feedback](https://github.com/ExpLangcn/FuYao-Go/issues) ｜ **[Problem solving](https://github.com/ExpLangcn/FuYao-Go/wiki/Problem)

<img src="https://tva1.sinaimg.cn/large/e6c9d24egy1h17yaqtwb7j20uq0lwdim.jpg" alt="image-20220413114822870" style="zoom: 50%;" />

**Automated target asset detection and security vulnerability scanning | Suitable for bounty campaigns, SRC campaigns, mass usage, mass usage | Discover valid subdomains of websites by using passive online sources | Use custom templates with zero false positives The target sends a request, and can perform a quick scan of a large number of hosts at the same time. ｜Provide scanning of various protocols such as TCP, DNS, HTTP, FILE, etc., simulate various security checks through powerful and flexible templates**

----

### update record

````
2022.4.15 17:10
- Release V1.1 version
- Fix file missing [file=MANIFEST-000000] error under Windows
- Fix no valid templates were found error under Windows
- Optimized scan concurrency configuration
2022.4.15 12:00
- Release v1.0 version
````

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

#### Windows system is not recommended!

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

### Configuration information

````
templates: "data" # Template Catalog
severity: medium,high,critical # optional: info,low,medium,high,critical
markdown-export: "result//pocscan" # POC result output directory
rate-limit: 500 # POC concurrent scans
bulk-size: 50 # Maximum number of parallel checks per template
concurrency: 50 # maximum number of templates to execute in parallel

#-----------------

disable-update-check: true # do not touch
silent: true # don't touch
stats: true # don't touch
project: true # don't touch
enable-pprof: true # do not touch
````

----

### Contact information

#### WeChat

<img src="https://tva1.sinaimg.cn/large/e6c9d24egy1h17yaq5zf6j20u012aq5x.jpg" alt="image-20220413113316684" style="zoom: 33%;" />

#### **[Join Discord](https://discord.gg/GCZzJmzW3G)**

----

### Stargazers over time

[![Stargazers over time](https://starchart.cc/ExpLangcn/FuYao-Go.svg)](https://starchart.cc/ExpLangcn/FuYao-Go)
