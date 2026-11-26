<h1 align="center">Ifan Ferdiansyah</h1>
<p align="center"><strong>Backend Developer</strong><br>Web APIs, database design, and background jobs</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ifanferdi"><img alt="Connect on LinkedIn" src="https://img.shields.io/badge/Connect_on_LinkedIn-0969DA?style=for-the-badge"></a>
  <a href="https://ifanferdi.github.io"><img alt="View portfolio" src="https://img.shields.io/badge/View_Portfolio-24292F?style=for-the-badge&amp;logo=github&amp;logoColor=white"></a>
</p>

---

I’m a backend developer based in Indonesia with 4+ years of experience. I build APIs for web applications, from authentication and role-based access to database queries and background jobs.

## Tech stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-226A38?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-24292F?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-34435D?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-A8281F?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-B24800?style=flat-square&logo=rabbitmq&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-B62B22?style=flat-square&logo=laravel&logoColor=white)

| Area | Technologies |
| --- | --- |
| Backend | TypeScript, JavaScript, PHP, Node.js, Bun, Express.js, Hono, Laravel |
| Frontend | React, Next.js (App Router), Tailwind CSS, shadcn/ui, Radix UI, TanStack Query, React Hook Form |
| Data | PostgreSQL, MySQL, MongoDB, Prisma |
| Messaging & jobs | RabbitMQ, Redis, Redis Pub/Sub, BullMQ |
| APIs & real-time | REST, gRPC, WebSocket, Socket.IO, Server-Sent Events (SSE), Zod |
| Authentication | NextAuth.js, JWT, Argon2, role-based access control (RBAC) |
| Video & streaming | FFmpeg, adaptive HLS, Video.js |

## Tools and integrations

- **Development & deployment** · Git, Docker, Docker Compose, ESLint, Prettier
- **APIs & infrastructure** · Swagger UI, Kong API Gateway
- **Object storage & search** · AWS SDK for S3, MinIO, Silo, Meilisearch
- **Payments & email** · Midtrans, Nodemailer
- **Observability & queue monitoring** · Sentry, OpenTelemetry, Bull Board

**Architecture** · Modular monoliths, microservices, domain-driven design (DDD), event-driven architecture

**Foundational experience** · Go, Fiber, NestJS, Kafka, Elasticsearch, Zustand

## Backend case studies

| Problem | What I changed |
| --- | --- |
| Clients received related data they rarely needed. | Returned essential fields by default in Prisma and let clients request specific, approved relations with a validated `with` parameter. |
| Failed jobs held up message processing. | Scaled RabbitMQ workers and used a dead-letter queue to handle retries. Logged messages that kept failing so they could be investigated. |

---

Need an API, a backend integration, or help improving an existing service? [Tell me about your project](https://www.linkedin.com/in/ifanferdi).
