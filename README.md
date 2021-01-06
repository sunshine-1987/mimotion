# 小米运动自动刷步数

> 小米运动自动刷步数

## Github Actions 部署指南

### 一、Fork 此仓库

### 二、设置账号密码

添加名为  **SCKEY**、**USER**、**PWD**、**STEP** 的变量，值分别为 **server酱推送key（0关闭）**、 **账号（仅支持手机号）**、**密码**、**步数（0则为1w-2w之间随机 或自定义随机范围[18000-25000]）**

> Settings-->Secrets-->New secret

## 注意事项

1. 每天运行一次，在下午 6 点.
2. 如果支付宝没有更新步数,到小米运动->设置->账号->注销账号->清空数据,然后重新登录,重新绑定第三方,重新刷步即可
