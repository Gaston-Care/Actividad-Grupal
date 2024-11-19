# Proyecto SCRUM en Django

## Descripción
El proyecto consiste en la implementación de modelos Django. Se crearon varios modelos (Tarea, Epica y Sprint) en la que se lleva a cabo modelos de bases de datos y sus respectivas restricciones, cumpliendo la normativa del trabajo practico establecido.

## Caracteristicas
- **Modelos de Datos**:
- Tarea: se almacena una tarea especifica, con una mision o tarea a realizar.
- Epica: representa una gran funcionalidad o conjunto de tareas a realizar.
- Sprint: Iteraciones de trabajo que contienen tareas y son gestionadas por un Scrum Master.

- **Consultas Avanzadas**: Ejecución de consultas para obtener información sobre tareas, estados, dependencias y progreso.

## Requisitos

- Python 3.10.14
- Django 4.2(especificado en el archivo 'requirements.txt')

## Instalacion

1. **Clonar el repositorio**:

2. **Navegar al directorio del proyecto**:
    cd

3. **Crear un entorno virtual**:
    virtualenv -p /usr/bin/python3.10 nombre_del_entorno

4. **Activar el entorno virtual**:

    - En Windows: .\nombre_del_entorno\Scripts\activate

    - En macOS/Linux: source nombre_del_entorno/bin/activate

5. **Instalar las dependencias**:
    pip install -r requirements.txt

6. **Realizar las migraciones a la base de datos**:
    python manage.py migrate

7. **Correr el Servidor**:
    python manage.py runserver

8. **Acceder a la Aplicacion**:
    Abre el navegador y visita http://127.0.0.1:8000/

## Uso y Funcionalidad
- Obtener todas las tareas asignadas a un usuario específico.
- Obtener las tareas completadas dentro de un sprint determinado
- Listar todas las tareas que dependen de una tarea específica.
- Listar todas las épicas que tienen tareas en progreso.
- Calcular el número total de tareas por estado (por hacer, en progreso, completada).
- Obtener la suma de esfuerzo estimado de todas las tareas asociadas a una épica específica.
- Listar los sprints que tiene un Scrum Master asignado.
- Obtener el progreso total de una épica en base a las tareas completadas.
- Obtener el backlog de un sprint específico y sus responsables.
- Listar todas las tareas que están bloqueadas.

## Contacto
    gecare@udc.edu.ar - jfsassenberg@udc.edu.ar - ggvega@udc.edu.ar - vnbravo@udc.edu.ar