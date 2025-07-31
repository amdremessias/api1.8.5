# api1.8.5
#deploy local m3ss14s lab -> api.homelab.mordor
#préconfigurado
#teste de cnx QR WPP ok!
use as veses:
docker compose down -v --remove-orphans
sudo systemctl restart docker
docker compose down -v --remove-orphans --rmi all
