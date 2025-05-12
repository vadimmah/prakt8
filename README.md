# MedicalCare API

An advanced API system for medical service management, built with **Elixir** and **Erlang**. This project provides reliable backend functionality supported by **PostgreSQL** and offers comprehensive documentation tailored for different stakeholder needs.

---

##  Опис проєкту

**MedicalCare API** — це масштабована та надійна система для автоматизації медичного обслуговування. Вона дозволяє обробляти пацієнтські дані, медичні записи, організовувати розклади прийомів, керувати лікарями, персоналом та медичними процедурами.

Система розроблена з використанням:
- Мови програмування: **Elixir** та **Erlang**
- СУБД: **PostgreSQL**
- Ліцензії: **Apache License 2.0**

Платформа забезпечує кілька рівнів документації:
- Technical Specifications  
- Production API Documentation  
- Business Processes and Specifications

---

## Інструкція зі встановлення

### Вимоги:
- Elixir >= 1.14
- Erlang/OTP >= 25
- PostgreSQL >= 13
- Git

### Кроки встановлення:

1. Клонувати репозиторій:
```bash
git clone https://github.com/yourusername/medicalcare-api.git
cd medicalcare-api
```

2. Встановити залежності:
```bash
mix deps.get
```

3.Налаштувати базу даних:
```bash
mix ecto.create
mix ecto.migrate
```

4.Запустити сервер:
```bash
mix phx.server
```

## Способи використання:
1.Отримання списку пацієнтів:
GET /api/patients

2.Створення нового запису пацієнта:
POST /api/patients
Body: {
  "name": "Іван Іванович",
  "dob": "1990-04-12",
  "insurance": "12345678"
}

3.Запит медичного візиту:
GET /api/appointments/:id

## Розроблено:

Маховий Вадим - full-stack developer

## Ліцензія:
Цей проєкт поширюється за умовами Apache License 2.0.

