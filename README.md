 ##SpendSense 💸
A Django-based expense tracking web application containerized with Docker.

Requirements
Docker Desktop installed
Docker Hub account
Run Locally (Build from Source)
git clone https://github.com/fraaays/SpendSense.git
cd SpendSense
docker compose up --build
Access at: http://localhost:8000

Run from Docker Hub (Client Setup)
cd for_client
docker compose up -d
Access at: http://localhost:8000

First Time Setup
docker compose exec web python manage.py createsuperuser
