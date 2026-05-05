# Duplas Intergeneracionales Tech

Landing del programa **Duplas Intergeneracionales Tech**, una alianza entre **Entel** (Fondo 55+) y **Desafío Latam**, con apoyo de **Huechuraba Capacita**.

## Stack

- Astro 5
- Tailwind CSS v4 (vía `@tailwindcss/vite`)
- pnpm

## Comandos

```bash
pnpm install
pnpm dev      # http://localhost:4321
pnpm build
pnpm preview
```

## Estructura

```
src/
├── layouts/Layout.astro       SEO + fonts
├── components/
│   ├── Nav.astro
│   ├── Hero.astro             Título + fecha postulación + cards stats
│   ├── WhatIs.astro           ¿Qué es el programa?
│   ├── Audience.astro         Senior 55-70 + Joven 18-30
│   ├── Program.astro          Etapa 1 + Etapa 2
│   ├── Webinars.astro         Los 8 webinars
│   ├── Timeline.astro         Cronograma de fechas clave
│   ├── FAQ.astro              Dudas y consultas
│   ├── Form.astro             Formulario de postulación
│   └── Footer.astro
├── pages/
│   ├── index.astro
│   └── success.astro
└── styles/global.css          Paleta entel + tokens
```

## Paleta

| Token         | Hex       | Uso                              |
|---------------|-----------|----------------------------------|
| `entel`       | `#0033a0` | Azul corporativo                 |
| `entel-deep`  | `#00205b` | Fondos oscuros                   |
| `entel-cyan`  | `#00c0f1` | Acento celeste                   |
| `orange`      | `#f37021` | Naranja Entel · CTA              |
| `violet`      | `#603bff` | Acento Desafío Latam             |
| `sand`        | `#e6efff` | Texto sobre oscuro               |
| `surface`     | `#f7f9fc` | Fondo claro                      |
| `ink`         | `#0b1f3a` | Texto principal                  |
