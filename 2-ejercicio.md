# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a una red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba 

<img width="1895" height="158" alt="image" src="https://github.com/user-attachments/assets/0c99fdee-71b1-44f9-929f-bb3538ff195d" />

verificacion de healthy en el servidor:

<img width="1459" height="578" alt="image" src="https://github.com/user-attachments/assets/312a45e8-d97f-4e75-8961-b968c7ab0788" />

<img width="1425" height="373" alt="image" src="https://github.com/user-attachments/assets/a5a124dc-e368-401f-8f24-a08e15fe201d" />


# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube

<img width="1851" height="869" alt="image" src="https://github.com/user-attachments/assets/335ca02e-4d40-444e-8c89-71ebc0f8f368" />
