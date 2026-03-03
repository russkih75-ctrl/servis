# servis

**Репозиторий:** https://github.com/russkih75-ctrl/servis

Один репозиторий — работа и в Cursor Web, и в десктопе. Всё синхронизируется через GitHub.

---

## Запуск веб-версии (всё уже настроено)

1. Откройте **https://cursor.com** и войдите в аккаунт.
2. Нажмите **Clone from GitHub** (или **Open from GitHub**).
3. Выберите репозиторий **russkih75-ctrl/servis** и откройте его.
4. Редактируйте код в браузере. Сохраняйте → делайте коммиты и push как в обычном Cursor — всё хранится в этом репозитории.

Настройки редактора (`.vscode/settings.json`) и структура проекта уже в репо — в веб-версии всё подхватится автоматически.

---

## Локально (если нужен десктоп)

```bash
git clone https://github.com/russkih75-ctrl/servis.git
cd servis
```

Дальше: `git add .` → `git commit -m "..."` → `git push`. Можно работать и в Cursor Web, и в десктопе с одного репо.

---

## Облачной агент (Cloud Agent)

Окружение для облака уже задано в репо (`.cursor/environment.json` + `AGENTS.md`).

1. **Один раз:** [cursor.com/onboard](https://cursor.com/onboard) → подключите GitHub и репозиторий **russkih75-ctrl/servis**.
2. **Каждый раз:** в чате агента выберите в выпадающем списке **«Cloud»** и отправьте задачу.

Подробно: [docs/CLOUD-AGENT.md](docs/CLOUD-AGENT.md).
