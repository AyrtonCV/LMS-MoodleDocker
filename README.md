# LMS-MoodleDocker
Archivo con los pasos de lo que se realizo en la clase con la mac

## Para clonar el repositorio desde el sitio oficial se puede usar el siguiente comando:
git clone -b MOODLE_310_STABLE git://git.moodle.org/moodle.git

## Instalar Docker compose de LMS - Moodle
Usar el comando
curl -sSL https://raw.githubusercontent.com/bitnami/containers/main/bitnami/moodle/docker-compose.yml > docker-compose.yml

## Para levantar el docker compose usar el comando
docker-compose up -d

![(imgs/1.jpeg)](https://github.com/AyrtonCV/LMS-MoodleDocker/blob/55a3f1574b154e51b92f87dcec29385e09cb8210/imgs/1.jpeg)

## Si se necesita detener el contenedor usar
docker compose stop

## 1) Entrar a localhost con las siguientes credenciales
user = user 
Password = bitnami

## 2) Crear el curso 1
## 3) Crear el curso con el nombre que se seleccione asi como las fechas y datos que se muestren

## 4) Ir a la pestaña de administracion del sitio e ir a "add a new user"
## 5) Antes pide seleccion de tipo, estudiante o maestro
## 6) Ir creando los usuarios, como se muestra acontinuacion. El username debe ser en minusculas y la contraseña debe contener minimo 8 caracteres, numeros y un caracter especial


## 7) Para iniciar sesion usamos el nombre de usuario que se habia creado asi como la contraseña que se creo

