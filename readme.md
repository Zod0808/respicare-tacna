# Clonar e inicializar proyecto
git clone <repo-url> respicare-tacna
cd respicare-tacna

# Setup inicial
make setup

# Construir y ejecutar
make build
make up

# Verificar que todo funciona
make health

# Ver logs en tiempo real
make dev

Puertos de Servicios incluidos:

Web Frontend (React) - Puerto 3000
Backend API (Node.js) - Puerto 3001
AI Services (Python/FastAPI) - Puerto 8000
MongoDB - Puerto 27017
Redis - Puerto 6379
Nginx (Proxy reverso) - Puerto 80/443
Adminer (Gestión BD) - Puerto 8080