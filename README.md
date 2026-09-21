### 何胜利 · heshengli

**全栈工程师｜10 年 .NET 全栈开发｜制造业 MES / 医疗行业系统**

![.NET](https://img.shields.io/badge/.NET-6%20%7C%208%20%7C%2010-512BD4?logo=dotnet&logoColor=white)
![ABP](https://img.shields.io/badge/ABP%20Framework-VNext-6C4AB6)
![C%23](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white)
![Microservices](https://img.shields.io/badge/Architecture-Microservices-0A7EA4)
![Vue](https://img.shields.io/badge/Vue-2-4FC08D?logo=vuedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

南京 · 求职方向：全栈工程师 / .NET 架构（社招）

---

## 关于我

- **10 年 .NET 一线研发**，长期做制造业与医疗行业的业务系统，从需求分析、架构设计、编码实现到部署运维整条链路都做
- **ABP Framework 源码级掌握**：从技术选型、模块化拆分到团队落地；主导过公司级 ABP 改造，覆盖 MOM / MES / QMS / WMS / EMS / PMS / Report / Print 等 8 类核心系统
- **制造业 MES 实践**：光伏 MES 服务 **10+ 客户**，单客户覆盖 2-3 个车间、最多 8 条产线；电子 MES；熟悉 ISA-95 制造分层模型
- **微服务改造**：主导云平台「单体 → 微服务」改造，拆分为**约 10 个微服务模块**（Ocelot 网关 / Consul + Steeltoe 服务发现 / RabbitMQ / Redis）
- **团队带教**：带过 **8 人**研发小组，周均 Code Review **5000+ 行 / 50+ 个 PR**
- **AI 辅助编程**：把 AI 代码生成、重构、单测生成的实践沉淀成团队内部规范与提示词模板

## 向 ABP 官方反馈过的框架级缺陷

不只是提 issue —— 定位到根因、给出修复方向，被官方采纳并合入主分支：

| 我反馈的问题 | 官方修复 | 状态 |
| :--- | :--- | :--- |
| [ABP Support #10259](https://abp.io/support/questions/10259)：应用配置缓存重置只对当前用户生效 —— 非 admin 用户权限变更后缓存无法清理，只能等 5 分钟超时 | [abpframework/abp #24486](https://github.com/abpframework/abp/pull/24486) | ✅ 已合入 `rel-10.0` |
| [ABP Support #9823](https://abp.io/support/questions/9823)：`PermissionStore.SetCacheItemsAsync` 首次加载缓慢 | [abpframework/abp #23622](https://github.com/abpframework/abp/pull/23622) | ✅ 已合入 `dev` |

> 第 2 项是通过在框架源码里埋点耗时日志定位到根因（权限名重复 LINQ 查询），推动官方用 `HashSet` 重写权限 / 配置项查找逻辑，改善了首次登录与缓存重建时的性能。

## 值得一看的仓库

| 仓库 | 说明 |
| :--- | :--- |
| [MicroserviceDemo](https://github.com/heshengli/MicroserviceDemo) | 基于 **ABP VNext** 的微服务实践：网关 / 服务发现 / 消息队列 / 缓存一整套跑通，含 docker-compose、K8s 与 ELK 日志方案 |
| [NanoFabric-Core3.1](https://github.com/heshengli/NanoFabric-Core3.1) | 微服务基础设施探索：Core 3.1 升级与调试记录 |
| [BlazorServerTest-IAsyncDisposable-GC](https://github.com/heshengli/BlazorServerTest-IAsyncDisposable-GC) | Blazor Server 内存回收（`IAsyncDisposable`）问题复现与验证 |

## 技术栈

| 方向 | 内容 |
| :--- | :--- |
| **后端** | .NET 6 / 8 / 10 · ABP Framework / ABP VNext · .NET Core Web API · Entity Framework · Dapper · Blazor |
| **架构与中间件** | 微服务拆分 · Ocelot · IdentityServer4 · Consul + Steeltoe · Autofac · RabbitMQ · Redis · Memcached · SuperSocket · Nginx |
| **数据库** | SQL Server · MySQL · PostgreSQL |
| **前端** | Vue 2 · JavaScript · Vant / Ant Design / Element UI · HTML / CSS |
| **工程与运维** | Docker · Linux · Nginx · Windows Server + IIS · DevOps |
| **行业域** | 光伏 MES · 电子 MES · MOM / MES / QMS / WMS / EMS / PMS · ISA-95 · 医疗 WMS · 数据中台 · 报表与标签打印 |

## 联系我

📧 74261727@qq.com　·　📍 南京　·　💼 全栈工程师 / .NET 架构（社招）

---

<sub>**Full-stack .NET Engineer · 10 years** — Specialized in **ABP Framework** and **manufacturing MES / healthcare systems**. 2 framework-level defects reported to the ABP team and merged into official branches ([#24486](https://github.com/abpframework/abp/pull/24486) into `rel-10.0`, [#23622](https://github.com/abpframework/abp/pull/23622) into `dev`). Based in Nanjing, China.</sub>
