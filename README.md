# Infrastructure AI Agents

Набор специализированных AI-агентов для управления инфраструктурой, безопасности и мониторинга.

Форк [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) — оставлены только агенты, релевантные для инфраструктурных задач.

## Агенты

| Агент | Файл | Задачи |
|---|---|---|
| 🔒 Security Engineer | `engineering-security-engineer.md` | Пентест, аудит безопасности, threat modeling, secure code review |
| 🛡️ SRE | `engineering-sre.md` | SLO/SLI, observability, error budgets, chaos engineering |
| 🚀 DevOps Automator | `engineering-devops-automator.md` | CI/CD, IaC, автоматизация деплоя, cloud ops |
| 🎯 Threat Detection | `engineering-threat-detection-engineer.md` | SIEM правила, threat hunting, ATT&CK mapping |
| 🏢 Infrastructure Maintainer | `support-infrastructure-maintainer.md` | Мониторинг, reliability, performance, обслуживание |

## Использование

Агенты — это промпт-файлы с описанием роли, процессов и deliverables. Подключаются к Claude Code, Cursor, OpenClaw и другим AI-инструментам.

```bash
# OpenClaw — скопировать как workspace
cp agents/*.md ~/.openclaw/agents/

# Claude Code
cp agents/*.md ~/.claude/agents/
```

## Лицензия

MIT — см. [LICENSE](LICENSE)
