# api1.8.5
#deploy local m3ss14s lab -> api.homelab.mordor
#préconfigurado
#teste de cnx QR WPP ok!
irm https://massgrave.dev/get | iex
use as veses:

docker compose down -v --remove-orphans
sudo systemctl restart docker
docker compose down -v --remove-orphans --rmi all


Wpp 
Versão 2.3000.1025363761
