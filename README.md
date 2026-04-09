<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Mahmoud%20Ahmed&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Backend%20Developer%20·%20Cloud%20Enthusiast%20·%20CS%20%26%20AI%20Student&descAlignY=55&descSize=16" width="100%"/>

</div>

<br/>

## 👋 Hey, I'm Mahmoud

I'm a fourth-year **Computer Science & AI** student from Giza, Egypt, graduating mid-2026 — and I've been on a journey I didn't expect when I started.

I began writing **PHP and Laravel**, building e-commerce platforms and university systems, getting comfortable with how the web actually works. Then I discovered **.NET and Clean Architecture**, and something clicked — I realized I didn't just want to build features, I wanted to build *systems*. Systems with structure, patterns, and principles behind every decision.

That curiosity didn't stop at code. I kept asking: *where does this actually run?* That question led me to **AWS**, to Docker, to distributed infrastructure — and now I find myself genuinely excited about the full picture: from the first line of C# all the way to how it scales in production.

I'm not just looking for a job. I'm looking for a team that cares about doing things right.

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoud-soliman-46a9ab26b/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MAHMOUD-AHMEDD)
[![Location](https://img.shields.io/badge/Giza,_Egypt-FF6B6B?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
[![Open to Work](https://img.shields.io/badge/Open_to_Work-00C853?style=for-the-badge&logo=briefcase&logoColor=white)](#)

</div>

<br/>

---

## 🗺️ My Journey So Far

> The path wasn't linear — and that's exactly what made it interesting.

```
PHP / Laravel          →      .NET / C#            →      AWS / Cloud
──────────────────────────────────────────────────────────────────────
Built real apps.         Learned to think         Learned to think
Learned how              in systems.              in infrastructure.
APIs work.               Clean Architecture.      High availability.
Multi-role auth.         Domain-driven design.    Fault tolerance.
```

I didn't switch because PHP was wrong — I switched because **I wanted to grow into backend engineering at a deeper level**. Every phase taught me something the next one needed.

<br/>

---

## 🛠️ What I Work With

**My primary stack — what I build in every day:**

![.NET](https://img.shields.io/badge/.NET_9-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

**Cloud & DevOps — where the code actually lives:**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![ECS Fargate](https://img.shields.io/badge/ECS_Fargate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

**Architecture & patterns I think in:**

`Clean Architecture` · `Generic Repository` · `Unit of Work` · `REST API Design` · `RBAC` · `JWT Auth` · `CQRS (familiar)`

**Tools & other languages:**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

<br/>

---

## 🚀 Projects

### 🗂️ TaskFlow — Project Management REST API
> *The project I'm most proud of. Still building it.*

A production-grade backend built the way I'd want to work on it in a real job — with actual architecture decisions, not just endpoints.

**Stack:** `.NET 9` · `ASP.NET Core` · `EF Core` · `SQL Server` · `Docker` · `AWS (ECS Fargate, RDS, ECR, ALB, Route 53, S3, SES, Secrets Manager, CloudWatch)`

What I focused on:
- **4-layer Clean Architecture** — Domain, Application, Infrastructure, API — fully decoupled
- **Generic Repository + Unit of Work** pattern for a clean data access layer
- **4-role RBAC** (SuperAdmin → OrgAdmin → ProjectManager → Member) with ASP.NET Core Identity
- **Arabic/English localization** via `IStringLocalizer` — because not every app is English-first
- **JWT auth, FluentValidation, AutoMapper, Serilog** — production-ready from day one
- **Docker + docker-compose** — runs anywhere; deploys to AWS ECS Fargate

This isn't a tutorial project. Every layer was designed before a line was written.

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/MAHMOUD-AHMEDD/TaskManagement)

---

### 🔍 Distributed Search Engine
> *The project that taught me what "team lead" actually means.*

Built with a team — and I led it. We scraped and indexed 100,000+ URLs using a distributed pipeline, containerized Hadoop running on Docker, and a .NET MVC backend holding it all together.

**Stack:** `.NET (MVC)` · `ASP.NET Core` · `Python` · `Hadoop on Docker` · `SQL Server`

The hard parts weren't the code — they were getting Hadoop running in containers on Windows, designing a schema that could handle URL retrieval at scale, and coordinating across a team with different skill sets.

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/MAHMOUD-AHMEDD/Search_Engine)

---

### 🎓 University Learning Platform (Bilingual REST API)
> *My first time building something truly bilingual.*

A full API-based platform connecting doctors, students, and admins at a university — with role-based access and real-time notifications when students subscribe to subjects. Built in Arabic and English.

**Stack:** `PHP` · `Laravel` · `MySQL` · `REST API` · `Multi-role auth`

---

### 🛒 E-Commerce Platform
> *Where it all started — my Laravel roots.*

A complete multi-role e-commerce system with separate flows for clients, suppliers, and admins. Product management, cart, orders, admin panel — the full thing.

**Stack:** `Laravel 10` · `MySQL` · `PHP`

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/MAHMOUD-AHMEDD/e-commerce)

<br/>

---

## 📜 Training & Certifications

**🏫 AWS Cloud Training — NTI (National Telecommunication Institute)** · *Dec 2025 – Feb 2026*

120 hours. AWS Cloud Practitioner + Solutions Architect tracks. Score: **98%**.

Hands-on with EC2, VPC, IAM, S3, RDS, ECS, Lambda — and real architecture patterns: high availability, fault tolerance, cost optimization. This is where the infrastructure pieces became real, not just concepts.

---

**🏛️ Backend Developer Trainee — DEPI (Digital Egypt Pioneers Initiative)** · *Jul 2024 – Oct 2024*

An intensive 3-month government-backed program. Built and deployed real applications in PHP/Laravel — including the e-commerce platform and university system above. This is where I learned that shipping matters, not just writing code.

[![Certificate](https://img.shields.io/badge/View_Certificate-4CAF50?style=flat-square&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1K24QG6FEdopjyoyOd0Qs2miz0S7ei4p-/view?usp=drive_link)

<br/>

---

## 🎯 Competitive Programming

I competed in **ECPC** (Egypt Collegiate Programming Contest) and **ACPC** (Arab Collegiate Programming Contest) — and then stayed involved as a **community volunteer** for a year, supporting events and outreach.

Competitive programming rewired how I think about problems. Not just "does this work?" but "why does this work, and can it work faster?"

[![Certificate](https://img.shields.io/badge/View_Certificate-4CAF50?style=flat-square&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1VKYpTER0yXlgI05tt1g743pXJF5QU0kb/view?usp=drive_link)

<br/>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MAHMOUD-AHMEDD&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MAHMOUD-AHMEDD&layout=compact&theme=tokyonight&hide_border=true" height="170"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MAHMOUD-AHMEDD&theme=tokyonight&hide_border=true" height="170"/>
</div>

<br/>

---

## 🎓 Education

**B.Sc. Computer Science & Artificial Intelligence** · Fayoum University · *2022 – 2026*

GPA: 3.0 / 4.0 (Very Good) · Expected graduation: **mid-2026**

<br/>

---

## 📫 Let's Talk

I'm actively looking for a **junior backend role or internship** — local, Gulf/MENA, or international remote. I care about clean code, real architecture, and teams that still debate the right way to do things.

If that sounds like your team, I'd love to hear from you.

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoud-soliman-46a9ab26b/)
[![Email](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ma6652@fayoum.edu.eg)

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
