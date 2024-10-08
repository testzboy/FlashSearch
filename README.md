# FlashSearch 闪电搜索⚡

# 简介

![image](https://github.com/user-attachments/assets/5e816d9f-96f8-44bb-9cee-2f1c6b44e8a6)

【点击右上角 Star，关注项目最新动态】

闪电搜索是一个用户友好的多平台资产测绘客户端，主要由 testzboy 维护。 利用强大的互联网搜索引擎，将众多常用的API封装到简洁的UI中，让网络安全专业人士更容易在目标网站上寻找漏洞。 凭借其开箱即用的功能，闪电搜索简化了搜索过程，帮助渗透测试人员快速获取所需信息。

当前版本：v2.0

# 更新日志

版本  2.0     完整支持国内所有测绘平台，新增进程杀软检测功能，上线新版UI界面

版本  1.2     修复 IconHash 模块缺失问题

版本  1.1     默认使用UTF-8编码

版本  1.0     2024-08-15 初始版完成

# 运行

java使用版本：java8+

如出现乱码请使用编码启动：
```
java -Dfile.encoding=UTF-8 -jar FlashSearch.jar
```

![image](https://github.com/user-attachments/assets/11e6145f-43eb-49da-a33a-d3e3f4ce3922)


支持资产测绘平台：

- [x] fofa
- [x] hunter
- [x] quake
- [x] 零零信安
- [x] Zoomeye

# 功能

支持图标Hash计算：

- [x] fofa
- [x] hunter

通用特性：

1. 支持手动修改查询最大条数
2. 支持官方语法查询
3. 支持右键面板（后续进行功能增强），当前为复制与查询
4. 支持数据导出
5. 支持查询结果分页显示
6. 支持翻页功能

支持平台特性：

Fofa：
1. 可展示字段
2. 可设置仅显示近一年数据/全部数据显示

Hunter：
1. 可设置查询时间区间
2. 可筛选资产类型
3. 可进行状态过滤（当前语法貌似存在问题）

Quake：
1. 可设置资产起点
2. 可设置查询时间区间
3. 可设置忽略缓存过滤
4. 可设置最新数据过滤

零零信安：
1. 支持信息系统查询
2. 支持移动应用查询
3. 支持域名查询
4. 支持邮箱查询

功能截图：

![image](https://github.com/user-attachments/assets/d67e44f2-4cf7-42f6-bb56-34dbbb0b3ba6)


![image](https://github.com/user-attachments/assets/800d2c85-c9ff-47ba-85f3-bffc124ac458)


