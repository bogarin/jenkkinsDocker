Jenkins on docker
---
intengrando un resetario para funcionar  y problema del volumen
---
>soluciona el problema:
si el directorio está vacío:
sudo chown 1000 volume_dir

>Si el directorio ya contiene archivos:
sudo chown -R 1000 volume_dir
---
para la instalación [docker y docker compose](ttps://www.digitalocean.com/community/tutorials/como-instalar-y-usar-docker-en-ubuntu-16-04-es)
