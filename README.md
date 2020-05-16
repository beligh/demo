
docker-compose up -d
docker-compose down -v
docker ps
docker system prune -a --volumes

238dea96fc7f40da8fdc13fe38901d64
docker exec container-id bash
cat /var/jenkins_home/secrets/initialAdminPassword