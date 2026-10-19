<div align="center">

<img src="assets/hero.svg" alt="belam muia, backend engineer. Animated terminal with a rotating motto and scrolling production logs." width="100%" />

<br/><br/>

[![email](https://img.shields.io/badge/email-belammuia0%40gmail.com-5EEAD4?style=for-the-badge&logo=gmail&logoColor=black)](mailto:belammuia0@gmail.com)
[![linkedin](https://img.shields.io/badge/linkedin-belam_muia-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/belam-muia-a690b326a/)
[![task-queue-system](https://img.shields.io/badge/featured-task--queue--system-0f1b2d?style=for-the-badge&logo=github&logoColor=5EEAD4)](https://github.com/belammuia/task-queue-system)

</div>

<img src="assets/divider.svg" alt="" width="100%" />

## ⚙️ how i build

| | principle | what it looks like |
|---|---|---|
| 🔁 | **idempotent by default** | retries should be safe, double-clicks should be boring. same request, same result, zero duplicate work. |
| ⏳ | **async where it counts** | slow work (images, emails, exports) leaves the request path and lives in worker pipelines. |
| 🗄️ | **the database is a feature** | deliberate schema design and query tuning (`select_related` / `prefetch_related`) before reaching for hardware. |
| 🔇 | **quiet in production** | the best systems page nobody. boring, observable, predictable. |

<img src="assets/divider.svg" alt="" width="100%" />

## 🧰 stack

<img src="assets/stack.svg" alt="Python, Django, DRF, Java, Spring Boot, PostgreSQL, Redis, Celery, Docker, Git, Linux, EndeavourOS" width="100%" />

- **core & frameworks:** Python, Django, DRF, Java, Spring Boot
- **data & async:** PostgreSQL, Redis, Celery
- **infrastructure & OS:** Linux (EndeavourOS), Docker, Git

<img src="assets/divider.svg" alt="" width="100%" />

## 🚀 featured systems

### [task-queue-system](https://github.com/belammuia/task-queue-system)
> asynchronous task queue and execution dashboard.

<img src="assets/architecture.svg" alt="Animated request flow: a client request passes the idempotency check, is queued in Redis and processed by Celery workers. A retry with the same key gets the saved response." width="100%" />

- custom **DRF idempotency middleware** using `Idempotency-Key` headers and Redis caching
- background **worker pipelines** for PIL image resizing, email delivery, and data exports

<br/>

### [momAid-backend](https://github.com/rufoabrahamguyo/momAid-backend)
> cloud-hosted maternal health API built with Django REST Framework and PostgreSQL.

<img src="assets/queries.svg" alt="Animated comparison of N+1 queries versus prefetch_related batching the lookups into two queries." width="100%" />

- relational schema design and query optimization (`select_related` / `prefetch_related`)
- scheduled **Celery** tasks for background work

<img src="assets/divider.svg" alt="" width="100%" />

## 🔭 currently

```diff
+ shipping:     real-time systems with WebSockets
+ leveling up:  security & GRC (CompTIA Security+ in progress)
+ sharpening:   async patterns, caching strategy, and API design
- avoiding:     anything that needs a 3am page
```

## 💬 ask me about

`idempotency keys` · `celery gotchas` · `taming the django ORM` · `designing APIs that survive retries` · `living on a rolling-release distro`

<img src="assets/divider.svg" alt="" width="100%" />

## 📊 the receipts

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=belammuia&show_icons=true&count_private=true&title_color=5eead4&text_color=cbd5e1&icon_color=38bdf8&bg_color=0a1220&border_color=1e3a4f&border_radius=16" alt="github stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=belammuia&layout=compact&langs_count=6&title_color=5eead4&text_color=cbd5e1&bg_color=0a1220&border_color=1e3a4f&border_radius=16" alt="top languages" />

<img src="https://streak-stats.demolab.com?user=belammuia&background=0a1220&border=1e3a4f&stroke=1e3a4f&ring=5eead4&fire=f87171&currStreakNum=e2e8f0&currStreakLabel=5eead4&sideNums=e2e8f0&sideLabels=94a3b8&dates=64748b&border_radius=16" alt="streak stats" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=belammuia&bg_color=0a1220&color=5eead4&line=38bdf8&point=e2e8f0&area=true&area_color=38bdf8&hide_border=true&height=300" alt="contribution activity graph" width="100%" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/belammuia/belammuia/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/belammuia/belammuia/output/github-snake.svg" />
  <img alt="a snake eating my contribution graph" src="https://raw.githubusercontent.com/belammuia/belammuia/output/github-snake.svg" width="100%" />
</picture>

</div>

<img src="assets/divider.svg" alt="" width="100%" />

<div align="center">

*if it runs in prod and no one notices - perfect.*

<br/>

![visitors](https://komarev.com/ghpvc/?username=belammuia&label=visitors&color=5EEAD4&style=flat-square)

</div>
