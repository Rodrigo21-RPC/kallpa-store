# Constitución de Kallpa Store

## Principios fundamentales

### I. Simplicidad ante todo

Ante dos soluciones que cumplen la especificación, se elige la más simple. La versión 1 no
incorpora complejidad anticipada.

### II. Idioma y mercado

Todo el producto usa español de Perú. Los importes se muestran en soles (S/), con dos decimales.

### III. Cero alcance fantasma

Solo se implementa funcionalidad escrita en la especificación. Las ideas nuevas se proponen para
su evaluación; no se construyen hasta que estén especificadas.

### IV. Verificación por personas no técnicas

Cada criterio de éxito se puede comprobar usando la aplicación, sin leer código.

### V. Respeto por los datos y pagos

Se solicitan solo los datos imprescindibles. Las contraseñas se almacenan con hash, nunca en texto
plano. La pasarela es una simulación en modo de prueba: nunca cobra dinero real ni guarda el número
completo de tarjeta o el CVV; la interfaz lo indica claramente. No se introducen claves ni secretos
en el código. Las credenciales del administrador se configuran mediante variables de entorno y se
proporciona un archivo `.env.example` sin secretos.

### VI. Pruebas primero

Cada regla de negocio tiene una prueba automática escrita y comprobada como fallida antes de su
implementación, incluidos los totales del carrito, el stock, la aprobación o rechazo del pago y los
estados del pedido. `npm test` debe pasar antes de cerrar una funcionalidad.

## Alcance del producto

Kallpa Store vende celulares y electrodomésticos. La tienda permite buscar productos, armar un
carrito, pagar mediante la simulación y seguir pedidos desde el perfil. La administración gestiona
productos, precios, stock, clientes y pedidos. La especificación define el alcance concreto de cada
funcionalidad.

## Flujo de trabajo

Cada funcionalidad parte de una especificación con criterios de éxito verificables en la aplicación.
Las reglas de negocio se desarrollan siguiendo el ciclo de prueba fallida, implementación y prueba
aprobada. Antes de cerrar una funcionalidad, se comprueban sus criterios y se ejecuta `npm test`.

## Gobernanza

Esta constitución rige las decisiones del proyecto. Toda modificación debe documentarse, revisarse y
aprobarse antes de adoptarse; si afecta trabajo existente, debe indicar cómo adaptarlo. Cada revisión
de una funcionalidad comprueba su cumplimiento y resuelve las desviaciones antes de cerrarla.

La versión sigue MAJOR.MINOR.PATCH: MAJOR para eliminar o redefinir principios de forma incompatible;
MINOR para añadir principios o ampliar reglas de manera sustancial; PATCH para aclaraciones y cambios
de redacción sin efecto normativo.

**Versión**: 1.0.0 | **Ratificada**: 2026-11-03 | **Última modificación**: 2026-11-03
