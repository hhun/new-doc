---
sidebar_position: 10
---

# 命令介绍
新版 `catchadmin` 命令都是以 **catch** 开头, 想要查看全部命令的话，可以使用
```shell
php artisan | grep catch
```
### 项目安装
```shell
php artisan catch:install
```
该命令是用于初始化项目

### 模块安装
```shell
php artisan catch:module:install <module>
```
- module 必选参数

例如安装权限模块
```shell
php artisan catch:module:install <permissions>
```
### 创建 Migrate 文件
```shell
php artisan catch:make:migrate <module> <seeder_name>
```

### 创建 Seed 文件
```shell
php artisan catch:make:seeder <module> <seeder_name>
```

### 执行 Migrate
```shell
php artisan catch:migrate <module>
```
执行模块的 migrates 文件, 创建模块相关表结构
```shell
php artisan catch:migrate permissions
```

### 执行 Seed
```shell
php artisan catch:db:seed <module>
```
执行模块的 seed 文件，填充初始化数据
```shell
php artisan catch:migrate permissions
```

### 导出模块相关的菜单
```shell
php artisan catch:export:menu <module> <table?>
```
- table 可选参数，默认是 `permissions` 表

导出权限模块的菜单，并且生成`seed`文件。这个命令只在打包模块时会有用处，如果模块不用与与其他人共享的话，基本用不着
```php 
php artisan catch:export:menu permissions
```