# ⚠️ ATENCIÓN AGENTE — LEE ESTO PRIMERO. TODO ESTÁ AQUÍ. ⚠️

Bienvenido al set de **LOS CAMINOS DE LA VIDA** (película/videoclip, campo dominicano años 80–90).
Repo **PÚBLICO DE LECTURA**: con solo este link lees TODO (órdenes, charters, veredictos). La rama `main` está **blindada por GitHub** (nadie puede borrar ni forzar cambios). **Escritura exclusiva del dueño y del DIRECTOR GENERAL: LEVI.** El dueño es el Jefe.

---

## 🔑 1. PUBLICA INMEDIATAMENTE — SIN ESPERAR PERMISO NI VEREDICTO

**ESTA ES LA ORDEN PARA TODA LA CUADRILLA (WILSON, RAMÓN, JUANA, YUDERKA, MARIO y los que vengan):**

1. Genera tus fotos (máx. 10 por lote).
2. **PUBLICA EL LOTE DE INMEDIATO** en este repo — no esperes autorización del dueño, no esperes veredicto del Director, no preguntes "¿puedo publicar?". PUBLICA Y SIGUE TRABAJANDO.
3. El Director tiene un radar que revisa el repo cada 30 minutos: tu veredicto aparecerá solo en `02_DIRECCION/03_TABLERO_DE_REPARACIONES.md` con tu próxima acción. Vuelve al repo, lees tu veredicto, corriges o pasas al siguiente plano de tu guion (`06_EQUIPO_DE_FOTOGRAFIA.md` / `02_ORDENES_NUEVAS_SECUENCIAS.md`).
4. El token de publicación te lo entrega el dueño UNA VEZ en el chat al presentarte. Con él:

```bash
git clone https://github.com/89musiclatin-sudo/los-caminos-de-la-vida.git
cd los-caminos-de-la-vida
# añades tus fotos nuevas en tu carpeta de secuencia + tu línea en REGISTRO_DE_AGENTES.md
git add .
git commit -m "[TU-NOMBRE] SECUENCIA_XX: entrega lote N (fotos nuevas, nada borrado)"
git push https://TU-TOKEN@github.com/89musiclatin-sudo/los-caminos-de-la-vida.git main
```

**PERMISOS (estrictos):**
- ✅ PUEDES: leer todo, AÑADIR fotos nuevas en `los_caminos_de_la_vida/01_FOTOGRAFIAS_POR_SECUENCIA/SECUENCIA_XX/`, añadir tu `SECUENCIA_XX_PLANOS.md` y tu línea en `02_DIRECCION/REGISTRO_DE_AGENTES.md`.
- ❌ NO PUEDES: borrar ni modificar NINGÚN archivo existente, ni tocar `00_continuidad/`, `02_DIRECCION/` (solo añadir tu línea de registro), `03_FOTOGRAFIA_FINAL/`, `04_FOTOGRAFIA_EN_REPARACION/` ni `README.md`. El radar restaura cualquier borrado y lo documenta como incidente.
- Decidir (aprobar/reparar/rechazar) es SOLO del Director (LEVI) con el dueño. Tu siguiente tarea SIEMPRE está en el tablero: publica → el radar revisa → lees el veredicto → ejecutas la siguiente orden. Así hasta terminar las 68 fotos de la película.

## 🟢 1.4 HAY TRABAJO AHORA MISMO — MIRA `los_caminos_de_la_vida/02_DIRECCION/11_ORDENES_LIBRES_HOY.md`
**ÓRDENES LIBRES ACTUALIZADAS: 4 bloques de Tiempo B (EL TRABAJO DEL HIJO - LA TARDE DE LA MADRE - EL DIA DEL REENCUENTRO - LA COMIDA DEL PRESENTE) + parejas de tiempo + transiciones + insertos. Toma una, escribe TOMADA POR [tu nombre], genera y publica. Y repite.

## 🟢 1.4b HAY TRABAJO AHORA MISMO (anterior) — 29 ÓRDENES ABIERTAS
**Ve a `los_caminos_de_la_vida/02_DIRECCION/10_MESA_DE_TRABAJO_ABIERTA.md`, elige una orden LIBRE, escribe "TOMADA POR [tu nombre]" al lado, y ejecuta. Primero llega, primero sirve. Terminaste una → tomas otra. Siempre hay trabajo.**

## 🔁 1.5 BUCLE CONTINUO — JAMÁS TE DETENGAS
Al despertar (cada vez que el dueño te escriba, aunque sea una palabra), ejecuta el bucle de `los_caminos_de_la_vida/02_DIRECCION/08_ORDEN_PERMANENTE_DE_BUCLE.md`: tablero → generar → publicar → tablero → repetir. NO EXISTE LA ACCIÓN "ESPERAR AUTORIZACIÓN". El veredicto del Director aparece solo en el tablero cada 30 minutos.

## 🪪 2. PRESENTACIÓN OBLIGATORIA (antes de generar UNA sola imagen)

1. Elige tu **ID de agente** libre del tablero de tareas (ejemplo: `AGENTE_C_S05`).
2. **Preséntate** al dueño: *"Soy [tu nombre], trabajo como AGENTE_C_S05, mi tarea es la SECUENCIA_05, leeré la MEMORIA MAESTRA DE SET y el ESTUDIO DE PERSONAJES antes de generar."*
3. Si vuelves en un chat nuevo → te presentas de nuevo y continúas tu tarea.
4. **Firma TODO tu trabajo con tu ID.** Trabajo sin firma = no existe y el Director no lo revisa.

## 🎬 3. LOS 5 DOCUMENTOS DE DIRECCIÓN — EN ORDEN, EN `los_caminos_de_la_vida/02_DIRECCION/`

| # | Documento | Qué te da |
|---|---|---|
| 1 | `00_MEMORIA_MAESTRA_DE_SET.md` | **LA LEY**: calidad de cine (ARRI Alexa 35 + lentes Cooke, 2.39:1, mínimo 2560×1072), nadie mira a cámara, misma escena = misma ropa, la regla de la lámpara (los objetos no desaparecen), anatomía (5 dedos), lógica. |
| 2 | `01_ESTUDIO_DE_PERSONAJES.md` | Estudio pieza por pieza de cada charter + tabla de vestuario fijo por secuencia. |
| 3 | `02_ORDENES_NUEVAS_SECUENCIAS.md` | Tu orden creativa concreta: locación, luz, planos con lente, props fijos. |
| 4 | `03_TABLERO_DE_REPARACIONES.md` + `04_CONTROL_DEPARTAMENTOS.md` | Los veredictos del Director (si tu foto dice REHACER, la rehaces con la orden exacta) y los 7 controles que pasa cada foto. |
| 5 | `05_SET_CASA_BLOQUEADO.md` | **LA CASA ES UNA SOLA**: geografía bloqueada de sala, cocina-fogón y dormitorios. Todo interior se clona de los masters; si no coincide = REHACER automático. |

Los charters están en `00_continuidad/` — **referencia obligatoria en cada generación. NUNCA se modifican ni borran.**

## 📋 4. TABLERO DE TAREAS — CADA AGENTE, UNA Y SOLO UNA

| ID de agente | Tarea | Estado |
|---|---|---|
| `AGENTE_A_REPARA` | Reparar las fotos REHACER del tablero (S01_P03, S01_P05, S03_P05, S04_P04; revisar S04_P03, S02_P03/P06, S01_P01) | 🟡 ABIERTA |
| `AGENTE_B_S04` | Terminar SECUENCIA_04: P05 llegada a la escuelita y P06 entrada a contraluz | 🟡 ABIERTA |
| `AGENTE_C_S05` | SECUENCIA_05 EL COLMADO (mín. 6 planos) | 🟢 LIBRE |
| `AGENTE_D_S06` | SECUENCIA_06 LA COMIDA (mín. 6 planos) | 🟢 LIBRE |
| `AGENTE_E_S07` | SECUENCIA_07 COSTURA DE NOCHE (mín. 5 planos) | 🟢 LIBRE |
| `AGENTE_F_S08` | SECUENCIA_08 LA PARTIDA (mín. 6 planos) | 🟢 LIBRE |
| `AGENTE_G_S09` | SECUENCIA_09 PRESENTE — hijo adulto y madre de 80, Tiempo B (mín. 6 planos) | 🟢 LIBRE |
| `AGENTE_H_S10` | SECUENCIA_10 PERFORMANCE del cantante Luis (mín. 6 planos) | 🟢 LIBRE |
| `AGENTE_I_S11` | SECUENCIA_11 CIERRE — el abrazo final (mín. 5 planos) | 🟢 LIBRE |

## ✅ 5. CÓMO NOMBRAS TU ENTREGA (para que el Director la publique correcto)

- Nombre: `SXX_PNN_DESCRIPCION_MM.jpg` (ej: `S05_P02_COLMADO_RADIO_50MM.jpg`).
- Adjunta también tu `SECUENCIA_XX_PLANOS.md` (lente, acción, luz, vestuario de cada plano).
- El Director publica en `01_FOTOGRAFIAS_POR_SECUENCIA/`, firma por ti en `REGISTRO_DE_AGENTES.md`, y lo aprobado pasa a `03_FOTOGRAFIA_FINAL/SECUENCIA_XX/` (la carpeta de animación). **Esa carpeta solo la toca el Director.**

---

## 📊 Estado de avance (lo actualiza el Director)
- [x] Charters: Luis, adulto, niño, Madre A, Madre B, Hermano A/B, Casa (9 masters restaurados).
- [x] S01 INTRO 8/10 aprobadas (P03, P05 a REHACER) · S02 EL RÍO 6/6 aprobadas (P03/P06 verificar cicatriz) · S03 CONUCO 5/6 (P05 a REHACER) · S04 ESCUELA 2/4 (P03 revisar, P04 REHACER, P05–P06 pendientes).
- [~] **S04 ESCUELA: 6/6 ENTREGADOS** — P05 y P06 subidos por `AGENTE_B_S04` (P03 REVISAR / P04 REHACER siguen con `AGENTE_A_REPARA`).
- [~] **S05 EL COLMADO: 6/6 ENTREGADOS** por `AGENTE_C_S05` al spec de `02_ORDENES_NUEVAS_SECUENCIAS.md` — **pendientes de veredicto del Director**.
- [ ] S06–S11 abiertas (`AGENTE_D_S06` … `AGENTE_I_S11`). Incidente del 11-sep: agente sin autorización borró charters y dirección → **restaurado al 100%**; protocolo sin-token activo.
