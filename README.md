# Hi, I'm Rahul 👋

Java backend developer building focused, production-style projects — where the concurrency design, the tests and the trade-offs are documented, not just the features.

## Selected projects

### [rate-limiter](https://github.com/rahulwaskale99/rate-limiter)
Zero-dependency Java 21 rate limiting library.
- Token bucket and fixed window use CAS-based state updates; sliding window uses a short synchronized section
- Tests cover fake-clock behavior and a 1,000-virtual-thread contention check for admission limits
- Not in this version: composite limiters, keyed registry, and Redis-backed distributed limits

### [log-analyzer](https://github.com/rahulwaskale99/log-analyzer)
Zero-dependency CLI that turns log files into insight.
- Streaming parser that folds multi-line stack traces into entries
- Message normalization (ids → `*`) that groups "the same error" across thousands of lines
- Burst detection with a resetting sliding window; text & JSON reports

### [expense-tracker-api](https://github.com/rahulwaskale99/expense-tracker-api)
Spring Boot 3 REST API for personal expenses, with a PostgreSQL profile.
- CRUD with bean validation and consistent error shaping via `@RestControllerAdvice`
- Monthly summaries aggregated in SQL through interface projections
- Tests: Mockito service tests + MockMvc web-layer tests

## 🧠 What I care about in code
- Small, honest abstractions — trade-offs documented where the decision was made
- Tests that pin down real behavior, including real concurrency tests
- Zero dependencies where zero dependencies make sense

## 📫 Reach me
- Open an issue on any of the repos above — that's the fastest way.
