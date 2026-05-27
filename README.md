# ##SpendSense 💸

A Django-based expense tracking web application containerized with Docker.

---

## 📌 Requirements

Before running the project, make sure you have the following installed:

- Docker Desktop
- Docker Hub account
- Git

---

## 🚀 Run Locally (Build from Source)

Clone the repository:

```bash
git clone https://github.com/fraaays/SpendSense.git
```

Go to the project directory:

```bash
cd SpendSense
```

Build and run the containers:

```bash
docker compose up --build
```

Access the application at:

```plaintext
http://localhost:8000
```

---

## 🐳 Run from Docker Hub (Client Setup)

Go to the client setup folder:

```bash
cd for_client
```

Run the containers:

```bash
docker compose up -d
```

Access the application at:

```plaintext
http://localhost:8000
```

---

## 👤 First Time Setup

Create a Django superuser account:

```bash
docker compose exec web python manage.py createsuperuser
```

Follow the prompts to create your admin account.

---

## 🛠️ Tech Stack

- Python
- Django
- Docker
- Docker Compose
- SQLite/PostgreSQL

---

## 📂 Project Structure

```plaintext
SpendSense/
│── for_client/
│── app/
│── docker-compose.yml
│── Dockerfile
│── manage.py
│── requirements.txt
```

---

## 📧 Author
 ### Frilyn Alicos & Ace Carl Dela Cruz
