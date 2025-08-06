# 🔌 Pruebas de Integración con Postman - API JSONPlaceholder

Este proyecto contiene una colección de pruebas de integración desarrolladas en Postman, usando la API pública JSONPlaceholder. Está diseñado como parte de mi proceso de actualización profesional para demostrar habilidades en pruebas de backend/API REST.

## 🔧 Tecnologías y herramientas

- Postman
- API REST pública: https://jsonplaceholder.typicode.com/
- Formato JSON
- HTTP Methods: GET, POST
- Validación de respuesta, estructura y códigos de estado

## Pruebas incluidas

1. **Obtener lista de posts (GET /posts)**
   - Verifica que el código de estado sea 200.
   - Verifica que la respuesta sea un array.

2. **Crear un nuevo post (POST /posts)**
   - Envia un objeto con `title`, `body` y `userId`.
   - Valida el código de estado (201).
   - Confirma que la respuesta contiene un campo `id`.

3. **Simular error al crear un post vacío (POST /posts con `{}`)**
   - Verifica el comportamiento de la API ante datos vacíos.

## Cómo ejecutar las pruebas

1. Importar el archivo `Pruebas_Integracion_JSONPlaceholder.postman_collection.json` en Postman.
2. Ejecutar la colección con el botón **Run Collection**.
3. Ver los resultados en la consola de ejecución.

## Archivos

- `Pruebas_Integracion_JSONPlaceholder.postman_collection.json` → colección Postman lista para importar.

## Autor

Proyecto personal de aprendizaje para fortalecer habilidades en pruebas de integración.  
**Yohan Mira**, Agosto 2025.
