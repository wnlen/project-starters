```
# Project Starters

<p align="center">
English | <a href="README.zh-CN.md">简体中文</a>
</p>

A collection of **ready-to-run project starters** for modern backend and frontend applications.

Clone → rename → start building.

---

## Purpose

Starting a new project should not require rebuilding the same infrastructure every time.

This repository provides **minimal but production-ready starters** so you can begin development immediately.

Each starter includes:

- basic project structure
- build configuration
- deploy scripts
- infrastructure setup

---

## Available Starters

### Java API Starter

Spring Boot backend starter with production-ready structure.

Includes:

- Spring Boot application
- Maven configuration
- deploy scripts
- systemd service template
- production configuration examples

---

### Java Multi-Module Starter

Spring Boot multi-module architecture.

Includes:

- parent pom
- modular service structure
- shared library modules

---

### Vue Admin Starter

Vue 3 + Vite admin application starter.

Includes:

- Vite configuration
- API request wrapper
- permission guards
- Nginx deployment configuration

---

### UniApp Starter

Starter template for UniApp applications.

Includes:

- project structure
- build configuration
- deployment notes

---

## Repository Structure
```

starters/
 java-api-starter/
 java-multi-module-starter/
 vue-admin-starter/
 uniapp-starter/

docs/

```
---

## Quick Start

Example: start a new Java backend project.

```bash
git clone https://github.com/yourname/project-starters

cd starters/java-api-starter

# rename the project folder
mv java-api-starter my-api

# start development
mvn spring-boot:run
```

------

## Deployment

Each starter includes basic deployment support:

- deploy scripts
- rollback scripts
- systemd services
- production configuration templates

For detailed deployment instructions, see the documentation in each starter.

------

## Related Repository

Reusable templates and infrastructure patterns live here:

👉 https://github.com/yourname/awesome-engineering-templates

------

## Philosophy

These starters follow three principles:

1. **Simple structure**
2. **Production readiness**
3. **Fast project bootstrapping**

The goal is to reduce setup time so you can focus on building actual features.

------

## License

MIT