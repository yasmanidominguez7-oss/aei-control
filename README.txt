AEI CONTROL — PROYECTO COMPLETO
================================

Este paquete contiene la aplicación completa de AEI Control para publicar en GitHub Pages.

ARCHIVOS
--------
index.html     Aplicación completa.
logo.jpg       Logo original proporcionado para American Engineering Inc.
manifest.json  Configuración PWA.
sw.js          Caché/offline básico.
README.txt     Instrucciones.

MÓDULOS INCLUIDOS
------------------
Inicio
Producción
Máquinas
Órdenes de trabajo
Mantenimiento
Alertas
Inventario
Reportes
Usuarios
Configuración

FUNCIONES
---------
- Dashboard operativo.
- Registro rápido de producción.
- Validación automática de buenas/rechazadas.
- Historial de producción.
- Alta y edición de máquinas.
- Estado de máquinas y detalle.
- Órdenes de trabajo.
- Avance de órdenes.
- Agenda de mantenimiento.
- Alertas atendibles.
- Inventario y ajuste de stock.
- Usuarios y roles.
- Configuración.
- Respaldo JSON.
- Importación de respaldo.
- Exportación CSV.
- Persistencia local.
- PWA.
- Diseño responsive PC/móvil.
- Logo original.

PUBLICACIÓN EN GITHUB PAGES
---------------------------
1. Abre tu repositorio aei-control.
2. Sube y reemplaza los 5 archivos directamente en la raíz.
3. Haz Commit changes.
4. Settings > Pages.
5. Branch: main.
6. Folder: / (root).
7. Guarda y espera la publicación.

IMPORTANTE
----------
Esta versión está diseñada para funcionar completamente como aplicación web local/PWA.
Los datos se almacenan en el navegador mediante localStorage.

La conexión con CNC físicas, sensores, PLC, MTConnect, OPC UA o una base de datos
central requiere posteriormente un servidor/gateway industrial; GitHub Pages por sí
solo no puede hablar directamente con una máquina CNC. La interfaz y los módulos
están preparados para esa integración sin cambiar el flujo sencillo para el operador.
