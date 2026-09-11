# 🎬 DIRECTOR DE PRODUCCIÓN — LOS CAMINOS DE LA VIDA

**Este repositorio es la SOLA FUENTE DE VERDAD del proyecto.**
Todos los agentes que trabajen aquí deben seguir este protocolo. Nada vive solo en un chat: si no está en el repo, no existe.

## Quién manda
- **DIRECTOR (agente principal):** analiza el repo, asigna trabajo, hace control de calidad (QA) de todo lo generado, corrige o manda regenerar, y mantiene actualizados README, INFORME_QA y ASIGNACIONES.
- **AGENTES COLABORADORES:** ejecutan las tareas asignadas y reportan en el archivo `TRABAJO/ASIGNACIONES.md` (marcando ✅/⏳/❌ con su nombre y fecha).

## Flujo obligatorio para CUALQUIER agente (5 pasos)
1. **Clona:** `git clone https://github.com/89musiclatin-sudo/los-caminos-de-la-vida.git`
2. **Lee (en orden):** `AGENTE_CONTINUIDAD.md` → `TRABAJO/REGLAS_DE_ORO.md` → `TRABAJO/ASIGNACIONES.md`
3. **Toma una tarea Libre** de ASIGNACIONES.md (o la que el Director te asigne) y **escríbete en ella** (nombre + fecha + estado ⏳).
4. **Genera cumpliendo REGLAS_DE_ORO.md:** usa SIEMPRE los charters como referencia, escena principal = mínimo 5-6 planos dentro del MISMO lugar y MISMO tiempo, cambia ropa solo al cambiar tiempo/lugar, 2.39:1 mínimo 2560×1072, nombra `SXX_PYY_TIPO_LENTE.jpg`.
5. **Commit + push inmediato** al terminar cada secuencia o plano:
```bash
git add . && git commit -m "SECUENCIA_XX: descripcion de lo aportado" && git push
```
   Y actualiza tu fila en `TRABAJO/ASIGNACIONES.md` (⏳ → ✅).

## Credenciales de subida (MUY IMPORTANTE — LEER)
- El token NO vive en este repositorio. **GitHub destruye automáticamente cualquier token que se suba a un repo público** (push-secret-protection). Si un agente subió un token al repo y dejó de funcionar, es por eso.
- El token válido está en el workspace del chat del dueño: archivo `/home/user/GITHUB_TOKEN.txt`.
- **Si no tienes el token:** pídeselo al dueño (usuario GitHub: **89musiclatin-sudo**) o pídele al Director que suba tu trabajo. NUNCA hagas `git push` incluyendo un token dentro de ningún archivo del repo.
- Subir así (el token va en el comando, no en archivos):
```bash
git push https://TU_TOKEN@github.com/89musiclatin-sudo/los-caminos-de-la-vida.git main
```

## Control de calidad del Director
Cada incorporación al repo pasa 3 filtros:
1. **Técnico:** 2.39:1, ≥2560×1072, no corrupta (ver script en INFORME_QA).
2. **Continuidad:** identidad según chárter (cicatriz ceja derecha SOLO protagonista niño/adulto; hermano SIN cicatriz; madre A vs madre B 80 años; casa fija sin electricidad).
3. **Narrativa:** escena completa (mín. 5-6 planos del mismo lugar/tiempo), pobreza con dignidad, Dominicana rural, época correcta.
Lo que no pase el filtro se marca ❌ REHACER en ASIGNACIONES.md con el motivo exacto.

## Estado actual del plan
Ver `README.md` (avance) y `TRABAJO/ASIGNACIONES.md` (tareas vivas).
