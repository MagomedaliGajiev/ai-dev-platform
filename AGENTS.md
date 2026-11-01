# AI Dev Platform

Платформа для AI-first разработки: связывает сотрудников, проекты, агентов и правила компании.

- Требования и границы первой версии: [docs/requirements.md](docs/requirements.md).
- Процесс работы и проверки: [docs/workflow.md](docs/workflow.md).
- Проектные скиллы: [.agents/skills](.agents/skills/) для Codex и [.claude/skills](.claude/skills/) для Claude Code.

## Agent skills

### Issue tracker

Задачи и спецификации ведём в GitHub Issues этого репозитория через `gh`. Перед работой с задачами читайте [настройку трекера](docs/agents/issue-tracker.md).

### Triage labels

При разборе задач используйте стандартные роли и [соответствие пометок](docs/agents/triage-labels.md).

### Domain docs

Один контекст: `DOMAIN.md` в корне и решения в `docs/adr/`. Перед исследованием предметной области читайте [правила работы со словарём и решениями](docs/agents/domain.md).
