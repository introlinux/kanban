# Tablero Kanban Personal

Un tablero estilo Kanban diseñado para uso personal, que permite organizar tareas y proyectos de manera visual.

## Características

- **Estructura simple**: Un único tablero compuesto por listas, que a su vez contienen tarjetas.
- **Contenido en tarjetas**: Cada tarjeta puede incluir:
  - Texto
  - Imágenes
  - Enlaces
  - Archivos adjuntos
  - Enlaces a vídeos de YouTube
- **Foto de portada**: Las tarjetas pueden tener una imagen de portada opcional en el tablero de listas.
- **Arrastrar y soltar**:
  - Cambia la posición de las tarjetas arrastrándolas verticalmente dentro de la misma lista u horizontalmente entre listas.
  - Las listas también se pueden desplazar horizontalmente a otra posición.
- **Búsqueda**: Incluye una caja de búsqueda para encontrar tarjetas rápidamente.
- **Guardado de datos**: 
  - Los datos se guardan en `localStorage` (aprox. 5MB).
  - Las imágenes y archivos adjuntos deben almacenarse en las carpetas `/images` y `/files`, respectivamente.
- **Importación automática**: Si existe un archivo `kanban-data.json` en la misma carpeta que `index.html`, los datos se importarán automáticamente al iniciar.
- **Exportación**: Permite exportar el tablero a formato `.json`.
- **Diseño responsivo**: Estilos adaptados para dispositivos móviles, aunque la funcionalidad de arrastrar y soltar tarjetas aún necesita mejoras.
