# FuYao - Go 扶摇直上九万里

####  [加入Discord](https://discord.gg/GCZzJmzW3G)｜[英文文档](README.md)｜[问题反馈](https://github.com/ExpLangcn/FuYao-Go/issues) ｜ **[问题解决](https://github.com/ExpLangcn/FuYao-Go/wiki/Problem)**

<img src="https://tva1.sinaimg.cn/large/e6c9d24egy1h17yaqtwb7j20uq0lwdim.jpg" alt="image-20220413114822870" style="zoom: 50%;" />

**自动化进行目标资产探测和安全漏洞扫描｜适用于赏金活动、SRC活动、大规模使用、大范围使用|通过使用被动在线资源来发现网站的有效子域｜使用零误报的定制模板向目标发送请求，同时可以对大量主机进行快速扫描。｜提供TCP、DNS、HTTP、FILE等各类协议的扫描，通过强大且灵活的模板，模拟各种安全检查**

## 法律免责声明
本工具仅面向合法授权的企业安全建设行为，如您需要测试本工具的可用性，请自行搭建靶机环境。 在使用本工具进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权。请勿对非授权目标进行扫描。 如果发现上述禁止行为，我们将保留追究您法律责任的权利。

如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任. 您的使用行为或者您以其他任何明示或者默示方式表示接受本协议的，即视为您已阅读并同意本协议的约束。

----

### 更新记录

```
2022.4.15 17:10
	- 发布V1.1版本
	- 修复Windows下 file missing [file=MANIFEST-000000] 错误
	- 修复Windows下 no valid templates were found 报错
	- 优化扫描并发配置
2022.4.15 12:00
	- 发布 v1.0版本
```

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

![image-20220413112118120](https://tva1.sinaimg.cn/large/e6c9d24egy1h17yarsz5hj20em08yt90.jpg)

----

### 使用帮助

#### 不推荐使用Windows系统！

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

**扫描一个网站**：`./FuYao -t xxx.com`

**扫描一个网站并扫描漏洞**：`./FuYao -t xxx.com -poc`

**扫描一个目标文件**：`./FuYao -l target.txt `

**扫描一个目标文件并扫描漏洞**：`./FuYao -l target.txt -poc`

----

### 配置信息

```
templates: "data" # Template Catalog
severity: medium,high,critical # 可选：info,low,medium,high,critical
markdown-export: "result//pocscan" # POC结果输出目录 
rate-limit: 500 # POC并发扫描
bulk-size: 50 # 每个模板最大并行检测数
concurrency: 50 # 并行执行的最大模板数量

#-----------------

disable-update-check: true # 勿碰
silent: true # 勿碰
stats: true # 勿碰
project: true # 勿碰
enable-pprof: true # 勿碰
```

----

### 联系方式

#### WeChat

<img src="https://tva1.sinaimg.cn/large/e6c9d24egy1h17yaq5zf6j20u012aq5x.jpg" alt="image-20220413113316684" style="zoom: 33%;" />

#### **[加入Discord](https://discord.gg/GCZzJmzW3G)**

----

### Stargazers over time

[![Stargazers over time](https://starchart.cc/ExpLangcn/FuYao-Go.svg)](https://starchart.cc/ExpLangcn/FuYao-Go)
