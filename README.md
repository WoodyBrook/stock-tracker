# Stock Tracker

Spring Boot REST API for tracking stocks and historical prices (Module 09 CI lab).

![CI](https://github.com/YOUR-USERNAME/stock-tracker/actions/workflows/ci.yml/badge.svg)

## Build & test

```bash
mvn -B package -DskipTests
mvn -B test
```

## CI

GitHub Actions (`.github/workflows/ci.yml`) runs on every push and pull request to `main`:
1. Checkout
2. Set up JDK 21 (Temurin) with Maven cache
3. Build (`mvn -B package -DskipTests`)
4. Test (`mvn -B test`)
