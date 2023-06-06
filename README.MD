# Sistema de Control de Asistencias de Empleados

Este es un sistema de control de asistencias de empleados que permite registrar la hora de entrada y hora de salida de cada empleado. Proporciona una manera eficiente de realizar un seguimiento de la puntualidad y la asistencia de los empleados.

## Características

- Registro de hora de entrada: Permite a los empleados marcar su hora de entrada al inicio de su jornada laboral.
- Registro de hora de salida: Los empleados pueden marcar su hora de salida al finalizar su jornada laboral.
- Registro de asistencias: El sistema registra las horas de entrada y salida de los empleados para llevar un seguimiento preciso de su asistencia.
- Informes de asistencia: Los administradores pueden generar informes de asistencia para ver el registro de horas de entrada y salida de los empleados en un período específico.
- Notificaciones: El sistema puede enviar notificaciones a los administradores cuando un empleado llega tarde o se va temprano.

## Tecnologías Utilizadas

- Lenguaje de programación: [Python](https://www.python.org/)
- Framework web: [Django](https://www.djangoproject.com/)
- Base de datos: [MySQL](https://www.mysql.com/), [PostgreSQL](https://www.postgresql.org/), o [SQLite](https://www.sqlite.org/) (según la elección del usuario)

## Requisitos de Instalación

- Python 3.7 o superior
- Django 3.2.0 o superior
- MySQL, PostgreSQL o SQLite (según la elección del usuario)
- Otros requisitos se pueden encontrar en el archivo `requirements.txt`

## Instalación

1. Clona este repositorio: `git clone https://github.com/gfrancojf/SIGAEP.git`
2. Ve al directorio del proyecto: `cd SIGAEP`
3. Crea y activa un entorno virtual (opcional): `python3 -m venv env` y `source env/bin/activate`
4. Instala las dependencias: `pip install -r requirements.txt`
5. Configura la base de datos en el archivo `settings.py`
6. Realiza las migraciones de la base de datos: `python manage.py migrate`
7. Inicia el servidor local: `python manage.py runserver`
8. Accede al sistema a través de tu navegador web: `http://localhost:8000`

## Uso

1. Registra un empleado en el sistema.
2. El empleado puede marcar su hora de entrada al inicio de su jornada laboral.
3. Al finalizar la jornada, el empleado puede marcar su hora de salida.
4. Los administradores pueden generar informes de asistencia para ver el registro de horas de entrada y salida de los empleados en un período específico.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas realizar mejoras en este proyecto, sigue los siguientes pasos:

1. Haz un fork de este repositorio.
2. Crea una rama para tu función o corrección: `git checkout -b feature/mi-nueva-funcion`
3. Realiza los cambios necesarios y realiza los commits: `git commit -am 'Agrega una nueva función'`
4. Sube los cambios a tu repositorio remoto: `git push origin feature/mi-nueva-funcion`
5. Abre un Pull Request en este repositorio y describe los cambios que has realizado.

## Licencia

Este proyecto se encuentra bajo la

 [Licencia MIT](LICENSE).

---
