# Marco Solimano

Software developer. I build from the screen to the cluster: mobile apps, web, and services. The business rule stays in the middle. The framework stays at the edge.

A model can suggest the next step. It does not get the keys. [Oficio de la IA](https://github.com/MsolimanoMiranda/anden-ia) keeps it on a contract: an allowlist of tools, a four-step budget, notes retrieved from the question, a policy that vetoes a go-ahead with no stock data, an audit trace, and a local fallback when the model is down. Tests use a scripted model. `ANDEN_MODELO_URL` points the same port at an OpenAI-compatible `/v1/chat/completions` endpoint. [Agentes](https://github.com/MsolimanoMiranda/anden-agentes) is the smaller sibling: it proposes order priority on Spring Boot and falls back to a heuristic.

Curiosity is the part of the job I trust most. I keep these repositories small and readable so someone opening one can follow the flow and learn the stack from the code.

## Stack

| Area | What I use |
| --- | --- |
| AI | Tool allowlist, step budget, policy veto, retrieval over local notes, audit trace, local fallback, OpenAI-compatible chat completions |
| iOS | Swift, MVVM, Clean Architecture |
| Android | Kotlin, Jetpack Compose, MVVM, Hilt, Coroutines, Flow, Firebase |
| React Native | CLI, Firebase, Clean Architecture, MVVM, dependency injection, realtime CRUD |
| Flutter | Clean Architecture, MVVM, Bloc, Provider, dependency injection, streams, images |
| Web | Next.js (SSR, SSG, CSR, ISR), middleware, dynamic routes, Route Handlers, NextAuth, Material UI, cookies |
| Node | NestJS (NATS, webhooks, gateways) and Express with dependency injection |
| JVM | Spring Boot, Spring Cloud, OpenAPI, API-first, OAuth2, DDD, CQRS, hexagonal architecture, Java 25 |
| .NET | ASP.NET Core, Clean Architecture, Entity Framework, Dapper, SOLID, DDD |
| Go | Clean Architecture, hexagonal architecture, Gin, GORM |
| Python | FastAPI, hexagonal architecture, Clean Architecture |
| PHP | Hexagonal architecture, Clean Architecture |
| Data | PostgreSQL, MongoDB, SQLite |
| Platform | Docker, Kubernetes, Amazon EKS, Helm, Argo CD, Prometheus, Grafana, GitHub Actions, AWS (OIDC, ECR, ECS), Google Cloud |

## Repositories

One project per stack. Each README has the concept, the stack, and a flow diagram.

| Project | Stack |
| --- | --- |
| [Oficio de la IA](https://github.com/MsolimanoMiranda/anden-ia) | Python, FastAPI, tool allowlist, policy veto, trace |
| [Andén](https://github.com/MsolimanoMiranda/anden) | Next.js, SSR, SSG, CSR, ISR, NextAuth, Material UI |
| [Cuentas claras](https://github.com/MsolimanoMiranda/anden-cuentas-claras) | Swift, MVVM, Clean Architecture |
| [Bodega](https://github.com/MsolimanoMiranda/anden-bodega) | Jetpack Compose, Hilt, Coroutines, Flow, Firebase |
| [Puesto vivo](https://github.com/MsolimanoMiranda/anden-puesto-vivo) | React Native CLI, Firebase, MVVM |
| [Taller](https://github.com/MsolimanoMiranda/anden-taller) | Flutter, Bloc, Provider |
| [Muelle](https://github.com/MsolimanoMiranda/anden-muelle) | NestJS, NATS, webhooks, Docker |
| [Consultorio](https://github.com/MsolimanoMiranda/anden-consultorio) | ASP.NET Core, EF, Dapper, DDD |
| [Banco](https://github.com/MsolimanoMiranda/anden-banco) | Spring Boot, OpenAPI, OAuth2 |
| [Ruta de pagos](https://github.com/MsolimanoMiranda/anden-ruta-pagos) | Spring Cloud Gateway, OAuth2 |
| [Agentes](https://github.com/MsolimanoMiranda/anden-agentes) | Spring Boot 4, DDD, CQRS, Java 25, heuristic fallback |
| [Caja](https://github.com/MsolimanoMiranda/anden-caja) | Go, Gin, GORM |
| [Mesa](https://github.com/MsolimanoMiranda/anden-mesa) | FastAPI, hexagonal architecture |
| [Comprobantes](https://github.com/MsolimanoMiranda/anden-comprobantes) | Express, dependency injection |
| [Estantería](https://github.com/MsolimanoMiranda/anden-estanteria) | PHP, hexagonal architecture |
| [Plataforma](https://github.com/MsolimanoMiranda/anden-plataforma) | Kubernetes, EKS, Helm, Argo CD, Prometheus |
| [Despliegue](https://github.com/MsolimanoMiranda/anden-despliegue) | GitHub Actions, AWS OIDC, ECR, ECS |
