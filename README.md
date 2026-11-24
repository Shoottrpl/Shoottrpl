# Hi, I'm a Python Backend Developer 👋

**3+ years of programming experience, including approximately 2 years building applications intended for real users.**

I develop Python backend systems, REST APIs, and integrations, focusing on business logic, data consistency, automated testing, and reliable deployment.

Разрабатываю backend-сервисы на Python/Django, REST API и интеграции для реальных задач.

## 🛠 Tech Stack

**Backend:** Python · Django · Django REST Framework · Celery · HTTPX · Pydantic

**Databases & Caching:** PostgreSQL · Redis · SQLite

**Testing & Quality:** pytest · respx · Ruff · mypy · FastAPI (mock API testing)

**Infrastructure:** Docker · Docker Compose · Linux · nginx · GitHub Actions · systemd

**Additional:** Next.js · TypeScript · Playwright

## 🚀 Projects

### Olex — E-commerce Platform

*Independently designed, built, and deployed e-commerce platform for aquarium products.*

**Status:** Live in production

**Backend engineering highlights:**

- Django REST Framework API with service-layer business logic
- Transactional checkout, PostgreSQL row locking, and conditional stock updates
- JWT authentication through a Next.js Backend-for-Frontend (BFF)
- Celery and Redis for background processing
- YooKassa integration with idempotent payment-state handling and refunds
- Automated testing, including PostgreSQL-specific locking tests
- Docker deployment on a Linux VPS with GitHub Actions CI/CD

**Live deployment:** https://olexaqua.ru (restricted via HTTP Basic Authentication)

**[Project overview & architecture](https://github.com/Shoottrpl/olex-showcase)**

*Application source code is private.*

### Secure Feed Connector — Backend Integration

*A production-oriented Python integration service for resilient external data ingestion and controlled file delivery.*

**Status:** Implemented and tested locally; target infrastructure acceptance pending.

**Backend engineering highlights:**

- HTTPX client with authenticated API access, bounded retries, and error classification
- Transactional SQLite state management and data-version tracking
- Dataset validation, SHA-256 integrity checks, and quarantine handling
- Staged output publication, execution locking, and recovery considerations
- Automated tests with pytest, respx, and a FastAPI mock server
- Scheduled Linux execution model using systemd

**[Project overview & architecture](https://github.com/Shoottrpl/secure-feed-connector-showcase)**

*Original application source code is private.*

## 📬 Contact

**Telegram:** [@Maksim_Golovlev](https://t.me/Maksim_Golovlev)
