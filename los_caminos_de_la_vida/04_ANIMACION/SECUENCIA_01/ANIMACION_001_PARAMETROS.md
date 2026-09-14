# ANIMACIÓN-001 — PARAMETROS (WILSON, 14-sep)
**Orden:** `02_DIRECCION/13_ESPEC_TECNICA_ANIMACION.md` · **Clip:** `S01_P01_ANIM.mp4`
- **Foto de origen (aprobada):** `03_FOTOGRAFIA_FINAL/SECUENCIA_01_INTRO/S01_P01_CAMINO_CASA_AMANECER_4K.jpg` (4096×1716). El frame 0 del clip ES la foto de origen; el encuadre respeta la foto aprobada.
- **Movimiento:** push-in lento hacia la casa, 6.0 s · 24 fps · easing cósmeno (respiración: arranca y termina en velocidad cero — "que nadie note la cámara").
- **Parallax 2.5D, 4 capas suaves (pesos gaussianos normalizados, sin costuras):**
  | Capa | Región | Escala inicio→fin |
  |---|---|---|
  | Cielo | banda superior (hasta la niebla) | 100% → 102% |
  | Niebla/colinas | horizonte | 100% → 103.5% |
  | Casa (+árbol del patio) | ancla central | 100% → 105% |
  | Camino/cercas | primer plano | 100% → 107% |
- **Ancla del zoom:** centro de la casa (px 1978, 756 en 3840×1608).
- **Entrega:** 3840×1608 (2.39:1) · H.264 yuv420p · sin música, sin texto, sin marca de agua.
