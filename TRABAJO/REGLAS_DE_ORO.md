# REGLAS DE ORO DE PRODUCCIÓN (obligatorias para todo agente)

## 1. Referencias obligatorias en CADA generación
- Personaje → su chárter en `00_continuidad/` (NUNCA se eliminan ni se regeneran los charters).
- Lugar → fotos del bloqueo en `00_continuidad/06_CASA_Y_LOCACIONES/` cuando aplique.
- Referencias de apoyo listas: la carpeta del chat original tiene /refs/ con nombres cortos (char_nino, char_madre_a, char_hermano_a, loc_cocina...).

## 2. Anatomía de toda escena principal
Mínimo 5-6 planos DENTRO del mismo lugar y mismo tiempo:
1. Plano general de geografía (24 mm)
2. Plano medio de acción del personaje A (35/50 mm)
3. Contraplano del personaje B (85 mm)
4. (si hay 3er personaje: su contraplano 85 mm)
5. Macro de detalle/objeto (100 mm)
6. Cierre: plano de dos/tres o plano emocional (50 mm)
PROHIBIDO: un plano suelto sin escena, o mosaicos/varias fotos en un mismo archivo.

## 3. Ropa por escena
- Dentro de una escena: la ropa NO cambia entre planos.
- Al cambiar tiempo o lugar: SÍ cambia la ropa (documentarla en el PLANOS.md de la secuencia).
- Identidad NUNCA cambia: cicatriz ceja derecha = SOLO protagonista (niño/adulto). Hermano SIN cicatriz. Madre A 50-60 / Madre B 80-85. Luis siempre traje negro.

## 4. Mundo y época
- Tiempo A: finales 80s/principios 90s — cero electricidad, cero objetos modernos, cero plástico contemporáneo.
- Tiempo B: presente narrativo — sigue siendo humilde, sin lujos ni neón.
- República Dominicana rural específica. Pobreza con verdad y dignidad. Nunca postal turística ni latino genérico.

## 5. Formato de entrega
- 2.39:1 — normalizar cada foto a mínimo 2560×1072 px (ideal 4096×1716).
- Comando: `convert foto.jpg -gravity center -crop 2.39:1 +repage -resize 2560x1072! -quality 95 foto.jpg`

## 6. Archivos y commits
- Carpeta: `01_FOTOGRAFIAS_POR_SECUENCIA/SECUENCIA_XX_NOMBRE/SXX_PYY_TIPO_LENTEMM.jpg`
- Cada secuencia con su `SECUENCIA_XX_PLANOS.md` (lista de planos + vestuario de la escena + reglas).
- Commit por secuencia: `SECUENCIA_XX: descripción` + push INMEDIATO.
- Actualizar `TRABAJO/ASIGNACIONES.md` al terminar.

## 7. Prohibiciones
- No borrar ni mover charters ni fotos aprobadas.
- No subir tokens al repo (GitHub los destruye y rompe el acceso de todos).
- No inventar personajes nuevos sin aprobación del Director + dueño.
- No usar nombres de archivo con ñ ni acentos.
