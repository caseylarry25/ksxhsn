最新前沿技术资讯

一、入门教程｜Getting Started
原标题：避坑：请求未设置read超时无限挂起连接
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.o11oko.asia/blog/456560.Doc

原标题：golang 告警推送钉钉机器人实现
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.o11oko.asia/blog/958770.Doc

原标题：golang http client 连接池调优
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://book.o11oko.asia/blog/723948.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://book.o11oko.asia/blog/678679.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.o11oko.asia/blog/601328.Doc

原标题：golang 系统设计最小权限原则落地实践
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.o11oko.asia/blog/937117.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.o11oko.asia/blog/082245.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.o11oko.asia/blog/904145.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://book.o11oko.asia/blog/335559.Doc

原标题：程序信号中断退出处理逻辑
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.o11oko.asia/blog/206016.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.o11oko.asia/blog/759266.Doc

原标题：数据库事务 ACID 原理讲解
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.o11oko.asia/blog/232985.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://book.o11oko.asia/blog/868995.Doc

原标题：golang 系统设计开源项目协作流程梳理
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.o11oko.asia/blog/664388.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.o11oko.asia/blog/632069.Doc

原标题：golang net/http 超时全套配置
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.o11oko.asia/blog/542263.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.o11oko.asia/blog/238126.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.o11oko.asia/blog/745479.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.o11oko.asia/blog/393274.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.o11oko.asia/blog/451245.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.o11oko.asia/blog/605180.Doc

原标题：golang docker 部署 kafka 本地调试
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.o11oko.asia/blog/464448.Doc

原标题：golang 布隆过滤器实现去重
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.o11oko.asia/blog/911513.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.o11oko.asia/blog/026039.Doc

原标题：golang http client 连接池调优
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.o11oko.asia/blog/408064.Doc

原标题：从零编写简易 CLI 命令行工具
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.o11oko.asia/blog/158232.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.o11oko.asia/blog/465971.Doc

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.o11oko.asia/blog/774536.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.o11oko.asia/blog/266706.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://book.o11oko.asia/blog/393382.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.o11oko.asia/blog/650894.Doc

原标题：DevOps：日志标准输出容器日志收集方案
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.o11oko.asia/blog/842950.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.o11oko.asia/blog/667048.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.o11oko.asia/blog/660477.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.o11oko.asia/blog/135029.Doc

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.o11oko.asia/blog/336063.Doc

原标题：golang prometheus histogram 指标
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.o11oko.asia/blog/744740.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.o11oko.asia/blog/932712.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.o11oko.asia/blog/193031.Doc

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.o11oko.asia/blog/715809.Doc


二、踩坑排错｜Troubleshooting
原标题：golang docker 镜像构建最佳实践
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.o11oko.asia/blog/209850.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.o11oko.asia/blog/698877.Doc

原标题：golang 互斥锁读写锁并发安全
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.o11oko.asia/blog/717044.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://book.o11oko.asia/blog/678281.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.o11oko.asia/blog/123919.Doc

原标题：部署实践：告警收敛避免告警风暴配置
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.o11oko.asia/blog/099955.Doc

原标题：golang redis 发布订阅简单示例
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.o11oko.asia/blog/407763.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.o11oko.asia/blog/367107.Doc

原标题：内存广播本地进程消息通知
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.o11oko.asia/blog/271439.Doc

原标题：golang 系统设计分布式锁选型对比
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.o11oko.asia/blog/337104.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.o11oko.asia/blog/829358.Doc

原标题：项目脚手架模板生成工具
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.o11oko.asia/blog/419054.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.o11oko.asia/blog/303303.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.o11oko.asia/blog/728437.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.o11oko.asia/blog/482154.Doc

原标题：批量异步处理系统业务落地
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://book.o11oko.asia/blog/663646.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://book.o11oko.asia/blog/614799.Doc

原标题：前端错误监控上报系统搭建
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.o11oko.asia/blog/484917.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.o11oko.asia/blog/599202.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.o11oko.asia/blog/275938.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.o11oko.asia/blog/341878.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.o11oko.asia/blog/722733.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.o11oko.asia/blog/048668.Doc

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.o11oko.asia/blog/018013.Doc

原标题：golang mysql 字符集排序规则设置
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.o11oko.asia/blog/048374.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.o11oko.asia/blog/537006.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.o11oko.asia/blog/964309.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.o11oko.asia/blog/492874.Doc

原标题：golang k8s helm chart 简单编写
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.o11oko.asia/blog/043660.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://book.o11oko.asia/blog/824223.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.o11oko.asia/blog/677360.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.o11oko.asia/blog/829004.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.o11oko.asia/blog/267334.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.o11oko.asia/blog/162251.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.o11oko.asia/blog/579106.Doc

原标题：业务错误码体系设计方案
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.o11oko.asia/blog/678555.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.o11oko.asia/blog/670968.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.o11oko.asia/blog/756114.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.o11oko.asia/blog/757331.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.o11oko.asia/blog/773205.Doc

三、实战开发｜Practice
原标题：文件描述符优化进程卡死修复
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.o11oko.asia/blog/789588.Doc

原标题：golang 参数校验业务接口处理
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://book.o11oko.asia/blog/616500.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.o11oko.asia/blog/763639.Doc

原标题：golang mongodb 文档结构设计原则
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.o11oko.asia/blog/219565.Doc

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.o11oko.asia/blog/829102.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.o11oko.asia/blog/339057.Doc

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.o11oko.asia/blog/436229.Doc

原标题：golang gin 静态资源访问配置
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.o11oko.asia/blog/486095.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.o11oko.asia/blog/799652.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.o11oko.asia/blog/308418.Doc

原标题：golang k8s liveness readiness 探针
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.o11oko.asia/blog/891755.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.o11oko.asia/blog/843465.Doc

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://book.o11oko.asia/blog/593170.Doc

原标题：慢查询分析索引调优数据库实战
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.o11oko.asia/blog/737087.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.o11oko.asia/blog/557453.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.o11oko.asia/blog/726579.Doc

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.o11oko.asia/blog/923374.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.o11oko.asia/blog/920241.Doc

原标题：浏览器内存泄漏排查前端页面
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.o11oko.asia/blog/634335.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.o11oko.asia/blog/536631.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.o11oko.asia/blog/963537.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.o11oko.asia/blog/229334.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.o11oko.asia/blog/605183.Doc

原标题：golang redis 批量 pipeline 实践
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.o11oko.asia/blog/264701.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.o11oko.asia/blog/386106.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.o11oko.asia/blog/493921.Doc

原标题：golang 熔断降级简易组件开发
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.o11oko.asia/blog/786143.Doc

原标题：容器软链接文件权限修复
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.o11oko.asia/blog/312811.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.o11oko.asia/blog/708650.Doc

原标题：前端大文件分片上传完整方案
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.o11oko.asia/blog/496149.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.o11oko.asia/blog/630291.Doc

原标题：golang 系统设计容量评估简单方法论
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.o11oko.asia/blog/191193.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.o11oko.asia/blog/290177.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.o11oko.asia/blog/189952.Doc

原标题：golang makefile 自动化构建脚本
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.o11oko.asia/blog/769215.Doc

原标题：分布式事务最终一致性实现
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.o11oko.asia/blog/596629.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.o11oko.asia/blog/331577.Doc

原标题：golang 项目 go mod 依赖管理
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.o11oko.asia/blog/789252.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.o11oko.asia/blog/060385.Doc

原标题：golang redis 过期 key 监听业务
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.o11oko.asia/blog/712999.Doc

四、架构设计｜Architecture
原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.o11oko.asia/blog/749622.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.o11oko.asia/blog/580021.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.o11oko.asia/blog/375256.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.o11oko.asia/blog/230303.Doc

原标题：golang prometheus counter gauge 使用
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.o11oko.asia/blog/596227.Doc

原标题：golang 批量任务协程控制防雪崩
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.o11oko.asia/blog/671710.Doc

原标题：手写简易 ORM 理解对象映射
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.o11oko.asia/blog/336187.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.o11oko.asia/blog/185924.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.o11oko.asia/blog/782702.Doc

原标题：golang mysql 存储过程简单使用
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.o11oko.asia/blog/525183.Doc

原标题：hosts 配置本地回环访问修复
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.o11oko.asia/blog/652449.Doc

原标题：前端错误监控上报系统搭建
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://book.o11oko.asia/blog/531033.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.o11oko.asia/blog/278290.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.o11oko.asia/blog/907950.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.o11oko.asia/blog/186579.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.o11oko.asia/blog/452842.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.o11oko.asia/blog/770115.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.o11oko.asia/blog/596808.Doc

?
