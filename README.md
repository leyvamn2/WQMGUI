# AquaSense: Dashboard de Monitoreo de Calidad del Agua
Este proyecto es un prototipo funcional de una interfaz gráfica de usuario (GUI) diseñada para el monitoreo en tiempo real de la calidad del agua, fundamentado en la normativa mexicana NOM-127-SSA1-2021.
## Descripción del Proyecto
#ste dashboard permite visualizar parámetros críticos del agua de forma sencilla para usuarios no especializados. Utiliza un sistema de semáforos y alertas dinámicas para informar sobre la potabilidad y seguridad del recurso hídrico.
## Características Principales
- Lógica en Tiempo Real: Simulación de dispositivos IoT mediante la lectura secuencial
de un archivo CSV (dataset_agua_NOM_25000_6Sensores.csv).
- Semáforo Normativo: Indicador visual (Verde/Amarillo/Rojo) basado en los límites
permisibles de la NOM-127-SSA1-2021.
-  Monitoreo de 6 Parámetros: pH, Turbidez, Temperatura, TDS (Sólidos Disueltos
Totales), ORP (Potencial de Oxidación-Reducción) y Oxígeno Disuelto.
- Predicciones con IA: Gráfica proyectada de calidad del agua para los próximos 3 días.
- Alertas Pop-up: Notificaciones inmediatas ante detecciones de anomalías químicas,
biológicas o de hardware.
️## Tecnologías Utilizadas
- HTML5/JavaScript (ES6+): Estructura y lógica de procesamiento de datos.
- Tailwind CSS: Diseño de interfaz moderno, minimalista y responsivo.
- Fetch API: Para la lectura dinámica del dataset local.

### Desarrollado por: Nicole Michelle Leyva Munguía
Doctorado en Tecnologías de Información - Interfaces Gráficas de Usuario
