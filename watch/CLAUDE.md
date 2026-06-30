# Proyecto presell_mediguard — AngelSense GPS Tracker for Elderly

## Descripción
Presell advertorial estilo Taboola para **AngelSense GPS Tracker for Elderly**. Página estilo artículo editorial / advertorial sobre wandering en adultos mayores con deterioro cognitivo. Sitio editorial: **Caregiver Journal** (alineado con `utm_source=caregiver_journal`).

**ÁNGULO PRINCIPAL:** Hija de 56 años cuenta cómo su madre (82, MCI / mild cognitive impairment) salió a comprar pan y reapareció 8 horas después en un Walmart a 60 millas de distancia. Después de probar Find My iPhone, Apple Watch, llamadas diarias y Life Alert, descubre AngelSense — un dispositivo de GPS en tiempo real diseñado específicamente para personas con pérdida de memoria, con altavoz auto-respondedor que permite a la familia hablar con su ser querido sin que tengan que presionar nada.

## Producto real
- **Nombre:** AngelSense (GPS Tracker for Elderly)
- **URL oficial:** https://www.angelsense.com/gps-tracker-for-elderly/
- **Empresa:** AngelSense (fundada por padre de niño con autismo, ahora también atiende elderly/dementia)
- **Form factors:** Wearable (clip-on que se esconde bajo ropa) o Watch (smartwatch)
- **Modelo de negocio:** suscripción (precio no documentado en presell — el CTA envía al sitio para verla)
- **Diferenciadores clave:**
  - Real-time GPS continuo
  - **Auto-answer two-way speakerphone** (la familia llama al dispositivo, este auto-responde, hablan con el ser querido sin que este toque nada)
  - AI-powered alerts cuando el usuario sale de rutas/lugares familiares
  - Indoor tracking via WiFi
  - Multi-guardian (toda la familia recibe alertas)
  - ETA notifications
  - Soporte staffeado por caregivers reales (no call center)
  - 95%+ wear compliance
  - Diseñado específicamente para memory loss / dementia / autismo (no es un fitness tracker adaptado)

## URL de ventas (CTAs) — con tracking completo
**TODAS las CTAs apuntan a:**
```
https://www.angelsense.com/gps-tracker-for-elderly/?utm_source=caregiver_journal&utm_medium=native&utm_campaign=presell_reloj&ref=alejandrita3125
```

**NO MODIFICAR los UTM params ni el `ref=alejandrita3125`** — son la attribution/affiliate del usuario.

CTAs en `index.html`:
- Botón CTA #1 (después del product reveal)
- Botón CTA #2 (`#trigger-section` — activa sticky bottom bar)
- Botón CTA #3 (final, antes del cierre emocional, con bullets)
- Sidebar CTA
- Sticky bottom bar

## Estructura de archivos
- `index.html` — Página principal (CSS inline en `<style>`)
- `disclaimer.html` — Disclaimer
- `privacy-policy.html` — Política de privacidad
- `term-of-use.html` — Términos de uso
- `style/style.css` — CSS heredado (no usado por index.html)
- `public/style.css` — CSS para páginas legales
- `img/` — Imágenes reales:
  - `02.webp` → hero (mujer mayor sola, pensativa)
  - `03.webp` → mamá en casa con té (sección post-hook)
  - `07.webp` → screenshot app "Mom is at an Unknown location" (sección dolor/CDC stats)
  - `06.webp` → pareja mayor en cocina (sección failed attempts)
  - `01.webp` → dos mujeres conversando (sección sister-in-law / Karen)
  - `04.webp` → teléfono con llamada "Mom" entrante (sección first-month wandering save)
  - `05.webp` → screenshot app "Mom is here" mapa (cierre emocional)
  - `producto.webp` → AngelSense watch + app (todos los CTAs y sidebar)

## Anatomía de la presell (index.html)
1. **Barra ADVERTORIAL** — texto superior obligatorio
2. **Masthead** — "Caregiver Journal" + tagline (fondo verde bosque)
3. **Benefits bar** — Real-Time GPS · Two-Way Speakerphone · Wandering Alerts
4. **Breadcrumb** — Home > Memory & Aging > Wandering & Safety
5. **Headline + categoría** — etiqueta naranja terracota subrayada
6. **Author card** — "By Sarah Kessler" — Family Caregiver Editor
7. **Meta row** — fecha dinámica + 8 min read + 213,894 views
8. **Hero image** (02.webp) — mujer mayor sola
9. **Hook narrativo** — llamada del state trooper desde Mansfield, Ohio
10. **Imagen 03.webp** — mamá con té en casa
11. **Sección estadística "MCI"** — Alzheimer's Association data (6 in 10 wander)
12. **Imagen 07.webp** — screenshot app alert
13. **Failed attempts** — daily calls / Find My iPhone / Apple Watch / Life Alert pendant
14. **Imagen 06.webp** — pareja mayor en cocina
15. **Discovery** — sister-in-law Karen (hospice nurse) menciona AngelSense
16. **Imagen 01.webp** — dos mujeres conversando
17. **Product reveal** — qué hace AngelSense (8 features explicadas)
18. **Imagen producto.webp** — el dispositivo + app
19. **CTA #1** con producto.webp
20. **8 features con checkmarks** (formato `feature-number`)
21. **First month con mom** — semanas 1-4 con la "first real-world save"
22. **Imagen 04.webp** — teléfono con "Mom" llamando
23. **CTA #2** (`id="trigger-section"`)
24. **4 testimonios** — wandering scenarios, no falls
25. **Why haven't I heard** — sección sobre por qué no se publicita
26. **Tabla comparativa** — AngelSense vs Apple Watch vs Life Alert Pendant vs Find My iPhone
27. **CTA #3** (final, con bullets y stock note)
28. **Cierre emocional** — voice message de la madre
29. **Imagen 05.webp** — mapa "Mom is here"
30. **Comments** — 7 comentarios estilo Facebook con replies
31. **Sidebar sticky** — Quick Summary + features + CTA
32. **Sticky bottom bar** — aparece después del CTA #2
33. **Footer** — disclaimer + enlaces legales

## Paleta de colores
Identidad visual propia (verde bosque + terracota). El verde es apropiado para el ángulo de "encontrar a tu ser querido" / vida / familia.

- **Fondo body:** `#f3eee5` (crema cálido)
- **Fondo blanco:** `#ffffff`
- **Texto oscuro:** `#1f2d24`
- **Texto body:** `#2e3d33`
- **Header/masthead:** `#2c4a3c` (verde bosque profundo)
- **CTA botones:** `#c25a35` (terracota cálido)
- **CTA hover:** `#a04a2b`
- **Accent:** `#b8442a`
- **Highlight boxes:** fondo blanco, borde top `#2c4a3c`
- **Update boxes:** fondo `#f5efe2`, borde lateral `#2c4a3c`
- **Estrellas:** `#d4a017`

## Tipografía
- **Serif (titulares):** Lora 400/700/900
- **Sans (cuerpo):** Source Sans 3 400/500/600/700/800

## Reglas de copy aplicadas
- Texto fraccionado en párrafos cortos (2-4 líneas máx)
- Historia en primera persona, perspectiva de hija adulta (mercado decisor)
- Negritas para frases de impacto, itálicas para diálogos
- Sin bloques grandes de texto
- INGLÉS US — "super white", sin claims médicos, sin urgencia agresiva
- Stats reales del Alzheimer's Association (6 in 10 wander, hasta 50% mortality si no se encuentra en 24h)
- Comparaciones honestas con Apple Watch / Life Alert / Find My iPhone

## Reglas de diseño aplicadas
- Identidad visual propia (no reusa azul de presell_2)
- Sin emojis — SVGs inline
- Sin animaciones en CTAs — botones planos, hover cambia color
- Border-radius máx 4px en botones
- Sin sombras ni gradientes (excepto sticky bottom)
- Comentarios estilo Facebook real
- Testimonios estilo cita editorial
- CTAs centrados con label descriptivo

## Pendientes para lanzar
1. ✅ HTML completo
2. ✅ CSS inline + páginas legales adaptadas a "Caregiver Journal"
3. ✅ URL de ventas real con tracking completo (5 lugares)
4. ✅ 8 imágenes reales en `img/`
5. ⬜ (Opcional) Verificar que la página de destino acepta los UTM params correctamente
6. ⬜ (Opcional) Pixel de Taboola si se usa para tracking adicional
7. ⬜ Test en mobile (responsive ya implementado, pero verificar)

## Directorio de trabajo
`/Users/emersoncordoba/Documents/Emerson/presell_create/presell_mediguard`

## Nota sobre el nombre de carpeta
La carpeta se llama `presell_mediguard` por una iteración previa con producto ficticio "MediGuard Pro". El proyecto pivotó a AngelSense pero la carpeta no se renombró. Si se quiere consistencia, se puede renombrar a `presell_angelsense`.
