# Trabajo Práctico: Git + Docker + Nginx

Este proyecto muestra una página HTML simple usando un contenedor Docker con Nginx.

## 🛠️ Cómo usarlo

1. Clonar el repositorio:
`git clone https://github.com/MaiaPardo/repositorio.git`
`cd TP--Docker-Git`

2. Construir la imagen Docker: 
`docker build -t practica-nginx .`

3. Correr el contenedor:
`docker run -d -p 8080:80 --name mi-practica-nginx practica-nginx`

4. Abrir el navegador en `http://localhost:8080`
## 📄 Contenido

- `index.html`: Página web con el mensaje del trabajo.
- `Dockerfile`: Configura el contenedor con Nginx.
- `README.md`: Este archivo con las instrucciones.


