# Orbital

## 修改内容

* 去除版权验证，去除暗桩
* 修改修改配置信息的异或密钥
* 修改BeaconEye特征的memset初始值
* 删除服务端响应返回字符串
* 修改默认配置文件名
* 修复foreign派生错误的bug
* 修改控制端与服务端间socket的magic值
* 修改beacon中特征字符串
* 修改http/https/dns的Beacon中Sleep Mask功能
* 修改Sleep Mask的异或密钥字节长度
* 修复CodeX发现的Sleep Mask未混淆部分的内存特征
* 修复CVE-2022-23317
* 修复CVE-2022-39197
* 修复C2 Profile中compile_time参数解析问题
* 修改winvnc.dll加载位置
* 启用Payload Generator(Stageless)生成选项
* 修改BOF加载部分，改为支持最多64个函数解析

## 功能增强

* Bypass UAC执行程序
* 增强版ls，ps命令
* 主题切换
* 显示IP对应地址
* curl在目标机器访问网站
* Askcreds诱导获取账户密码
* 获取、设置剪贴板
* 获取wifi信息
* 录音
* 反向代理插件
* 添加计划任务
* 添加服务
* 自删除
* 下载文件至目标机器
* 自实现systeminfo，cat，ipconfig，whoami，quser，nslookup命令

## 删除功能

* Java Applet
* System Profiler
* Clone Site

## 注

http/https/dns的Beacon不再支持Kit中的用户自定义Sleep Mask以及Artifact的堆栈欺骗选项
