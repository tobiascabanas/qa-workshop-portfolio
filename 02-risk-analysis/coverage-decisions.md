# Coverage Decisions

## Riesgos que se probarán primero
1. El sistema podría permitir realizar compras sin completar el proceso de pago
2. Los precios de productos podrían mostrarse incorrectamente en el carrito
3. El sistema podría fallar al procesar múltiples productos en el carrito

## ¿Por qué esos riesgos son prioridad?
Estos riesgos son críticos porque impactan directamente en los ingresos del negocio y en la experiencia del usuario. Cualquier error en el flujo de compra puede generar pérdidas económicas o abandono de usuarios.

## Qué se probará menos o quedará fuera por ahora
- Validaciones menores en formularios secundarios
- Casos poco frecuentes de uso del sistema
- Funcionalidades no críticas de la API

## Justificación de exclusiones
Estas áreas se priorizan menos porque tienen menor impacto en el negocio y no afectan directamente el flujo principal de compra. En una primera fase de testing, es más importante asegurar que los procesos críticos funcionen correctamente.