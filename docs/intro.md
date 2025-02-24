---
sidebar_position: 1
---

# 介绍
<p align="center"><code>CatchAdmin</code>是一款基于<a href="http://www.thinkphp.cn/" target="_blank">thinkphp framework</a>和
<a href="https://github.com/PanJiaChen/vue-element-admin/">element admin</a>二次开发而成后台管理系统。因为 thinkphp 的简单高效，文档齐全。在看了很多 thinkphp 生态中的后台管理系统，发现没有一款合适的前后端分离系统。遂开发了 CatchAdmin。
完全利用了 thinkphp6 的新版本特性 ServiceProvider，将管理系统模块之间的耦合降到了最低限度。每个模块之间都有独立的 controller，路由，模型，数据表`。在开发上尽可能将模块之间的影响降到最低，降低了开发上的难度。基于 CatchAdmin 可以开发 cms，CRM，OA 等
等系统。也封装了很多实用的工具，提升开发体验。
</p>

<p align="center">
<a href="http://doc.catchadmin.com/">文档</a> |
<a href="http://vue.catchadmin.com">演示地址</a> |
<a href="https://gitee.com/jaguarjack/catchAdmin">项目源码</a> |
<a href="https://www.kancloud.cn/akasishikelu/thinkphp6">看云分析</a> 
<a href="#extensions">扩展</a>
</p>

<p align="center">
    <a href="https://gitee.com/jaguarjack/catchAdmin" target="_blank">
        <img src="https://svg.hamm.cn/gitee.svg?type=star&user=jaguarjack&project=catchAdmin"/>
    </a >
    <a href="https://gitee.com/jaguarjack/catchAdmin" target="_blank">
        <img src="https://svg.hamm.cn/gitee.svg?type=fork&user=jaguarjack&project=catchAdmin"/>
    </a >
    <img src="https://svg.hamm.cn/badge.svg?key=Base&value=ThinkPHP6"/>
    <img src="https://svg.hamm.cn/badge.svg?key=Data&value=MySQL5.7"/>
    <img src="https://svg.hamm.cn/badge.svg?key=Runtime&value=PHP7.1"/>
    <img src="https://svg.hamm.cn/badge.svg?key=License&value=Apache-2.0"/>
</p >

## 功能
- [x] `用户管理` 后台用户管理
- [x] `部门管理` 配置公司的部门结构，支持树形结构
- [x] `岗位管理` 配置后台用户的职务
- [x] `菜单管理` 配置系统菜单，按钮等等
- [x] `角色管理` 配置用户担当的角色，分配权限
- [x] `数据字典` 管理后台表结构
- [x] `操作日志` 后台用户操作记录
- [x] `登录日志` 后台系统用户的登录记录
- [x] `代码生成` 生成 API 端的 CURD 操作
- [x] `敏感词`  支持敏感词配置
- [x] `附件管理` 可管理上传的文件
- [ ] `微信管理`

## 项目地址
- [github 地址](https://github.com/yanwenwu/catch-admin)
- [gitee 地址](https://gitee.com/jaguarjack/catchAdmin)
- [前端 Vue 项目地址](https://github.com/yanwenwu/catch-admin-vue)

## 预览
<table>
    <tr>
        <td><img src="https://s1.ax1x.com/2020/09/07/wucNXq.md.png"/></td>
        <td><img src="https://s1.ax1x.com/2020/09/07/wucm6I.md.png"/></td>
    </tr>
    <tr>
        <td><img src="https://s1.ax1x.com/2020/09/07/wucZpd.md.png"/></td>
        <td><img src="https://s1.ax1x.com/2020/09/07/wuce1A.md.png"/></td>
    </tr>
    <tr>
        <td><img src="https://s1.ax1x.com/2020/09/07/wucnXt.md.png"/></td>
        <td><img src="https://s1.ax1x.com/2020/09/07/wucKnP.md.png"/></td>
    </tr>
    <tr>
        <td><img src="https://s1.ax1x.com/2020/09/07/wuc3tg.md.png"/></td>
        <td><img src="https://s1.ax1x.com/2020/09/07/wucM0f.md.png"/></td>
    </tr>
    <tr>
        <td><img src="https://s1.ax1x.com/2020/09/07/wucQ78.md.png"/></td>
        <td><img src="https://s1.ax1x.com/2020/09/07/wuc1AS.md.png"/></td>
    </tr>
     <tr>
        <td><img src="https://s1.ax1x.com/2020/09/07/wuc8hQ.md.png"/></td>
        <td><img src="https://s1.ax1x.com/2020/09/07/wucY1s.md.png"/></td>
    </tr>
    <tr>
        <td><img src="https://s1.ax1x.com/2020/09/07/wucJpj.md.png"/></td>
        <td><img src="https://s1.ax1x.com/2020/09/07/wuctcn.md.png"/></td>
    </tr>
</table>

## 环境要求
- php7.1+ (需以下扩展)
    - [x] mbstring
    - [x] json
    - [x] openssl
    - [x] xml
    - [x] pdo
- nginx
- mysql

#### 下载项目
- 通过 Git 下载(推荐)
```shell
git clone https://gitee.com/jaguarjack/catchAdmin && cd catchAdmin

curl -sS https://install.phpcomposer.com/installer | php

composer config -g repo.packagist composer https://mirrors.aliyun.com/composer/

composer install

```
- composer 安装
```shell
composer create-project jaguarjack/catchadmin:dev-master
```

#### 安装
下载完成之后通过命令来进行安装, 一键安装 🚀
```shell
 php think catch:install 
```

## 体验地址
[体验地址](https://demo.catchadmin.com)
- 账号: `catch@admin.com`
- 密码: `catchadmin`

## 赞助
如果项目对你有帮助，或者在工作上帮你节省了开发时间。在力所能及的情况下，可以支持下`Catchadmin`项目, 非常感谢🙏
<img src="/img/support.jpeg" width = "200" alt="support"/>

## 系列文章
如果是刚开始使用 `thinkphp6`, 以下文章可能会对你有些许帮助，文章基于 RC3 版本。整体架构是不变的。
- [Tp6 启动分析](https://www.kancloud.cn/akasishikelu/thinkphp6/1129385)
- [Tp6 Request 解析](https://www.kancloud.cn/akasishikelu/thinkphp6/1134496)
- [TP6 应用初始化](https://www.kancloud.cn/akasishikelu/thinkphp6/1130427)
- [Tp6 中间件分析](https://www.kancloud.cn/akasishikelu/thinkphp6/1136616)
- [Tp6 请求流程](https://www.kancloud.cn/akasishikelu/thinkphp6/1136608)

## 讨论
- [论坛讨论](https://bbs.catchadmin.com)
- 可以提 `ISSUE`，请按照 `issue` 模板提问
- 加入 Q 群 `302266230` 暗号 `catchadmin`。


## 感谢🙏
> 排名不分先后

- [top-think/think](https://github.com/top-think/think)
- [element-admin](https://panjiachen.gitee.io/vue-element-admin-site/zh/)
- [jaguarjack/think-filesystem-cloud](https://github.com/yanwenwu/think-filesystem-cloud)
- [overtrue/wechat](https://github.com/overtrue/wechat)
- [jaguarjack/migration-generator](https://github.com/yanwenwu/migration-generator)
- [phpoffice/phpspreadsheet](https://github.com/PHPOffice/PhpSpreadsheet)
