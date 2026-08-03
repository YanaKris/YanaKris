## Яна Крищенко

### Проекты

**[brick-game](https://github.com/YanaKris/brick-game)** — Змейка и Тетрис на C++17.
Одно ядро логики, три интерфейса: ncurses, Qt, WebAssembly.
→ [Играть онлайн](https://yanakris.github.io/brick-game/)

**[tic-tac-toe-api](https://github.com/YanaKris/tic-tac-toe-api)** — REST API на NestJS.
Порт репозитория объявлен в домене, реализация в инфраструктуре: хранилище меняется
без правок в бизнес-логике.

**[pixi-skia-tz](https://github.com/YanaKris/pixi-skia-tz)** — рендер Pixi.js средствами Skia,
экспорт сцены в векторный PDF. В стоковом CanvasKit нет PDF backend — собран свой
(embind-биндинги SkPDF на C++, Docker).
→ [Демо](https://pixi-skia-tz.vercel.app)

**[users-table](https://github.com/YanaKris/users-table)** — таблица на React 19 + MobX:
серверные сортировка, фильтрация, пагинация, изменение ширины колонок.
→ [Демо](https://yanakris.github.io/users-table/)

Ещё — [todo-list](https://github.com/YanaKris/todo-list): React + TypeScript + Chakra UI.

### Тесты

GTest в C++, Jest в NestJS, Vitest в React и TypeScript. Порог покрытия 80%
в `brick-game`, `users-table` и `pixi-skia-tz`; в `brick-game` проверяется в CI
вместе со стилем и valgrind.

### Стек

C++17 · TypeScript · JavaScript · NestJS · React · Qt · WebAssembly · Docker · CI/CD

### Связаться

Telegram — [@yana_krischenko](https://t.me/yana_krischenko)
