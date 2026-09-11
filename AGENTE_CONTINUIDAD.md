# PROTOCOLO PARA CUALQUIER AGENTE QUE CONTINÚE EL PROYECTO

> **PROYECTO MULTI-AGENTE:** este repositorio funciona con DIRECTOR y agentes colaboradores.
> Lee primero `DIRECTOR.md` (jerarquía y flujo), luego `TRABAJO/REGLAS_DE_ORO.md` (producción)
> y firma tu tarea en `TRABAJO/ASIGNACIONES.md`. Calidad auditada en `INFORME_QA.md`.

## Paso 0.5 — Credenciales
- Token NUNCA dentro del repo (GitHub lo destruye). Está en `/home/user/GITHUB_TOKEN.txt` del workspace del dueño. Para push: `git push https://TOKEN@github.com/89musiclatin-sudo/los-caminos-de-la-vida.git main`

## Paso 0 — Fuente original de respaldo
Si algún archivo de continuidad faltara o estuviera corrupto, el ZIP original del dueño está en:
`https://files.catbox.moe/hwjosm.zip` (contiene los charters originales, la casa y la SECUENCIA_01).
Verificar SIEMPRE, tras clonar, que existan las 9 fotos de `00_continuidad/06_CASA_Y_LOCACIONES/CASA_TIEMPO_A_RECUERDOS/`.

## Paso 1 — Clonar o descargar este repositorio
```bash
git clone https://github.com/89musiclatin-sudo/los-caminos-de-la-vida.git
```
(Repositorio PUBLICO: lectura libre con solo el enlace. Para SUBIR trabajo nuevo se necesita el Personal Access Token del dueño (permiso repo).)

## Paso 2 — Memorizar los charters
Abrir y estudiar como referencia visual obligatoria:
- `00_continuidad/01_CANTANTE_LUIS/CANTANTE_LUIS_CHARTER_OFICIAL_6K.jpg` — traje negro total, nunca interpreta al protagonista.
- `00_continuidad/02_PROTAGONISTA_ADULTO/PROTAGONISTA_ADULTO_CHARTER_OFICIAL_6K.jpg` — cicatriz ceja derecha.
- `00_continuidad/03_PROTAGONISTA_NINO/PROTAGONISTA_NINO_CHARTER_OFICIAL_6K.jpg` — cicatriz ceja derecha, 9–10 años.
- `00_continuidad/04_MADRE/TIEMPO_A_RECUERDOS/MADRE_TIEMPO_A_RECUERDOS_CHARTER_OFICIAL_6K.jpg`
- `00_continuidad/04_MADRE/TIEMPO_B_PRESENTE_80_ANOS/MADRE_TIEMPO_B_PRESENTE_CHARTER_OFICIAL_6K.jpg`
- `00_continuidad/05_HERMANO/` — adolescente y joven adulto, SIN cicatriz.
- `00_continuidad/06_CASA_Y_LOCACIONES/CASA_CHARTER_FASE_1_5K.jpg` + `PLANTA_MAESTRA_CASA_4K.png`

## Paso 3 — Leer la biblia y el timeline
`BIBLIA_MAESTRA_DE_CONTINUIDAD.md` y `TIMELINE_OFICIAL.md` en la raíz de `los_caminos_de_la_vida/`.

## Paso 4 — Crear secuencias nuevas
- Una escena principal = mínimo 5 planos dentro de la misma escena:
  plano general (24mm) → planos medios de acción (35/50mm) → contraplano personaje A (85mm) → contraplano personaje B (85mm) → macro de detalle (100mm) → cierre (plano de dos o cierre emocional).
- Pasar las imágenes de referencia (charters) en cada generación.
- Cambiar ropa si cambia el tiempo o el lugar. Nunca cambiar identidad.
- Normalizar cada entrega a 2.39:1, mínimo 2560×1072 px.
- Escribir `SECUENCIA_XX_PLANOS.md` con la lista de planos.

## Paso 5 — Commitear y subir SIEMPRE al terminar cada lote
```bash
git add .
git commit -m "SECUENCIA_XX: descripción"
git push
```

## Plan de secuencias sugerido (orden narrativo de la canción)
- S01 INTRO — casa al amanecer (HECHA, 10 planos)
- S02 EL RÍO — madre y niño lavando (HECHA, 6 planos)
- S03 EL CONUCO — la familia trabajando la tierra (Tiempo A) [HECHA 6/6]
- S04 LA ESCUELA / EL CAMINO — el niño camina, soledad y esfuerzo [6/6 ENTREGADOS: P05+P06 por AGENTE_B_S04 el 2026-09-11; P03 y P04 en tablero de reparaciones]
- S05 EL COLMADO — la radio, la canción, la comunidad [6/6 ENTREGADOS al spec del Director por AGENTE_C_S05 el 2026-09-11, pendiente veredicto]
- S06 LA COMIDA — mesa, platos compartidos, la ponchera
- S07 COSTURA — la madre remienda de noche con aguja e hilo (luz de queroseno)
- S08 PARTIDA — el niño crece, la despedida en el camino
- S09 PRESENTE — el hijo adulto trabaja y cuida a la madre de 80 años (Tiempo B)
- S10 PERFORMANCE — el cantante Luis en parajes hermosos del campo dominicano (intercalada)
- S11 CIERRE — abrazo final, los caminos de la vida

Ajustar este plan con el dueño del proyecto si él lo pide. Cada secuencia puede cambiar de ropa y época según el timeline.

## Credenciales de subida
- El Personal Access Token del dueño NO vive dentro de este repositorio (por seguridad, para no publicarlo).
- En el workspace de la conversación original está el archivo `/home/user/GITHUB_TOKEN.txt`.
- Si abres un chat nuevo: pídele al dueño el token (classic, permiso `repo`) y sube con:
```bash
git push https://<TOKEN>@github.com/89musiclatin-sudo/los-caminos-de-la-vida.git main
```
