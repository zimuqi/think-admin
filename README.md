## TAnt

[![Build Status](https://travis-ci.org/edenleung/think-admin.svg?branch=6.0)](https://travis-ci.org/edenleung/think-admin)

ThinkPHP 6.0 与 Ant Design Pro Vue 基础前后分离权限系统

预览地址: 
 * ~~https://ant-design-vue-edenleung.cloud.okteto.net~~
 * http://ant.wfunc.com

**目前为止，它还是一个开发版本**

前端: 
Ant Design Vue Pro [项目](https://github.com/xiaodit/think-ant-vue) [预览](http://ant.wfunc.com)

[开发文档](http://muaawn.coding-pages.com)

[开发计划](https://github.com/edenleung/think-admin/projects/1)

[最新版本](https://github.com/edenleung/think-admin/releases/latest)

没安装Composer？ 请在最新版本链接下找到`TAnt_Full.zip`下载

~~服务器提供：[okteto](https://okteto.com)~~

## 安装
根据情况选取适合自己版本，安装后端项目
```bash
# 最新源码
git clone https://github.com/edenleung/think-admin.git

# 稳定版
composer create-project xiaodi/tant

# 安装依赖
cd think-admin && composer install

# 执行安装
php think tant:install

# 最新数据库 可以从 database/2020-05-27.sql 导入
```

### 权限包
https://github.com/xiaodit/think-permission

### JWT包
https://github.com/xiaodit/think-jwt

### h5 模板
https://github.com/edenleung/vue-h5-template

## 打赏
如果此项目对你有帮助的，不忘给我打赏哦。

<div>
    <img src="./static/author.png" width="250" />
</div>

# License
Apache License Version 2.0
