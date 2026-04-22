# Sesión 1

## Charter
Explorar el flujo completo de compra desde el catálogo hasta el checkout para detectar fallos en validaciones y comportamiento del sistema.

## ÁREAS
Aplicación web JPetStore (OctoPerf) – flujo de compra

## INICIO
Fecha: [Pon la fecha]
Duración: 30 minutos

## TESTER
[TU NOMBRE]

## DESGLOSE DE TAREAS
- Navegación del catálogo (5 min)
- Selección de productos (5 min)
- Pruebas con carrito (10 min)
- Simulación de compra (10 min)

## ARCHIVOS DE DATOS
- Datos válidos (productos reales)
- Datos inválidos (cantidades altas, inputs incorrectos)

## NOTAS DE PRUEBA
- Se exploró la navegación entre categorías sin problemas visibles
- Al agregar múltiples productos, el carrito respondió correctamente
- No se valida claramente si el usuario está logueado antes del checkout
- No hay mensajes claros de error en algunos casos

## LISTA DE RIESGOS
- Posible compra sin autenticación adecuada
- Falta de validación en cantidades de productos
- Manejo limitado de errores en el checkout

## DEFECTOS (BUGS)
- El sistema permite avanzar en el checkout sin validaciones claras de usuario
- Falta feedback visual en algunos errores del carrito

## INCIDENTES (ISSUES)
- No está claro si el sistema requiere login obligatorio para comprar
- No hay documentación visible sobre validaciones del carrito