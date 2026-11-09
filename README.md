# Laboratorio 04 — MongoDB con JPA y Atlas

Entrega del laboratorio de persistencia NoSQL basada en [gpedrazag/Lab-DespliegueCloud](https://github.com/gpedrazag/Lab-DespliegueCloud).

## Descargar el proyecto

[**Descargar Didierpd.zip**](https://github.com/Didierpd/Lab04-MongoDB-JPA/raw/refs/heads/main/Didierpd.zip)

El ZIP incluye el proyecto Maven, código fuente, instrucciones de ejecución, colección Postman, pruebas y evidencia de validación local y en MongoDB Atlas.

## Actividades implementadas

- Persistencia JPA con EclipseLink NoSQL y MongoDB.
- Competidores con vehículo embebido y un producto asociado obligatorio.
- Entidad Producto con nombre, marca y fecha de compra.
- Listado de productos y consultas de competidores, incluidos los nombres que empiezan por A.
- Conexión y persistencia comprobadas en MongoDB Atlas real.

## Validación

- 10 pruebas unitarias correctas.
- 31 comprobaciones HTTP contra Atlas correctas.
- Persistencia verificada después de reiniciar la API.
- Inspección directa del BSON y asociación de producto verificadas.

Las instrucciones completas están en `Lab04_MongoDB_JPA/README.md` dentro del ZIP. Extraerlo y ejecutar `mvn clean package`. Cada persona configura sus propias credenciales antes de usar Atlas; **no se incluyen contraseñas ni el archivo `.env`**.

La publicación en GitHub no sustituye la entrega solicitada del ZIP en Moodle.

## Integridad del archivo

SHA-256 de `Didierpd.zip`:

`9cd3cb3f2bfa056f98fa5db821cb82f1fd9cf3210ac7c1b198e3c4790edf439b`
