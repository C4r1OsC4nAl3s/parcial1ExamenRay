Dependencias tipicas de proyectos de Ray:
pip install django djangorestframework django-filter markdown requests pillow psycopg2-binary httpie

Notas: 
A veces presenta problemas con las migraciones de carpetas individuales

> Usar comandos de migraciones
```
python3 manage.py makemigrations <folder>

python3 manage.py migrate <folder>
```