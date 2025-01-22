# Usa una imagen base de Linux
FROM ubuntu:latest

# Copia el script en el contenedor
COPY script.sh /script.sh

# Da permisos de ejecución al script
RUN chmod +x /script.sh

# Define el comando que se ejecutará al iniciar el contenedor
CMD ["/script.sh"]