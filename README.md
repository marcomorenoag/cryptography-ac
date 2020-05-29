# Criptografía

### Descripción
Este repositorio contiene el código realizado para la creación de un servidor web local que actue como Autoridad Certificadora
para generar y validar firmas a través del estándar JSON Web Tokens (JWT).

### Herramientas empleadas y requerimientos
- Python v3.7 o superior.
- Django Framework v3.0.
- Djando Rest Framework v3.11.0.
- Pipenv (recomendado para la creación de entornos virtuales aislados).

### Proceso
1. Clonar este repositorio.
2. Posicionarse dentro del directorio (al nivel del Pipfile).
3. Instalar las dependencias del entorno virtual con ```pipenv install```
4. Levantar el entorno virtual con ```pipenv shell```
5. Posicionarse en el subdirectorio /app/
6. Iniciar el servidor local con el comando ```./manage.py runserver```
7. En el navegador web abrir en una pestaña ```http://localhost:8000/``` y empezar a usar la aplicación.
