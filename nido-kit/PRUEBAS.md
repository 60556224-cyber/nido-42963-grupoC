# Pruebas

| ID | Requisito | Orden o secuencia | Resultado esperado | Resultado obtenido | OK |
|---|---|---|---|---|---|
| P01 | R1 | `registrar @volt` (dos veces) | La segunda vez: `E: No se pudo registrar @volt` | `E: No se pudo registrar @volt` | `ok` |
| P02 | R1 | `registrar volt` (sin @) | `E: No se pudo registrar volt` | `E: No se pudo registrar volt`  |`ok`  |
| P03 | R2 | `arbol`, `usuarios` |Preorden y enorden correctos; 10 nodos, altura 5 y 4 hojas   | Recorridos correctos; 10 nodos, altura 5 y 4 hojas | ok |
| P04 | R3 | `seguir @zorro @zorro` | `E: Una cuenta no puede seguirse a si misma` | `E: Una cuenta no puede seguirse a si misma` |  `ok` |
| P05 | R4 | `mutuos @mochila` | `mutuos de @mochila (1): @nachos` | `mutuos de @mochila (1): @nachos` |  `ok` |
| P06 | R5 |  |  |  |  |
| P07 | R6 | `guardar`, `salir`, abrir, `cargar`, `arbol` | El mismo preorden, la misma altura y los mismos seguimientos |  |  |
| P08 | R7 | `hola`, `seguir`, `perfil @nadie` | Mensajes de error; el programa sigue |  |  |

Agreguen todas las que necesiten. Incluyan casos con datos invalidos.
