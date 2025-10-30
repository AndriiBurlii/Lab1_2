# 🪐 CosmoCats — Лабораторна робота 1.2 (KPI)
**Автор:** Андрій Бурлій (ІО-32, КПІ)

## Мета
Покрити функціонал CosmoCats юніт-тестами, перевірити CI через GitHub Actions та згенерувати JaCoCo coverage.

## Технології
- Java 23
- Gradle 8.10.1
- Spring Boot 3.3.4
- JUnit 5, Mockito 5.11.0
- JaCoCo, WireMock
- GitHub Actions (CI)

## Як запустити тести локально
```bash
gradlew clean test jacocoTestReport
```
