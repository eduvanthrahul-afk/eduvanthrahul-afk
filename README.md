<div align="center">

# Rahul E.
### Backend Developer — Java · Spring Boot · System Design

📍 Chennai, India &nbsp;·&nbsp; 🎓 SRM Easwari Engineering College, CSE '28 &nbsp;·&nbsp; ☕ Oracle Certified, Java SE 17

<a href="mailto:eduvanthrahul@gmail.com"><img src="https://img.shields.io/badge/-Email-0D1117?style=flat-square&logo=gmail&logoColor=39FF88"/></a>
<a href="https://linkedin.com/in/rahul-eduvanth"><img src="https://img.shields.io/badge/-LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=39FF88"/></a>
<a href="https://leetcode.com/Rahul_E"><img src="https://img.shields.io/badge/-LeetCode-0D1117?style=flat-square&logo=leetcode&logoColor=39FF88"/></a>
<a href="https://github.com/eduvanthrahul-afk"><img src="https://img.shields.io/badge/-GitHub-0D1117?style=flat-square&logo=github&logoColor=39FF88"/></a>

</div>

---

### Schema

```mermaid
erDiagram
    DEVELOPER ||--o{ SKILL : has
    DEVELOPER ||--o{ PROJECT : builds
    DEVELOPER ||--o{ CERTIFICATION : holds
    SKILL ||--o{ PROJECT : "applied in"

    DEVELOPER {
        string name
        string role
        string location
        string status
    }
    SKILL {
        string category
        string name
    }
    PROJECT {
        string name
        string stack
        string status
    }
    CERTIFICATION {
        string name
        string issuer
    }
```

I got into backend engineering by taking apart a tutorial CRUD app and asking what happens when it meets real traffic and real attackers. That question is still what I build toward — systems with real access control, real encryption, and a schema that was actually thought through.

---

### Skills

**Languages**
- <img src="https://skillicons.dev/icons?i=java" height="18"/>&nbsp; Java
- <img src="https://skillicons.dev/icons?i=js" height="18"/>&nbsp; JavaScript
- <img src="https://skillicons.dev/icons?i=html" height="18"/>&nbsp; HTML
- <img src="https://skillicons.dev/icons?i=css" height="18"/>&nbsp; CSS

**Backend & Data**
- <img src="https://img.shields.io/badge/-6DB33F?style=flat-square&logo=springboot&logoColor=white" height="18"/>&nbsp; Spring Boot
- <img src="https://img.shields.io/badge/-59666C?style=flat-square&logo=hibernate&logoColor=white" height="18"/>&nbsp; Spring Data JPA / Hibernate
- <img src="https://img.shields.io/badge/-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" height="18"/>&nbsp; Spring Security
- <img src="https://img.shields.io/badge/-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" height="18"/>&nbsp; JWT
- <img src="https://skillicons.dev/icons?i=mysql" height="18"/>&nbsp; MySQL
- <img src="https://skillicons.dev/icons?i=postgres" height="18"/>&nbsp; PostgreSQL

**Security Layer**
- 🔐 AES-256-GCM
- 🔐 PBKDF2
- 🔐 RBAC
- 🔐 Web Crypto API

**Tooling**
- <img src="https://skillicons.dev/icons?i=git" height="18"/>&nbsp; Git
- <img src="https://skillicons.dev/icons?i=github" height="18"/>&nbsp; GitHub
- <img src="https://skillicons.dev/icons?i=postman" height="18"/>&nbsp; Postman
- <img src="https://skillicons.dev/icons?i=maven" height="18"/>&nbsp; Maven
- <img src="https://skillicons.dev/icons?i=idea" height="18"/>&nbsp; IntelliJ IDEA
- <img src="https://skillicons.dev/icons?i=vscode" height="18"/>&nbsp; VS Code

**In progress**
- <img src="https://skillicons.dev/icons?i=nodejs" height="18"/>&nbsp; Node.js
- <img src="https://skillicons.dev/icons?i=express" height="18"/>&nbsp; Express

---

### Projects

<details open>
<summary><b>🧭 Digital Journal — Team Lead, 5 engineers</b></summary>
<br/>

`Spring Boot` `PostgreSQL` `Alpine.js` `htmx` `AWS S3`

My first project-leadership role. Owned the system design docs, a phased build roadmap, and the frontend/backend integration contract for a team of five.

</details>

<details>
<summary><b>🔐 KeyVault — Secrets & API Key Manager</b></summary>
<br/>

`Java` `Spring Boot` `MySQL` `Web Crypto API`

Client-encrypted secrets manager — PBKDF2 + AES-256-GCM encryption happens before anything reaches the backend. Workspaces, RBAC, secret versioning with rollback, audit logs, machine tokens, expiry alerts.

</details>

<details>
<summary><b>📊 Verdant CRM — Commercial Operations Platform</b></summary>
<br/>

`Java 17` `Spring Boot 3` `PostgreSQL` `Flyway` `Spring Security`

Lead tracking, quoting, milestone-billing, and field-survey workflows. PostgreSQL materialized view for analytics, paginated REST via Pageable, Flyway migrations, JWT auth.

</details>

<details>
<summary><b>💰 Expense Manager — Full-Stack Finance Tracker</b></summary>
<br/>

`Java` `Spring Boot` `MySQL` `JPA` `HTML/CSS/JS`

Recurring expense tracking with budget calculations, category filtering, and aggregate SQL queries behind a dynamic async UI.

</details>

---

### Growth

```mermaid
gitGraph
   commit id: "Java fundamentals"
   commit id: "Oracle Java SE 17 cert"
   branch spring-boot
   checkout spring-boot
   commit id: "Learned Spring Boot"
   commit id: "Built Verdant CRM"
   commit id: "Built Expense Manager"
   checkout main
   merge spring-boot
   branch security
   checkout security
   commit id: "AES-256-GCM + PBKDF2"
   commit id: "Built KeyVault"
   checkout main
   merge security
   branch leadership
   checkout leadership
   commit id: "Led team: Digital Journal"
   checkout main
   merge leadership
   branch node-express
   checkout node-express
   commit id: "Learning Node.js + Express"
```

---

### Stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=eduvanthrahul-afk&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=39FF88&icon_color=39FF88&text_color=c9d1d9" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=eduvanthrahul-afk&theme=dark&hide_border=true&background=0D1117&ring=39FF88&fire=39FF88&currStreakLabel=39FF88" height="165"/>
</div>

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=eduvanthrahul-afk&theme=darkhub&no-frame=true&row=1&column=6&margin-w=10"/>
</div>

<div align="center">
400+ LeetCode problems solved · 1503 CodeChef rating (Div 3)
</div>

---

<div align="center">
<sub>Always building something. Reach out about backend systems, security, or SaaS ideas.</sub>
<br/><br/>
<img src="https://komarev.com/ghpvc/?username=eduvanthrahul-afk&label=PROFILE+VIEWS&color=39FF88&style=flat-square&base=0D1117"/>
</div>
