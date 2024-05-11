# Bienvenido a Kubernets/Deploy/Service/SVC

## Descripción
Este repositorio contiene los archivos necesarios para desplegar y gestionar una aplicación de que utiliza la imagen creada en dockerhub de PrestaShop y tambien en laza una imagen creada de Mysql utilizando Kubernetes.

## Imágenes en Docker Hub
- [MySQL Docker Compose](https://hub.docker.com/r/luisjulian/mysql-dockercompose): Imagen de Docker para MySQL utilizada en el despliegue.
- [PrestaShop Docker Compose](https://hub.docker.com/r/luisjulian/prestashopdockercompose): Imagen de Docker para PrestaShop utilizada en el despliegue.

## Estructura del Repositorio
- **deploy-ejercicio3.yaml**: Archivo YAML que define los recursos de Kubernetes necesarios para desplegar la aplicación.
- **README.md**: Este archivo, que proporciona información sobre el proyecto.

## Instrucciones de Uso
1. Clona este repositorio en tu máquina local.
2. Instala Kubernetes si aún no lo has hecho.
3. Aplica el archivo `deploy-ejercicio3.yaml` en tu clúster de Kubernetes utilizando el comando `kubectl apply -f deploy-ejercicio3.yaml`.
4. Verifica el estado de los pods y servicios desplegados con `kubectl get pods` y `kubectl get services`.
5. Accede a la aplicación desde tu navegador web utilizando la dirección proporcionada por el servicio de Kubernetes.

## Contribuciones
¡Las contribuciones son bienvenidas! Si tienes sugerencias de mejoras o encuentras errores, no dudes en abrir un issue o enviar un pull request.


