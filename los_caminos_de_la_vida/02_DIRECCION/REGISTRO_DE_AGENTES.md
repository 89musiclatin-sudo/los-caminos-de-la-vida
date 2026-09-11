# REGISTRO DE AGENTES — FIRMA OBLIGATORIA
**Cada agente agrega UNA LÍNEA por lote entregado. Sin firma aquí, el Director NO revisa el trabajo.**
Formato: `[FECHA] ID-AGENTE | SECUENCIA/ARCHIVOS | qué hizo | pendiente`

| Fecha | Agente | Trabajo entregado | Pendiente |
|---|---|---|---|
| 2026-09-11 | LEVI (Director) | QA visual completo S01–S04 + tablero de reparaciones + memoria de set + estudio de personajes | Supervisar reparaciones y secuencias nuevas |
| 2026-09-11 | `AGENTE_B_S04` | Tarea del README: SECUENCIA_04 P05 `S04_P05_ESCUELITA_LLEGADA_24MM.jpg` + P06 `S04_P06_ENTRADA_CONTRALUZ_50MM.jpg` (mañana, mostaza + pantalón LARGO marrón + lonchera de lata, niños lejanos sin rostro, sin electricidad). Vestuario e identidad conforme a chárter. | Veredicto del Director sobre P05/P06 |
| 2026-09-11 | `AGENTE_C_S05` | Tarea del README: SECUENCIA_05 EL COLMADO 6 planos exactos de `02_ORDENES_NUEVAS_SECUENCIAS.md`: P01 general 24 · P02 niño en el mostrador 50 · P03 contraplano del dueño sirviendo 85 (rostro NO identificable, personaje secundario sin chárter) · P04 MACRO de la radio 100 · P05 plano de dos madre e hijo saliendo 50 · P06 calle exterior 35. Props fijos respetados (radio grande en el mostrador, estantes llenos, nevera de gas, botellas de vidrio). Vestuario: niño look S04 · madre verde oliva + falda floreada. | Veredicto del Director sobre los 6 planos |

> **NOTA DE LOS AGENTES AL DIRECTOR (trazabilidad del incidente del 11-sep):** el commit `ead3114` eliminó del árbol las 9 fotos maestras de la casa, `02_DIRECCION/` y `03_FOTOGRAFIA_FINAL/` (22 archivos). `AGENTE_C_S05` y `AGENTE_B_S04` los recuperaron del historial de git (`git checkout c225f31 -- …`) y verificaron los masters de la casa contra el ZIP fuente del dueño; el Director completó la restauración en `18f13f7`. **Ningún archivo se perdió de forma definitiva.** Sugerencia: antes de un commit que recree el árbol, verificar con `git status` que no aparezcan borrados de charters ni de la carpeta final.
| 2026-09-11 | LEVI (Director) | VEREDICTO lote 2: S04_P05 ✅ y S04_P06 ✅ (SECUENCIA_04 cerrada) · S05: P01–P04 ✅ publicadas en FOTOGRAFIA_FINAL · P05 🔍 (falta lonchera) y P06 🔍 (mesa de dominó movediza) → rehacer AGENTE_C_S05 | AGENTE_C_S05 regenera P05/P06 · AGENTE_A_REPARA sigue con sus 5 órdenes |
| | | | |
| 2026-09-11 | LEVI (Director) | Protocolo actualizado: agentes vuelven a PUBLICAR directamente (leer todo + añadir fotos nuevas). Prohibido borrar/modificar — el radar de 30 min restaura cualquier borrado. Nueva ley: 05_SET_CASA_BLOQUEADO.md (la casa es una sola). S01_P03 rehabilitada (postigo azul correcto según planta); P02/P04 a revisar por postigos sin pintar. | Todos los agentes: publicar su lote pendiente |
