

| ***Comando***                   | ***Descripción***                                               |
| ------------------------------- | --------------------------------------------------------------- |
| __docker container ls__         | Muestra todos los contenedores en ejecucion                     |
| __docker container ls -a__      | Muestra todos los contenedores en ejecución y los detenidos     |
| __docker container rm__ `id`    | Borra uno o varios contenedores pasando el id o varios shortcut |
| __docker container rm -f__ `id` | Borra uno o varios contenedores de forma forzada                |
| __docker container prune__ `id` | Borra todos los contenedores detenidos                          |
|                                 |                                                                 |
hihiin
jo

|    Comando                            |               Descripcion                 |
|---------------------------------------|-------------------------------------------|
| __docker container run__ `image name` | Ejecuta y crea un contener posando el nombre de la imagen|
| __docker container stop__ `id` | Detiene un contenedor en ejecucion|
| __docker container start__ `id` | Ejecuta un contenedor en ejecucion|
| __docker container logs__ `id`  | Muestra los logs del contendor que esta en ejecucion | 
| __docker container logs -f__ `id`  | Muestra los logs del contendor en ejecucion de manera activa | 