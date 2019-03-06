# pasadmin
打卡考勤后台系统
使用技术： redis + websso + 拦截器 + spring cloud + spring boot + vue + element前端框架
概述：    通过websso实现统一登陆操作，并将cookie信息保存在redis缓存中，并通过拦截器配置用户的角色权限菜单列表，同时根据spring cloud中的feign和Hystrix组件对打卡考勤前台系统的RPC调用，前端界面采用vue+element框架实现。
实现功能：用户角色权限管理，前台用户信息管理，打卡规则表管理，组织架构管理等。
