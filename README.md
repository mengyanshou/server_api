# 设计文档

为接口加上版本前缀，/api/v1
## 登录

### 提交信息

**POST /logn**

|  Key  | Value |
|  ----  | ----  |
| username | 用户名 |
| password | 密码 |
- 登录成功返回完成 user info、token

### 
## 注册
**POST /user**

### 提交信息

|  Key  | Value |
|  ----  | ----  |
| username | 用户名 |
| password | 密码 |
| email | 邮箱(用于重置密码) |

- 注册成功返回完整的 user info
- 后端用邮箱协议发送邮箱校验链接

