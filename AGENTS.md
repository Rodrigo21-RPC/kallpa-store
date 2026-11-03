# Kallpa Store

Tienda en línea de celulares y electrodomésticos, con módulos de tienda y administración y una pasarela de pago simulada.

## Stack

- JavaScript y Node.js 22.13 o superior, por `node:sqlite`.
- Cliente: React, Vite y Tailwind CSS. Servidor: Express y SQLite mediante `node:sqlite`.
- Validación: Zod. Pruebas: Vitest y supertest.

## Desarrollo local

Comandos previstos; estarán disponibles cuando se implemente el proyecto y su `package.json`:

- `npm install`: instalar dependencias.
- `npm run dev`: iniciar el entorno de desarrollo.
- `npm test`: ejecutar las pruebas.
- `npm start`: iniciar la aplicación.

## Convenciones

- Preferir la solución más simple e implementar solo lo especificado.
- Usar español de Perú y mostrar soles (S/) con dos decimales.
- Escribir primero una prueba fallida para cada regla de negocio; ejecutar `npm test` antes de cerrar una funcionalidad.
- Definir criterios de éxito comprobables desde la aplicación sin leer código.
- Pedir datos imprescindibles, guardar contraseñas con hash y mantener secretos en variables de entorno, con `.env.example` sin secretos.
- Informar que el pago es simulado; nunca cobrar dinero real ni guardar el número completo de tarjeta o el CVV.

Las reglas de producto viven en .specify/memory/constitution.md y el estado del producto en specs/README.md
