### 5.e Usability Report de B

#### Evaluación de usabilidad del proyecto AL Burguers

[29/05/2026]

![Icono AL](img/iconoAL.png)

![Enlace a GITHUB del proyecto](https://github.com/xGeaa/UX_CaseStudy)

Realizado por: Goiko Finder

#### 1. Resumen Ejecutivo

- **Objetivo:** Evaluar la usabilidad de AL Burguers (Caso B) en el marco del A/B Testing frente a Goiko Finder (Caso A), identificando fortalezas y barreras de uso reales.
- **Metodología:** Tarea supervisada T1 (_"Busca una hamburguesa sin gluten y anota sus ingredientes"_) + Eye Tracking con GazeMapping + cuestionario SUS.
- **Principales Hallazgos:**
  1. **Sin alérgenos integrados en la carta:** los usuarios deben navegar a una sección separada para ver alérgenos, en lugar de verlos junto a cada plato. Lucia (B): _"No están especificados los alérgenos, tenía que leerlo todo"_.
  2. **Sin detalle ni imagen por hamburguesa:** los platos solo muestran ingredientes en texto; no hay página de detalle ni foto individual. David (B): _"No hay vista previa de la hamburguesa, únicamente se describen los ingredientes"_.
  3. **Contenido escaso:** la web transmite poca información general sobre el restaurante. Fernando (B): _"Poca información y escaso contenido"_.
- **Resultado Global:** Caso B completa la tarea con éxito en los 5 usuarios. Tiempo medio Caso B: **15.0 seg** vs. **28.7 seg** Caso A. Puntuación SUS media: **Caso A (Goiko Finder) = 89.0** · **Caso B (AL Burguers) = 87.0** — ambos en categoría **Best Imaginable** (>85). Goiko Finder supera por 2 puntos, con ventaja en integración de funciones (Q5) y confianza de uso (Q9).

#### 2. Metodología y Reclutamiento

- **Perfil de los participantes:** 10 usuarios en total (5 Caso A, 4 datos válidos Caso B). Edad media 20-22 años, todos estudiantes universitarios, nivel TIC mayoritariamente alto. Todos los participantes del Caso B llevan gafas o lentillas (relevante para la calibración de Eye Tracking).
- **Escenario de la prueba:** Tarea única T1 — _"Busca una hamburguesa sin gluten en el menú y anota cuáles son sus ingredientes"_. Flujo esperado en Caso B: Home → círculo ALÉRGENOS o La Carta → ALÉRGENOS → identificar plato sin gluten → volver a La Carta → localizar ingredientes.
- **Herramientas:** GazeMapping + FireShot para Eye Tracking, cuestionario SUS vía Tally.so, registro manual de tiempo de tarea y observaciones del evaluador.

#### 3. Resultados del Cuestionario SUS

| Usuario     | Caso | Puntuación SUS | Etiqueta            |
| ----------- | ---- | :------------: | ------------------- |
| Fernando    | A    |      87.5      | Best Imaginable     |
| Yeray       | A    |      87.5      | Best Imaginable     |
| Ares        | A    |      92.5      | Best Imaginable     |
| Lucia       | A    |      95.0      | Best Imaginable     |
| Pablo DLTR  | A    |      82.5      | Excellent           |
| **Media A** |      |    **89.0**    | **Best Imaginable** |
| David       | B    |      90.0      | Best Imaginable     |
| Pablo       | B    |      87.5      | Best Imaginable     |
| Ares        | B    |      82.5      | Excellent           |
| Lucia       | B    |      87.5      | Best Imaginable     |
| Fernando    | B    |      87.5      | Best Imaginable     |
| **Media B** |      |    **87.0**    | **Best Imaginable** |

**Comparativa A vs. B — distribución de scores (box plot):**

![Box Plot SUS](P5/Realizacion/plot.png)

**Posición percentil:**

![Percentil SUS](<P5/Realizacion/plot (1).png>)

Ambos casos en **percentil ~96-97** — por encima del 95% de sistemas evaluados con SUS.

**Desglose por ítem:**

![Barras por pregunta](<P5/Realizacion/plot (2).png>)

![Radar comparativo](<P5/Realizacion/plot (3).png>)

- **Q1** (visitar con frecuencia): A(9.0) > B(7.0) — Goiko Finder genera más intención de revisita.
- **Q2** (complejidad): B(9.5) > A(8.5) — AL Burguers percibido como más simple.
- **Q5** (funciones integradas): A(9.0) > B(7.5) — confirma la queja de alérgenos no integrados en carta.
- **Q8** (demasiado grande): B(10.0) > A(8.0) — AL Burguers no se percibe como excesivo; Goiko Finder con más contenido roza la sensación de amplitud.
- **Q9** (confianza en el manejo): A(8.0) > B(6.5) — **peor puntuación de B en todo el cuestionario**, coherente con _"poca información"_ y _"sin vista previa"_.

#### 4. Análisis de Eye Tracking

Sesiones realizadas con 3 usuarios (David, Jose, Pablo) sobre tres páginas: **Home**, **La Carta** y **Eventos**. Capturas rasterizadas con FireShot y analizadas con GazeMapping.

---

##### 4.1 Home (Página Principal)

| Usuario | Heatmap                                                                                  |
| ------- | ---------------------------------------------------------------------------------------- |
| David   | ![Heatmap Principal David](P5/EyeTracking/David/Heatmap%20-%20principal%20-%20David.png) |
| Jose    | ![Heatmap Principal Jose](P5/EyeTracking/Jose/HeatMap%20-%20Principal%20-%20Jose.png)    |
| Pablo   | ![Heatmap Principal Pablo](P5/EyeTracking/Pablo/Heatmap%20-%20Principal%20-%20Pablo.png) |

**Hallazgos Home:**

| POI                                           | Observación real                                                                                                                      |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Barra de navegación superior                  | **Hotspot en los 3 usuarios.** Primera zona de fijación. "La Carta" y "Eventos" son los ítems más leídos antes de mirar los círculos. |
| Círculos LA CARTA y EVENTOS (fila superior)   | Alta atención en los 3. Jerarquía visual arriba-abajo funciona correctamente.                                                         |
| Círculos ALÉRGENOS y RESERVAS (fila inferior) | Fijación secundaria y más tardía. Reciben menos atención que los superiores en todos los usuarios.                                    |
| GALERÍA (columna derecha)                     | **Zona de silencio total** en los 3 usuarios. Ninguno fijó la mirada en las fotos de la galería.                                      |
| Panel RESEÑAS (columna izquierda)             | Atención ocasional sobre la reseña activa, pero no sistemática. El texto truncado y el efecto blur no invitan a leer.                 |
| CTA "RESERVAR" (nav, extremo derecho)         | Escasa fijación a pesar del bold. Compite en atención con los círculos centrales y pierde.                                            |

---

##### 4.2 La Carta

| Usuario | Heatmap                                                                          |
| ------- | -------------------------------------------------------------------------------- |
| David   | ![Heatmap Carta David](P5/EyeTracking/David/Heatmap%20-%20carta%20-%20David.png) |
| Jose    | ![Heatmap Carta Jose](P5/EyeTracking/Jose/Heatmap%20-%20Carta%20-%20Jose.png)    |
| Pablo   | ![Heatmap Carta Pablo](P5/EyeTracking/Pablo/Heatmap%20-%20Carta%20-%20Pablo.png) |

**Hallazgos La Carta:**

| POI                                 | Observación real                                                                                                                                             |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Hero "LA CARTA" (banner superior)   | **Hotspot intenso** en los 3. Primera zona de fijación — el título y la imagen de fondo absorben la mayor parte de la atención inicial.                      |
| Círculo PRINCIPALES                 | Alta fijación. Es el primer círculo de categoría al que van los usuarios antes de explorar los demás.                                                        |
| Círculo ALÉRGENOS (último, derecha) | **El menos atendido en 2 de 3 usuarios.** Solo Pablo registra fijación notable. Confirma que la información de alérgenos no es descubierta de forma natural. |
| Sección de platos PRINCIPALES       | Atención moderada sobre los nombres y precios. Los ingredientes en texto pequeño se leen poco.                                                               |
| CTA "RESERVAR →" (hero, derecha)    | Fijación moderada en Jose y Pablo. David prácticamente lo ignora.                                                                                            |

---

##### 4.3 Eventos

| Usuario | Heatmap                                                                                    |
| ------- | ------------------------------------------------------------------------------------------ |
| David   | ![Heatmap Eventos David](P5/EyeTracking/David/Heatmap%20-%20eventos%20-%20David.png)       |
| Jose    | ![Heatmap Eventos Jose](P5/EyeTracking/Jose/Heatmap%20-%20Eventos%20-%20Jose.png)          |
| Pablo   | ![Heatmap Eventos Pablo](P5/EyeTracking/Pablo/Heatmap%20-%20Eventos%20-%20%20%20Pablo.png) |

**Hallazgos Eventos:**

| POI                                           | Observación real                                                                                                                    |
| --------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| Sección "NUESTRAS CELEBRACIONES"              | **Hotspot dominante en los 3 usuarios**, especialmente Jose (zona roja intensa sobre el texto). Mayor engagement de toda la página. |
| Sección "NUESTROS FOODTRUCKS"                 | Significativamente menos atendida. El patrón vertical de lectura se agota antes de llegar al final de la página.                    |
| Fotos de evento — panel derecho               | **Zona de silencio en los 3 usuarios.** Las imágenes rectangulares de la sección celebraciones no atraen la mirada.                 |
| Imagen circular food truck (derecha)          | Fijación escasa. El formato circular no compensa la poca atención que llega a la sección inferior.                                  |
| Footer "Contáctanos" / "Preguntas Frecuentes" | Fijaciones inesperadas en 2 de 3 usuarios — buscan info de contacto que no encuentran fácilmente en la nav principal.               |

---

##### 4.4 Hallazgo clave

> **El 100% de los usuarios ignoró la GALERÍA** en la Home. El círculo ALÉRGENOS en La Carta fue ignorado por 2 de 3 usuarios, lo que explica los tiempos más altos en T1 y el comentario de Lucia B: _"tenía que leerlo todo"_. La sección FOODTRUCKS es ignorada por la mayoría — el contenido clave debe subir en la jerarquía de página.

#### 5. Auditoría de Accesibilidad

- **`lang` incorrecto:** HTML declara `lang="en"` pero todo el contenido está en español. Los lectores de pantalla pronunciarán el texto con fonética inglesa. **Corrección:** `<html lang="es">`.
- **Texto blanco sobre imágenes circulares:** Los botones LA CARTA, EVENTOS, ALÉRGENOS, RESERVAS usan texto blanco sobre fotografías de fondo variable. El contraste no está garantizado y puede no superar WCAG AA (4.5:1). Añadir overlay oscuro fijo o sombra de texto.
- **Imágenes sin `alt` descriptivo:** Las fotos de galería y los círculos usan imágenes de fondo CSS o stock sin texto alternativo accesible para lectores de pantalla.
- **Navegación por teclado:** No verificada. Las SPA en React pueden generar trampas de foco si los círculos no tienen `role="button"` y `tabIndex`. Pendiente de prueba con Tab.
- **Puntuación Lighthouse:** Pendiente. Ejecutar desde DevTools → Lighthouse → Accessibility y adjuntar captura en P5/.

#### 6. Conclusiones y Recomendaciones

| **Prioridad** | **Hallazgo**                                                                                   | **Recomendación de Mejora**                                                                               |
| ------------- | ---------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| **Alta**      | `lang="en"` en HTML con contenido en español — rompe accesibilidad con lectores de pantalla    | Cambiar a `lang="es"` en el `<html>`.                                                                     |
| **Alta**      | Alérgenos no integrados en la carta — el usuario debe ir a sección separada (Lucia B, David B) | Añadir iconos/etiquetas de alérgenos junto a cada plato dentro de La Carta.                               |
| **Alta**      | Sin detalle ni imagen por hamburguesa — solo texto de ingredientes (David B)                   | Crear página de detalle por plato con foto, ingredientes, precio y etiquetas de alérgenos.                |
| **Media**     | Navegación duplicada — La Carta y Eventos aparecen en nav bar Y en círculos de home            | Eliminar la redundancia: usar los círculos como destacados visuales, no como navegación secundaria.       |
| **Media**     | Alérgenos y Reservas en círculos de home pero ausentes de la barra de navegación principal     | Añadir "Alérgenos" al menú de navegación para garantizar acceso consistente desde cualquier página.       |
| **Baja**      | Panel de reseñas con texto truncado y efecto blur — dificulta lectura sin interacción previa   | Mostrar al menos una reseña completa por defecto sin blur.                                                |
| **Baja**      | Contenido escaso en la web general (Fernando B)                                                | Ampliar sección "Acerca de" con historia del restaurante, valores y equipo para dar confianza al usuario. |
