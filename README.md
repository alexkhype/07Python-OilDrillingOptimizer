# Análisis de Ventas Históricas de Videojuegos

## Tabla de Contenidos
- [Descripción](#Descripción)
- [Datos](#Datos)
- [Análisis](#Análisis)
- [Tecnologías y herramientas](#Tecnologías-y-herramientas)
- [Resultados](#Resultados)
- [Contribuciones](#Contribuciones)
- [Licencia](#Licencia)
- [Contacto](#Contacto)

## Descripción
La compañía minera OilyGiant busca determinar la región más rentable para un nuevo pozo petrolero a partir de datos de crudo y parámetros de pozos en tres zonas. Se desarrolló un modelo de machine learning para evaluar riesgos y beneficios potenciales, ayudando a seleccionar la región con mayor margen de beneficio para optimizar la inversión.

## Datos
Se utilizaron 3 conjuntos de datos principales:  
- **geo_data_0.csv.csv**: Tabla con 100,000 registros de pozos petroleros, con ID único, tres características y volumen de reservas en miles de barriles.
- **geo_data_1.csv.csv**: Tabla con 100,000 registros de pozos petroleros, con ID único, tres características y volumen de reservas en miles de barriles.
- **geo_data_2.csv.csv**: Tabla con 100,000 registros de pozos petroleros, con ID único, tres características y volumen de reservas en miles de barriles.

## Análisis
- Se recolectaron parámetros relevantes como calidad del petróleo y volumen de reservas en tres regiones.
- Se entrenaron modelos de regresión independientes para cada región con datos limpios y sin valores faltantes (100,000 observaciones por zona).
- Validación del modelo mostró buena precisión en la zona B (RECM 0.89), mientras que las zonas A y C presentan margen de mejora (RECM ~40).
- Evaluación estadística avanzada con cálculo de medias, medianas y puntos de equilibrio para identificar zonas prometedoras.
- Análisis de intervalos de confianza y evaluación de riesgos para la selección definitiva de pozos con mayor producción proyectada.

## Tecnologías y herramientas
- Python 3.9
- Pandas y NumPy para manipulación y análisis de datos
- SciPy para funciones estadísticas avanzadas
- Scikit-learn para modelado predictivo y evaluación
- Jupyter Notebook para desarrollo interactivo

## Resultados
- La zona A mostró la mayor rentabilidad promedio con 163.22 unidades producidas por pozo y un beneficio bruto aproximado de $46.9 millones USD (margen 31.93%).
- La zona B destacó en la evaluación de riesgos, con un intervalo de confianza del 95% entre $395,594 y $8.27 millones USD y un riesgo bajo del 1.4%.
- Se identificaron más de 36,000 puntos en zonas A y C con potencial para alcanzar el punto de equilibrio.
- Selección final basada en las 200 mejores predicciones por región para maximizar beneficios y minimizar riesgos.
 
## Contribuciones
Bienvenidas sugerencias, correcciones y nuevas visualizaciones. Por favor, abre un issue o pull request para colaborar.

## Licencia
Este proyecto está bajo la licencia MIT.

## Contacto
Nombre: Alejandro M. García  
Email: [alexkhype@gmail.com](mailto:alexkhype@gmail.com)  
LinkedIn: [linkedin.com/in/amggl](https://linkedin.com/in/amggl)
