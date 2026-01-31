# STAGE 1:

Para entornos de prueba/pre-producción:
Más rápido que desarrollo
Sin recarga automática (ahorra recursos)
Listo para producción básica


# 1º CAMBIAR EL CMD DEL DOCKERFILE:
Gunicorn en lugar de runserver
WSGI = protocolo para producción
Workers = múltiples procesos para atender varias peticiones

<img width="610" height="154" alt="image" src="https://github.com/user-attachments/assets/cf3043d6-f46c-4404-a69d-2116a0cd7539" />

# 2º  QUITAR EL RELOAD DE REQUIEREMST Y SETTINGS :
 Porque en producción no necesitamos recarga automática
 
<img width="697" height="385" alt="image" src="https://github.com/user-attachments/assets/2868ba1d-def7-4ddd-b9a6-992da9989c68" />

<img width="664" height="665" alt="image" src="https://github.com/user-attachments/assets/9d30e5ba-f3cb-445a-9ce1-32a2bd240576" />

# 3º MODIFICAR EL .YML:
para DEBUG desactivado (seguridad) y Si hay error, solo ves página genérica, no detalles internos.

<img width="681" height="522" alt="image" src="https://github.com/user-attachments/assets/40e6089a-68f3-483c-91f3-a6c2b87c4a5e" />

(ACTUALIZARIAMOS CON COMANDOS , PERO COMO CREO Q NO TENGO ESPACIO EL DOCKER NO VA )
