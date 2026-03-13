# 📚 My Learning Notes

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=30&pause=1000&color=58A6FF&center=true&vCenter=true&width=435&lines=Personal+Learning+Repository" alt="Typing SVG" />
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Status-Active-success?style=flat&logo=statuspage" alt="Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/Language-Chinese-blue?style=flat&logo" alt="Language"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow?style=flat&logo=license" alt="License"></a>
  <a href="#"><img src="https://img.shields.io/badge/Last_Update-March_2026-orange?style=flat&logo=calendar" alt="Last Update"></a>
</p>

---

## 📌 项目简介

> 🎯 这里是我的个人学习笔记仓库，记录后端开发、分布式系统、微服务等技术栈的学习记录。

```mermaid
graph LR
    A[开始学习] --> B[后端基础]
    B --> C[分布式技术]
    C --> D[微服务]
    D --> E[项目实战]
    E --> F[持续精进]
    
    style A fill:#58A6FF,color:#fff
    style F fill:#3FB950,color:#fff
```

---

## 🗂️ 目录结构

```
MyRepo/
├── 📁 linux/                  # Linux 系统学习
│   ├── 命令行基础/
│   ├── Shell脚本/
│   └── 系统运维/
│
├── 📁 java/                   # Java 后端
│   ├── 核心基础/
│   ├── 并发编程/
│   ├── JVM/
│   └── 新特性/
│
├── 📁 spring/                 # Spring 全家桶
│   ├── Spring/
│   ├── Spring Boot/
│   └── Spring Cloud/
│
├── 📁 database/              # 数据库
│   ├── MySQL/
│   ├── Redis/
│   └── MongoDB/
│
├── 📁 distributed/           # 分布式技术
│   ├── RPC/
│   ├── 消息队列/
│   ├── 分布式事务/
│   └── 分布式锁/
│
├── 📁 microservices/          # 微服务
│   ├── Docker/
│   ├── Kubernetes/
│   └── 服务网格/
│
└── 📁 interview/              # 面试题整理
```

---

## 📖 学习路线图

```mermaid
flowchart TB
    subgraph 阶段一["🎯 阶段一：夯实基础"]
        direction TB
        J1[Java 基础] --> J2[Java 进阶]
        J2 --> J3[MySQL]
        J3 --> J4[Redis]
    end
    
    subgraph 阶段二["🚀 阶段二：构建框架"]
        direction TB
        S1[Spring] --> S2[Spring Boot]
        S2 --> S3[MyBatis]
        S3 --> S4[Spring Cloud]
    end
    
    subgraph 阶段三["⚡ 阶段三：分布式进阶"]
        direction TB
        D1[消息队列] --> D2[分布式事务]
        D2 --> D3[分布式锁]
        D3 --> D4[微服务治理]
    end
    
    subgraph 阶段四["🎓 阶段四：DevOps"]
        direction TB
        O1[Docker] --> O2[Kubernetes]
        O2 --> O3[CI/CD]
        O3 --> O4[监控与日志]
    end
    
    阶段一 --> 阶段二 --> 阶段三 --> 阶段四
    
    style 阶段一 fill:#1f6feb,color:#fff
    style 阶段二 fill:#238636,color:#fff
    style 阶段三 fill:#8957e5,color:#fff
    style 阶段四 fill:#bf8700,color:#fff
```

---

## 🛠️ 技术栈

### 🟢 编程语言

<div align="center">

| 语言 | 掌握程度 | 学习阶段 |
|:---:|:---:|:---:|
| <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white" /> | ⭐⭐⭐⭐⭐ | 熟练 |
| <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" /> | ⭐⭐⭐⭐ | 进阶 |
| <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" /> | ⭐⭐⭐ | 学习中 |
| <img src="https://img.shields.io/badge/Rust-ce422b?style=flat&logo=rust&logoColor=white" /> | ⭐⭐ | 入门 |

</div>

### 🔵 后端框架

<div align="center">

| 框架 | 状态 | 熟练度 |
|:---|:---:|:---:|
| Spring | 🟢 熟练 | ⭐⭐⭐⭐⭐ |
| Spring Boot | 🟢 熟练 | ⭐⭐⭐⭐⭐ |
| Spring Cloud | 🟡 学习中 | ⭐⭐⭐ |
| MyBatis | 🟢 熟练 | ⭐⭐⭐⭐ |
| Dubbo | 🟡 学习中 | ⭐⭐⭐ |

</div>

### 🟣 数据库

<div align="center">

| 数据库 | 状态 | 用途 |
|:---|:---:|:---|
| <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" /> | 🟢 熟练 | 主数据库 |
| <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" /> | 🟢 熟练 | 缓存 |
| <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" /> | 🟡 学习中 | 文档数据库 |

</div>

### 🟠 基础设施

<div align="center">

| 技术 | 状态 | 用途 |
|:---|:---:|:---|
| <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" /> | 🟢 熟练 | 容器化 |
| <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white" /> | 🟡 学习中 | 容器编排 |
| <img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white" /> | 🟢 熟练 | 反向代理 |

</div>

---

## 📊 学习统计

```text
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   💻 代码学习                                                │
│   ████████████████████████████░░░░░░░░░░░░░░░  65%          │
│                                                             │
│   📖 理论学习                                                │
│   ████████████████████████████████████████░░  85%          │
│                                                             │
│   🔧 实战项目                                                │
│   ██████████████████░░░░░░░░░░░░░░░░░░░░░░  35%          │
│                                                             │
│   📝 面试准备                                                │
│   ████████████████████████████████░░░░░░░░  70%          │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 🔥 最近更新

| 日期 | 内容 | 分类 |
|:---|:---|:---:|
| 2026-03-13 | 更新 Linux 笔记 | Linux |
| 2026-03-10 | 新增 Spring Cloud 学习笔记 | Spring |
| 2026-03-08 | 完善 Redis 面试题 | Database |
| 2026-03-05 | 添加分布式事务笔记 | Distributed |

---

## 📈 贡献指南

欢迎提交 PR！请遵循以下步骤：

```bash
# 1. Fork 本仓库
# 2. 创建你的特性分支
git checkout -b feature/your-feature

# 3. 提交你的更改
git commit -m 'Add some feature'

# 4. 推送到分支
git push origin feature/your-feature

# 5. 创建 Pull Request
```

---

## 📝 笔记规范

> 📌 每篇笔记都遵循以下格式：

- ✅ **代码完整**：可运行的示例代码
- ✅ **原理深入**：底层原理分析
- ✅ **细节详尽**：不遗漏关键点
- ✅ **对比分析**：优缺点对比

---

## 📞 联系我

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Email-guide@email.com-red?style=flat&logo=gmail" /></a>
  <a href="#"><img src="https://img.shields.io/badge/GitHub-username-black?style=flat&logo=github" /></a>
</p>

---

## 🙏 致谢

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=your-github-username&label=Views&color=58A6FF&style=flat" alt="Profile Views" />
</p>

---

<p align="center">
  <strong>Keep Learning, Keep Growing 🌱</strong>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=58A6FF&height=200&section=footer" />
</p>
