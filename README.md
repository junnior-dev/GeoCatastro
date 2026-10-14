# GeoCatastro

Prototipo de **visor y captura catastral GIS** en React + TypeScript (Vite).
Dibujo de polígonos sobre mapa, ficha técnica del predio, generación de PDF y
panel de estadísticas, con soporte offline.

## Stack

- React + TypeScript + Vite
- Mapas: Leaflet + react-leaflet + Leaflet.draw + Turf
- Gráficos: Recharts
- PDF: react-pdf
- Datos locales: Dexie (IndexedDB) + capa mock / sincronización (`lib/sync.ts`)
- Backend objetivo: Supabase
- Prototipado inicial con Bolt

## Características

- `MapaCatastral` y `MapaFicha`: visualización de predios
- `DibujarPoligono`: delimitación interactiva de linderos
- `FichaPDF`: exportación de la ficha catastral
- `useGeolocation` / `useOnline`: geolocalización y detección de conectividad
- `GraficoBarras` / `Tarjeta`: panel de métricas

## Puesta en marcha

```bash
npm install
npm run dev
```

## Scripts

| Comando | Descripción |
| --- | --- |
| `npm run dev` | Desarrollo |
| `npm run build` | Build de producción |
| `npm run preview` | Previsualizar build |

---

Por [junnior-dev](https://github.com/junnior-dev).
