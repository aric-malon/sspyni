最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.tzr3ix.asia/blog/827513.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.tzr3ix.asia/blog/994061.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.tzr3ix.asia/blog/518205.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.tzr3ix.asia/blog/362794.Doc

原标题：短信服务封装失败自动重试
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.tzr3ix.asia/blog/856769.Doc

原标题：golang http grpc 全链路埋点示例
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.tzr3ix.asia/blog/608798.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.tzr3ix.asia/blog/955436.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.tzr3ix.asia/blog/445686.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.tzr3ix.asia/blog/114286.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.tzr3ix.asia/blog/845341.Doc

原标题：前端打包分包加载提速方案
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.tzr3ix.asia/blog/545226.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.tzr3ix.asia/blog/514237.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.tzr3ix.asia/blog/373613.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.tzr3ix.asia/blog/789863.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.tzr3ix.asia/blog/225183.Doc

原标题：golang ci 流水线环境变量管理方案
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.tzr3ix.asia/blog/528025.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.tzr3ix.asia/blog/937840.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.tzr3ix.asia/blog/196340.Doc

原标题：死信队列处理消息阻塞业务
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.tzr3ix.asia/blog/834020.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.tzr3ix.asia/blog/666048.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.tzr3ix.asia/blog/676486.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.tzr3ix.asia/blog/884336.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.tzr3ix.asia/blog/957908.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.tzr3ix.asia/blog/709776.Doc

原标题：数据库死锁成因规避方案
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.tzr3ix.asia/blog/362202.Doc

原标题：golang 布隆过滤器实现去重
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.tzr3ix.asia/blog/519090.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.tzr3ix.asia/blog/802265.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.tzr3ix.asia/blog/922706.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.tzr3ix.asia/blog/148529.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.tzr3ix.asia/blog/149835.Doc

原标题：golang redis 地理位置 geo 使用
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.tzr3ix.asia/blog/820765.Doc

原标题：golang 消息死信处理业务逻辑
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.tzr3ix.asia/blog/814607.Doc

原标题：分布式 ID 全局唯一生成方案
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.tzr3ix.asia/blog/598381.Doc

原标题：K8s 镜像拉取网络故障修复
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.tzr3ix.asia/blog/366369.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.tzr3ix.asia/blog/069893.Doc

原标题：golang 系统设计序列化性能选型对比
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.tzr3ix.asia/blog/584120.Doc

原标题：golang goroutine 协程基础实操
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.tzr3ix.asia/blog/361461.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.tzr3ix.asia/blog/263054.Doc

原标题：网关集成鉴权限流日志一体化
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.tzr3ix.asia/blog/358295.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.tzr3ix.asia/blog/779792.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 sql 注入 xss 防护实践
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.tzr3ix.asia/blog/604243.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.tzr3ix.asia/blog/250987.Doc

原标题：Security：RPC调用身份认证安全加固
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.tzr3ix.asia/blog/333089.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.tzr3ix.asia/blog/300298.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.tzr3ix.asia/blog/254195.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://book.tzr3ix.asia/blog/062943.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.tzr3ix.asia/blog/564895.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.tzr3ix.asia/blog/928989.Doc

原标题：golang mock 单元测试编写技巧
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.tzr3ix.asia/blog/800063.Doc

原标题：手写简易 ORM 理解对象映射
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://book.tzr3ix.asia/blog/528679.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://book.tzr3ix.asia/blog/395563.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.tzr3ix.asia/blog/735203.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.tzr3ix.asia/blog/500242.Doc

原标题：缓存过期打散防止缓存雪崩
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.tzr3ix.asia/blog/660282.Doc

原标题：短信服务封装失败自动重试
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.tzr3ix.asia/blog/443197.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.tzr3ix.asia/blog/570362.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.tzr3ix.asia/blog/285327.Doc

原标题：重复提交幂等防护再次讲解
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.tzr3ix.asia/blog/581276.Doc

原标题：golang 互斥锁读写锁并发安全
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://book.tzr3ix.asia/blog/599010.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.tzr3ix.asia/blog/402256.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.tzr3ix.asia/blog/433649.Doc

原标题：从零搭建简单Mock接口服务
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.tzr3ix.asia/blog/191374.Doc

原标题：golang es 聚合统计查询实现
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.tzr3ix.asia/blog/560593.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.tzr3ix.asia/blog/916448.Doc

原标题：上传接口跨域配置特殊适配
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.tzr3ix.asia/blog/705101.Doc

原标题：数据库排序规则统一结果一致
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.tzr3ix.asia/blog/294640.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.tzr3ix.asia/blog/088363.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.tzr3ix.asia/blog/933814.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.tzr3ix.asia/blog/834147.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.tzr3ix.asia/blog/112495.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.tzr3ix.asia/blog/283535.Doc

原标题：批量操作分批处理防止 OOM
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://book.tzr3ix.asia/blog/554934.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.tzr3ix.asia/blog/848009.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.tzr3ix.asia/blog/660808.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.tzr3ix.asia/blog/189640.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.tzr3ix.asia/blog/810376.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.tzr3ix.asia/blog/475113.Doc

原标题：Git 分支管理多人协作实战教程
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.tzr3ix.asia/blog/662703.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.tzr3ix.asia/blog/708758.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.tzr3ix.asia/blog/296820.Doc

三、实战开发｜Practice
原标题：跨域偶现失败配置修复
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.tzr3ix.asia/blog/230561.Doc

原标题：入门实践：使用模板快速生成项目脚手架
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.tzr3ix.asia/blog/848916.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.tzr3ix.asia/blog/042194.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.tzr3ix.asia/blog/794952.Doc

原标题：任务执行锁防止并发重复调度
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.tzr3ix.asia/blog/857549.Doc

原标题：vite 项目配置与构建提速技巧
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.tzr3ix.asia/blog/116417.Doc

原标题：golang 系统设计分库分表中间件思路
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.tzr3ix.asia/blog/624032.Doc

原标题：golang mysql 字符集排序规则设置
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.tzr3ix.asia/blog/406065.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.tzr3ix.asia/blog/923423.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.tzr3ix.asia/blog/122442.Doc

原标题：golang prometheus 指标暴露实现
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://book.tzr3ix.asia/blog/927951.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.tzr3ix.asia/blog/631219.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.tzr3ix.asia/blog/401006.Doc

原标题：golang websocket 消息广播实现
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.tzr3ix.asia/blog/140931.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.tzr3ix.asia/blog/968665.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.tzr3ix.asia/blog/003017.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.tzr3ix.asia/blog/929078.Doc

原标题：从零学习简单分布式ID生成思路
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.tzr3ix.asia/blog/170969.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.tzr3ix.asia/blog/080193.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.tzr3ix.asia/blog/376153.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.tzr3ix.asia/blog/016043.Doc

原标题：golang redis 锁超时业务处理
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.tzr3ix.asia/blog/649417.Doc

原标题：golang excel 简单读写操作示例
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://book.tzr3ix.asia/blog/043947.Doc

原标题：限流规则误拦截正常请求修复
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.tzr3ix.asia/blog/340674.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.tzr3ix.asia/blog/401738.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.tzr3ix.asia/blog/942649.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.tzr3ix.asia/blog/640186.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.tzr3ix.asia/blog/768139.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.tzr3ix.asia/blog/614386.Doc

原标题：Git commit 钩子提交规范校验
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.tzr3ix.asia/blog/852399.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.tzr3ix.asia/blog/095684.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.tzr3ix.asia/blog/443792.Doc

原标题：单元测试用例编写入门实操
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.tzr3ix.asia/blog/222387.Doc

原标题：批量异步处理系统业务落地
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.tzr3ix.asia/blog/584481.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.tzr3ix.asia/blog/871874.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.tzr3ix.asia/blog/441257.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.tzr3ix.asia/blog/743282.Doc

原标题：OAuth2 第三方登录服务搭建
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.tzr3ix.asia/blog/655672.Doc

原标题：本地数据库开发环境搭建指南
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://book.tzr3ix.asia/blog/767088.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.tzr3ix.asia/blog/062256.Doc

四、架构设计｜Architecture
原标题：golang 系统设计数据库基准压测简单思路
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.tzr3ix.asia/blog/294240.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://book.tzr3ix.asia/blog/931900.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.tzr3ix.asia/blog/580031.Doc

原标题：业务错误码体系设计方案
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.tzr3ix.asia/blog/586035.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.tzr3ix.asia/blog/841643.Doc

原标题：golang 多协程任务池并发控制
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.tzr3ix.asia/blog/698331.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.tzr3ix.asia/blog/324759.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.tzr3ix.asia/blog/789079.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.tzr3ix.asia/blog/910853.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.tzr3ix.asia/blog/723449.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.tzr3ix.asia/blog/369427.Doc

原标题：nodejs 中间件模式原理剖析
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.tzr3ix.asia/blog/552677.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.tzr3ix.asia/blog/194798.Doc

原标题：分布式 ID 全局唯一生成方案
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.tzr3ix.asia/blog/296551.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.tzr3ix.asia/blog/324844.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.tzr3ix.asia/blog/141864.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.tzr3ix.asia/blog/266004.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.tzr3ix.asia/blog/236040.Doc

?
