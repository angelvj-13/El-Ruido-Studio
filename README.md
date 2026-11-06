# EL RUIDO · STUDIO 2.0

Estudio de producción local-first para el cortometraje *El Ruido*.

## Funciones
- 18 misiones iniciales, editables y con texto de trabajo y archivos adjuntos.
- Guion de escenas 1–6, con textos de referencia y editor autosalvado; escenas 7–9 pendientes.
- Archivo de imágenes, audio, vídeo y documentos en IndexedDB, con previsualización/reproductor y eliminación.
- Notas y enlaces, progreso semanal (3 misiones libres), archivo y biblia creativa.
- Exportación e importación JSON de una copia completa, incluidos archivos adjuntos.
- En Chrome/Edge de escritorio, elección opcional de carpeta para copiar los archivos nuevos al disco. No sincroniza ni recupera automáticamente una carpeta anterior.

## Datos y precauciones
La app es estática y funciona en GitHub Pages. **GitHub no guarda el contenido que añades en la interfaz**: se almacena en el navegador y dispositivo mediante IndexedDB. No se sincroniza entre Mac e iPhone. Al borrar los datos del navegador o desinstalar la app, puedes perderlos. Exporta copias de seguridad frecuentes y guárdalas en un lugar seguro. Las copias JSON con audio/vídeo pueden ser grandes.

Los dibujos de los personajes incluidos en la portada son **ilustraciones nuevas provisionales**, no reproducciones exactas de los fotogramas originales. Para conservar los diseños definitivos, adjunta los archivos originales en Archivo.

## Publicación
Subir los archivos a la raíz de la rama `main`, activar GitHub Pages desde `main / (root)`. Para probar en local, ejecutar `python3 -m http.server 8000` y abrir http://localhost:8000.
