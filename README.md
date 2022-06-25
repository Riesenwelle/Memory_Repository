# Memory_Repository - 记忆保存库  
---
## 目前的最新Release版本  
+ Windows：Ver_0.1  
+ Android：Ver_0.1  

## 说明
+ 基于Qt 5.4.0框架，使用C++开发  
+ 跨平台项目：目前支持Windows平台与Android平台  

## 预期用户功能  
+ 对记忆碎片分级存放  
+ 文章中可插入图片  
+ 多种页面UI模板  
+ 宠物小精灵  
+ 设置任务日历  
+ 数据上传云端：与账号对应的备份文件  

## 实现想法  
+ 采用SQLite创建本地数据库，对记忆碎片进行类似文件系统方式的存放  
+ 考虑使用Markdown，并考虑将Markdown的交互GUI化  
+ 多设计几套默认可供替换的GUI  
+ 尚待研究  
+ 新建表用于存放  
+ 数据上传云端：考虑将SQLite数据转入MySQL；需要架设服务器  