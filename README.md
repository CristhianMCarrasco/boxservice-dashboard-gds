# Dashboard de seguimiento — BoxService V2

**Soluciones que conectan**

Dashboard académico estático para Gestión del Desarrollo de Software.

## Visualización local
En la carpeta del proyecto ejecutar `python -m http.server 8000` y abrir `http://localhost:8000`.

## Publicación en GitHub Pages
Crear repositorio público, subir estos cuatro archivos en la raíz y activar Settings → Pages → Deploy from a branch → main / (root).

## Versión 2
Menú de navegación con anclas, comparativa de tarjetas por sprint y metodología de los indicadores.

## Actualización de datos
Modificar `data.json` y volver a publicar. Los datos proceden de capturas de Trello y GitHub compartidas el 4 de noviembre de 2026.

## Precauciones
- El avance 25/34 es provisional según columnas contabilizadas.
- Los PR cerrados no equivalen a PR fusionados.
- Las ejecuciones CI exitosas/fallidas se refieren únicamente a filas visibles en capturas, no a todo el historial.
- Las 19 pruebas unitarias corresponden a una etapa anterior documentada; no hay evidencia de ejecución automática de tests en el workflow inspeccionado.
