\# Práctica 6: Servidor Web Nginx con Docker



\*\*Estudiante:\*\* Vanessa Collado  

\*\*Institución:\*\* Instituto Tecnológico de las Américas (ITLA)  

\*\*Carrera:\*\* Desarrollo de Software



\## 1. Descripción



Esta práctica consiste en implementar un servidor web utilizando Nginx mediante Docker y Docker Compose.



Se utiliza un contenedor para ejecutar el servidor web y publicar una página HTML personalizada, permitiendo acceder a ella desde un navegador web.



\## 2. Objetivos



\- Comprender el funcionamiento de Docker.

\- Implementar un servidor web Nginx.

\- Utilizar Docker Compose para administrar contenedores.

\- Configurar puertos y volúmenes.

\- Publicar una página web localmente.



\## 3. Tecnologías utilizadas



\- Docker Desktop

\- Docker Compose

\- Nginx

\- Ubuntu

\- WSL 2

\- HTML5



\## 4. Estructura del proyecto



```text

Practica-6-Servidor-web-Nginx-con-Docker/

├── src/

│   └── index.html

├── docker-compose.yml

└── README.md

```



\## 5. Configuración de Docker Compose



El archivo `docker-compose.yml` configura el servicio Nginx, utilizando una imagen oficial, el puerto 8080 y un volumen para publicar los archivos HTML.



\## 6. Ejecución del servidor



Ubicarse en la carpeta del proyecto:



```powershell

cd "Practica-6-Servidor-web-Nginx-con-Docker"

```



Iniciar el servidor:



```powershell

docker compose up -d

```



Verificar los contenedores activos:



```powershell

docker ps

```



\## 7. Acceso al servidor



Abrir el navegador y visitar:



http://localhost:8080



El servidor muestra una página HTML personalizada con el mensaje:



\*\*¡Hola Mundo! Mi servidor web Nginx funciona con Docker Compose.\*\*



\## 8. Detener el servidor



Para detener los servicios y eliminar los contenedores:



```powershell

docker compose down

```



\## 9. Conclusión



Mediante esta práctica se logró implementar y ejecutar un servidor web Nginx utilizando Docker Compose. También se aprendió a configurar contenedores, administrar puertos y compartir archivos HTML mediante volúmenes.



\## 10. Autora



\*\*Vanessa Collado\*\*  

Estudiante de Desarrollo de Software – ITLA.

