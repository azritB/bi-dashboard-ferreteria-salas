# BI-dashboard-ferreteria-salas
Dashboard de BI con datos sintéticos y esquema de BD para el análisis del negocio de Ferretería Salas y la optimización de su proceso de ingreso de productos. El dashboard presenta 3 hojas; ventas y rotación de productos, inventario y productos, e ingresos de almacén; que permiten el análisis de negocio y, de esta manera, tener una vista general de su funcionamiento para un mejor diagnóstico y solución basados en datos. 

El repositorio cuenta con los siguientes documentos:
- Dashboard en archivo pbix.
- Excel de datos.
- Imagen de estructura de datos (estructura relacional).
- Archivo README.

Para realizar el dashboard:
- Se diseñó el esquema de la base de datos.
- Se generó datos sintéticos coherentes con el esquema.
- Se definieron los objetivos y KPIs del proyecto.
- Se limpiaron los datos.
- Finalmente se construyó el dashboard para obtener insights relevantes.

Para ello, se utilizaron las herramientas de Excel, Google Docs, Power BI, y SQL server. 

El esquema de la base de datos contiene 8 tablas, donde la tabla principal es "Productos".
<img width="1176" height="685" alt="imagen" src="https://github.com/user-attachments/assets/df81274d-67aa-44c5-8d36-ba189b08070e" />

KPIs:
- Porcentaje de productos vendidos respecto al stock disponible (%).
- Número de productos ingresados al almacén por mes.
- Número de rotación mensual de producto. Mide las unidades de un producto que se venden en promedio por mes
- Porcentaje de productos de baja rotación (%).

Los datos permitieron hacer los siguientes hallazgos:
- El 65% de las ventas anuales se concentran en el primer trimestre (enero-abril).
- Para los meses de julio-setiembre se presenta una caída de ventas.
- Para los meses de julio-setiembre se encuentra exceso de stock.
- Las categorías Herramientas, Materiales de Construcción, Jardinería y Pinturas
destacan como las más rentables ya que representan el 45% de ingresos.
- Las categorías Tuberías y Seguridad representan solo el 9% de ingresos, evidenciando una mala asignación de recursos.
- Productos como la Abrazadera metálica tienen alta rotación.
- El Foco LED y Ladrillo KING Kong acumulan stock innecesario.
- Los proveedores "Fijaciones SRL", "Tuberías del Centro", y "Tubos Perú" dominan el volumen de ingresos a almacén.

En base a estos hallazgos se hacen las siguientes recomendaciones:
- Ajustar el plan de abastecimiento al calendario de demanda.
- Reducir el volumen de ingreso de productos con baja rotación (como foco LED, ladrillos, y codos PVC).
- Aumentar volumen de adquisición de productos en categorías como herramientas, materiales de construcción y jardinería, puesto que demuestran presencia en ventas.
- Mantener catálogo actual de productos pero ajustar cantidades de ingresos por producto.
- Establecer negociaciones estratégicas con proveedores clave como Fijaciones SRL y Tubos Perú para asegurar condiciones más favorables, re abastecimiento oportuno y productos de calidad. 



