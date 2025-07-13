# 🚆 RailSathi Complaint API

A FastAPI-based microservice to manage rail-related complaints, dockerized with PostgreSQL.

---

## 📦 Project Structure

RailSathiBE/
├── pycache/ # Compiled Python files
├── templates/ # Email templates (if used)
├── utils/ # Utility/helper functions
├── .env # Environment config (keep secret)
├── .gitignore # Git ignore rules
├── database.py # DB setup with SQLAlchemy
├── docker-compose.yml # Docker services
├── Dockerfile # FastAPI container config
├── logger_config.py # Logging configuration
├── mail_config.py # Mail server setup
├── main.py # Entry point of the FastAPI app
├── README.md # Project documentation
├── requirements.txt # Python dependencies
├── services.py # Business logic/service layer
└── test_email.py # Email test script


---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/RailSathiBE.git
cd RailSathiBE


### 2. Create .env File

POSTGRES_DB=railsathi
POSTGRES_USER=postgres
POSTGRES_PASSWORD=yourpassword

### 3. Run the App with Docker
```bash
docker-compose up --build

FastAPI will run on: http://localhost:5002
PostgreSQL DB on: localhost:5432