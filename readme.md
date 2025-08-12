kalau untuk di test di local lakukan dlu ini

sudo nano /etc/hosts

lalu tambahkan ini

127.0.0.1 portainer.localhost
127.0.0.1 laravel.localhost
127.0.0.1 pma.localhost

buat networks

docker network create --driver bridge portainer_networks
