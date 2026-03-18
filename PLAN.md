# PLAN — 61_Bortovoy_bot_app

## Этапы

### Этап 1 — Проектная документация
**Статус: ✅ завершён**

- [x] README.md
- [x] CONTEXT.md
- [x] GOALS.md
- [x] CONDITIONS_n_CONSTRAINTS.md
- [x] PLAN.md
- [x] FACTS.md
- [x] BACKLOG.md

### Этап 2 — HTML Mini App
**Статус: ✅ завершён**

- [x] Создать `index.html` на основе шаблона с кастомизацией под @bortovoyzhurnal
  - Название: «Ключ к реальному управлению»
  - Username: @bortovoyzhurnal
  - Навигация: Обучение, Проекты, Консультации, Управленческий спецназ

### Этап 3 — GitHub Pages
**Статус: ✅ завершён**

- [x] Создать публичный GitHub-репозиторий
- [x] Запушить `index.html`
- [x] Включить GitHub Pages
- [x] Записать URL в FACTS.md

### Этап 4 — BotFather (выполняет пользователь)
**Статус: ⏳ ожидает**

- [ ] Создать нового бота: `/newbot` в @BotFather
- [ ] Bot Settings → Configure Mini App → указать URL и текст «Услуги центра»
- [ ] Добавить бота администратором в @bortovoyzhurnal

### Этап 5 — Проверка
**Статус: ⏳ ожидает**

- [ ] Открыть канал в Telegram Desktop — проверить кнопку
- [ ] Открыть канал в Telegram Mobile — проверить кнопку
- [ ] Нажать кнопку — убедиться, что Mini App открывается корректно

---

## Текущий фокус

Этапы 1–3 выполнены. Ожидается действие пользователя: создать бота в BotFather и настроить Mini App.

## Следующий шаг

Открыть [@BotFather](https://t.me/BotFather) → `/newbot` → создать бота для @bortovoyzhurnal.
Инструкция: [FACTS.md](FACTS.md) (раздел «Инструкция BotFather»).
