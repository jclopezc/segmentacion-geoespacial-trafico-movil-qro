# Segmentación Geoespacial de la Calidad de Tráfico Móvil de la Red en el Estado de Querétaro
## Resumen del proyecto
Este proyecto desarrolla una metodología para evaluar la calidad del tráfico en redes móviles mediante técnicas de aprendizaje automático no supervisado como una alternativa eficaz a los métodos tradicionales internacionales. Esta solución facilita tanto a las autoridades reguladoras como a las empresas operadores de red, la planificación estratégica y la optimización de infraestructura crítica de las telecomunicaciones.
## Problema empresarial
El mercado actual de las telecomunicaciones es muy competitivo, lo que obliga a las empresas operadoras de red a garantizar un servicio sobresaliente para atraer y retener usuarios. Sin embargo, las redes móviles son sistemas complejos que cambian constantemente dependiendo de muchos factores y esto dificulta una evaluación precisa a través de los métodos de muestreo tradicionales, los cuales son demasiado estrictos y en la gran mayoría de los casos imposbiles de cumplir en escenarios reales. 
Esta gran limitación genera puntos ciegos en la medición de la cobertura de la red, inversiones ineficientes en infraestructura crítica y una lentitud operativa que impacta directamente en la experiencia del usuario y en la toma de decisiones estratégicas de las compañías.
## Stack tecnológico y Herramientas
* **Lenguajes:** Python
* **Librerías de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Modelado Geoespacial:** H3 (Uber Hexagonal Hierarchical Spatial Index)
*  **Herramientas de visualización de datos geoespaciales:** GeoDa, QGIS
## Metodología
**Fase 1: Preprocesamiento de datos espaciales**
Esta fase inicial se centra en la preparación y homogenización de las fuentes de datos heterogéneos para su posterior análisis.
**Fase 2: Procesamiento e integración espacial**
Esta fase integra los datos georreferenciados con la malla hexagonal, creando el conjunto de datos analítico principal.
<img width="837" height="689" alt="Captura de pantalla 2025-03-04 210828" src="https://github.com/user-attachments/assets/3ccab3de-23e6-4e14-a428-6925a7ea529d" />
**Fase 3: Modelado de datos mediante técnicas de clustering**
Esta fase constituye el enfoque analítico del estudio, aplicando múltiples algoritmos de agrupamiento para identificar patrones espaciales naturales en los datos de tráfico móvil.
<img width="1279" height="729" alt="Captura de pantalla 2025-06-15 194635" src="https://github.com/user-attachments/assets/8575aadb-8f47-444e-8e52-43869fdee000" />
<img width="1279" height="709" alt="Captura de pantalla 2025-06-15 194437" src="https://github.com/user-attachments/assets/6b71aee4-c73e-486c-a690-9ff5c11fe48b" />
## Resultados y trabajo futuro
La metodología desarrollada facilita la identificación de zonas críticas por sobrecarga o baja calidad del tráfico, proporcionando a los operadores una herramienta para priorizar inversiones en infraestructura y optimizar la asignación de recursos técnicos y humanos.
Se proporciona a las autoridades regulatorias una herramienta complementaria para evaluar la calidad del servicio que no depende únicamente de los métodos tradicionales, permitiendo análisis más flexibles y adaptativos a las condiciones reales de los datos de telecomunicaciones.
El siguiente paso es ampliar el análisis a períodos más extensos para capturar variaciones estacionales y tendencias a largo plazo. Un estudio que abarque todo un año permitiría identificar patrones temporales como aumentos de tráfico durante vacaciones, eventos especiales o cambios estacionales que le ayuden a las empresas a entender mejor a su base de usuarios. 
