<p align="center">
  <img height="100px" src="./logo.png" />
</p>

# [WordPress](https://github.com/WordPress/WordPress)

WordPress!是世界排名第一的开源博客和CMS系统。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-WordPress&branch=master)
### 配置
- `ALLOW_EMPTY_PASSWORD`：是否允许密码为空
- `MARIADB_HOST`：wordpress数据库地址
- `MARIADB_PORT_NUMBER`：wordpress数据库端口
- `MYSQL_CLIENT_CREATE_DATABASE_NAME`: 客户端创建的数据库名称
- `MYSQL_CLIENT_CREATE_DATABASE_USER`: 客户端创建的数据库账号
- `MYSQL_CLIENT_CREATE_DATABASE_PASSWORD`: 客户端创建的数据库账号密码
- `WORDPRESS_DATABASE_NAME`：wordpress数据库名
- `WORDPRESS_DATABASE_USER`：wordpress数据库用户名
- `WORDPRESS_DATABASE_PASSWORD`：wordpress数据库密码
- `WORDPRESS_USERNAME`：wordpress后台用户名
- `WORDPRESS_PASSWORD`：wordpress后台密码

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
