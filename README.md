# 1. Uruchamianie aplikacji
## 1.1. Lokalnie
- Zainstaluj zależności `pip install -r requirements.txt`
- Uruchom serwer `gunicorn app:app`
## 1.2. Za pomocą Dockera
- Zbuduj obraz `docker build -t ml-api .`
- Uruchom kontener `docker run -d -p 8000:8000 ml-api`
## 1.3. Za pomocą Docker Compose
- Upewnij się, że plik `docker-compose.yml` jest w katalogu głównym projektu
- Uruchom serwisy `docker-compose up --build`
# 2. Konfiguracja aplikacji
## 2.1. Konfiguracja parametrów
Zmienne środowiskowe
- `POSTGRES_USER`
- `POSTGRES_PASSWORD`
- `POSTGRES_DB`
## 2.2. Wymagane zasoby
- Python 3.11+
- Docker
- Docker Compose
