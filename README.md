# Dashboard de Cámaras Trampa (GitHub Pages)

Página estática con el dashboard de cámaras trampa: KPIs, actividad por hora y especie, matriz sitio x especie, índices de diversidad y galería de fotos. Es un único `index.html` autocontenido (sin dependencias ni internet).

Paleta de Fundación Naturaleza Argentina (verde #69BE28 / #007934).

Generado desde el pipeline con:

```bash
python3 scripts/dashboard.py --embed --thumb-px 1000 --quality 68
cp out/dashboard_standalone.html ../github-pages/index.html
```

Publicado con GitHub Pages.
