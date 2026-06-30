# presell_mediguard (AngelSense)

Presell advertorial estilo Taboola para **AngelSense GPS Tracker for Elderly** — dispositivo de tracking en tiempo real diseñado específicamente para adultos mayores con pérdida de memoria.

> Nota: la carpeta se llama `presell_mediguard` por iteración previa, pero el contenido es de AngelSense.

## Quick start

```
open index.html
```

Todo el CSS está inline. No requiere build. Las imágenes están en `img/`.

## Estructura

```
presell_mediguard/
├── index.html              ← Presell advertorial (CSS inline)
├── disclaimer.html         ← Disclaimer médico
├── privacy-policy.html     ← Privacidad
├── term-of-use.html        ← Términos
├── img/                    ← 8 imágenes (.webp)
│   ├── 02.webp             ← hero (mamá sola)
│   ├── 03.webp             ← mamá con té
│   ├── 07.webp             ← screenshot "Unknown location"
│   ├── 06.webp             ← pareja en cocina
│   ├── 01.webp             ← dos mujeres conversando
│   ├── 04.webp             ← teléfono "Mom" llamando
│   ├── 05.webp             ← screenshot "Mom is here"
│   └── producto.webp       ← AngelSense + app (CTAs)
├── style/style.css         ← (heredado, no usado)
├── public/style.css        ← CSS para páginas legales
├── CLAUDE.md               ← Documentación detallada
└── README.md               ← Este archivo
```

## URL de ventas (todos los CTAs)

```
https://www.angelsense.com/gps-tracker-for-elderly/?utm_source=caregiver_journal&utm_medium=native&utm_campaign=presell_reloj&ref=alejandrita3125
```

**Importante:** los UTM params + `ref=alejandrita3125` son la attribution del usuario. NO modificar.

## Ángulo

Hija de 56 años cuenta cómo su madre (82, MCI) salió a comprar pan y reapareció 8 horas después en un Walmart a 60 millas. Después de probar Find My iPhone, Apple Watch, Life Alert y llamadas diarias, descubre AngelSense — el único dispositivo diseñado específicamente para personas con pérdida de memoria, con auto-answer speakerphone que permite a la familia hablar con su ser querido sin que tengan que presionar nada.

**Audiencia:** Adultos 50-65 con padres mayores que muestran early signs de pérdida de memoria.

## Identidad visual

Sitio editorial: **Caregiver Journal** (alineado con `utm_source=caregiver_journal`).

Paleta cálida verde bosque (`#2c4a3c`) + terracota (`#c25a35`). Distinta de `presell_2` (azul profundo) — siguiendo la regla de identidad propia para cada presell.

Tipografía: Lora (serif) + Source Sans 3.

## Notas

- Idioma: inglés (US)
- Tono: editorial/advertorial "super white" — sin claims médicos exagerados, stats reales del Alzheimer's Association
- CTAs todos al mismo URL con tracking
- Comparaciones honestas con Apple Watch / Life Alert / Find My iPhone
