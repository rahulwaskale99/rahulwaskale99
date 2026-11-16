# Hi, I'm Rahul 👋

Java backend developer building focused, production-style projects — where the concurrency design, the tests and the trade-offs are documented, not just the features.

## 🔨 Projects I'm actively working on

### [rate-limiter](https://github.com/rahulwaskale99/rate-limiter)
Zero-dependency Java 21 rate limiting library.
- Lock-free token bucket & fixed window (CAS loops), sliding window log with a documented trade-off
- Deterministic unit tests via an injected clock, plus a 1000-thread virtual-thread stress test proving no over-admission
- Working on: composite limiters, keyed registry, Redis-backed distributed bucket

### [log-analyzer](https://github.com/rahulwaskale99/log-analyzer)
Zero-dependency CLI that turns log files into insight.
- Streaming parser that folds multi-line stack traces into entries
- Message normalization (ids → `*`) that groups "the same error" across thousands of lines
- Burst detection with a resetting sliding window; text & JSON reports

### [expense-tracker-api](https://github.com/rahulwaskale99/expense-tracker-api)
Spring Boot 3 REST API for personal expenses (PostgreSQL-ready).
- CRUD with bean validation and consistent error shaping via `@RestControllerAdvice`
- Monthly summaries aggregated in SQL through interface projections
- Test pyramid: Mockito unit tests + MockMvc web-layer tests

## 🧠 What I care about in code
- Small, honest abstractions — trade-offs documented where the decision was made
- Tests that pin down real behavior, including real concurrency tests
- Zero dependencies where zero dependencies make sense

## 📫 Reach me
- Open an issue on any of the repos above — that's the fastest way.
