# ⚽ PremierZone Backend

A robust and scalable RESTful API built with **Spring Boot** for managing **Premier League** player data. Supports dynamic filtering, full CRUD operations, and PostgreSQL integration.

---

## 📌 Overview

This backend service is designed to manage data for over **700+ football players**, offering:

- ✅ Full CRUD operations
- ✅ Dynamic filtering by:
  - Team
  - Position
  - Nationality
  - Name
- ✅ Clean layered architecture (`Controller → Service → Repository`)
- ✅ Integrated with **PostgreSQL**

---

## 🛠 Tech Stack

| Category      | Technology                  |
|---------------|-----------------------------|
| Language      | Java 17                     |
| Framework     | Spring Boot 3               |
| Database      | PostgreSQL                  |
| Build Tool    | Maven                       |

---

## 🚀 Features

### 🎯 Player Management

- Add new players
- Update existing player data
- Delete players
- Filter players by:
  - Team
  - Position
  - Nationality
  - Name
  - Team & Position combined

---

## 📡 API Endpoints

| HTTP Method | Endpoint                     | Description                       |
|-------------|------------------------------|-----------------------------------|
| `GET`       | `/api/v1/player`             | Get all players (with filters)    |
| `POST`      | `/api/v1/player`             | Add a new player                  |
| `PUT`       | `/api/v1/player`             | Update a player's information     |
| `DELETE`    | `/api/v1/player/{name}`      | Delete a player by name           |

