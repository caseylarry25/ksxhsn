最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.jgkds3.asia/blog/031408.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.jgkds3.asia/blog/509824.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.jgkds3.asia/blog/958075.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.jgkds3.asia/blog/234232.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.jgkds3.asia/blog/907433.Doc

原标题：golang prometheus histogram 指标
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.jgkds3.asia/blog/593292.Doc

原标题：golang 接口请求日志记录中间件
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.jgkds3.asia/blog/093818.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.jgkds3.asia/blog/418485.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.jgkds3.asia/blog/934333.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.jgkds3.asia/blog/630137.Doc

原标题：golang 系统设计序列化性能选型对比
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://book.jgkds3.asia/blog/166818.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.jgkds3.asia/blog/093421.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.jgkds3.asia/blog/885302.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.jgkds3.asia/blog/458300.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.jgkds3.asia/blog/258214.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.jgkds3.asia/blog/193355.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.jgkds3.asia/blog/250592.Doc

原标题：golang consul 健康检查服务注册
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.jgkds3.asia/blog/047103.Doc

原标题：golang docker 部署 mysql 注意事项
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.jgkds3.asia/blog/930570.Doc

原标题：Performance：JSON序列化性能优化实践
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.jgkds3.asia/blog/355703.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.jgkds3.asia/blog/861070.Doc

原标题：异步异常捕获避免进程崩溃
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.jgkds3.asia/blog/371000.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.jgkds3.asia/blog/677847.Doc

原标题：前端虚拟列表大数据渲染优化
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.jgkds3.asia/blog/716447.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.jgkds3.asia/blog/826277.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.jgkds3.asia/blog/284404.Doc

原标题：golang grafana 面板变量模板制作
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.jgkds3.asia/blog/592766.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.jgkds3.asia/blog/215037.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.jgkds3.asia/blog/193953.Doc

原标题：预编译 SQL 防注入实现
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.jgkds3.asia/blog/026437.Doc

原标题：极简方式搭建个人技术文档站点
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.jgkds3.asia/blog/155018.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.jgkds3.asia/blog/456296.Doc

原标题：包管理器依赖缓存清理
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.jgkds3.asia/blog/294109.Doc

原标题：golang etcd 配置中心简单使用
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://book.jgkds3.asia/blog/756583.Doc

原标题：定时任务重复执行分布式锁
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.jgkds3.asia/blog/073351.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.jgkds3.asia/blog/412777.Doc

原标题：golang mysql 事务回滚异常处理
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.jgkds3.asia/blog/789879.Doc

原标题：OpenAPI 自动接口文档生成
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.jgkds3.asia/blog/043115.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.jgkds3.asia/blog/173287.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.jgkds3.asia/blog/136481.Doc


二、踩坑排错｜Troubleshooting
原标题：Practice：实现接口签名、验签完整示例代码
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.jgkds3.asia/blog/940255.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.jgkds3.asia/blog/671812.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.jgkds3.asia/blog/296281.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.jgkds3.asia/blog/207295.Doc

原标题：webpack chunk 分包策略详解
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://book.jgkds3.asia/blog/023258.Doc

原标题：golang 系统设计大文件上传架构
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.jgkds3.asia/blog/315471.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.jgkds3.asia/blog/972852.Doc

原标题：golang redis 客户端业务使用
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://book.jgkds3.asia/blog/531511.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.jgkds3.asia/blog/329415.Doc

原标题：golang redis 网络超时参数调优
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.jgkds3.asia/blog/758209.Doc

原标题：Architecture：日志、监控、告警整套可观测架构
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.jgkds3.asia/blog/901365.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.jgkds3.asia/blog/633982.Doc

原标题：分布式锁失效问题排查修复
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.jgkds3.asia/blog/759544.Doc

原标题：AI‑Dev：AI辅助编码高效使用提示词技巧
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.jgkds3.asia/blog/497885.Doc

原标题：golang mongodb 索引优化查询速度
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.jgkds3.asia/blog/716629.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.jgkds3.asia/blog/033522.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.jgkds3.asia/blog/820688.Doc

原标题：零基础理解依赖管理与包管理器
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.jgkds3.asia/blog/275602.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.jgkds3.asia/blog/897222.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.jgkds3.asia/blog/048281.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.jgkds3.asia/blog/564625.Doc

原标题：端口占用释放资源重启服务
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.jgkds3.asia/blog/648398.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.jgkds3.asia/blog/066929.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.jgkds3.asia/blog/169888.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.jgkds3.asia/blog/426414.Doc

原标题：消息队列消费堆积扩容处理
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.jgkds3.asia/blog/205076.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.jgkds3.asia/blog/698770.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.jgkds3.asia/blog/575402.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.jgkds3.asia/blog/500984.Doc

原标题：静态资源 404 路径打包修复
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.jgkds3.asia/blog/448037.Doc

原标题：nodejs 跨域中间件配置细节
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://book.jgkds3.asia/blog/689122.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.jgkds3.asia/blog/648558.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.jgkds3.asia/blog/341077.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.jgkds3.asia/blog/195076.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.jgkds3.asia/blog/014858.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.jgkds3.asia/blog/120063.Doc

原标题：实战：数据库explain执行计划分析实操演练
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.jgkds3.asia/blog/537639.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.jgkds3.asia/blog/000512.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.jgkds3.asia/blog/183478.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.jgkds3.asia/blog/915470.Doc

三、实战开发｜Practice
原标题：安全组端口开放网络访问
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.jgkds3.asia/blog/233222.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.jgkds3.asia/blog/612131.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.jgkds3.asia/blog/349798.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.jgkds3.asia/blog/900992.Doc

原标题：Practice：实现接口防重提交组件实践
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.jgkds3.asia/blog/863440.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.jgkds3.asia/blog/049876.Doc

原标题：golang 系统设计错误码体系完整设计
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.jgkds3.asia/blog/602468.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.jgkds3.asia/blog/246211.Doc

原标题：golang mysql 读写分离简单实现
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.jgkds3.asia/blog/524070.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://book.jgkds3.asia/blog/297009.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.jgkds3.asia/blog/923144.Doc

原标题：golang 互斥锁读写锁并发安全
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.jgkds3.asia/blog/375154.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.jgkds3.asia/blog/389251.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.jgkds3.asia/blog/264982.Doc

原标题：golang redis 缓存雪崩完整处理
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://book.jgkds3.asia/blog/275498.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.jgkds3.asia/blog/124659.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.jgkds3.asia/blog/715744.Doc

原标题：提交第一个开源 PR 完整流程
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.jgkds3.asia/blog/935148.Doc

原标题：monorepo 项目多包管理最佳实践
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.jgkds3.asia/blog/220295.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.jgkds3.asia/blog/042144.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.jgkds3.asia/blog/116818.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.jgkds3.asia/blog/660244.Doc

原标题：Practice：实现业务操作日志记录中间件实践
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.jgkds3.asia/blog/231699.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://book.jgkds3.asia/blog/626525.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://book.jgkds3.asia/blog/083141.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.jgkds3.asia/blog/933912.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.jgkds3.asia/blog/045229.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.jgkds3.asia/blog/126547.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.jgkds3.asia/blog/544020.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.jgkds3.asia/blog/504458.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.jgkds3.asia/blog/808292.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.jgkds3.asia/blog/152209.Doc

原标题：golang 分布式锁防死锁处理
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.jgkds3.asia/blog/420386.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.jgkds3.asia/blog/152573.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.jgkds3.asia/blog/042883.Doc

原标题：golang mock 单元测试编写技巧
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://book.jgkds3.asia/blog/088557.Doc

原标题：开源源码阅读拆解学习思路
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.jgkds3.asia/blog/239247.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.jgkds3.asia/blog/354311.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.jgkds3.asia/blog/206659.Doc

原标题：golang consul 健康检查服务注册
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.jgkds3.asia/blog/532522.Doc

四、架构设计｜Architecture
原标题：golang ci 流水线单元测试集成测试
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.jgkds3.asia/blog/774392.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.jgkds3.asia/blog/753730.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.jgkds3.asia/blog/156606.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.jgkds3.asia/blog/351440.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.jgkds3.asia/blog/747130.Doc

原标题：前端静态缓存更新生效处理
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.jgkds3.asia/blog/416177.Doc

原标题：golang 互斥锁读写锁并发安全
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.jgkds3.asia/blog/551389.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.jgkds3.asia/blog/548473.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.jgkds3.asia/blog/541167.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.jgkds3.asia/blog/189091.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.jgkds3.asia/blog/485172.Doc

原标题：定时任务重复执行分布式锁
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://book.jgkds3.asia/blog/329251.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.jgkds3.asia/blog/342986.Doc

原标题：golang minio 对象存储接口开发
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://book.jgkds3.asia/blog/304998.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://book.jgkds3.asia/blog/788400.Doc

原标题：golang k8s service 服务暴露几种类型
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.jgkds3.asia/blog/014009.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.jgkds3.asia/blog/530084.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.jgkds3.asia/blog/077026.Doc

?
