# small
基于SOA架构的分布式商城系统后端
### 基于SOA架构的分布式购物电商商城
- [x] 后台管理系统：管理商品、订单、类目、商品规格属性、用户、权限、系统统计、系统日志以及前台内容等功能
- [x] 前台系统：用户可以在前台系统中进行注册、登录、浏览商品、首页、下单等操作
- [x] 会员系统：用户可以在该系统中查询已下的订单、管理订单、我的优惠券等信息
- [x] 订单系统：提供下单、查询订单、修改订单状态、定时处理订单
- [x] 搜索系统：提供商品的搜索功能
- [x] 单点登录系统：为多个系统之间提供用户登录凭证以及查询登录用户的信息
### v1.1更新日志(需更新前后台代码及SQL)
- [x] 更新Dubbo(2.6.1)、ES(6.2.3)等依赖版本 
- [x] 取消ES需在页面中配置及跨域问题，ES默认配置集群名改为原elasticsearch
- [x] 修复后台统计热卖商品SQL错误，xmall-front-web模块支持SpringMVC文件上传配置
- [x] 修改金额字段类型优化SQL与备注
- [x] 优化后台页面 修复用户修改BUG 优化批量删除 优化商品分类添加
- [x] 重构首页，后台可配置，包括3D轮播图
- [x] 后台新增缓存管理功能菜单 完成订单打印发货等功能，实现快递管理
- [x] 增添订单统计报表
- [x] 修复前后端分离极验验证码session存储问题
- [x] 实现ES IK分词插件扩展词典库管理
- [x] 增添限流
- [x] 2018.7.22 取消快速搜索接口需前端配置 发送邮件端口改为465
- [x] 2018.7.24 修复添加分类BUG
- [x] 2018.7.27 首页导航栏可后台配置

### 项目架构及功能模块图
