最新前沿技术资讯

一、入门教程｜Getting Started
原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.rkxmnx.asia/aTs/106054.sHtML

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.rkxmnx.asia/aTs/386219.sHtML

原标题：后端登录鉴权模块完整开发
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.rkxmnx.asia/aTs/596827.sHtML

原标题：golang 日志 zap 结构化日志实践
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.rkxmnx.asia/aTs/942254.sHtML

原标题：DevOps：容器健康探针livenessreadiness配置
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.rkxmnx.asia/aTs/944956.sHtML

原标题：golang 集成测试启动测试数据库
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.rkxmnx.asia/aTs/385128.sHtML

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.rkxmnx.asia/aTs/432923.sHtML

原标题：Debug：序列化反序列化版本不一致解析失败
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.rkxmnx.asia/aTs/657553.sHtML

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.rkxmnx.asia/aTs/702023.sHtML

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.rkxmnx.asia/aTs/016030.sHtML

原标题：golang es 高亮搜索结果实现方案
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.rkxmnx.asia/aTs/033976.sHtML

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.rkxmnx.asia/aTs/798752.sHtML

原标题：内存溢出问题现象识别排查
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.rkxmnx.asia/aTs/260557.sHtML

原标题：HelloShell：入门常用shell脚本编写
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.rkxmnx.asia/aTs/626010.sHtML

原标题：Nginx 反向代理路由配置实战
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.rkxmnx.asia/aTs/085760.sHtML

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.rkxmnx.asia/aTs/865062.sHtML

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.rkxmnx.asia/aTs/504319.sHtML

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.rkxmnx.asia/aTs/741486.sHtML

原标题：日志驱动异常日志不输出修复
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://book.rkxmnx.asia/aTs/799389.sHtML

原标题：golang redis 位图用户签到统计
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.rkxmnx.asia/aTs/441244.sHtML

原标题：golang redis 地理位置 geo 使用
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.rkxmnx.asia/aTs/809012.sHtML

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.rkxmnx.asia/aTs/838208.sHtML

原标题：golang mock 单元测试编写技巧
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.rkxmnx.asia/aTs/099352.sHtML

原标题：golang 系统设计灰度发布实现思路
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.rkxmnx.asia/aTs/228550.sHtML

原标题：新手教程：Gittag版本标签打标签实操
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.rkxmnx.asia/aTs/803969.sHtML

原标题：Performance：长连接管理优化减少连接重建开销
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.rkxmnx.asia/aTs/601804.sHtML

原标题：nodejs 中间件模式原理剖析
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://book.rkxmnx.asia/aTs/720459.sHtML

原标题：零基础理解读写分离基础思想
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.rkxmnx.asia/aTs/677083.sHtML

原标题：从零搭建本地开发环境完整教程
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.rkxmnx.asia/aTs/054229.sHtML

原标题：开发记录：表单参数校验统一中间件实现
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.rkxmnx.asia/aTs/571695.sHtML

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.rkxmnx.asia/aTs/927211.sHtML

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.rkxmnx.asia/aTs/244067.sHtML

原标题：数据库事务 ACID 原理讲解
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.rkxmnx.asia/aTs/508876.sHtML

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.rkxmnx.asia/aTs/089790.sHtML

原标题：Architecture：服务注册发现架构原理与选型
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.rkxmnx.asia/aTs/465296.sHtML

原标题：golang gorm 预加载关联查询优化
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.rkxmnx.asia/aTs/686228.sHtML

原标题：nodejs 集群模式多核利用实现
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.rkxmnx.asia/aTs/403571.sHtML

原标题：前端图片懒加载性能优化
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.rkxmnx.asia/aTs/361659.sHtML

原标题：快速上手单元测试，写出第一个测试用例
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.rkxmnx.asia/aTs/196145.sHtML

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.rkxmnx.asia/aTs/750430.sHtML


二、踩坑排错｜Troubleshooting
原标题：实战：数据库索引设计，复合索引最佳实践
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.rkxmnx.asia/aTs/713559.sHtML

原标题：实践：代码提交前自动格式化校验配置实践
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.rkxmnx.asia/aTs/979311.sHtML

原标题：golang kafka 生产者参数调优
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.rkxmnx.asia/aTs/805156.sHtML

原标题：macOS 脚本执行权限开启
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.rkxmnx.asia/aTs/428373.sHtML

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.rkxmnx.asia/aTs/382415.sHtML

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.rkxmnx.asia/aTs/501999.sHtML

原标题：golang 接口限流中间件开发
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.rkxmnx.asia/aTs/501179.sHtML

原标题：包管理器依赖冲突解决方案
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.rkxmnx.asia/aTs/660264.sHtML

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.rkxmnx.asia/aTs/205355.sHtML

原标题：golang grafana 面板变量模板制作
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://book.rkxmnx.asia/aTs/750887.sHtML

原标题：正则表达式优化 CPU 占满问题
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.rkxmnx.asia/aTs/538662.sHtML

原标题：Performance：后端接口性能优化完整分析流程
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.rkxmnx.asia/aTs/103944.sHtML

原标题：golang 系统设计多级缓存更新策略
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.rkxmnx.asia/aTs/341105.sHtML

原标题：golang 系统设计埋点数据上报方案
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.rkxmnx.asia/aTs/938208.sHtML

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.rkxmnx.asia/aTs/697763.sHtML

原标题：版本升级服务启动失败处理
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.rkxmnx.asia/aTs/998848.sHtML

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.rkxmnx.asia/aTs/728885.sHtML

原标题：实战：搭建日志收集分析简易完整演示环境
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.rkxmnx.asia/aTs/023475.sHtML

原标题：golang 系统设计灰度发布实现思路
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://book.rkxmnx.asia/aTs/432560.sHtML

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.rkxmnx.asia/aTs/464750.sHtML

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.rkxmnx.asia/aTs/552914.sHtML

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.rkxmnx.asia/aTs/356512.sHtML

原标题：golang redis bitmap 位图统计实现
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.rkxmnx.asia/aTs/132046.sHtML

原标题：golang mysql exists in 性能对比
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.rkxmnx.asia/aTs/255093.sHtML

原标题：全局时间标准统一逻辑错乱修复
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.rkxmnx.asia/aTs/211342.sHtML

原标题：golang 容器健康检查接口开发
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.rkxmnx.asia/aTs/502963.sHtML

原标题：golang 结构体 json 序列化坑点
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.rkxmnx.asia/aTs/069728.sHtML

原标题：Architecture：API网关核心能力与组件拆分
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.rkxmnx.asia/aTs/678351.sHtML

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.rkxmnx.asia/aTs/097929.sHtML

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.rkxmnx.asia/aTs/882813.sHtML

原标题：异步异常捕获避免进程崩溃
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.rkxmnx.asia/aTs/665398.sHtML

原标题：5分钟快速搭建个人技术文档站点
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.rkxmnx.asia/aTs/285877.sHtML

原标题：RPC 接口字段增减兼容处理
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.rkxmnx.asia/aTs/278305.sHtML

原标题：golang 系统设计压测指标确定与分析
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.rkxmnx.asia/aTs/717771.sHtML

原标题：golang channel 通道并发处理
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.rkxmnx.asia/aTs/248526.sHtML

原标题：golang 系统设计 mq 消息重复消费处理
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.rkxmnx.asia/aTs/603757.sHtML

原标题：golang 系统设计索引设计通用方法论汇总
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.rkxmnx.asia/aTs/802137.sHtML

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://book.rkxmnx.asia/aTs/424696.sHtML

原标题：golang docker 部署 es 本地开发
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.rkxmnx.asia/aTs/977959.sHtML

原标题：golang 系统设计性能优化通用思路方法论
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.rkxmnx.asia/aTs/609067.sHtML

三、实战开发｜Practice
原标题：golang http 服务性能优化调参
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.rkxmnx.asia/aTs/968620.sHtML

原标题：golang 系统设计传输加密 tls 配置要点
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.rkxmnx.asia/aTs/728881.sHtML

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.rkxmnx.asia/aTs/356025.sHtML

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.rkxmnx.asia/aTs/935922.sHtML

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.rkxmnx.asia/aTs/532349.sHtML

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.rkxmnx.asia/aTs/568927.sHtML

原标题：golang minio 存储桶权限管控配置
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.rkxmnx.asia/aTs/613178.sHtML

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.rkxmnx.asia/aTs/250511.sHtML

原标题：golang redis zset 延时队列实现
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.rkxmnx.asia/aTs/439068.sHtML

原标题：网关集成鉴权限流日志一体化
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://book.rkxmnx.asia/aTs/436954.sHtML

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.rkxmnx.asia/aTs/996483.sHtML

原标题：实战：Docker资源监控查看容器状态实操
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.rkxmnx.asia/aTs/818366.sHtML

原标题：方案设计：接口版本管理架构向前兼容策略
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.rkxmnx.asia/aTs/213707.sHtML

原标题：golang 系统设计开源项目依赖版本升级维护
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.rkxmnx.asia/aTs/158239.sHtML

原标题：golang redis bitmap 位图统计实现
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.rkxmnx.asia/aTs/448828.sHtML

原标题：golang 系统设计日志系统架构思路
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.rkxmnx.asia/aTs/757939.sHtML

原标题：golang 文件上传下载接口开发
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.rkxmnx.asia/aTs/794496.sHtML

原标题：零基础理解前后端简单交互流程
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.rkxmnx.asia/aTs/650974.sHtML

原标题：golang 系统设计 rest 状态码合理使用指南
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.rkxmnx.asia/aTs/843854.sHtML

原标题：优化实践：读写分离分担主库查询压力
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.rkxmnx.asia/aTs/529600.sHtML

原标题：新手教程：本地项目初始化gitignore配置
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.rkxmnx.asia/aTs/589099.sHtML

原标题：golang 链路 traceId 透传中间件
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.rkxmnx.asia/aTs/503171.sHtML

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.rkxmnx.asia/aTs/898161.sHtML

原标题：定时任务周期调度 demo 开发
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.rkxmnx.asia/aTs/725564.sHtML

原标题：golang 系统设计 id 生成器选型对比
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.rkxmnx.asia/aTs/539538.sHtML

原标题：Hands‑on：简易网关路由转发组件开发
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.rkxmnx.asia/aTs/271797.sHtML

原标题：golang 告警推送钉钉机器人实现
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.rkxmnx.asia/aTs/765636.sHtML

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.rkxmnx.asia/aTs/069450.sHtML

原标题：Practice：实现请求body重复读取中间件实践
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.rkxmnx.asia/aTs/462726.sHtML

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.rkxmnx.asia/aTs/901199.sHtML

原标题：大文件导出内存溢出防护
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.rkxmnx.asia/aTs/747470.sHtML

原标题：golang 系统设计灰度发布实现思路
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.rkxmnx.asia/aTs/566056.sHtML

原标题：快速入门：API接口调试完整实操步骤
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.rkxmnx.asia/aTs/387804.sHtML

原标题：系统时间同步定时任务偏移
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.rkxmnx.asia/aTs/710761.sHtML

原标题：golang 系统设计回调重试幂等完整处理
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.rkxmnx.asia/aTs/416522.sHtML

原标题：golang docker compose 本地开发最佳实践
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.rkxmnx.asia/aTs/385610.sHtML

原标题：golang 系统设计缓存预热脚本编写实操
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.rkxmnx.asia/aTs/684045.sHtML

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.rkxmnx.asia/aTs/901804.sHtML

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.rkxmnx.asia/aTs/189561.sHtML

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.rkxmnx.asia/aTs/391366.sHtML

四、架构设计｜Architecture
原标题：gRPC 服务端客户端入门示例
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.rkxmnx.asia/aTs/898919.sHtML

原标题：golang k8s 滚动更新回滚策略
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.rkxmnx.asia/aTs/619678.sHtML

原标题：安全复盘：业务接口越权测试与修复实践
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.rkxmnx.asia/aTs/436404.sHtML

原标题：Git 标签版本标记发布管理
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.rkxmnx.asia/aTs/867301.sHtML

原标题：CLI 批量处理工具文件操作开发
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.rkxmnx.asia/aTs/202182.sHtML

原标题：Architecture：配置中心架构，动态配置设计思路
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.rkxmnx.asia/aTs/227694.sHtML

原标题：golang 系统设计缓存预热脚本编写实操
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.rkxmnx.asia/aTs/318956.sHtML

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.rkxmnx.asia/aTs/925693.sHtML

原标题：golang 接口请求日志记录中间件
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.rkxmnx.asia/aTs/762083.sHtML

原标题：golang defer panic 异常处理
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.rkxmnx.asia/aTs/278692.sHtML

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.rkxmnx.asia/aTs/640968.sHtML

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.rkxmnx.asia/aTs/724100.sHtML

原标题：从零编写简易 CLI 命令行工具
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.rkxmnx.asia/aTs/163412.sHtML

原标题：golang etcd 租约 lease 过期机制
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.rkxmnx.asia/aTs/341994.sHtML

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.rkxmnx.asia/aTs/668210.sHtML

原标题：ORM 隐式慢查询问题规避
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.rkxmnx.asia/aTs/984634.sHtML

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.rkxmnx.asia/aTs/793144.sHtML

原标题：golang git 提交信息规范校验
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.rkxmnx.asia/aTs/507168.sHtML

?
