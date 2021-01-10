# DataTools

#### DataTools是数据管理工具
##### 解决方案:
* 在线查询sql
* 导出不同数据格式的查询sql集(包括导出csv/xls)
* 支持跨库拼接
* 支持一次性任务/定时任务/间隔任务

##### 配置项:
* 数据库配置
* 需求描述配置
* 需求对应SQL配置
* 需求定时发送方式及发送人配置
* 导出字段配置

___

#### 环境
* Python 3.7+
* Pip 10+

---
#### 开发顺序与规划
* ~~创建项目~~ ~~已完成~~
* **基础框架 正在开发**
* 使用UWSGI并正常启动项目
* 实现在线sql执行并结果集展示(暂时不做长链接)
* 实现不同数据格式的导出(json/xls/csv)
* 实现任务计划并前台展示任务列表及操作
* 优化DB链接
* 扩展为多用户/组的组织体系

___
