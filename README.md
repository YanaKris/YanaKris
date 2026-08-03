## Яна Крищенко

### Проекты

**[brick-game](https://github.com/YanaKris/brick-game)** — Змейка и Тетрис на C++17.
Библиотека логики отделена от интерфейсов: три представления над одним ядром — консоль
(ncurses), десктоп (Qt) и веб (WebAssembly). Логика формализована конечным автоматом.
CI прогоняет проверку стиля, тесты, покрытие и valgrind.
→ [Играть онлайн](https://yanakris.github.io/brick-game/)

**[tic-tac-toe-api](https://github.com/YanaKris/tic-tac-toe-api)** — REST API на NestJS
со слоями domain / datasource / web. Домен объявляет порт репозитория, инфраструктура его
реализует — хранилище заменяется без единой правки в бизнес-логике. Ход компьютера
считается минимаксом с полным перебором.

**[pixi-skia-tz](https://github.com/YanaKris/pixi-skia-tz)** — рендер Pixi.js средствами
Skia (CanvasKit/WASM) с экспортом сцены в векторный PDF. Стоковый CanvasKit не содержит
PDF backend, поэтому собран свой: embind-биндинги SkPDF на C++, патч GN-таргета,
воспроизводимое окружение в Docker.
→ [Демо](https://pixi-skia-tz.vercel.app)

**[users-table](https://github.com/YanaKris/users-table)** — таблица пользователей
на React 19 + MobX: серверные сортировка, фильтрация и пагинация, изменение ширины колонок.
→ [Демо](https://yanakris.github.io/users-table/)

Ещё — [todo-list](https://github.com/YanaKris/todo-list): React + TypeScript + Chakra UI.

### Тесты

Тесты есть в каждом проекте, в трёх экосистемах: GTest в C++, Jest в NestJS,
Vitest в React и TypeScript. В `brick-game`, `users-table` и `pixi-skia-tz` настроен
порог покрытия 80%; в `brick-game` он проверяется в CI вместе со стилем и valgrind.

### Стек

C++17 · TypeScript · JavaScript · NestJS · React · Qt · WebAssembly · Docker · CI/CD

### Связаться

Telegram — [@yana_krischenko](https://t.me/yana_krischenko)
