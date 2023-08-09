# 我的工具md文件归档
## MY SERVER SEARCHER --java  
### Hi
欢迎使用我这个无聊的程序可以查询服务器的玩家列表  
使用了[mcsrvstatAPI][1]处理  
配置文件使用的使用(可用此初始化)编号按顺序由1开始：   
```
{
  "serverList":
    [
       {"serverName":"hypixel","serverIp":"hypixel.net"},
       {"serverName":"我是二号名称","serverIp":"我是二号IP"}
    ]
}  
```
预计添加的功能:

* 自动化更改配置
* ~~添加自定义ip 数字的功能~~  
* 检测OS以输出正确的启动包
---
* **Depend on**   
1. com.alibaba.fastjson2:2.0.22
* Link：https://github.com/alibaba/fastjson2
---
### 新功能日志
**v1.1**利用json添加持久化文件 实现！！！  
**v1.2-S1a**按jar名称输出启动文件 实现！！！  
**v1.2-S2a**maven带依赖输出 与lib依赖输出 完成！！！  
**v1.2-S2b**准备独立于mcsrvstat的发包检测 其基础逻辑已完成 内部待优化  
_**v1.2-S2c**_ ~~_**内部优化 添加接口 重构代码**_~~ 未完成
### 无法处理的BUG：  
BC端无法查询 [API][1]受限

[1]: https://api.mcsrvstat.us