# LMS-MoodleDocker
Archivo con los pasos de lo que se realizo en la clase con la mac

Integrantes:

Caamal Ku Laura Guadalupe

Canto Medina Rogelio Andres

Caballero Viera Ayrton Enrique (Presenta en este GitHub el README y lo solicitado)

## Para clonar el repositorio desde el sitio oficial se puede usar el siguiente comando:
git clone -b MOODLE_310_STABLE git://git.moodle.org/moodle.git

## Instalar Docker compose de LMS - Moodle, Usar el comando

curl -sSL https://raw.githubusercontent.com/bitnami/containers/main/bitnami/moodle/docker-compose.yml > docker-compose.yml

## Para levantar el docker compose usar el comando
docker-compose up -d

![(imgs/1.jpeg)](https://github.com/AyrtonCV/LMS-MoodleDocker/blob/026e8b2351c43a413b03652ae95c115e9b1f9010/imgs/1.jpeg)

## Si se necesita detener el contenedor usar
docker compose stop

## 1) Entrar a localhost con las siguientes credenciales
user = user 

Password = bitnami

![(imgs/2.png)](https://github.com/AyrtonCV/LMS-MoodleDocker/blob/026e8b2351c43a413b03652ae95c115e9b1f9010/imgs/2.png)

## 2) Crear el curso 1

![(imgs/4.png)](https://github.com/AyrtonCV/LMS-MoodleDocker/blob/6798c87a7ec2f28e5a56d65d555ce1d53115a4b2/imgs/4.jpeg)

## 3) Crear el curso con el nombre que se seleccione asi como las fechas y datos que se muestren

## 4) Ir a la pestaña de administracion del sitio e ir a "add a new user"

![(imgs/3.png)](https://github.com/AyrtonCV/LMS-MoodleDocker/blob/7a210bd997d9ac4a0f4f5d403410aea6b4121169/imgs/3.png)

## 5) Antes pide seleccion de tipo, estudiante o maestro
## 6) Ir creando los usuarios, como se muestra acontinuacion. El username debe ser en minusculas y la contraseña debe contener minimo 8 caracteres, numeros y un caracter especial

![(imgs/5.png)](https://github.com/AyrtonCV/LMS-MoodleDocker/blob/a852ca1bb8afb84672dcbc1d5cba189fd143ac61/imgs/5.jpeg)

![(imgs/7.png)](https://github.com/AyrtonCV/LMS-MoodleDocker/blob/a852ca1bb8afb84672dcbc1d5cba189fd143ac61/imgs/7.jpeg)

## 7) Para iniciar sesion usamos el nombre de usuario que se habia creado asi como la contraseña que se creo

![(imgs/9.png)](https://github.com/AyrtonCV/LMS-MoodleDocker/blob/5ff6d8653748fd3ff97868326d83bf0946747d0a/imgs/9.jpeg)

Conclusiones por cada integrante:

Rogelio: En esta actividad no tuvimos complicaciones debido a que ya habiamos realizado la practica anteriormente en equipo pero en nuestra propia maquina, el docker levanta los servicios de Moodle y configura el uso de volumenes lo cual lo hace sencillo

Laura: Esta practica fue sencilla el uso de docker y el comando nos ahorro mucho la practica asi como el levantamiento para el moodle sin olvidar que el propio Moodle es facil de entender una vez en el localHost debido a su intuitiva interfaz

Ayrton: En el ejercicio pudimos realizar algo visto anteriormente en otra actividad donde en este caso lo senti algo mas sencillo, la parte de crear usuarios es donde si se debe tener mucho cuidado debido a parte de sus propias reglas que establece como minusculas o caracteres especiales