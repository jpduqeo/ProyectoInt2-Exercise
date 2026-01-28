# ProyectoInt2-Exercise
# Ejecutar el proyecto Django

## 1. Activar el entorno virtual
venv\Scripts\activate

## 2. Instalar dependencias
pip install django psycopg2

## 3. Configurar la base de datos
Asegúrate de que PostgreSQL esté corriendo y que en settings.py 

## 4. Aplicar migraciones
python manage.py makemigrations  
python manage.py migrate  

## 5. Ejecutar el servidor
python manage.py runserver  

## 6. Abrir en el navegador
http://127.0.0.1:8000/