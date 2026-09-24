# CLAUDE.md

Guidance for Claude Code when working in this repository.

## Project

Spring Boot + Kafka microservices implementing the orchestrated SAGA pattern.
Services: `order-service`, `orchestrator-service`, `payment-service`,
`product-validation-service`, `inventory-service`. Infra is defined in
`docker-compose.yml`.

## Rules

- Never run `git commit` or `git push`. Prepare and stage changes as
  requested, but leave committing and pushing to the user.
