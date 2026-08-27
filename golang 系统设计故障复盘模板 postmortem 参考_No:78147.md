最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.yyxhozy.asia/blog/7119938.sHtMl

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://book.yyxhozy.asia/blog/3532578.sHtMl

原标题：golang 系统设计数据库慢查询治理方案
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.yyxhozy.asia/blog/1868649.sHtMl

原标题：golang 参数校验业务接口处理
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.yyxhozy.asia/blog/1514540.sHtMl

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.yyxhozy.asia/blog/7122579.sHtMl

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.yyxhozy.asia/blog/3213252.sHtMl

原标题：快速上手阅读开源项目源码的入门思路
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.yyxhozy.asia/blog/4809166.sHtMl

原标题：调优方案：Web服务内核socket参数调优
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.yyxhozy.asia/blog/3798102.sHtMl

原标题：golang 系统设计分库分表中间件思路
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.yyxhozy.asia/blog/7578167.sHtMl

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.yyxhozy.asia/blog/4269817.sHtMl

原标题：git rebase 整理提交历史实操
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.yyxhozy.asia/blog/1866804.sHtMl

原标题：service‑worker 离线缓存实践
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.yyxhozy.asia/blog/7779320.sHtMl

原标题：实战项目：WSL开发环境完整配置实操
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.yyxhozy.asia/blog/0127823.sHtMl

原标题：大事务拆分回滚日志暴涨解决
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.yyxhozy.asia/blog/9117022.sHtMl

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.yyxhozy.asia/blog/0802926.sHtMl

原标题：项目实践：本地模拟多节点分布式系统实践
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.yyxhozy.asia/blog/6025978.sHtMl

原标题：特殊输入字符过滤解析防护
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.yyxhozy.asia/blog/2768177.sHtMl

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://book.yyxhozy.asia/blog/3243843.sHtMl

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.yyxhozy.asia/blog/1957334.sHtMl

原标题：golang mysql 长连接短连接对比
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.yyxhozy.asia/blog/9794201.sHtMl

原标题：从零搭建简单的身份登录模拟示例
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.yyxhozy.asia/blog/7159127.sHtMl

原标题：读懂开源项目 README 实用技巧
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.yyxhozy.asia/blog/4033503.sHtMl

原标题：golang 系统设计大事务拆分实战思路
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.yyxhozy.asia/blog/1203912.sHtMl

原标题：golang 内存 pprof 定位内存泄漏
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://book.yyxhozy.asia/blog/2307455.sHtMl

原标题：Practice：实现简单信号处理优雅停机实践
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.yyxhozy.asia/blog/6992201.sHtMl

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.yyxhozy.asia/blog/4321819.sHtMl

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.yyxhozy.asia/blog/2489192.sHtMl

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.yyxhozy.asia/blog/9368573.sHtMl

原标题：golang kafka 消息丢失重复消费
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.yyxhozy.asia/blog/4743745.sHtMl

原标题：优化实践：Redis性能调优，避免大key热key
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.yyxhozy.asia/blog/9430640.sHtMl

原标题：golang docker 部署 mysql 注意事项
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.yyxhozy.asia/blog/9650275.sHtMl

原标题：golang base64 编码解码实操
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.yyxhozy.asia/blog/7249983.sHtMl

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.yyxhozy.asia/blog/2490717.sHtMl

原标题：golang elasticsearch 索引设计思路
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.yyxhozy.asia/blog/7499105.sHtMl

原标题：golang 系统设计架构图绘制规范简单建议
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.yyxhozy.asia/blog/4898762.sHtMl

原标题：踩坑：大事务引发数据库连接池耗尽
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.yyxhozy.asia/blog/7424763.sHtMl

原标题：golang 项目 go mod 依赖管理
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.yyxhozy.asia/blog/7644154.sHtMl

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.yyxhozy.asia/blog/7613899.sHtMl

原标题：golang docker 基础命令实操汇总
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.yyxhozy.asia/blog/0274022.sHtMl

原标题：复盘总结：技术选型对比文档模板实践
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.yyxhozy.asia/blog/8679760.sHtMl


二、踩坑排错｜Troubleshooting
原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.yyxhozy.asia/blog/7310760.sHtMl

原标题：运维笔记：备份策略数据库定时备份脚本
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.yyxhozy.asia/blog/1495751.sHtMl

原标题：golang 系统设计网关性能压测优化简单思路
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.yyxhozy.asia/blog/5591834.sHtMl

原标题：golang etcd watch 监听配置变更
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.yyxhozy.asia/blog/5946374.sHtMl

原标题：Practice：简易限流器分布式版本Redis实现
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.yyxhozy.asia/blog/5681095.sHtMl

原标题：golang 大文件读取内存优化
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.yyxhozy.asia/blog/0105311.sHtMl

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.yyxhozy.asia/blog/7964847.sHtMl

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.yyxhozy.asia/blog/7794285.sHtMl

原标题：eslint prettier 代码规范落地
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.yyxhozy.asia/blog/0643940.sHtMl

原标题：nodejs redis 缓存业务实战
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.yyxhozy.asia/blog/9392591.sHtMl

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://book.yyxhozy.asia/blog/6282548.sHtMl

原标题：golang prometheus counter gauge 使用
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.yyxhozy.asia/blog/6093969.sHtMl

原标题：前端骨架屏提升页面体验
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://book.yyxhozy.asia/blog/9009540.sHtMl

原标题：golang ci 流水线环境变量管理方案
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.yyxhozy.asia/blog/8223830.sHtMl

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.yyxhozy.asia/blog/8752409.sHtMl

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.yyxhozy.asia/blog/8500189.sHtMl

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.yyxhozy.asia/blog/3923863.sHtMl

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.yyxhozy.asia/blog/9394908.sHtMl

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.yyxhozy.asia/blog/5634496.sHtMl

原标题：golang docker compose 本地开发最佳实践
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.yyxhozy.asia/blog/5758650.sHtMl

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.yyxhozy.asia/blog/4264232.sHtMl

原标题：实践：分布式事务本地模拟验证实践
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.yyxhozy.asia/blog/5576041.sHtMl

原标题：项目实践：灰度发布简易方案落地实践
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.yyxhozy.asia/blog/5612895.sHtMl

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.yyxhozy.asia/blog/5093158.sHtMl

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.yyxhozy.asia/blog/3702237.sHtMl

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.yyxhozy.asia/blog/2892473.sHtMl

原标题：golang pprof 线上采集性能数据
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.yyxhozy.asia/blog/2010003.sHtMl

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.yyxhozy.asia/blog/1983754.sHtMl

原标题：快速入门消息队列基础概念模型
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.yyxhozy.asia/blog/5636237.sHtMl

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.yyxhozy.asia/blog/5753534.sHtMl

原标题：零基础学习简单正则表达式实战案例
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.yyxhozy.asia/blog/5016644.sHtMl

原标题：排错：多实例部署session共享失效登录失效
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.yyxhozy.asia/blog/1280218.sHtMl

原标题：数据库排序规则统一结果一致
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.yyxhozy.asia/blog/3929352.sHtMl

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://book.yyxhozy.asia/blog/0051757.sHtMl

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.yyxhozy.asia/blog/5022515.sHtMl

原标题：浮点计算精度错误处理方案
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.yyxhozy.asia/blog/8961561.sHtMl

原标题：Architecture：文件处理服务架构大文件内存规避
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.yyxhozy.asia/blog/1537964.sHtMl

原标题：调优方案：容器CPU内存参数压测后调优
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.yyxhozy.asia/blog/7288061.sHtMl

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.yyxhozy.asia/blog/6582700.sHtMl

原标题：golang ci 流水线单元测试集成测试
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.yyxhozy.asia/blog/0498799.sHtMl

三、实战开发｜Practice
原标题：入门实践：本地简单代理服务搭建
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.yyxhozy.asia/blog/6091687.sHtMl

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.yyxhozy.asia/blog/8952556.sHtMl

原标题：游标分页大数据查询性能提升
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.yyxhozy.asia/blog/4515634.sHtMl

原标题：方案设计：异步解耦业务架构边界识别
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.yyxhozy.asia/blog/7254635.sHtMl

原标题：Docker 容器入门镜像实操教程
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.yyxhozy.asia/blog/6125509.sHtMl

原标题：golang 日志脱敏敏感字段过滤
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.yyxhozy.asia/blog/6467612.sHtMl

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.yyxhozy.asia/blog/1025876.sHtMl

原标题：快速上手阅读开源项目源码的入门思路
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.yyxhozy.asia/blog/7879642.sHtMl

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.yyxhozy.asia/blog/1751957.sHtMl

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.yyxhozy.asia/blog/4170817.sHtMl

原标题：golang k8s secret 加密敏感信息
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.yyxhozy.asia/blog/0804262.sHtMl

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.yyxhozy.asia/blog/1588238.sHtMl

原标题：golang 系统设计限流熔断降级组合使用
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.yyxhozy.asia/blog/6862570.sHtMl

原标题：后端登录鉴权模块完整开发
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.yyxhozy.asia/blog/2383461.sHtMl

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.yyxhozy.asia/blog/4221400.sHtMl

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.yyxhozy.asia/blog/4949602.sHtMl

原标题：静态博客部署 GitHub Pages 教程
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.yyxhozy.asia/blog/7719181.sHtMl

原标题：操作系统内核版本适配服务
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.yyxhozy.asia/blog/1971790.sHtMl

原标题：golang 静态编译缩小镜像体积
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.yyxhozy.asia/blog/9994798.sHtMl

原标题：golang 系统设计无锁编程思路简单示例
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.yyxhozy.asia/blog/5162348.sHtMl

原标题：golang 系统设计 csrf 接口防护实现
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.yyxhozy.asia/blog/2869324.sHtMl

原标题：快速入门消息通知简单实现方案
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.yyxhozy.asia/blog/3391130.sHtMl

原标题：架构笔记：业务操作审计日志系统架构设计
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.yyxhozy.asia/blog/1921942.sHtMl

原标题：golang kafka 同步异步消费对比
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.yyxhozy.asia/blog/3719956.sHtMl

原标题：golang 系统设计参数校验统一处理方案
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.yyxhozy.asia/blog/7108697.sHtMl

原标题：排错：GitLFS大文件推送失败完整排障
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.yyxhozy.asia/blog/2849605.sHtMl

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://book.yyxhozy.asia/blog/3534394.sHtMl

原标题：安全实践：防止重放攻击接口签名方案
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.yyxhozy.asia/blog/8720154.sHtMl

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.yyxhozy.asia/blog/1561726.sHtMl

原标题：Git LFS 大文件推送失败解决
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://book.yyxhozy.asia/blog/4004326.sHtMl

原标题：调试工具断点调试变量查看技巧
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.yyxhozy.asia/blog/4409849.sHtMl

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.yyxhozy.asia/blog/8380085.sHtMl

原标题：ORM 隐式慢查询问题规避
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.yyxhozy.asia/blog/5930236.sHtMl

原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.yyxhozy.asia/blog/6053572.sHtMl

原标题：golang k8s cronjob 定时任务配置
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.yyxhozy.asia/blog/7192785.sHtMl

原标题：Performance：数据库索引优化常见错误案例
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.yyxhozy.asia/blog/5443025.sHtMl

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.yyxhozy.asia/blog/4374055.sHtMl

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.yyxhozy.asia/blog/2642084.sHtMl

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.yyxhozy.asia/blog/1287725.sHtMl

原标题：golang 优雅停机服务关闭实现
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.yyxhozy.asia/blog/6057115.sHtMl

四、架构设计｜Architecture
原标题：零基础理解读写分离基础思想
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.yyxhozy.asia/blog/3253887.sHtMl

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.yyxhozy.asia/blog/2812004.sHtMl

原标题：Cookie 跨环境登录配置调整
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.yyxhozy.asia/blog/8649456.sHtMl

原标题：git cherry‑pick 规范操作防 bug
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.yyxhozy.asia/blog/9019198.sHtMl

原标题：TCP 心跳检测清理僵死连接
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.yyxhozy.asia/blog/0009257.sHtMl

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.yyxhozy.asia/blog/6894155.sHtMl

原标题：从零搭建本地开发环境完整教程
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.yyxhozy.asia/blog/5976092.sHtMl

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.yyxhozy.asia/blog/8621945.sHtMl

原标题：Performance：缓存策略优化，降低数据库压力
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.yyxhozy.asia/blog/9389677.sHtMl

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.yyxhozy.asia/blog/8818654.sHtMl

原标题：快速入门：API接口调试完整实操步骤
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.yyxhozy.asia/blog/2790106.sHtMl

原标题：vite 插件开发自定义构建逻辑
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.yyxhozy.asia/blog/5396926.sHtMl

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.yyxhozy.asia/blog/5310425.sHtMl

原标题：运维笔记：服务器日志轮转logrotate配置
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.yyxhozy.asia/blog/8474003.sHtMl

原标题：golang mongodb 事务多文档使用
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.yyxhozy.asia/blog/0854092.sHtMl

原标题：golang 灰度权重流量分发简单实现
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.yyxhozy.asia/blog/7503988.sHtMl

原标题：Practice：实现接口防重提交组件实践
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.yyxhozy.asia/blog/0506914.sHtMl

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.yyxhozy.asia/blog/7877530.sHtMl

?
