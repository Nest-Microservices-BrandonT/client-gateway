# Client Gateway

El gateway es el punto de comunicación entre nuestros clientes y nuestros servicios. Es el encargado de recibir las peticiones, enviarlas a los servicios correspondientes y devolver la respuesta al cliente.

## Dev

1. Clonar el repositorio
2. Istalar dependencias
3. Crear un archivo `.env` basado en el `.env.template`
4. Ejecutar migración de prisma `npx prisma migrate dev`
5. Ejecutar `npm run start :dev`
