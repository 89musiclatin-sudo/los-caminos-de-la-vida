# 04 — CONTROL DE PRODUCCIÓN POR DEPARTAMENTOS (PODER TOTAL DEL DIRECTOR)
**El Director (LEVI) controla TODOS los departamentos. Ningún agente decide nada por su cuenta: ejecuta las órdenes.**
**Toda foto nueva pasa por este control ANTES de entrar a `03_FOTOGRAFIA_FINAL/`.**

## CÓMO SE CONTROLA A LOS AGENTES (protocolo anti-caos)
1. El dueño (Jefe) le da el link del repo a cada agente nuevo. El agente OBLIGATORIAMENTE se presenta: nombre + ID tomado del tablero del README.
2. El agente firma su primer mensaje en `REGISTRO_DE_AGENTES.md` con su ID. **Sin firma = su trabajo se ignora y no se revisa.**
3. El agente SOLO trabaja SU tarea del tablero. Si toca otra secuencia, se rechaza sin revisar.
4. Máximo 10 fotos por lote. Cada lote: commit + push firmado `[ID] ...`.
5. El Director revisa CADA lote y publica veredicto en `03_TABLERO_DE_REPARACIONES.md`:
   - ✅ **APROBADA** → el Director la copia a `03_FOTOGRAFIA_FINAL/`.
   - 🔍 **REVISAR** → corrección menor, la vuelve a subir el mismo agente.
   - ❌ **REHACER** → orden obligatoria con la causa exacta. Si un agente falla 3 veces el mismo plano, el dueño le quita la tarea y se la asigna a otro ID.
6. **El Jefe ya no responde preguntas técnicas de los agentes.** Todo lo que un agente necesite está en el repo: si pregunta, la respuesta es "lee el README y los 4 documentos de 02_DIRECCION".

## LOS 7 CONTROLES QUE EL DIRECTOR APLICA A CADA FOTO

### 1. DEPARTAMENTO DE PERSONAJES / CHARTERS
- [ ] ¿El rostro es el clon del charter correcto? (misma persona, ni parecido ni "inspirado")
- [ ] ¿Edad correcta según timeline? (niño 9-10, adolescente 15-16, adulto 31-34, madre 35-40 / 80)
- [ ] ¿La cicatriz en ceja derecha del protagonista está cuando se ve la cara? ¿El hermano NO la tiene?
- [ ] ¿La madre Tiempo B es LA MISMA mujer del Tiempo A envejecida?
- [ ] ¿5 dedos por mano, 2 brazos, 2 piernas, ojos sanos? (contar siempre)

### 2. DEPARTAMENTO DE VESTUARIO
- [ ] ¿La ropa es EXACTAMENTE la de la tabla de vestuario de `01_ESTUDIO_DE_PERSONAJES.md` para ESA secuencia?
- [ ] ¿Idéntica en todos los planos de la misma escena? (color, mangas, calzado, delantal sí/no, pañuelo sí/no)
- [ ] ¿Desgaste coherente? (polvo/sudor solo al final del día de trabajo)
- [ ] ¿Sin objetos modernos ni marcas legibles?

### 3. DEPARTAMENTO DE CONTINUIDAD DE ESCENA / OBJETOS
- [ ] ¿Los objetos vistos en el plano general siguen en su lugar en los planos cerrados? (REGLA DE LA LÁMPARA)
- [ ] ¿La arquitectura coincide con los masters de la casa? (puertas, ventanas, postigos de madera natural)
- [ ] ¿Props de mano consistentes? (batea de zinc, lonchera de lata, azadón, olla de hierro, radio del colmado, lámpara de queroseno)
- [ ] ¿El clima y la hora son los mismos que el resto de la escena?

### 4. DEPARTAMENTO DE ILUMINACIÓN
- [ ] ¿La luz está motivada? (sol por hora de la escena, fogón, queroseno, ventana)
- [ ] ¿La dirección de las sombras coincide entre planos de la misma escena?
- [ ] ¿Tiempo A sin electricidad? (cero bombillas, cero cables)
- [ ] ¿Skin tones dominicanos correctos, sin quemar ni lavar?

### 5. DEPARTAMENTO DE DIRECCIÓN DE ACTOR / EXPRESIONES
- [ ] ¿NADIE mira a la cámara? (personaje principal, secundarios y figuras de fondo)
- [ ] ¿La mirada va a la tarea, al objeto o al otro personaje (eyeline correcta para el contraplano)?
- [ ] ¿La emoción es la de la orden del plano? (cansancio contenido, orgullo, ternura, decisión — sin gestos de catálogo ni sonrisa de postal)
- [ ] ¿Las acciones son del día a día real y creíbles? (nada de poses)

### 6. DEPARTAMENTO DE CÁMARA / CALIDAD TÉCNICA
- [ ] ¿Lente correcto según el plano (24/35/50/85/100macro)?
- [ ] ¿Formato 2.39:1, mínimo 2560×1072?
- [ ] ¿Look cine: ARRI Alexa 35 + Cooke, bokeh redondo, grano fino, negros con información?
- [ ] ¿Sin texto, marcas de agua, bordes ni frames falsos?

### 7. DEPARTAMENTO DE LÓGICA
- [ ] ¿Todo lo que aparece tiene sentido físico y narrativo? (nada de 4 machetes, 3 manos, objetos flotando, escaleras a ningún lado)
- [ ] ¿La acción continúa el hilo de la canción y del timeline?

## ESTADO DE CONTROL (lo firma el Director tras cada revisión)
| Lote | Agente | Veredicto | Nota |
|---|---|---|---|
| S01–S04 (26 fotos heredadas) | agencias anteriores (Arena) | ✅ 21 / 🔍 3 / ❌ 4 | Ver tablero de reparaciones |
| — próximo lote — | | | |
