# DevOps-Challenge

DevOps Challenge - Dockerización de aplicaciones Flask y Angular
Se dockerizaron dos aplicaciones web: 
una desarrollada en Flask y otra en Angular. 
A continuación, se proporciona una bitácora del paso a paso para la ejecución de las imágenes Docker.

Contenido
Estructura del proyecto
Configuración del entorno
Instrucciones de uso
Referencias


El repositorio contiene los siguientes archivos y directorios:
flask-app/: Directorio que contiene la aplicación Flask.
angular-app/: Directorio que contiene la aplicación Angular.
Dockerfile.flask: Dockerfile para la imagen de la aplicación Flask.
Dockerfile.angular: Dockerfile para la imagen de la aplicación Angular.
docker-compose.yml: Archivo de configuración de Docker Compose para ejecutar las aplicaciones.

Instrucciones de ejecución

Clonar el repositorio en tu máquina local:
git clone https://github.com/Garbox0/DevOps-Challenge.git

Directorio del proyecto:
cd DevOps-Challenge

Constructor de imágenes de Docker:
docker-compose build

Ejecuta las aplicaciones en contenedores:
docker-compose up

Accede a las aplicaciones desde tu navegador web:
Aplicación Flask: http://localhost:5000
Aplicación Angular: http://localhost:80
