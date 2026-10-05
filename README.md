Analizador Biomecánico Dual de Sentadilla
Este repositorio contiene el código fuente de una plataforma web para el análisis cinemático y bioinstrumental de la sentadilla en dos planos anatómicos simultáneos (Sagital y Frontal), desarrollada para la asignatura de Análisis Bioinstrumental del Movimiento Humano de la Universidad de Chile.
 Enlace a la Aplicación Web
• URL Pública Directa:https://paskalzamorano-ctrl.github.io/an-lisis-sentadilla/
───
Archivos Principales
• index.html: Archivo principal que contiene la estructura HTML de la interfaz, los estilos en CSS para la disposición responsiva y los scripts de procesamiento en JavaScript con MediaPipe Pose.
• README.md: Documentación técnica, requisitos de ejecución y guía de uso del proyecto.
───
Requisitos y Dependencias

Al ser una aplicación web nativa (desarrollada con HTML5, CSS3 y JavaScript vanilla), no requiere instalación previa de software ni compiladores locales como Python o Node.js.
Librerías Externas Cargadas mediante CDN:
• MediaPipe Pose (v0.5.1675469404): Motor de visión computacional para la estimación de marcadores anatómicos 3D (landmarks). 
◦ URL CDN: https://cdn.jsdelivr.net/npm/@mediapipe/pose@0.5.1675469404/pose.js
Requisitos de Hardware y Navegador:
• Navegador web moderno con soporte para WebGL y HTML5 Canvas (Google Chrome, Mozilla Firefox, Safari o Microsoft Edge).
• Conexión a internet activa para la carga inicial de la librería MediaPipe desde el CDN.
───
 Instrucciones de Ejecución
Opción 1: Ejecución en línea (Recomendada)
1. Acceder directamente al enlace público del proyecto en GitHub Pages:
https://paskalzamorano-ctrl.github.io/an-lisis-sentadilla/
Opción 2: Ejecución Local
1. Descargar o clonar este repositorio en su computador.
2. Hacer doble clic sobre el archivo index.html para abrirlo directamente en cualquier navegador web.
3. Cargar los videos correspondientes al plano sagital y frontal en los botones de selección e iniciar el análisis.
───
👥 Autoras
• Francisca Barriga Lara - Estudiante de Kinesiología, Universidad de Chile.
• Sofía Zamorano - Estudiante de Kinesiología, Universidad de Chile.
