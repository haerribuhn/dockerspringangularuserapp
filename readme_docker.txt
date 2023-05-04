# Build backend with gradle

# build docker image for backend
cd backend
./docker_build.sh

# build docker image for frontend
cd frontend
./build_docker.sh

# Stop native mysql database
service mysql stop

# Start all services
cd docker
docker-compose up -d

# Browser
localhost:80

# Stop all services
docker-compose down

