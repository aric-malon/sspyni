最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计代码评审 checklist 清单
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.th5jok.asia/arts/695336.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.th5jok.asia/arts/601960.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.th5jok.asia/arts/618705.Doc

原标题：操作系统内核版本适配服务
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.th5jok.asia/arts/713522.Doc

原标题：golang docker 运行 etcd 本地测试
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.th5jok.asia/arts/456514.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.th5jok.asia/arts/301969.Doc

原标题：Mock 接口服务快速搭建实操
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.th5jok.asia/arts/207110.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.th5jok.asia/arts/858177.Doc

原标题：golang http 服务性能优化调参
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.th5jok.asia/arts/933934.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.th5jok.asia/arts/357555.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.th5jok.asia/arts/412833.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.th5jok.asia/arts/770803.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.th5jok.asia/arts/942795.Doc

原标题：golang kafka offset 提交策略
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.th5jok.asia/arts/680615.Doc

原标题：nodejs 集群模式多核利用实现
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.th5jok.asia/arts/598157.Doc

原标题：golang 简易埋点日志上报实现
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.th5jok.asia/arts/341857.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.th5jok.asia/arts/334058.Doc

原标题：golang kafka 生产者参数调优
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.th5jok.asia/arts/553062.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.th5jok.asia/arts/833013.Doc

原标题：实战：数据库explain执行计划分析实操演练
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.th5jok.asia/arts/283009.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.th5jok.asia/arts/661381.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.th5jok.asia/arts/603614.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.th5jok.asia/arts/763953.Doc

原标题：日志输出规范防止磁盘爆满
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.th5jok.asia/arts/745406.Doc

原标题：golang kafka 消息顺序性保证方案
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.th5jok.asia/arts/782132.Doc

原标题：golang goroutine 协程基础实操
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.th5jok.asia/arts/895381.Doc

原标题：零基础理解HTTP常用请求头与状态码
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.th5jok.asia/arts/105286.Doc

原标题：golang docker 部署 mysql 注意事项
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.th5jok.asia/arts/151762.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.th5jok.asia/arts/460936.Doc

原标题：golang redis 连接池参数最佳值
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.th5jok.asia/arts/188645.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.th5jok.asia/arts/489733.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.th5jok.asia/arts/633128.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.th5jok.asia/arts/927164.Doc

原标题：多版本开发环境共存配置
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.th5jok.asia/arts/273069.Doc

原标题：golang html 模板渲染简单示例
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.th5jok.asia/arts/234766.Doc

原标题：程序信号中断退出处理逻辑
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.th5jok.asia/arts/726953.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.th5jok.asia/arts/330089.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.th5jok.asia/arts/089971.Doc

原标题：超大数据集分页性能优化方案
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.th5jok.asia/arts/525794.Doc

原标题：批量操作分批处理防止 OOM
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.th5jok.asia/arts/276871.Doc


二、踩坑排错｜Troubleshooting
原标题：实战：Docker资源监控查看容器状态实操
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.th5jok.asia/arts/019536.Doc

原标题：golang 系统设计热点数据缓存处理
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.th5jok.asia/arts/661651.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.th5jok.asia/arts/462330.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.th5jok.asia/arts/457473.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.th5jok.asia/arts/318499.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.th5jok.asia/arts/078882.Doc

原标题：golang 系统设计排行榜几种实现
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.th5jok.asia/arts/264529.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.th5jok.asia/arts/525776.Doc

原标题：golang 速率限制令牌桶实现
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.th5jok.asia/arts/001434.Doc

原标题：开发测试生产多环境配置区分
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.th5jok.asia/arts/086845.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.th5jok.asia/arts/089635.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.th5jok.asia/arts/890645.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.th5jok.asia/arts/070029.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.th5jok.asia/arts/920846.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.th5jok.asia/arts/259853.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.th5jok.asia/arts/458358.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.th5jok.asia/arts/022473.Doc

原标题：零基础理解幂等性基础概念与场景
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.th5jok.asia/arts/664469.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.th5jok.asia/arts/307736.Doc

原标题：vue3 组合式 API 业务开发实战
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.th5jok.asia/arts/218233.Doc

原标题：golang viper 配置热更新实操
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.th5jok.asia/arts/785189.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.th5jok.asia/arts/451082.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.th5jok.asia/arts/678107.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.th5jok.asia/arts/122430.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.th5jok.asia/arts/181888.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.th5jok.asia/arts/196946.Doc

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.th5jok.asia/arts/189692.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.th5jok.asia/arts/424684.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.th5jok.asia/arts/755766.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.th5jok.asia/arts/966322.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.th5jok.asia/arts/044399.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.th5jok.asia/arts/841376.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.th5jok.asia/arts/630922.Doc

原标题：golang docker compose 完整语法
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.th5jok.asia/arts/904997.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.th5jok.asia/arts/952657.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.th5jok.asia/arts/175824.Doc

原标题：golang validator 自定义校验规则
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.th5jok.asia/arts/899719.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.th5jok.asia/arts/688954.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.th5jok.asia/arts/770111.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.th5jok.asia/arts/367376.Doc

三、实战开发｜Practice
原标题：golang 项目 go mod 依赖管理
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.th5jok.asia/arts/315452.Doc

原标题：前端错误监控上报系统搭建
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.th5jok.asia/arts/490687.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.th5jok.asia/arts/944384.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.th5jok.asia/arts/605870.Doc

原标题：golang grafana 监控面板简单配置
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.th5jok.asia/arts/136528.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.th5jok.asia/arts/751081.Doc

原标题：程序日志分级输出规范实践
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.th5jok.asia/arts/520662.Doc

原标题：golang 系统设计用户签到统计方案
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.th5jok.asia/arts/628366.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.th5jok.asia/arts/377994.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.th5jok.asia/arts/714003.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.th5jok.asia/arts/855103.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.th5jok.asia/arts/631164.Doc

原标题：手写简易 ORM 理解对象映射
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.th5jok.asia/arts/896595.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.th5jok.asia/arts/712888.Doc

原标题：实战：对象存储断点续传下载实践
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.th5jok.asia/arts/033107.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.th5jok.asia/arts/856957.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.th5jok.asia/arts/939840.Doc

原标题：设计思考：分布式锁选型、风险、业务约束
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.th5jok.asia/arts/692705.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.th5jok.asia/arts/432029.Doc

原标题：语义化版本依赖管理防错乱
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.th5jok.asia/arts/596352.Doc

原标题：多操作系统开发兼容处理
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.th5jok.asia/arts/984105.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.th5jok.asia/arts/929809.Doc

原标题：前端骨架屏提升页面体验
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.th5jok.asia/arts/422130.Doc

原标题：golang 系统设计读写分离架构示例
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.th5jok.asia/arts/739993.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.th5jok.asia/arts/291889.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.th5jok.asia/arts/116128.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.th5jok.asia/arts/807770.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.th5jok.asia/arts/856573.Doc

原标题：网关集成鉴权限流日志一体化
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.th5jok.asia/arts/010959.Doc

原标题：预编译 SQL 防注入实现
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.th5jok.asia/arts/534870.Doc

原标题：数据库分表路由写入分片修正
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.th5jok.asia/arts/086801.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.th5jok.asia/arts/584910.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.th5jok.asia/arts/591274.Doc

原标题：短信服务封装失败自动重试
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.th5jok.asia/arts/985004.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.th5jok.asia/arts/643802.Doc

原标题：golang consul 健康检查服务注册
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.th5jok.asia/arts/933641.Doc

原标题：golang kafka 监控指标简单梳理
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.th5jok.asia/arts/789130.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.th5jok.asia/arts/520615.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.th5jok.asia/arts/119514.Doc

原标题：业务错误码体系设计方案
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.th5jok.asia/arts/363634.Doc

四、架构设计｜Architecture
原标题：golang proto 默认值坑点梳理
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.th5jok.asia/arts/745747.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.th5jok.asia/arts/385846.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.th5jok.asia/arts/458060.Doc

原标题：golang redis 锁超时业务处理
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.th5jok.asia/arts/159733.Doc

原标题：golang 接口返回统一封装工具
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.th5jok.asia/arts/018544.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.th5jok.asia/arts/488070.Doc

原标题：golang 系统信号信号量处理
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.th5jok.asia/arts/598007.Doc

原标题：golang 系统设计大文件上传架构
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.th5jok.asia/arts/872168.Doc

原标题：磁盘占满服务不可用清理方案
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.th5jok.asia/arts/419518.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.th5jok.asia/arts/269917.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.th5jok.asia/arts/926400.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.th5jok.asia/arts/200440.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.th5jok.asia/arts/782106.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.th5jok.asia/arts/894698.Doc

原标题：模拟登录鉴权权限判断示例
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.th5jok.asia/arts/898034.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.th5jok.asia/arts/018881.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.th5jok.asia/arts/125528.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.th5jok.asia/arts/307536.Doc

?
