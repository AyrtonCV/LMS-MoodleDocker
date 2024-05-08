# LMS-MoodleDocker

Para clonar el repositorio desde el sitio oficial se puede usar el siguiente comando:
# git clone -b MOODLE_310_STABLE git://git.moodle.org/moodle.git

Instalar Docker compose de LMS - Moodle
Usar el comando
# curl -sSL https://raw.githubusercontent.com/bitnami/containers/main/bitnami/moodle/docker-compose.yml > docker-compose.yml

Para levantar el docker compose usar el comando
# docker-compose up -d

(imgs/1)

Si se necesita detener el contenedor usar
# docker compose stop

