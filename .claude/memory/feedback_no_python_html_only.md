---
name: No Python files - HTML/Chart.js only
description: User prefers pure HTML+Chart.js dashboards, no Python script files as output
type: feedback
---

Не создавать Python-скрипты как конечный продукт. Дашборды — чистый HTML + Chart.js.

**Why:** Пользователь явно попросил "не используй Python только HTML/Chart.js". Python допускается только для извлечения данных из Excel (временно), но итоговый файл должен быть self-contained HTML.

**How to apply:** При создании дашбордов — данные встраивать напрямую в HTML как JS-переменные. Python-скрипты для извлечения — удалять после использования.
