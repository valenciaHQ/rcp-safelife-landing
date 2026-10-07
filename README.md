# Landing — Curso RCP y DEA (Safe Life Medical School)

Sitio estático (HTML + CSS + JS vanilla), sin build. Listo para Vercel.

## Deploy

```bash
npx vercel          # preview
npx vercel --prod   # producción
```

En el primer deploy: framework **Other**, sin build command, output directory `.` (raíz).

## Estructura

- `index.html` — la landing completa
- `img/` — imágenes optimizadas en WebP
- `vercel.json` — URLs limpias y caché larga para `/img`

## Datos a editar

- Fecha/hora de la cuenta regresiva: buscar `new Date('2026-10-17T16:30:00-03:00')` en `index.html`
- WhatsApp: constante `WA` (5491132946939)
