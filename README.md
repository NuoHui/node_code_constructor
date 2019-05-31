# node_code_constructor

node.js应用的目录结构

## 描述


```
|-app
  ├── logs                                                        # 存放日志
  │   ├── index.log
  ├── scripts                                                     # 脚本集合
  │   └── do_some_thing.js
  └── src                                                         # 源码目录
      ├── config                                                    # 配置文件夹
      │   ├── config.default.js                                       # 默认配置
      │   ├── config.dev.js                                           # 开发配置
      │   └── config.prod.js                                          # 生产配置
      ├── controller                                                # controller
      │   ├── controller-1.js                                         # controller1
      │   └── controller-2.js                                         # controller1
      ├── graphql                                                   # graphql相关
      │   ├── index.js                                                # graphql总入口
      │   ├── mutation                                                # mutation
      │   │   └── index.js                                              # mutation入口文件
      │   ├── query                                                   # query
      │   │   └── index.js                                              # query入口文件
      │   └── types                                                   # 类型定义
      │       ├── type-a.js                                             # 类型a
      │       └── type-b.js                                             # 类型b
      ├── orm                                                       # orm相关
      │   ├── config                                                  # 数据库配置
      │   │   └── config.json                                           # 配置文件
      │   ├── index.js                                                # orm入口文件
      │   ├── migrations                                              # 数据库迁移目录
      │   │   └── 20170825085908-update-migration.js                    # 数据库迁移脚本
      │   └── model                                                   # 数据库model目录
      │       ├── post.js                                               # post model
      │       └── user.js                                               # user model
      ├── router                                                    # 路由
      │   ├── news.js                                                 # news 的路由
      │   └── user.js                                                 # user 的路由
      ├── rpc                                                       # rpc相关
      │   ├── client                                                  # 客户端
      │   │   └── index.js
      │   ├── server                                                  # 服务端
      │   │   └── index.js
      │   └── types                                                   # 类型文件
      │       ├── user.thrift
      │       └── wallet.thrift
      ├── app.js                                                 # 程序总入口
      ├── service                                                   # 服务
      │   ├── server-a.js                                             # a服务
      │   └── server-b.js                                             # b服务
      ├── utils                                                  # 常用工具集
      └── views                                                  # 视图层
          ├── index.html
          └── login.html
```
