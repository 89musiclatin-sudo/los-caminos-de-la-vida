# LOS CAMINOS DE LA VIDA — Producción fotográfica del videoclip/película

Repositorio oficial de producción. **Este repositorio es la fuente única de verdad:**
si un chat se vence o se pierde, cualquier agente puede continuar desde aquí sin detener el proyecto.

## Qué hay aquí
| Carpeta | Contenido |
|---|---|
| `00_continuidad/` | Charters oficiales aprobados de todos los personajes + casa + locaciones. **NUNCA ELIMINAR NI MODIFICAR.** |
| `01_FOTOGRAFIAS_POR_SECUENCIA/` | Secuencias narrativas terminadas (mínimo 5 planos por escena principal + sus planos secundarios). |
| `uploads/` | Material fuente original del dueño del proyecto (foto real del cantante para clonar). |

## Documentos de gobierno (leer en este orden)
1. `los_caminos_de_la_vida/BIBLIA_MAESTRA_DE_CONTINUIDAD.md` — reglas centrales.
2. `los_caminos_de_la_vida/TIMELINE_OFICIAL.md` — Tiempo A (recuerdos, años 80–90) y Tiempo B (presente).
3. `00_continuidad/06_CASA_Y_LOCACIONES/CONTINUIDAD_CASA.md` — casa fija.
4. `00_continuidad/05_HERMANO/CONTINUIDAD_HERMANO.md` — hermano (creado en producción).

## Reglas de oro (resumen para el agente que continúa)
1. **Los charters nunca se eliminan ni se regeneran.** Se usan como referencia en cada imagen nueva (referencia de personaje + locación + utilería cuando aplique).
2. **Cada escena principal tiene mínimo 5 planos DENTRO de la misma escena:** plano general + planos secundarios (medios, contraplanos de cada personaje, macro de detalle, plano de dos). Nunca un plano suelto "a lo loco".
3. **Cada vez que cambia el tiempo o el lugar, cambian las ropas** de los personajes (pero nunca la identidad, edad narrativa ni la marca del protagonista).
4. Identidad bloqueada: el protagonista (niño y adulto) tiene **cicatriz pequeña en la ceja derecha**; el hermano **no** la tiene.
5. Estética: ARRI Alexa 35, lentes Cooke, 2.39:1, entrega mínima 2560×1072, piel real, sin electricidad en Tiempo A, pobreza con dignidad, República Dominicana rural (nunca genérico latinoamericano).
6. Cada secuencia nueva va con su archivo `SECUENCIA_XX_PLANOS.md` documentando cada plano.
7. **Cada lote de trabajo se sube a este repositorio con un commit.** Así nunca se pierde trabajo.

```
Este repositorio es **PRIVADO**: solo entra quien el dueño autorice con este token. **El token oficial de producción es:**

```
TOKEN: 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
USUARIO: 89musiclatin-sudo
```

Cuando termines tu lote de imágenes, subes así:

```bash
git add .
git commit -m "[TU-ID-DE-AGENTE] SECUENCIA_XX: lo que hiciste"
git push https://TU-TOKEN@github.com/89musiclatin-sudo/los-caminos-de-la-vida.git main
```

⚠️ Si el campo TOKEN dice `[EL_DUEÑO_DEBE_PEGAR_AQUI_SU_TOKEN]`, el dueño aún no lo puso: **avísale al dueño que lo pegue en este README** y mientras tanto entrega tu trabajo igual (commit local), nunca lo borres.

---

## 🪪 2. PRESENTACIÓN OBLIGATORIA (antes de generar UNA sola imagen)

1. Elige tu **ID de agente** libre de la tabla de tareas de abajo (ejemplo: `AGENTE_B_S05`).
2. **Preséntate** al dueño en el chat: *"Soy [tu nombre], trabajo como AGENTE_B_S05, mi tarea es la SECUENCIA_05, leeré la MEMORIA MAESTRA DE SET y el ESTUDIO DE PERSONAJES antes de generar."*
3. Abre un chat nuevo cada vez que vuelvas → te presentas de nuevo y continúas tu tarea.
4. **Firma TODO tu trabajo** con tu ID: en el commit, en el `REGISTRO_DE_AGENTES.md` y en cada entrada del plan de planos. Trabajo sin firma = no existe y el Director lo rechaza.

## 🎬 3. TU JEFE EN SET ES EL DIRECTOR — OBEDECE LAS 3 DOCUMENTOS DE DIRECCIÓN

Léelos EN ORDEN antes de trabajar (están en `los_caminos_de_la_vida/02_DIRECCION/`):

| # | Documento | Qué te da |
|---|---|---|
| 1 | `02_DIRECCION/00_MEMORIA_MAESTRA_DE_SET.md` | **LA LEY**: calidad de imagen de cine (ARRI Alexa 35 + lentes Cooke, 2.39:1, mínimo 2560×1072), nadie mira a la cámara, continuidad de ropa/objetos/luz, anatomía (5 dedos), lógica de escena. |
| 2 | `02_DIRECCION/01_ESTUDIO_DE_PERSONAJES.md` | El estudio pieza por pieza de cada personaje (ojos, manos, dedos, cejas, vestuario fijo por secuencia). Cíñete a él al 100%. |
| 3 | `02_DIRECCION/03_TABLERO_DE_REPARACIONES.md` | El veredicto del Director sobre cada foto existente. Si tu foto dice **REHACER**, la rehaces tú siguiendo la orden exacta. |

Los charters (rostros oficiales) están en `00_continuidad/` — **se usan SIEMPRE como referencia en cada generación y NUNCA se modifican ni borran.**

## 📋 4. TABLERO DE TAREAS — CADA AGENTE TOMA UNA Y SOLO UNA

| ID de agente | Tarea | Estado |
|---|---|---|
| `AGENTE_A_REPARA` | Reparar las fotos marcadas REHACER en el Tablero (S01_P03, S01_P05, S03_P05, S04_P04, revisar S04_P03) | 🟡 ABIERTA |
| `AGENTE_B_S04` | Terminar SECUENCIA_04: planos P05 y P06 (ver SECUENCIA_04_PLANOS.md) | 🟡 ABIERTA |
| `AGENTE_C_S05` | SECUENCIA_05 EL COLMADO (mín. 6 planos) | 🟢 LIBRE |
| `AGENTE_D_S06` | SECUENCIA_06 LA COMIDA (mín. 6 planos) | 🟢 LIBRE |
| `AGENTE_E_S07` | SECUENCIA_07 COSTURA DE NOCHE (mín. 5 planos) | 🟢 LIBRE |
| `AGENTE_F_S08` | SECUENCIA_08 LA PARTIDA (mín. 6 planos) | 🟢 LIBRE |
| `AGENTE_G_S09` | SECUENCIA_09 PRESENTE — hijo adulto y madre de 80 (Tiempo B, mín. 6 planos) | 🟢 LIBRE |
| `AGENTE_H_S10` | SECUENCIA_10 PERFORMANCE del cantante Luis (mín. 6 planos) | 🟢 LIBRE |
| `AGENTE_I_S11` | SECUENCIA_11 CIERRE — el abrazo final (mín. 5 planos) | 🟢 LIBRE |

Al tomar tu tarea: cambia el estado a 🟠 EN PROGRESO, preséntate, y trabaja. Máximo **10 imágenes por turno**, commit + push en cada lote.

## ✅ 5. DÓNDE VA CADA COSA

- Fotos nuevas: `los_caminos_de_la_vida/01_FOTOGRAFIAS_POR_SECUENCIA/SECUENCIA_XX_NOMBRE/` con nombre `SXX_PNN_DESCRIPCION_MM.jpg` (ej: `S05_P02_COLMADO_RADIO_50MM.jpg`).
- Su lista de planos: en la misma carpeta, `SECUENCIA_XX_PLANOS.md` (cada plano: lente, acción, luz, vestuario).
- Tu firma: `02_DIRECCION/REGISTRO_DE_AGENTES.md` (una línea por lote entregado).
- El Director aprueba → tu foto pasa a `03_FOTOGRAFIA_FINAL/SECUENCIA_XX/` (esa es la carpeta que se usa para animar). **No toques esa carpeta tú.**

---

## Estado de avance (el Director lo actualiza)
- [x] Charters: Luis, Protagonista adulto, Protagonista niño, Madre Tiempo A, Madre Tiempo B, Hermano A/B, Casa.
- [x] S01 INTRO (10 planos — 8 aprobadas, 2 a REHACER) · S02 EL RÍO (6 — aprobadas, 2 con revisión de cicatriz) · S03 CONUCO (6 — 5 aprobadas, 1 a REHACER) · S04 ESCUELA (4/6 — 2 aprobadas, 1 REVISAR, 1 REHACER).
- [ ] S05–S11: abiertas (ver tablero de tareas).
