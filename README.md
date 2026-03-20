# AI-coding: Best Practices (RU)

Коллекция переводов и адаптаций ключевых статей о программировании с помощью AI на русский язык.

---

## 1. Глубокое погружение

Перевод и адаптация статьи **Tw93** об архитектуре, управлении и инженерных практиках Claude Code.

### Оригинал
- Автор: [Tw93](https://x.com/HiTw93)
- Статья: [tw93.fun/en/2026-03-12/claude.html](https://tw93.fun/en/2026-03-12/claude.html)

### Что внутри
- Полный перевод на русский язык (23 страницы)
- Оригинальные иллюстрации из поста
- Дополнения Claude Opus 4.6 с актуальными best practices на март 2026

### Скачать
- [claude_code_handbook_ru.pdf](./claude_code_handbook_ru.pdf)

---

## 2. Skills — уроки из создания Claude Code

Полный перевод статьи **Thariq** «Lessons from Building Claude Code: How We Use Skills» (17 марта 2026) — все 9 категорий скиллов с примерами, все советы по созданию, секция по распространению в команде.

### Оригинал
- Автор: [Thariq](https://x.com/trq212)
- Статья: опубликована 17 марта 2026

### Что внутри
- 11 оригинальных изображений из поста — grid категорий, примеры SKILL.md, gotchas, progressive disclosure, скоупированные хуки
- Дополнения Opus 4.6 в жёлтых блоках — привязка к multi-agent SDLC, практический план внедрения, пояснения для нетехнических PO

### Скачать
- [claude_code_skills_ru.pdf](./claude_code_skills_ru.pdf)

---

## 3. Как я использую Claude Code — Boris Tane

Перевод статьи **Boris Tane** «How I Use Claude Code» (10 февраля 2026) — дисциплинированный workflow из трёх фаз: Research → Plan → Implement, с циклом аннотаций как ключевым элементом контроля качества.

### Оригинал
- Автор: [Boris Tane](https://x.com/boristane)
- Статья: [boristane.com/blog/how-i-use-claude-code/](https://boristane.com/blog/how-i-use-claude-code/)

### Что внутри
- Фаза исследования: research.md как «контекстный снимок» системы
- Фаза планирования: plan.md вместо встроенного plan mode
- Цикл аннотаций (1–6 раундов) — инжекция доменных знаний через inline-заметки
- Промпты имплементации и паттерны обратной связи
- Дополнения Opus 4.6 — связь с multi-agent SDLC и паттерном HANDOFF.md

### Скачать
- [boris_tane_claude_code_ru.pdf](./boris_tane_claude_code_ru.pdf)

---

## 4. 50 советов и лучших практик Claude Code

Перевод треда **Vishwas (Codevolution)** «50 Claude Code Tips and Best Practices For Daily Use» (19 марта 2026) — 50 практических советов от настройки и основ до продвинутых паттернов работы с Claude Code.

### Оригинал
- Автор: [Vishwas / Codevolution](https://x.com/CodevolutionWeb)
- Тред: [x.com/CodevolutionWeb/status/2034683638382506063](https://x.com/CodevolutionWeb/status/2034683638382506063)

### Что внутри
- Настройка и основы: алиасы, горячие клавиши, LSP-плагины
- Качество и обратная связь: тесты, линтеры, скриншоты
- CLAUDE.md, хуки, MCP-серверы, мультиагентные паттерны
- Дополнения Opus 4.6 в жёлтых блоках

### Скачать
- [50_claude_code_tips_ru.pdf](./50_claude_code_tips_ru.pdf)

---

## 5. Как я работаю с AI-агентами для кодинга — Daz

Перевод статьи **Daz (Darren)** «How I Work with AI Coding Agents» (1 марта 2026) — взгляд tech lead с 25+ лет опыта: LLM stateless, набор инструментов вместо пайплайна, три точки ревью, управление контекстом и когнитивный долг.

### Оригинал
- Автор: [Daz (Darren)](https://daz.is) — tech lead, 25+ лет в разработке
- Статья: [daz.is/blog/how-i-work-with-ai-coding-agents/](https://daz.is/blog/how-i-work-with-ai-coding-agents/)

### Что внутри
- Ключевой принцип: LLM stateless — каждый запуск начинается с нуля
- Research → Plan → Implement как набор инструментов, а не жёсткий пайплайн
- Три точки ревью вместо одной; бутылочное горлышко ревью
- Конфигурация: детерминированное vs. инструкции; когнитивный долг
- Дополнения Opus 4.6 — связь с workflow Boris Tane и Tw93

### Скачать
- [daz_ai_coding_agents_ru.pdf](./daz_ai_coding_agents_ru.pdf)

---

## 6. Я построил язык программирования с Claude Code — Ankur Sethi

Перевод статьи **Ankur Sethi** «I built a programming language using Claude Code» (10 марта 2026) — кейс создания языка Cutlet за 4 недели и четыре ключевых навыка агентной инженерии.

### Оригинал
- Автор: [Ankur Sethi](https://ankursethi.com) — фронтенд-разработчик, независимый консультант ([github.com/s3thi](https://github.com/s3thi))
- Статья: [ankursethi.com/blog/programming-language-claude-code/](https://ankursethi.com/blog/programming-language-claude-code/)

### Что внутри
- Кейс: язык Cutlet (лексер, парсер, интерпретатор, REPL) за 4 недели
- 4 навыка агентной инженерии: понимание задач LLM, коммуникация намерений, среда для агента, оптимизация цикла
- Размышления: мертва ли software engineering, кредит за работу Claude, влияние на ментальное здоровье
- Дополнения Opus 4.6

### Скачать
- [ankur_sethi_cutlet_ru.pdf](./ankur_sethi_cutlet_ru.pdf)

---

## 7. Мой опыт с Claude Code — Bruce Wilson

Перевод статьи **Bruce E. Wilson** «My Experience with Claude Code: AI-Assisted Development in Practice» (11 марта 2026) — опыт учёного-практика (химик, 25+ лет в разработке, Oak Ridge National Laboratory), вернувшегося к программированию после долгого перерыва.

### Оригинал
- Автор: [Bruce E. Wilson](https://x.com/usethedata) — Distinguished R&D Staff, Oak Ridge National Laboratory ([github.com/usethedata](https://github.com/usethedata))
- Статья: [podfeet.com/blog/2026/03/claude-code-bruce/](https://www.podfeet.com/blog/2026/03/claude-code-bruce/) (Podfeet Podcasts)

### Что внутри
- Контекст: доменный эксперт, а не профессиональный разработчик
- Четыре ключевых наблюдения о работе с Claude Code
- CLAUDE.md как контекст проекта; токены и rate limits
- Итеративное определение фич; рабочий workflow разработки
- Вопросы о trade-offs; дополнения Opus 4.6

### Скачать
- [bruce_wilson_claude_code_ru.pdf](./bruce_wilson_claude_code_ru.pdf)

---

## Подготовил
- [alienxs2](https://github.com/alienxs2)
- Перевод и дополнения: Claude Opus 4.6 (Anthropic)
