# Risk Matrix
| ID | Riesgo | Impacto | Probabilidad | Nivel | Mitigacion | Justificacion |
|----|--------|---------|--------------|-------|---------------|--------------|
| R1 | Permitir comprar items sin stock | 5 | 3 | 15 |[Incluir pruebas de actualizacion de carritos en el flujo e2e]|[Perdidas financieras, confianza rota, riesgo de ser controlado al inicio de sesion pero no actualizado correctamente] |
| R2 | Realizar cambios de contraseña sin autenticar | 5 | 2 | 10 |[Realizar pruebas de seguridad - Incluir pruebas en API a contraseña]|[Si un usuario logueado deja la cuenta sin supervisar la contraseña puede ser modificada por terceros] |
| R3 | Carrito no se actualiza al ingresar nuevos items | 4 | 3 | 12 |[Probar la sesion luego de una recarga]| [Impacta directamente al proposito de negocio, si el sistema no es suficientemente moderno aumenta la probabilidad] |
| R4 | Busqueda no filtra correctamente los resultados | 4 | 3 | 12 |[Incrementar las exigencias en los requerimientos de pruebas para busquedas] |[Las busquedas son un elemento complejo propenso a tener errores. En caso de un malfuncionamiento de la busqueda, el usuario no puede encontrar items validos] |
| R5 | Boton de Regresar al Menu Principal roto | 2 | 2 | 4 |[Incluir la funcionalidad del boton en pruebas de humo]| [El boton es un elemento que es estable y no requiere modificaciones, por lo que no hay riesgo de bugs luego de ser probado, y su malfuncionamiento puede ser sobrepasado por otros mecanismos] |

## Agregar categoria