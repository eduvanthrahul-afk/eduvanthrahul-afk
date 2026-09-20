<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&pause=1400&color=39FF88&background=0D1117&center=true&vCenter=true&width=750&height=90&lines=%24+curl+https%3A%2F%2Fapi.rahul.dev%2Fv1%2Fprofile;%3E+HTTP%2F1.1+200+OK;%3E+Backend+Developer+%7C+Java+%C2%B7+Spring+Boot+%7C+Chennai%2C+IN" alt="api boot sequence" />

<sub><b>api.rahul.dev</b> — a developer, documented as an API · <img src="https://img.shields.io/badge/status-operational-39FF88?style=flat-square&labelColor=0D1117"/> <img src="https://img.shields.io/badge/uptime-since_2024-39FF88?style=flat-square&labelColor=0D1117"/> <img src="https://img.shields.io/badge/version-v4.1.0--beta-39FF88?style=flat-square&labelColor=0D1117"/></sub>

</div>

---

## `GET /v1/profile`

```json
{
  "name": "Rahul E.",
  "role": "Backend Developer",
  "status": "in_development",
  "location": "Chennai, India",
  "education": {
    "degree": "B.E. Computer Science",
    "institution": "SRM Easwari Engineering College",
    "graduating": 2028,
    "cgpa": 8.3
  },
  "certifications": [
    "Oracle Certified Professional, Java SE 17",
    "Cisco - Networking Basics"
  ],
  "bio": "Started backend engineering by asking what happens when a tutorial CRUD app meets real traffic and real attackers. Still asking that question — just with better answers now."
}
```

---

## `GET /v1/skills`

```json
{
  "languages": [
    "Java",
    "JavaScript",
    "HTML",
    "CSS"
  ],
  "backend": [
    "Spring Boot",
    "Spring Data JPA / Hibernate",
    "Spring Security",
    "JWT",
    "MySQL",
    "PostgreSQL"
  ],
  "security": [
    "AES-256-GCM",
    "PBKDF2",
    "RBAC",
    "Web Crypto API"
  ],
  "tooling": [
    "Git",
    "GitHub",
    "Postman",
    "Maven",
    "IntelliJ IDEA",
    "VS Code"
  ],
  "in_progress": [
    "Node.js",
    "Express"
  ]
}
```

---

## `GET /v1/projects`

```json
[
  {
    "name": "Digital Journal",
    "role": "Team Lead (5 engineers)",
    "stack": ["Spring Boot", "PostgreSQL", "Alpine.js", "htmx", "AWS S3"],
    "description": "First project-leadership role. Owned system design docs, a phased build roadmap, and the frontend/backend integration contract.",
    "status": "shipped"
  },
  {
    "name": "KeyVault",
    "role": "Solo build",
    "stack": ["Java", "Spring Boot", "MySQL", "Web Crypto API"],
    "description": "Secrets manager where encryption happens client-side (PBKDF2 + AES-256-GCM) before anything reaches the backend. Workspaces, RBAC, secret versioning, audit logs, machine tokens.",
    "status": "shipped"
  },
  {
    "name": "Verdant CRM",
    "role": "Solo build",
    "stack": ["Java 17", "Spring Boot 3", "PostgreSQL", "Flyway"],
    "description": "Commercial ops CRM — leads, quoting, milestone billing, field surveys. Materialized view for analytics, paginated REST via Pageable, JWT auth.",
    "status": "shipped"
  },
  {
    "name": "Expense Manager",
    "role": "Solo build",
    "stack": ["Java", "Spring Boot", "MySQL", "JPA"],
    "description": "Full-stack expense tracker with budget calculations, category filtering, and aggregate SQL queries behind a dynamic async UI.",
    "status": "shipped"
  }
]
```

---

## `GET /v1/stats`

```
Response: image/svg+xml
```

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=eduvanthrahul-afk&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=39FF88&icon_color=39FF88&text_color=c9d1d9" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=eduvanthrahul-afk&theme=dark&hide_border=true&background=0D1117&ring=39FF88&fire=39FF88&currStreakLabel=39FF88" height="165"/>
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=eduvanthrahul-afk&theme=react-dark&bg_color=0D1117&color=39FF88&line=39FF88&point=ffffff&hide_border=true" width="97%"/>
</div>

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=eduvanthrahul-afk&theme=darkhub&no-frame=true&row=1&column=6&margin-w=10"/>
</div>

```json
{
  "leetcode_problems_solved": "400+",
  "codechef_rating": 1503,
  "codechef_division": 3
}
```

---

## `CHANGELOG.md`

```
## [4.1.0-beta] — current
### Added
- Node.js + Express (in progress)
- Exploring shippable SaaS ideas beyond solo demo projects

## [4.0.0]
### Added
- Led a 5-person team building Digital Journal
- First system design docs + phased roadmap ownership

## [3.0.0]
### Added
- Security layer: AES-256-GCM, PBKDF2, RBAC
- Shipped KeyVault

## [2.0.0]
### Added
- Spring Boot, Spring Security, Spring Data JPA
- Shipped Verdant CRM, Expense Manager

## [1.0.0]
### Added
- Java fundamentals
- Oracle Certified Professional, Java SE 17
- Started competitive programming on LeetCode + CodeChef
```

---

## Error Responses

```json
HTTP/1.1 404 Not Found
{
  "error": "tutorial_clone_not_found",
  "message": "This developer does not ship tutorial-clone-only projects."
}
```

```json
HTTP/1.1 429 Too Many Requests
{
  "error": "rate_limited",
  "message": "Currently rate-limited by semester exams.",
  "retry_after": "end_of_semester"
}
```

---

## `POST /v1/contact`

```bash
curl -X POST https://api.rahul.dev/v1/contact \
  -H "Content-Type: application/json" \
  -d '{
    "channel": "email",
    "address": "eduvanthrahul@gmail.com"
  }'
```

```json
HTTP/1.1 202 Accepted
{
  "message": "Queued.",
  "average_response_time": "< 24h"
}
```

<div align="center">

[![Email](https://img.shields.io/badge/-Email-0D1117?style=flat-square&logo=gmail&logoColor=39FF88)](mailto:eduvanthrahul@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=39FF88)](https://linkedin.com/in/rahul-eduvanth)
[![LeetCode](https://img.shields.io/badge/-LeetCode-0D1117?style=flat-square&logo=leetcode&logoColor=39FF88)](https://leetcode.com/Rahul_E)
[![GitHub](https://img.shields.io/badge/-GitHub-0D1117?style=flat-square&logo=github&logoColor=39FF88)](https://github.com/eduvanthrahul-afk)

</div>

---

<div align="center">
<sub><code>X-Requests-Served:</code> <img src="https://komarev.com/ghpvc/?username=eduvanthrahul-afk&label=views&color=39FF88&style=flat-square&base=0D1117" height="18"/></sub>
</div>
