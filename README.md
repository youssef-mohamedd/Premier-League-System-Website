**PremierZone Backend **⚽
A RESTful API for Premier League Player Statistics & Management

📌 Overview
A Spring Boot backend system for managing Premier League player data, featuring:

CRUD operations for 700+ players

Dynamic filtering (by team, position, nationality, etc.)

PostgreSQL database integration

Clean architecture with controllers, services, and repositories

**🛠 Technologies**
Category	Tech Stack
Backend	Java 17, Spring Boot 3
Database	PostgreSQL
API Docs	OpenAPI (Swagger) (optional)
Build Tool	Maven
🚀 Features
1. Player Management
✅ Add new players

✅ Update existing player stats

✅ Delete players

✅ Filter players by:



**2. API Endpoints**
HTTP Method	Endpoint	Description
GET	/api/v1/player	Get all players (with filters)
POST	/api/v1/player	Add a new player
PUT	/api/v1/player	Update player stats
DELETE	/api/v1/player/{name}	Delete a player by name
