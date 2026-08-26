最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计创建更新时间自动维护方案
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.7h0liu.asia/arts/976662.Doc

原标题：主干开发团队代码合并策略
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.7h0liu.asia/arts/894301.Doc

原标题：看懂报错日志快速定位问题
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.7h0liu.asia/arts/893535.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.7h0liu.asia/arts/069397.Doc

原标题：程序预加载加快服务启动速度
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.7h0liu.asia/arts/561796.Doc

原标题：golang redis 大 key 识别处理方案
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.7h0liu.asia/arts/890148.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.7h0liu.asia/arts/800292.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.7h0liu.asia/arts/493706.Doc

原标题：新手教程：本地环境变量配置全流程
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.7h0liu.asia/arts/997304.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.7h0liu.asia/arts/236111.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.7h0liu.asia/arts/758903.Doc

原标题：快速入门对象存储基础使用场景
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.7h0liu.asia/arts/820641.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.7h0liu.asia/arts/029544.Doc

原标题：golang kafka 死信队列业务落地
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.7h0liu.asia/arts/956830.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.7h0liu.asia/arts/450395.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.7h0liu.asia/arts/374669.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.7h0liu.asia/arts/845703.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.7h0liu.asia/arts/311004.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.7h0liu.asia/arts/380542.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.7h0liu.asia/arts/413442.Doc

原标题：golang html 模板渲染简单示例
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.7h0liu.asia/arts/311066.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.7h0liu.asia/arts/973704.Doc

原标题：golang docker compose 完整语法
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.7h0liu.asia/arts/856692.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.7h0liu.asia/arts/380766.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.7h0liu.asia/arts/823658.Doc

原标题：golang kafka 重试机制配置实操
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.7h0liu.asia/arts/159663.Doc

原标题：文件批量导入导出功能实现
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.7h0liu.asia/arts/660034.Doc

原标题：入门实践：本地简单代理服务搭建
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.7h0liu.asia/arts/375584.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.7h0liu.asia/arts/782928.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.7h0liu.asia/arts/299541.Doc

原标题：golang gin 静态资源访问配置
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.7h0liu.asia/arts/326583.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.7h0liu.asia/arts/938365.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.7h0liu.asia/arts/526498.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.7h0liu.asia/arts/819031.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.7h0liu.asia/arts/719092.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.7h0liu.asia/arts/053176.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.7h0liu.asia/arts/444358.Doc

原标题：异步异常捕获避免进程崩溃
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.7h0liu.asia/arts/014146.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.7h0liu.asia/arts/152110.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.7h0liu.asia/arts/933786.Doc


二、踩坑排错｜Troubleshooting
原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.7h0liu.asia/arts/561437.Doc

原标题：golang redis set 集合去重业务
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.7h0liu.asia/arts/445722.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.7h0liu.asia/arts/416395.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.7h0liu.asia/arts/500980.Doc

原标题：时间精度统一业务判断修复
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.7h0liu.asia/arts/852832.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.7h0liu.asia/arts/642504.Doc

原标题：数据库事务 ACID 原理讲解
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.7h0liu.asia/arts/919433.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.7h0liu.asia/arts/402542.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.7h0liu.asia/arts/375276.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.7h0liu.asia/arts/389177.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.7h0liu.asia/arts/719279.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.7h0liu.asia/arts/308159.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.7h0liu.asia/arts/021808.Doc

原标题：JSON XML 数据解析处理示例
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.7h0liu.asia/arts/078141.Doc

原标题：golang kafka 死信队列业务落地
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.7h0liu.asia/arts/933790.Doc

原标题：死信队列处理消息阻塞业务
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.7h0liu.asia/arts/891150.Doc

原标题：golang channel 通道并发处理
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.7h0liu.asia/arts/341347.Doc

原标题：多套环境灵活切换配置方案
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.7h0liu.asia/arts/609181.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.7h0liu.asia/arts/799141.Doc

原标题：零基础理解模块化与组件化基础思想
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.7h0liu.asia/arts/419689.Doc

原标题：多操作系统开发兼容处理
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.7h0liu.asia/arts/615282.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.7h0liu.asia/arts/793996.Doc

原标题：缓存穿透防护保护数据库
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.7h0liu.asia/arts/422448.Doc

原标题：消息消费重试次数限制防爆炸
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.7h0liu.asia/arts/199922.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.7h0liu.asia/arts/892895.Doc

原标题：零基础理解进程、线程基础概念区别
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.7h0liu.asia/arts/060191.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.7h0liu.asia/arts/455725.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.7h0liu.asia/arts/081011.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.7h0liu.asia/arts/699393.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.7h0liu.asia/arts/269623.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.7h0liu.asia/arts/723704.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.7h0liu.asia/arts/904752.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.7h0liu.asia/arts/678798.Doc

原标题：开源项目本地运行排错完整清单
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.7h0liu.asia/arts/341791.Doc

原标题：golang mysql 慢查询日志开启分析
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.7h0liu.asia/arts/416390.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.7h0liu.asia/arts/127987.Doc

原标题：HTTPS 证书过期更新操作
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.7h0liu.asia/arts/481587.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.7h0liu.asia/arts/594073.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.7h0liu.asia/arts/467769.Doc

原标题：数值 key 浮点匹配异常规避
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.7h0liu.asia/arts/348540.Doc

三、实战开发｜Practice
原标题：入门实践：实现简单文件读写功能
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.7h0liu.asia/arts/275687.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.7h0liu.asia/arts/561796.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.7h0liu.asia/arts/147722.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.7h0liu.asia/arts/615207.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.7h0liu.asia/arts/084436.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.7h0liu.asia/arts/948874.Doc

原标题：golang 系统设计读写分离架构示例
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.7h0liu.asia/arts/544346.Doc

原标题：Git 分支管理多人协作实战教程
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.7h0liu.asia/arts/972052.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.7h0liu.asia/arts/481992.Doc

原标题：项目目录结构规范化最佳实践
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.7h0liu.asia/arts/315205.Doc

原标题：Redis 分布式锁高并发安全实现
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.7h0liu.asia/arts/982229.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.7h0liu.asia/arts/997748.Doc

原标题：rebase 操作防止代码丢失
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.7h0liu.asia/arts/610774.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.7h0liu.asia/arts/596226.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.7h0liu.asia/arts/205171.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.7h0liu.asia/arts/908082.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.7h0liu.asia/arts/354839.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.7h0liu.asia/arts/857785.Doc

原标题：从零搭建简单Mock接口服务
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.7h0liu.asia/arts/723314.Doc

原标题：golang mongodb 文档结构设计原则
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.7h0liu.asia/arts/615514.Doc

原标题：本地数据库开发环境搭建指南
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.7h0liu.asia/arts/560651.Doc

原标题：golang 系统设计文件存储选型对比
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.7h0liu.asia/arts/753326.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.7h0liu.asia/arts/469612.Doc

原标题：GitHub 项目提交推送完整流程讲解
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.7h0liu.asia/arts/203628.Doc

原标题：golang mysql json 字段查询使用
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.7h0liu.asia/arts/260770.Doc

原标题：golang k8s helm chart 简单编写
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.7h0liu.asia/arts/072567.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.7h0liu.asia/arts/716929.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.7h0liu.asia/arts/127371.Doc

原标题：golang 熔断降级简易组件开发
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.7h0liu.asia/arts/996097.Doc

原标题：golang ci 流水线漏洞扫描依赖检查
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.7h0liu.asia/arts/829525.Doc

原标题：golang github actions 完整工作流示例
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.7h0liu.asia/arts/561489.Doc

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.7h0liu.asia/arts/576612.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.7h0liu.asia/arts/233548.Doc

原标题：前端骨架屏提升页面体验
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.7h0liu.asia/arts/042589.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.7h0liu.asia/arts/852872.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.7h0liu.asia/arts/586951.Doc

原标题：TCP 心跳检测清理僵死连接
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.7h0liu.asia/arts/153958.Doc

原标题：网关超时时间调优后端等待
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.7h0liu.asia/arts/388062.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.7h0liu.asia/arts/830612.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.7h0liu.asia/arts/196577.Doc

四、架构设计｜Architecture
原标题：线程调度优化减少上下文切换
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.7h0liu.asia/arts/189923.Doc

原标题：golang prometheus counter gauge 使用
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.7h0liu.asia/arts/152981.Doc

原标题：golang 告警推送钉钉机器人实现
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.7h0liu.asia/arts/936354.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.7h0liu.asia/arts/892130.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.7h0liu.asia/arts/880254.Doc

原标题：看懂报错日志快速定位问题
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.7h0liu.asia/arts/345858.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.7h0liu.asia/arts/378163.Doc

原标题：对象存储上传下载权限实操
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.7h0liu.asia/arts/949245.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.7h0liu.asia/arts/789291.Doc

原标题：版本升级服务启动失败处理
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.7h0liu.asia/arts/381170.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.7h0liu.asia/arts/198795.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.7h0liu.asia/arts/471942.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.7h0liu.asia/arts/917730.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.7h0liu.asia/arts/964734.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.7h0liu.asia/arts/159774.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.7h0liu.asia/arts/787968.Doc

原标题：golang 协程泄露问题排查方法
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.7h0liu.asia/arts/161557.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.7h0liu.asia/arts/771416.Doc

?
