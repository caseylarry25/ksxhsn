最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.2bhujh.asia/arts/363924.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.2bhujh.asia/arts/392709.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.2bhujh.asia/arts/294370.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.2bhujh.asia/arts/606117.Doc

原标题：Performance：JSON序列化性能优化实践
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.2bhujh.asia/arts/318738.Doc

原标题：golang 系统设计序列化性能选型对比
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.2bhujh.asia/arts/412958.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.2bhujh.asia/arts/529925.Doc

原标题：golang minio 对象存储接口开发
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.2bhujh.asia/arts/818430.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.2bhujh.asia/arts/748412.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.2bhujh.asia/arts/869662.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.2bhujh.asia/arts/736705.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.2bhujh.asia/arts/306284.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.2bhujh.asia/arts/156840.Doc

原标题：golang mongodb 事务多文档使用
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.2bhujh.asia/arts/600409.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.2bhujh.asia/arts/335006.Doc

原标题：前端骨架屏提升页面体验
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.2bhujh.asia/arts/377915.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.2bhujh.asia/arts/701699.Doc

原标题：开发生产环境资源路径统一
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.2bhujh.asia/arts/389813.Doc

原标题：golang 数据库慢查询监控实现
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.2bhujh.asia/arts/123144.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.2bhujh.asia/arts/690333.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.2bhujh.asia/arts/683683.Doc

原标题：YAML 配置文件语法快速上手
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/181833.Doc

原标题：Shell 脚本自动化命令编写
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.2bhujh.asia/arts/378974.Doc

原标题：语义化版本依赖管理防错乱
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.2bhujh.asia/arts/867443.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.2bhujh.asia/arts/751428.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.2bhujh.asia/arts/829864.Doc

原标题：gitignore 文件编写过滤规则
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/652243.Doc

原标题：布隆过滤器误判问题修正
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.2bhujh.asia/arts/193273.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.2bhujh.asia/arts/000092.Doc

原标题：golang excel 简单读写操作示例
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.2bhujh.asia/arts/529135.Doc

原标题：Dockerfile 编写容器打包实战
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.2bhujh.asia/arts/232875.Doc

原标题：golang 多协程任务池并发控制
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.2bhujh.asia/arts/561976.Doc

原标题：本地简易配置中心动态管理
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.2bhujh.asia/arts/421025.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.2bhujh.asia/arts/183806.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.2bhujh.asia/arts/934725.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.2bhujh.asia/arts/125836.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.2bhujh.asia/arts/189731.Doc

原标题：golang redis 地理位置 geo 使用
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.2bhujh.asia/arts/488383.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/852492.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.2bhujh.asia/arts/228133.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计最小权限原则落地实践
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.2bhujh.asia/arts/921787.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.2bhujh.asia/arts/079462.Doc

原标题：golang 系统设计技术方案文档模板参考
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/885324.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.2bhujh.asia/arts/164213.Doc

原标题：golang context 上下文传参讲解
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.2bhujh.asia/arts/741066.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.2bhujh.asia/arts/711376.Doc

原标题：Docker 网络模式容器互通设置
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.2bhujh.asia/arts/815384.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.2bhujh.asia/arts/484216.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.2bhujh.asia/arts/204327.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.2bhujh.asia/arts/300338.Doc

原标题：golang 时间时区处理避坑指南
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.2bhujh.asia/arts/200946.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.2bhujh.asia/arts/302794.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.2bhujh.asia/arts/638725.Doc

原标题：golang redis 缓存预热实现思路
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.2bhujh.asia/arts/429895.Doc

原标题：golang elasticsearch 索引设计思路
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.2bhujh.asia/arts/013548.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.2bhujh.asia/arts/477947.Doc

原标题：golang mysql 慢查询日志开启分析
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.2bhujh.asia/arts/451728.Doc

原标题：时间同步修复令牌提前过期
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.2bhujh.asia/arts/887722.Doc

原标题：golang 简单爬虫请求防封禁
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.2bhujh.asia/arts/150310.Doc

原标题：golang github actions 多平台构建
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.2bhujh.asia/arts/930391.Doc

原标题：Redis 分布式锁高并发安全实现
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.2bhujh.asia/arts/411987.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.2bhujh.asia/arts/129524.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.2bhujh.asia/arts/797549.Doc

原标题：项目目录结构规范化最佳实践
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.2bhujh.asia/arts/411328.Doc

原标题：数据库排序规则统一结果一致
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.2bhujh.asia/arts/630559.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.2bhujh.asia/arts/885390.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.2bhujh.asia/arts/112073.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.2bhujh.asia/arts/778091.Doc

原标题：零基础理解前后端简单交互流程
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.2bhujh.asia/arts/163617.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.2bhujh.asia/arts/481370.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.2bhujh.asia/arts/667824.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.2bhujh.asia/arts/580754.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.2bhujh.asia/arts/376962.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.2bhujh.asia/arts/352903.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/344762.Doc

原标题：golang 系统设计参数校验统一处理方案
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.2bhujh.asia/arts/666925.Doc

原标题：golang redis 过期 key 监听业务
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.2bhujh.asia/arts/921896.Doc

原标题：react 状态管理方案选型对比
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.2bhujh.asia/arts/411579.Doc

原标题：HTTPS 证书过期更新操作
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.2bhujh.asia/arts/823922.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.2bhujh.asia/arts/475252.Doc

三、实战开发｜Practice
原标题：golang 系统设计数据库死锁分析规避
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.2bhujh.asia/arts/396285.Doc

原标题：golang git 提交信息规范校验
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.2bhujh.asia/arts/637065.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.2bhujh.asia/arts/748781.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.2bhujh.asia/arts/866787.Doc

原标题：golang mongodb 分页性能优化技巧
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.2bhujh.asia/arts/186980.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.2bhujh.asia/arts/674981.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.2bhujh.asia/arts/999766.Doc

原标题：本地运行正常线上报错排查
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.2bhujh.asia/arts/235738.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.2bhujh.asia/arts/429658.Doc

原标题：数据库排序规则统一结果一致
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.2bhujh.asia/arts/969644.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.2bhujh.asia/arts/607401.Doc

原标题：Docker 网络模式容器互通设置
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.2bhujh.asia/arts/666732.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.2bhujh.asia/arts/285299.Doc

原标题：代码模块化组件化拆分思路
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.2bhujh.asia/arts/067422.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.2bhujh.asia/arts/323236.Doc

原标题：Git commit 钩子提交规范校验
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.2bhujh.asia/arts/996105.Doc

原标题：全平台系统环境变量配置
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.2bhujh.asia/arts/226429.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.2bhujh.asia/arts/845257.Doc

原标题：批量异步处理系统业务落地
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.2bhujh.asia/arts/082517.Doc

原标题：golang docker 部署 kafka 本地调试
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/337306.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.2bhujh.asia/arts/440484.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.2bhujh.asia/arts/885173.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.2bhujh.asia/arts/033269.Doc

原标题：代码模块化组件化拆分思路
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.2bhujh.asia/arts/340295.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.2bhujh.asia/arts/505102.Doc

原标题：golang 系统设计消息消费 offset 管理策略
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.2bhujh.asia/arts/852295.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.2bhujh.asia/arts/004061.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.2bhujh.asia/arts/788754.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.2bhujh.asia/arts/199758.Doc

原标题：golang redis 五种数据结构实战
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.2bhujh.asia/arts/862736.Doc

原标题：快速上手阅读开源项目源码的入门思路
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.2bhujh.asia/arts/426882.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.2bhujh.asia/arts/788628.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.2bhujh.asia/arts/883521.Doc

原标题：程序预加载加快服务启动速度
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.2bhujh.asia/arts/088728.Doc

原标题：golang 跨域处理中间件编写
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.2bhujh.asia/arts/275491.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.2bhujh.asia/arts/235281.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.2bhujh.asia/arts/889433.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.2bhujh.asia/arts/778606.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.2bhujh.asia/arts/041951.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.2bhujh.asia/arts/222276.Doc

四、架构设计｜Architecture
原标题：golang k8s rbac 权限控制配置示例
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.2bhujh.asia/arts/806051.Doc

原标题：golang redis 锁超时业务处理
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.2bhujh.asia/arts/556227.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.2bhujh.asia/arts/412659.Doc

原标题：API 接口调试与异常处理实战
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.2bhujh.asia/arts/156369.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.2bhujh.asia/arts/560083.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/036421.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.2bhujh.asia/arts/451932.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.2bhujh.asia/arts/370258.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.2bhujh.asia/arts/347340.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.2bhujh.asia/arts/630811.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.2bhujh.asia/arts/718162.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.2bhujh.asia/arts/165798.Doc

原标题：TCP 心跳检测清理僵死连接
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.2bhujh.asia/arts/204625.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.2bhujh.asia/arts/535688.Doc

原标题：多规则数据脱敏组件开发
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.2bhujh.asia/arts/425866.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.2bhujh.asia/arts/818406.Doc

原标题：项目脚手架模板生成工具
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.2bhujh.asia/arts/993786.Doc

原标题：nodejs 跨域中间件配置细节
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.2bhujh.asia/arts/770642.Doc

?
