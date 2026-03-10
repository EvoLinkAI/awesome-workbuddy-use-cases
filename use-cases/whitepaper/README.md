# WorkBuddy Use Case Whitepaper

> **100 fully-detailed AI Agent cases** with structured tables: Case Name / Scenario Description / Core Agent Capabilities

**Language / 语言:** English | [简体中文](README.zh-CN.md)

[← Back to main README](../../README.md)

---

## Part 1: Office Collaboration · 办公协作篇

*Office scenarios are about restructuring information flows. WorkBuddy connects local files, internal networks, and third-party SaaS into fully automated pipelines.*

*办公场景的本质是信息流的流转与处理。WorkBuddy 通过打通本地文件、企业内网与第三方 SaaS，将碎片化办公转变为全自动流水线。*

### 1. Administration · 行政与流程管理 (Cases 01–10)

| Case · 案例 | Scenario · 场景描述 | Core Capabilities · Agent 核心能力 |
| :--- | :--- | :--- |
| **01. Smart Inbox Cleanup · 智能收件箱清理** | Real-time email monitoring, semantic auto-classification of attachments (contracts/invoices), build tiered local directory archiving, generate cleanup report. 实时监控邮件，根据语义自动分类附件（合同/发票）并建立本地分级目录归档，生成清理报告。 | **Local File Read/Write · 本地文件读写**、OAuth2 Auth · OAuth2 鉴权、Semantic Classification Engine · 语义分类引擎。 |
| **02. Full-Auto Meeting Loop · 全自动会议闭环** | Auto-login to meeting software and record, transcribe locally with Whisper, extract action items, sync to Feishu/DingTalk calendar. 自动登录会议软件并录制，利用本地 Whisper 转写，提取待办事项并同步至飞书/钉钉日程。 | **Browser Automation · 浏览器自动化**、Shell Script Execution (A/V tools) · Shell 脚本执行（音视频工具）、API Integration · API 集成。 |
| **03. Multi-Platform Calendar Sync · 多平台日历同步** | Scan emails, WeChat, and DingTalk for time info, detect conflicts between Apple and Google Calendar, deduplicate and write. 扫描邮件、微信、钉钉通知中的时间信息，检测 Apple 与 Google Calendar 冲突并执行去重写入。 | **Multi-source Data Scraping · 多源数据抓取**、Conflict Detection Logic · 冲突检测逻辑、Persistent Task Running · 持久化任务运行。 |
| **04. Smart Travel Check-in · 智能差旅值机** | Monitor airline website, at the moment check-in opens, auto-select seat based on user preference (window/aisle) and download boarding pass. 监控航司官网，在开放值机瞬间根据用户偏好（靠窗/过道）自主选座并下载登机牌。 | **Browser Click Control · 浏览器点击控制**、Scheduled Task · 定时任务、Exception Handling · 异常处理机制。 |
| **05. Office Supplies Auto-Reorder · 办公用品自动补货** | Read local inventory Markdown, when stock is low, auto-compare prices on JD Enterprise, add to cart, send approval notification. 读取本地库存 Markdown 库，余量不足时自主在京东企业购比价、加购并发送审批通知。 | **Local File Monitoring · 本地文件监控**、Browser Automation (price compare/cart) · 浏览器自动化（比价/加购）、Threshold Trigger · 阈值触发。 |
| **06. File System Semantic Reorganization · 文件系统语义重组** | Periodically scan disordered folders, execute system-level `mv` commands by file content (not extension), build logically rigorous knowledge directory. 定期扫描乱序文件夹，按文件内容（而非后缀）执行系统级 `mv` 命令，建立逻辑严密的知识目录。 | **Shell Script Execution · Shell 脚本执行**、Semantic Clustering Analysis · 语义聚类分析、System File Operations · 系统文件操作。 |
| **07. Visitor Appointment Automation · 访客预约自动化** | Recognize visitor email requests, generate QR code pass and Gaode route guide, sync to front desk system and host calendar. 识别访客邮件请求，生成二维码通行证与高德路线指南，同步至前台系统和接待人日历。 | **Shell Call (QR generation) · Shell 调用（二维码生成）**、Multi-step Workflow Orchestration · 多步骤工作流编排。 |
| **08. Team Building Planning & Booking · 团建方案策划预订** | Based on team dietary preference doc, search restaurants on Meituan comparing reviews, simulate booking submission or compile voting options. 根据团队饮食偏好文档，在美团检索餐厅并对比评价，模拟提交预订请求或汇总投票方案。 | **Browser Scraping · 浏览器抓取**、User Profile Analysis · 用户画像分析、Multi-option Evaluation · 多方案评估。 |
| **09. Repair Ticket Auto-Dispatch · 报修工单自动派发** | Monitor IM channel, recognize "malfunction" descriptions, extract location and type, auto-fill form in internal work order system to assign ops. 监听 IM 频道，识别"故障"描述，提取位置与类型，自动填表登录内网工单系统指派运维。 | **Message Monitoring · 消息监听**、Browser Automation Form Fill · 浏览器自动化表单填充、Key Info Extraction · 关键信息提取。 |
| **10. Daily Morning Brief Push · 每日早间简报推送** | 8am auto-execute: aggregate weather, industry news, today's Todo, stock market open; push Markdown brief via Telegram. 8 点自动执行：聚合天气、行业新闻、今日 Todo 及股市开盘，通过 Telegram 推送 Markdown 简报。 | **Multi-channel Data Aggregation · 多渠道数据聚合**、Info Compression & Formatting · 信息压缩格式化、Scheduled Trigger · 定时触发。 |

### 2. Finance, Legal & HR · 财务、法务与人力资源 (Cases 11–20)

| Case · 案例 | Scenario · 场景描述 | Core Capabilities · Agent 核心能力 |
| :--- | :--- | :--- |
| **11. Invoice OCR Auto-Reimbursement · 发票 OCR 自动报销** | Monitor scan folder, call local OCR to extract data, log into reimbursement system and fill form, generate Excel expense table. 监控扫描件文件夹，调用本地 OCR 提取数据并登录报销系统填报，最后生成 Excel 支出表。 | **File System Monitoring · 文件系统监听**、Shell Script (OCR call) · Shell 脚本（OCR 调用）、Browser Form Fill · 浏览器填表。 |
| **12. Resume Smart Pre-screening · 简历智能初筛** | Log into Boss Zhipin/LinkedIn to scrape resumes, match against local JD doc for scoring, rename and download. 登录 Boss 直聘/LinkedIn 抓取简历，根据本地 JD 文档进行匹配度打分并重命名下载。 | **Browser Automation · 浏览器自动化**、LLM Semantic Matching · LLM 语义匹配、Local File Organization · 本地文件组织。 |
| **13. Contract Compliance Auto-Comparison · 合同合规性自动对比** | Receive counterparty's revision, use local `diff` and semantic comparison to highlight key clause change risks. 接收对方回传稿，通过执行本地 `diff` 与语义比对，利用高亮标出关键条款修改风险。 | **Local File Read/Write · 本地文件读写**、Shell Code Comparison · Shell 代码比对、Semantic Risk Analysis · 语义风险分析。 |
| **14. Payslip Multi-channel Distribution · 工资条多渠道分发** | Read encrypted payroll Excel, match contact info, send 1-to-1 messages via iMessage/email/DM and log. 读取加密工资 Excel，匹配联系方式后通过 iMessage/邮件/私信发送 1对1 消息并记录日志。 | **Local Sensitive Data Processing · 本地敏感数据处理**、Multi-channel API Collaboration · 多渠道 API 协作、Security Encryption · 安全性加密。 |
| **15. Government Portal Auto-Query · 政务系统自动化查询** | Scheduled login to government portal with credentials, screenshot payment records, download PDF to sync to Obsidian library. 定时使用凭据登录政府政务系统，截取缴费记录图像，下载 PDF 同步至 Obsidian 库。 | **Browser Complex Login · 浏览器复杂登录**、Screenshot Function · 截图功能、Local File Sync · 本地文件同步。 |
| **16. Onboarding Process Automation · 入职流程自动化** | Input new employee info, auto-create email, invite to groups, package and send role handbook and installation packages. 输入新员工信息，自动开通邮箱、邀请进群、打包发送岗位手册与安装包。 | **Multi-system API Auth · 多系统 API 鉴权**、File Packaging · 文件打包、Process-based Step Decomposition · 流程化步骤拆解。 |
| **17. Tax Policy Auto-Capture · 税务政策自动捕捉** | Monitor tax bureau website, on finding new announcement with "incentive/subsidy" keywords, summarize company impact and email CC to supervisor. 监控税局官网，发现含"优惠/补贴"关键词的新公告，总结对公司的影响并邮件抄送主管。 | **Web Monitoring (Change Detection) · 网页监控（变更检测）**、Semantic Analysis · 语义分析、Email Automation · 邮件自动化。 |
| **18. Expense Compliance Monitoring · 费用合规性监控** | Compare rideshare trip records with HR overtime records, flag anomalies in Excel, draft inquiry email. 比对打车平台行程单时间与考勤系统加班记录，在 Excel 中标记异常项并起草咨询邮件。 | **Cross-source Data Correlation · 跨源数据关联**、Logic Rule Verification · 逻辑规则校验、Local Document Update · 本地文档更新。 |
| **19. IP Library Maintenance · 知识产权库维护** | Search competitor keywords on Google Patents, auto-download PDF specs, build local index by technology dimension. 在 Google Patents 检索竞品关键词，自动下载 PDF 说明书并按技术维度建立本地索引。 | **File Download & Scraping · 文件下载与抓取**、Local Index Library Maintenance · 本地索引库维护、Keyword Filtering · 关键词过滤。 |
| **20. License Expiry Alert · 证照过期预警** | Scan license folder, OCR-read validity dates, build reminder queue in local DB, publish group task 3 months ahead. 扫描证照文件夹，利用 OCR 读取有效期并在本地数据库建立提醒队列，提前 3 个月发布群任务。 | **Local File OCR · 本地文件 OCR**、Scheduled Reminder Logic · 定时提醒逻辑、IM Tool Integration · 即时通讯工具集成。 |

### 3. R&D & Ops · 技术研发与运维 (Cases 21–30)

| Case · 案例 | Scenario · 场景描述 | Core Capabilities · Agent 核心能力 |
| :--- | :--- | :--- |
| **21. Autonomous Code Bug Fix · 自主代码 Bug 修复** | Monitor Sentry error logs, auto-clone codebase, analyze stack trace, modify code, run local tests, submit PR. 监听 Sentry 错误日志，自动克隆代码库，分析堆栈、修改代码并执行本地测试后提交 PR。 | **Git/Shell Deep Execution · Git/Shell 深度执行**、Automated Testing · 自动化测试、GitHub API Coordination · GitHub API 协同。 |
| **22. Automated Environment Setup · 自动化环境搭建** | Receive deployment instruction, auto-execute Shell commands to install dependencies, configure Docker and env variables per `README.md`. 接收部署指令，根据 `README.md` 自动执行 Shell 命令安装依赖、配置 Docker 及环境变量。 | **Environment Dependency Parsing · 环境依赖解析**、Local Config File Read/Write · 本地配置文件读写、Command Sequence Execution · 命令序列执行。 |
| **23. Distributed Log Monitoring · 分布式日志监控** | Remote-connect to multiple servers, stream-read logs. Detect OOM or similar errors, capture context, alert via Telegram. 远程连接多台服务器，流式读取日志。检测到 OOM 等错误时截取上下文并通过 Telegram 告警。 | **Remote SSH Connection · 远程 SSH 连接**、Streaming Text Processing · 流式文本处理、Real-time Push Notification · 实时消息推送。 |
| **24. GitHub PR Auto-Review · GitHub PR 自动评审** | Run static scan tools, analyze change logic; if complexity too high or vulnerability found, auto-comment suggestions on GitHub. 运行静态扫描工具，分析变更逻辑，若发现复杂度过高或漏洞，自动在 GitHub 评论区给建议。 | **Local Scan Tool Execution · 本地扫描工具执行**、Logic Analysis · 逻辑分析、GitHub API Monitoring · GitHub API 监听。 |
| **25. API Docs Auto-Generation · API 文档自动生成** | Monitor local codebase interface definitions, auto-run Swagger tool on change to generate new docs, sync to company Wiki. 监控本地代码仓库接口定义，变更时自动运行 Swagger 工具生成新文档并同步至公司 Wiki。 | **File Monitoring · 文件监控**、Shell Command Call · Shell 命令调用、Cross-system Data Sync · 跨系统数据同步。 |
| **26. Automated Performance Regression Test · 自动化性能回归测试** | Before code merge, trigger Headless Browser to run Lighthouse script, record metrics; if performance drops, open Jira ticket. 代码合并前触发 Headless Browser 运行 Lighthouse 脚本，记录指标，若性能下降则在 Jira 开单。 | **Performance Probing · 性能探测**、Local Data Analysis · 本地数据分析、Jira API Linkage · Jira API 联动。 |
| **27. Database Backup & Encryption · 数据库备份与加密** | Execute SQL export at midnight, complete AES encryption, then upload file to offsite cloud storage via browser or API. 凌晨执行 SQL 导出，完成 AES 加密后利用浏览器或 API 将文件上传至异地云存储。 | **Scheduled Task · 定时任务**、Shell Tools (DB/encryption) · Shell 工具（DB/加密）、File Auto-upload · 文件自动化上传。 |
| **28. Security Vulnerability Scan Agent · 安全漏洞扫描代理** | Periodically run Nmap or Nessus probe on internal IPs, parse reports; immediately lock machine and alert on high-risk ports. 定期对内网 IP 执行 Nmap 或 Nessus 探测，解析报告并在发现高危端口时立即锁定机器及告警。 | **Network Tool Execution · 网络工具执行**、Data Parsing · 数据解析、Security Policy Judgment · 安全策略判断。 |
| **29. Tech Selection Researcher · 技术选型研究员** | Scrape GitHub Stars and Stack Overflow volume, write Python scripts for performance tests, output comparative report. 爬取 GitHub Stars、Stack Overflow 讨论量，编写 Python 脚本进行性能测试并输出报告。 | **Multi-source Data Scraping · 多源数据抓取**、Local Benchmark Code Execution · 本地基准测试代码执行、Comprehensive Analysis · 综合分析。 |
| **30. Cluster Smart Auto-scaling · 集群智能扩缩容** | Read Prometheus metrics, execute `kubectl scale` to adjust replicas when CPU exceeds threshold, send confirmation. 读取 Prometheus 指标，当 CPU 超过阈值时执行 `kubectl scale` 调整副本数并发送确认。 | **API Monitoring · API 监控**、Kubectl Command Execution · Kubectl 命令执行、Closed-loop Feedback Control · 闭环反馈控制。 |

### 4. Sales & Customer Success · 市场销售与客户成功 (Cases 31–40)

| Case · 案例 | Scenario · 场景描述 | Core Capabilities · Agent 核心能力 |
| :--- | :--- | :--- |
| **31. Prospect Web Harvesting · 潜在客户全网搜寻** | Search by industry keywords on LinkedIn/Crunchbase, filter existing CRM data, compile to Excel. 根据行业词在 LinkedIn/Crunchbase 抓取线索，过滤 CRM 已有数据并汇总至 Excel。 | **Browser Crawler Automation · 浏览器爬虫自动化**、Data Cleaning · 数据清洗、Local File Write · 本地文件写入。 |
| **32. CRM Auto-Sync · CRM 自动同步** | Scan sales correspondence emails, recognize "quote/signing intent," sync conversation summary to Salesforce or internal system. 扫描销售往来邮件，识别"报价/签约意向"后将沟通摘要同步至 Salesforce 或内部系统。 | **Email Semantic Understanding · 邮件语义理解**、CRM API Integration · CRM API 对接、Multi-step Automation · 多步骤自动化。 |
| **33. Competitor Real-time Price Monitoring · 竞品价格实时监控** | Hourly patrol of e-commerce platforms, detect fluctuations, screenshot and extract price, send trend analysis chart to sales group. 每小时巡检电商平台，发现波动则截取屏幕提取价格，在销售群发送动态分析图。 | **Scheduled Patrol/Screenshot · 定时巡检/截图**、OCR Extraction · OCR 提取、IM Integration · 即时通讯集成。 |
| **34. Smart Customer Service L2 Support · 智能客服二级支撑** | Handle complex technical queries, auto-semantic-search solutions in local PDF manuals, draft reply for human confirmation. 处理复杂技术咨询，自动在本地 PDF 手册中语义检索方案，起草回复稿供人工确认。 | **Local RAG Retrieval · 本地 RAG 检索**、Semantic Analysis · 语义分析、Draft Generation · 草稿生成。 |
| **35. Satisfaction Survey Automation · 满意度调查自动化** | Auto-send survey email after project close, track response; if no reply within a week, auto-send reminder at non-intrusive time. 结项后自动发送调研邮件并跟踪，若一周未回则在非干扰时间自动发送提醒。 | **State Machine Monitoring · 状态机监听**、Email Automation · 邮件自动化、Delayed Task Management · 延时任务管理。 |
| **36. Sales Weekly Report Auto-Generation · 销售周报自动生成** | Pull performance data from ERP, combine with sales manager's local Notion notes, auto-generate PPT draft with charts. 从 ERP 拉取业绩数据，结合销售经理的本地 Notion 记录，自动生成带图表的 PPT 初稿。 | **ERP Data Collection · ERP 数据采集**、Chart Generation Script · 图表生成脚本、PPT File Processing · PPT 文件处理。 |
| **37. Social Media Sentiment Monitoring · 社交媒体舆情监控** | Real-time monitor brand keywords, sentiment-analyze positive/negative. If negative spike, wake PR lead via call/IM. 实时监听品牌词，情感分析判断正负评。若负评激增，通过电话/IM 唤醒公关负责人。 | **Social Media Scraping · 社交媒体抓取**、Sentiment Modeling · 情感建模、Multi-level Alert · 多级预警。 |
| **38. Ad Campaign Performance Tracking · 广告投放效果跟踪** | Log into platforms to export spend and conversion data, merge to Excel, calculate ROI and generate dashboard. 登录各平台导出消耗与转化数据，合并到 Excel 中并计算 ROI 生成仪表盘。 | **Simulated Login Download · 模拟登录下载**、Multi-table Merge · 多表合并、Pandas Data Processing · Pandas 数据处理。 |
| **39. Event Registration Auto-Audit · 活动报名自动审核** | Receive registration forms, audit by rules, generate e-tickets to WeChat, update attendee list. 接收报名表单，按规则审核并生成电子门票发至微信，同步更新参会名单。 | **Form Monitoring · 表单监听**、Rule Verification · 规则校验、Ticketing API Integration · 票务 API 集成。 |
| **40. Meeting Material Preparation · 会议物料准备** | Calculate handbook/gift quantities based on final attendee count, auto-send inquiry emails to suppliers and track replies. 根据最终参会人数计算手册/礼品量，自动向供应商发送询价邮件并跟踪回复。 | **Data Calculation · 数据计算**、Email Automation Template · 邮件自动化模板、Task Tracking · 任务追踪。 |

### 5. Data & Research · 数据处理与战略研究 (Cases 41–50)

| Case · 案例 | Scenario · 场景描述 | Core Capabilities · Agent 核心能力 |
| :--- | :--- | :--- |
| **41. Financial Report Auto-Analysis · 财报数据自动分析** | Download annual PDF reports, extract balance sheet key figures, calculate gross margin and turnover, archive. 下载年度 PDF 财报，提取资产负债表关键数值，计算毛利、周转率等指标并存档。 | **PDF Data Structuring · PDF 数据结构化**、Browser Download · 浏览器下载、Local Calculation Script · 本地计算脚本。 |
| **42. Industry Trend Report Synthesis · 行业趋势研报合成** | Aggregate info from 10 vertical media, deduplicate, translate, generate deep research report with citations via LLM. 整合 10 个垂直媒体资讯，去重、翻译并基于 LLM 生成带出处的深度研报。 | **Multi-source Crawler Aggregation · 多源爬虫聚合**、Text Dedup & Translation · 文本去重翻译、Research Logic Orchestration · 研报逻辑编排。 |
| **43. Database Anomaly Value Cleaning · 数据库异常值清洗** | Scan CSV/SQL data, recognize format errors or extreme outliers, run correction script, generate cleaning log. 扫描 CSV/SQL 数据，识别格式错误或异常极端值，调用脚本修正并生成清洗日志。 | **DB/File Read/Write · DB/文件读写**、Data Verification · 数据校验、Shell Script Execution · Shell 脚本执行。 |
| **44. Automated Translation Workflow · 自动化翻译工作流** | Monitor local "to-translate" folder, auto-translate Markdown/PDF using specialized model while preserving original layout. 监控本地"待翻译"文件夹，自动调用专业模型翻译 Markdown/PDF 并保持原版排版。 | **File System Monitoring · 文件系统监控**、Format Preservation Algorithm · 格式保持算法、Translation API Auth · 翻译 API 鉴权。 |
| **45. Project Progress Tracking Agent · 项目进度追踪代理** | Read multi-project Gantt charts, identify "at risk" items, auto-ask responsible persons for updates and compile. 读取多项目甘特图，识别"逾期"风险，自动向负责人询问进展并汇总。 | **Management Tool Sync · 管理工具同步**、Logic Judgment · 逻辑判断、IM Interaction · 即时通讯交互。 |
| **46. Stock Real-time Dashboard · 股票实时看板** | Monitor stock pool, combine news and K-line technicals, push analysis alert to Discord on deviation. 监控股票池，结合新闻面与技术面 K 线，发生偏离时在 Discord 推送分析预警。 | **Real-time Data Stream Processing · 实时数据流处理**、Technical Indicator Calculation · 技术指标计算、Comprehensive Evaluation · 综合评估。 |
| **47. Academic Paper Tracking · 学术论文追踪** | Search arXiv for new papers, download PDF, use LLM to generate 300-word abstract, categorize and store by field. 在 arXiv 检索新论文，下载 PDF 并利用 LLM 生成 300 字摘要并按领域分类存放。 | **Academic Site Search · 学术网站检索**、PDF Automation Processing · PDF 自动化处理、Summary Generation · 摘要生成。 |
| **48. Macro Indicator Monitoring · 宏观指标监控** | Collect CPI, PMI, exchange rates, compare with local historical database, generate trend charts, analyze potential business impact. 采集 CPI、PMI、汇率等数据，与本地历史库对比生成趋势图，分析对业务的潜在影响。 | **Multi-site Collection · 多站点采集**、Matplotlib Plotting · Matplotlib 绘图、Data Extrapolation · 数据推演。 |
| **49. BP Material Collection · BP 素材搜集** | Auto-search market size data, benchmark company fundraising stages, compile supporting data into structured "data source package." 自动搜寻市场规模数据、对标公司融资阶段，将支撑数据汇总成结构化"数据源包"。 | **Deep Search · 深度搜索**、Authenticity Comparison · 真伪比对、Structured Document Export · 文档结构化导出。 |
| **50. Knowledge Base Auto-Tagging · 知识库自动标签化** | Semantic scan of local Obsidian notes, auto-add tags, establish bidirectional links to build knowledge graph. 对本地 Obsidian 笔记进行语义扫描，自动添加 Tag 并建立双向链接构建知识图谱。 | **Local File Operations · 本地文件操作**、Semantic Modeling · 语义建模、Knowledge Graph Construction · 知识图谱构建。 |

---

## Part 2: Creative Domain · 创作领域篇

*Creative work is no longer just generation — it's asset management, tool coordination, and multi-modal output engineering.*

*创作不再是单一的生成，而是资产管理、工具协同与多模态输出的综合工程。*

### 6. Writing & Editing · 文字创作与编辑 (Cases 51–60)

| Case · 案例 | Scenario · 场景描述 | Core Capabilities · Agent 核心能力 |
| :--- | :--- | :--- |
| **51. Deep Topic Research Agent · 主题深度研报代理** | Autonomously search academic databases, download and read dozens of PDFs, produce a 5000-word synthesis. 自主检索学术数据库，下载并阅读数十份 PDF，完成 5000 字综述。 | **PDF Parsing · PDF 解析**、Long-flow Planning · 长流程规划、Information Synthesis · 信息合成。 |
| **52. E-book Auto-Publishing · 电子书自动出版** | Organize local Markdown into logical structure, call `Pandoc` to convert to EPUB/Kindle format. 将本地 Markdown 整理成逻辑结构，调用 `Pandoc` 转换为 EPUB/Kindle 格式。 | **Shell Script Execution · Shell 脚本执行**、Local File Organization · 本地文件组织、Format Conversion · 格式转换。 |
| **53. Citation Auto-Verification · 引用自动核查** | Scan paper draft, find missing sources online, generate BibTeX. 扫描论文草稿，在网上寻找缺失来源的原始出处并生成 BibTeX。 | **Browser Automation · 浏览器自动化**、Semantic Matching · 语义匹配、Literature Retrieval · 文献检索。 |
| **54. Multi-role Creative Debate · 多角色创意辩论** | Simulate multi-stance experts (logician, marketing manager) in local multi-round brainstorm debate, summarize conflicts. 模拟多立场专家（如逻辑学家、市场经理）在本地进行多轮构思辩论，总结冲突。 | **Multi-agent Collaboration · 多代理协作**、Long-flow Dialog Trajectory Recording · 长流程对话轨迹记录。 |
| **55. Fiction Logic Audit · 小说逻辑审计** | Traverse all branches of interactive fiction, detect logic dead-ends or character inconsistency. 遍历交互式小说所有分支，检测是否存在逻辑死循环或人设崩塌。 | **Graph DB Application · 图数据库应用**、Path Search Algorithm · 路径搜索算法、Local System Access · 本地系统访问。 |
| **56. SEO Competitor Analysis · SEO 竞争对手分析** | Monitor competitor rankings, analyze keyword density, directly modify local Markdown metadata. 监控竞品排位，分析其关键词密度，直接修改本地 Markdown 元数据。 | **Browser Monitoring · 浏览器监控**、API Semantic Analysis · API 语义分析、Local File Modification · 本地文件修改。 |
| **57. Global Literature Localization · 全球化文学适配** | During translation, auto-search and replace cultural references, units of measure, maintaining original layout via script. 翻译时自动搜索并替换文化梗、度量衡，并利用脚本保持原排版。 | **Cross-system Search · 跨系统搜索**、Long-flow Translation Loop · 长流程翻译闭环、Layout Regeneration · 排版重生成。 |
| **58. Creative Brief Generation · 创意简报生成** | Aggregate fragmented ideas from Telegram, generate next day's writing task list at midnight. 汇总 Telegram 中的碎片想法，每日凌晨生成第二天的写作任务清单。 | **IM Integration · IM 集成**、Semantic Classification · 语义归类、Task Planning · 任务规划。 |
| **59. Technical Docs Sync · 技术文档同步** | Monitor GitHub code changes; when interface changes, auto-rewrite corresponding usage guide. 监控 GitHub 代码变更，接口变化时自动重写对应的使用手册。 | **Git Integration · Git 集成**、Code Logic Understanding · 代码逻辑理解、Automated Writing · 自动化撰写。 |
| **60. Writing Style Transfer Engine · 文风迁移引擎** | Learn user's vocabulary habits from their work, deeply reshape new drafts to match personal style. 学习用户作品的用词习惯，对新草稿进行深度重塑以匹配个人风格。 | **Local Knowledge Base Learning · 本地知识库学习**、Style Vector Modeling · 风格向量建模、End-to-end Proofreading · 端到端校对。 |

### 7. Visual Art & Design · 视觉艺术与设计 (Cases 61–70)

| Case · 案例 | Scenario · 场景描述 | Core Capabilities · Agent 核心能力 |
| :--- | :--- | :--- |
| **61. Midjourney Batch Experiment · Midjourney 批量实验** | Generate 100 prompt variations, control Discord to generate images, visually review and archive best works. 生成 100 组提示词，操控 Discord 生成图像并视觉评审出最佳作品存档。 | **Web Control · Web 操控**、Visual Model Review · 视觉模型评审、Automated Classification · 自动化分类。 |
| **62. Brand Visual One-Click Adaptation · 品牌视觉一键适配** | Upload Logo, auto-apply it to Banner, business card, PPT, and other multi-size templates. 上传 Logo，自动将其应用到 Banner、名片、PPT 等多尺寸模板中。 | **Image Tool Call (ImageMagick) · 图像工具调用（ImageMagick）**、Scripted Compositing · 脚本化合成。 |
| **63. Asset Library Semantic Restructuring · 素材库语义重构** | Scan asset folder, recognize image colors and style, reorganize local folder structure by semantic tags. 扫描素材夹，识别图片配色与风格，按语义标签重组本地文件夹结构。 | **Local System Access · 本地系统访问**、AI Image Recognition · AI 识图、Automated Archiving · 自动化归档。 |
| **64. E-commerce Detail Page Generation · 电商详情页生成** | Scrape parameters, call drawing API to generate model images, composite detail pages with promotional text. 抓取参数，调用绘图 API 生成模特图，并合成带促销文字的详情页。 | **Cross-tool Coordination · 跨工具协同**、API Integration · API 集成、Local Compositing Script · 本地合成脚本。 |
| **65. Design Trend Report · 流行趋势报告** | Scrape popular works from Behance, extract color distribution, generate local `.ase` palette file. 从 Behance 抓取热门作品，提取色彩分布，生成本地 `.ase` 色板文件。 | **Automated Collection · 自动化采集**、Data Analysis · 数据分析、Asset File Generation · 资产文件生成。 |
| **66. Storyboard Sketch Colorization · 视频分镜草图上色** | Recognize hand-drawn sketches, auto-colorize and apply lighting based on text description. 识别手绘草图，根据文字描述自动进行局部上色与光影处理。 | **Edge Detection · 边缘检测**、Generative Model API · 生成模型 API、Long-flow Loop · 长流程闭环。 |
| **67. Copyright Image Risk Scan · 版权图片风险扫描** | Run reverse image search across web before publishing, assess copyright risk and suggest alternatives. 发布前执行全网以图搜图，判定版权风险并给出替代方案。 | **Reverse Search · 反向搜索**、Compliance Assessment · 合规性评估、Browser Automation · 浏览器自动化。 |
| **68. UI Design → Code · UI 设计稿转代码** | Scan Figma export image, recognize components, generate Tailwind CSS code. 扫描 Figma 导出图，识别组件并生成 Tailwind CSS 代码。 | **Visual Understanding · 视觉理解**、Code Generation · 代码生成、Local Preview · 本地预览。 |
| **69. Personalized Font Assistant · 个性化字体助手** | Learn user's handwriting characteristics, call scripts to generate installable TTF font file. 学习用户手写字特征，调用脚本生成可安装的 TTF 字体文件。 | **Specialized Tool Chain Call · 专用工具链调用**、Vectorization · 矢量化、Font Packaging · 字体打包。 |
| **70. 3D Material Auto-Matching · 3D 材质自动匹配** | Scan 3D model names, find matching material textures from cloud/local, complete association. 扫描 3D 模型名，在云端/本地寻找匹配材质贴图并完成关联。 | **Deep File System Operations · 文件系统深度操作**、Asset Association Automation · 资产关联自动化。 |

### 8. Audio & Video Production · 音视频制作 (Cases 71–80)

| Case · 案例 | Scenario · 场景描述 | Core Capabilities · Agent 核心能力 |
| :--- | :--- | :--- |
| **71. Short Video Remix Agent · 短视频混剪代理** | Based on rhythm, auto-find emotionally matching footage in library, execute beat-cut editing export. 根据节奏，自动在库中寻找匹配情绪的素材，执行卡点剪辑导出。 | **Shell (FFmpeg) · Shell (FFmpeg)**、Rhythm-aware Recognition · 节奏感知识别、Unattended Editing · 无人值守剪辑。 |
| **72. Podcast Post-production Expert · 播客后期专家** | Auto-remove "uh/ah" filler words, silent segments, balance volume and denoise. 自动移除"呃/啊"口癖、静音段，平衡音量并去噪。 | **Audio Processing Automation · 音频处理自动化**、Local Library Call · 本地库调用、Full Post-production Pipeline · 全流程后期。 |
| **73. Video Auto-Dubbing · 视频自动译制** | Extract subtitles, translate, synthesize AI voice, complete audio-visual alignment, export multi-language version. 提取字幕、翻译、合成 AI 语音并完成声画对齐导出多语种版。 | **Cross-platform API Collaboration · 跨平台 API 协作**、ASR/TTS Integration · ASR/TTS 整合、Long-flow Adaptation · 长流程适配。 |
| **74. Video Semantic Search · 视频语义搜索** | Ask "find a sunny ocean scene," Agent searches local library and locates to specific second. 询问"找一段阳光的大海"，Agent 搜索本地库并定位到具体秒数。 | **Local Metadata Management · 本地元数据管理**、Semantic Index · 语义索引、Shell Call · Shell 调用。 |
| **75. Thumbnail A/B Pressure Test · 封面压力测试** | Generate 5 style thumbnail variations, small-scale CTR test, feed back best result. 生成 5 种风格封面并小范围测试点击率，反馈最佳结果。 | **Browser Automation · 浏览器自动化**、A/B Testing · A/B 测试、Data Feedback · 数据反馈。 |
| **76. Smart Transition Suggestions · 智能转场建议** | Analyze video color trends, call scripts to add mask or light transition effects. 分析视频色彩趋势，调用脚本添加遮罩或光效转场。 | **Feature Analysis · 特征分析**、FFmpeg Filter Instruction Generation · FFmpeg 滤镜指令生成。 |
| **77. Highlight Moment Clipping · 高光时刻切片** | Scan live replay, combine with comment density to auto-cut 10 short video segments. 扫描直播回放，结合弹幕密度自动切出 10 段短视频。 | **Multi-dimensional Data Fusion · 多维数据融合**、Comment Scraping · 弹幕抓取、Value Interval Location · 价值区间定位。 |
| **78. Auto-generated Background Music · 自动化配乐生成** | Analyze video tone, call Suno to generate music, composite to background. 分析视频基调，调用 Suno 生成音乐并合成至背景。 | **Emotion Parameterization · 情绪参数化**、API Loop · API 闭环、Video Compositing · 视频合成。 |
| **79. Script vs Footage Comparison · 脚本与素材比对** | Read shooting plan and check local footage, remind of missing shots. 读取拍摄计划检查本地素材，提醒漏拍分镜。 | **Logic Comparison · 逻辑比对**、File Status Tracking · 文件状态追踪、Self-audit · 自主审计。 |
| **80. Video Duplicate Detection · 视频查重系统** | Before publishing, run fingerprint comparison across web to prevent demotion from high similarity rate. 发布前在全网进行指纹比对，防止因查重率过高限流。 | **Fingerprint Recognition · 指纹识别**、Browser Search · 浏览器搜索、Content Risk Control · 内容风控。 |

### 9. Social Media & Community Ops · 自媒体与社群运营 (Cases 81–90)

| Case · 案例 | Scenario · 场景描述 | Core Capabilities · Agent 核心能力 |
| :--- | :--- | :--- |
| **81. Multi-platform One-click Distribution · 多平台一键分发** | Auto-login to Xiaohongshu, Douyin, Zhihu, adapt dimensions and complete publishing. 自动登录小红书、抖音、知乎，适配尺寸并完成发布。 | **Browser Automation · 浏览器自动化**、Bypass API Limits · 绕过 API 限制、Form Upload · 填表上传。 |
| **82. Real-time PR Monitoring · 实时舆情公关** | Monitor comments; thank positive, explain negative, or escalate to human. 监控评论，正面感谢、负面回复解释或向人工预警。 | **Automated Monitoring · 自动化监控**、Semantic Recognition · 语义识别、Real-time Reply · 实时回复。 |
| **83. Trending Topic Content Creation · 热点自动洗稿** | Monitor Weibo hot search, on detection auto-scrape info and generate different style copy. 监控微博热搜，发现后自动抓取信息并生成不同风格文案。 | **Trending Capture · 热点捕捉**、Copy Generation · 文案生成、No-intervention Publishing · 无干预发布。 |
| **84. Community Engagement Expert · 社群活跃专家** | Launch polls, Q&A, or giveaways in Discord/TG groups. 在 Discord/TG 组内发起投票、答疑或发放福利。 | **Native IM Integration · 原生 IM 集成**、Community Ecosystem Drive · 社群生态驱动、Advanced Management · 高级管理。 |
| **85. Fan Profile Analysis · 粉丝画像分析** | Scrape backend data to generate visual dashboard, provide next week's topic strategy. 抓取后台数据生成可视化看板，给出下周选题策略。 | **Data Collection · 数据采集**、Local Processing · 本地处理、Decision Analysis Report · 决策分析报告。 |
| **86. Sponsor Outreach · 赞助商拓展** | Search matching brand websites, find PR email, send self-recommendation. 搜索匹配的品牌官网，寻找 PR 邮箱并发送自荐信。 | **Browser Search · 浏览器搜索**、Email Distribution · 邮件分发、BD Process Automation · BD 流程自动化。 |
| **87. Live Comment Feedback · 直播弹幕反馈** | Real-time analyze comments, prompt host on teleprompter with top questions worth answering. 实时分析弹幕，在提词器上提示博主最值得回答的问题。 | **Streaming Data Processing · 流式数据处理**、Monitoring Extraction · 监控提取、Local Display · 本地展示。 |
| **88. Giveaway Full-loop Management · 抽奖发放闭环** | Identify compliant winners, DM to collect address, place e-commerce order for shipping. 识别合规中奖用户，私信收集地址并在电商下单寄送。 | **Long-flow E-commerce Operation · 长流程电商操作**、Reply Interaction · 回复交互、Logistics Loop · 物流闭环。 |
| **89. Evergreen Content Re-publishing · 过期内容再发布** | Scan old posts, rewrite based on current trends, reschedule and distribute. 扫描旧文，根据当下热梗改写并再次排期分发。 | **Local Archive Activation · 本地仓库激活**、Lifecycle Management · 生命周期管理、LLM Awakening · LLM 唤醒。 |
| **90. DM Classification & Routing · 私信分类分流** | Classify DMs (business/feedback/help), compile and notify via Feishu. 将私信分类（商务/建议/求助），汇总至飞书通知。 | **Automation Coordination · 自动化协同**、Information Bus · 信息总线、Classification Routing · 分类分流。 |

### 10. Experimental · 跨领域创意实验 (Cases 91–100)

| Case · 案例 | Scenario · 场景描述 | Core Capabilities · Agent 核心能力 |
| :--- | :--- | :--- |
| **91. Personal Digital Twin · 个人数字孪生** | Scan user's full notes and records, build a conversational "digital self." 扫描用户全量笔记与记录，构建可对话的"数字分身"。 | **Large-scale Local Indexing · 大规模本地索引**、Privacy Protection · 隐私保护、Semantic Understanding · 语义理解。 |
| **92. Technical Tutorial Auto-Generation · 技术教程生成** | Record terminal code operations, auto-screenshot and generate annotated Markdown. 记录终端代码操作，自动截图并生成带讲解的 Markdown。 | **System-level Monitoring · 系统级监控**、Screenshot · 截图、Structured Writing · 结构化撰写。 |
| **93. Bilingual Academic Reader · 双语论文阅读器** | Convert web page to PDF, insert AI interpretation and background links alongside paragraphs. 将网页转 PDF，并在段落旁插入 AI 解读和背景链接。 | **Web Scraping · Web 抓取**、Document Reconstruction · 文档重构、Enhanced Reading · 增强阅读。 |
| **94. Creative Hackathon · 创意黑客马拉松** | Decompose main goal, launch 10 sub-Agents to work in parallel, aggregate results. 拆解总目标，启动 10 个子 Agent 并行工作并汇总成果。 | **Recursive Task Decomposition · 递归任务拆解**、Concurrent Execution · 并发执行、Scheduling · 调度能力。 |
| **95. Open Source Project Operator · 开源项目运营员** | Monitor GitHub Issues, try running error-causing code, submit fix PRs. 监控 GitHub Issue，尝试运行报错代码并提交修复 PR。 | **Sandbox Env Simulation · 沙盒环境模拟**、Code Execution · 代码执行、Git Contribution · Git 贡献。 |
| **96. Future Simulation Lab · 未来模拟实验室** | Based on news, extrapolate 3-year industry shifts, run thousands of simulation scenarios. 基于新闻推演未来三年行业变局，运行数千次模拟演练。 | **Data Extrapolation · 数据推演**、Causal Reasoning · 因果推理、Logic Simulation · 逻辑模拟。 |
| **97. Mind Map → PPT · 思维导图转 PPT** | Read XMind file, search images for branches, generate beautifully laid-out presentation. 读取 XMind，为分支搜寻配图并生成精美排版的 PPT。 | **Cross-format Conversion · 跨格式转换**、Asset Search · 资产搜寻、Presentation Doc Generation · 演示文档生成。 |
| **98. Offline Creative Assistant · 离线创意助理** | In offline environment, use local LLM to collaborate on complex creative tasks. 在断网环境下，利用本地大模型协作完成复杂构思。 | **Fully Local Execution · 纯本地化执行**、Privacy Security · 隐私安全、Model Call · 模型调用。 |
| **99. Game World-building · 游戏世界观设定** | Generate 10,000-word geography/history lore, generate map and character illustration preview. 生成万字地理/历史设定，并生成地图与角色立绘预览。 | **Multi-modal Long Text · 多模态长文本**、Cross-media Consistency · 跨媒介一致性、Large-scale Generation · 大规模生成。 |
| **100. Workflow Self-Optimizer · 流程自我优化器** | Observe user habits, auto-write Shell scripts to replace repetitive operations. 观察用户习惯，自动编写 Shell 脚本替代重复操作。 | **Code Self-generation · 代码自生成**、Environment Optimization · 环境优化、Tool Chain Evolution · 工具链进化。 |

---

[← Back to main README](../../README.md)
