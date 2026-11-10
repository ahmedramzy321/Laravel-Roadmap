[Roadmap](../README.md) › Advanced  ·  [← Intermediate](../intermediate/README.md) · [Next: Career →](../career.md)

# Advanced

> **Level 3 of 3** · Set by the squad · 3 core topics + 14 elective topics

The goal of this level is to write clean, structured applications. It has
two parts. **Core topics** are the same for every track and go in order:
SOLID, then design patterns, then MVC. After them come **advanced topics
you pick yourself**, ordered by priority.

## Part 1 · Core topics (in order)

| # | Topic | Deliverable | Items | Resources |
|:-:|-------|----------------|:-----:|:--------:|
| 1 | [1. SOLID principles](core/01-solid-principles.md) | refactor a piece of your own earlier code to follow SOLID. | 5 | 3 |
| 2 | [2. Design patterns](core/02-design-patterns.md) | implement three patterns (one creational, one structural, one behavioral) in small PHP examples. | 5 | 6 |
| 3 | [3. MVC](core/03-mvc.md) | (1) a native PHP MVC application with full CRUD. (2) a Laravel application with authentication, relationships and a dashboard (a blog, social app or portfolio with admin). | 7 | 8 |

## Part 2 · Advanced topics: pick yours

Everyone is free to add the advanced topics they think are worth it.
Pick the ones that match your goals and the jobs you are targeting, and
agree with your squad on which ones you cover. Topics are ordered by
priority: finish the Tier 1 topics you choose before moving to Tier 2 and
Tier 3.

| Tier | Meaning | Topics |
|:----:|---------|--------|
| 1 | Most Laravel jobs expect these | Web API, Testing, Security, Queues and events |
| 2 | Make your project production-ready | Caching, Docker, CI/CD, Deployment |
| 3 | Extras that set you apart | Third-party APIs, Real-time, Admin panel, Livewire/Inertia, Packages, Scaling |

### Tier 1

| Topic | Deliverable | Items | Resources |
|-------|----------------|:-----:|:--------:|
| [1. Web API](topics/01-web-api.md) | a documented REST API secured with Sanctum (a travel, booking or e-commerce API). | 5 | 5 |
| [2. Testing](topics/02-testing.md) | at least one feature test for every project you build, and feature tests for your API endpoints. | 3 | 2 |
| [3. Security](topics/03-security.md) | review one of your own projects against the OWASP Top 10 and fix what you find. | 3 | 2 |
| [4. Queues, events and authorization](topics/04-queues-events-and-authorization.md) | a feature that sends an email or notification through a queued job, triggered by an event. | 4 | 2 |

### Tier 2

| Topic | Deliverable | Items | Resources |
|-------|----------------|:-----:|:--------:|
| [5. Caching with Redis](topics/05-caching-with-redis.md) | cache an expensive query or API response in your project and measure the difference. | 3 | 1 |
| [6. Docker](topics/06-docker.md) | run your Laravel project in containers (Laravel Sail or your own `docker-compose.yml`). | 3 | 3 |
| [7. CI/CD](topics/07-ci-cd.md) | a GitHub Actions workflow that runs your tests on every push. | 2 | 1 |
| [8. Deployment](topics/08-deployment.md) | your project live on the internet with HTTPS. | 4 | 3 |

### Tier 3

| Topic | Deliverable | Items | Resources |
|-------|----------------|:-----:|:--------:|
| [9. Third-party APIs and payments](topics/09-third-party-apis-and-payments.md) | — | 3 | 0 |
| [10. Real-time programming](topics/10-real-time-programming.md) | — | 2 | 1 |
| [11. Admin panel with Filament](topics/11-admin-panel-with-filament.md) | a full project with a Filament dashboard. Follow the e-commerce playlist below, then build your own. | 2 | 3 |
| [12. Livewire, or Inertia with Vue or React](topics/12-livewire-or-inertia-with-vue-or-react.md) | — | 1 | 2 |
| [13. Packages](topics/13-packages.md) | — | 2 | 2 |
| [14. Scaling and computer science depth (Optional)](topics/14-scaling-and-computer-science-depth-optional.md) | — | 7 | 5 |

## Final project

Build on your Laravel app (or your REST API, if you picked Web API) with
at least two of the advanced topics you picked (for example caching,
Docker, queues, deployment), add tests, and deploy it publicly.

## Advanced: done when you can

-   Build a Laravel app without following a tutorial step by step, and a documented API too if you picked Web API.
-   Explain why you structured the code the way you did (SOLID, patterns, MVC).
-   Show a deployed project with tests, and defend the trade-offs you made.

**Levels:** [Roadmap](../README.md) | [Beginner](../beginner/README.md) | [Intermediate](../intermediate/README.md) | **Advanced** | [Career](../career.md)
