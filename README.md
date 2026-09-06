## Кирилл Лоншаков

Fullstack-разработчик — C# / ASP.NET Core + React. Красноярск, открыт к удалённой работе.

Около 2 лет в разработке. Пишу серверную часть на ASP.NET Core, клиентскую — на React с TypeScript. Проектирую модель данных, разбираю требования, довожу проекты до эксплуатации.

### Стек

**Backend:** C#, ASP.NET Core 8/10, Entity Framework Core, MediatR (CQRS), FluentValidation, SignalR, JWT, ASP.NET Identity, REST, OpenAPI
**Frontend:** React 19, TypeScript, React Router, TanStack React Query, Vite, React Native (Expo)
**Базы данных:** PostgreSQL, MongoDB, MySQL
**Инструменты:** Git, Docker и Docker Compose, xUnit, Locust, nginx

### Проекты

**[BoxingCRM](https://github.com/CrispX13/BoxingCRM)** — мобильная CRM для школы бокса. *Коммерческий проект, в эксплуатации.*
React Native (Expo) + TypeScript, ASP.NET Core 10, EF Core, PostgreSQL.
Клиенты, абонементы, шаблоны абонементов, статусы. Аутентификация: BCrypt + JWT. Бэкенд развёрнут на удалённом сервере, приложение работает по HTTPS.

**[BoxingGym](https://github.com/CrispX13/BoxingGym)** — веб-версия той же системы, предшественник BoxingCRM.
.NET 10, PostgreSQL, EF Core, ASP.NET Identity, React 19 + TypeScript.
Чистая архитектура (Domain / Application / Infrastructure / Contracts), CQRS на MediatR, валидация через pipeline behavior. ~5 000 строк backend и ~2 700 строк frontend.

**[Timesheet App](https://github.com/CrispX13/timesheet-app)** — учёт трудозатрат и стоимости работ.
.NET 8, MongoDB, React 19 + TypeScript, Docker.
Стоимость считается по ставке, действовавшей на дату записи; списки и отчёты целиком строятся aggregation pipeline на стороне MongoDB. 16 юнит-тестов xUnit. Стенд поднимается одной командой `docker compose up`.

**[Online Chat](https://github.com/CrispX13/online-chat)** — мессенджер с личными и групповыми чатами.
ASP.NET Core 8, PostgreSQL, EF Core, SignalR, React 19 + Vite.
Обмен сообщениями в реальном времени через SignalR-хаб с авторизацией по JWT. Нагрузочное тестирование Locust на 20/50/100 одновременных пользователей.

### Контакты

- Сайт-визитка: https://crispx13.github.io/personal-site-card/
- Почта: trololonik@inbox.ru
## Hi there 👋

<!--
**CrispX13/CrispX13** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
