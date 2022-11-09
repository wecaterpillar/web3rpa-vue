web3RPA平台 前端
===============

web3rpa front based on jeecg-boot-vue3
## getting start

- Installation dependencies

```bash
cd web3rpa-vue

yarn install

```

- 配置后台接口地址
>[info] 说明：把`http://localhost:8080/rpa-server` 替换成自己地址即可，其他不用改。

配置文件：.env.development
```bash
VITE_GLOB_API_URL=/rpa-server
VITE_PROXY = [["/rpa-server","http://localhost:8080/rpa-server"],["/upload",
"http://localhost:3300/upload"]]
VITE_GLOB_DOMAIN_URL=http://localhost:8080/rpa-server
```
- run

```bash
yarn serve
```


- build

```bash
yarn build
```


## 技术框架及源码
### 源码下载

- 后台源码 ：https://github.com/wecaterpillar/web3rpa-server
- 前端源码 ：https://github.com/wecaterpillar/web3rpa-vue

### jeecg菜单

```
├─首页
│  ├─首页（四套首页满足不同场景需求）
│  └─工作台
├─系统管理
│  ├─用户管理
│  ├─角色管理
│  ├─菜单管理
│  ├─权限设置（支持按钮权限、数据权限）
│  ├─表单权限（控制字段禁用、隐藏）
│  ├─部门管理
│  ├─我的部门（二级管理员）
│  └─字典管理
│  └─分类字典
│  └─系统公告
│  └─职务管理
│  └─通讯录
│  └─对象存储
│  └─多租户管理
├─消息中心
│  ├─我的消息
│  ├─消息管理
│  ├─模板管理
├─Online在线开发(低代码)
│  ├─Online在线表单 - 功能已开放
│  ├─Online代码生成器 - 功能已开放
│  ├─Online在线报表 - 功能已开放
│  ├─多数据源管理 - 功能已开放
 
```

## 申明
- 本软件源代码开放MIT，涉及第三方软件版权按原版权方要求处理
- 不可用于任何违法事情，本软件不承担任何相关的法律责任
- 涉及道任何经济相关的活动请自行承担风险，本工具不做任何推荐或建议
