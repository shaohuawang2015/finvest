## 快速入门
本文档基于SOFA BOOT构建的WEB项目的目录结构划分如下：
```text
app
│
├── biz
│   ├── service-impl (模块)
│   └── shared (模块)
│
├── common 
│   ├── dal (模块)
│   └── service 
│       └── facade (模块)
│ 
├── test (模块)
│ 
└── web (模块)
```

上图中未标注 `(模块)` 均为目录，各个模块的作用如下：
- facade (模块)：定义了 对外提供RPC/JVM 服务接口
- dal (模块)：定义了数据源, 完成数据存储接口的操作
- service-impl (模块): 业务实现模块，提供业务数据
- shared (模块):业务流程规划模块，提供业务流程管理公用模块

