# **Analisis Acceso a Internet**

# Descripción del problema (Contexto y rol a desarrollar)

## **Contexto**
La industria de las telecomunicaciones ha jugado un papel vital en nuestra sociedad, facilitando la información a escala internacional y permitiendo la comunicación continua incluso en medio de una pandemia mundial. La transferencia de datos y comunicación se realiza en su mayoría a través de internet, líneas telefónicas fijas, telefonía móvil, casi en cualquier lugar del mundo. 

En comparación con la media mundial, Argentina está a la vanguardia del desarrollo de las telecomunicaciones, teniendo para el 2020 un total de [62,12 millones conexiones](https://www.datosmundial.com/america/argentina/telecomunicacion.php). 

## Rol a desarrollar

En este contexto, una empresa prestadora de servicios de telecomunicaciones le encarga a usted la realización de un **análisis** completo que permita reconocer el comportamiento de este sector a nivel nacional. Considere que la principal actividad de la empresa es brindar **acceso a internet**, pero también es importante considerar el resto de los servicios.

Con el fin de monitorear la eficacia de los objetivos de la empresa, se le pide **visualizar** en un dashboard el siguiente KPI y **establecer 3 KPIs adicionales** producto de su análisis:


# Analisis Exploratorio de los datos y transformaciones y analisis de objetivos

## Transformaciones y objetivos:

### Internet_Penetracion : 
**Datos :** Hogares con disponibilidad a internet cada 100 hogares, separado por provincia y año-trimestre, desde 2014 hasta 2020.

**Transformacion :** Cambiados a tipo numérico las columnas AÑO y TRIMESTRE

**Objetivo :** Realizar un KPI que indique la variacion trimestre a trimestre de hogares con acceso a internet

### Velocidad_por_provincia : 
**Datos :** Variación de velocidad de internet, separado por provincia y año-trimestre

**Transformacion :** Cambiados a tipo numérico las columnas AÑO y TRIMESTRE

**Objetivo :** Mostrar estadisticas que indiquen la velocidad de bajada mas común por provincia y tiempo

### Vel_media_por_provincia : 
**Datos :** Variación media de bajada, separado por provincia y año-trimestre

**Transformacion :** Cambiados a tipo numérico las columnas AÑO y TRIMESTRE

**Objetivo :** Realizar un KPI que indique la variacion del promedio de velocidad media trimestre a trimestre

### tecnologia_por_provincia : 
**Datos :** Usos de distintas tecnologias de internet separado por provincia y año-trimestre

**Transformacion :** Arreglados errores de tipeo de las columnas AÑO y TRIMESTRE, cambiados a tipo numérico las columnas AÑO Y TRIMESTRE, quitados errores.

**Objetivo :** Indicar el cambio de tecnologias por provincia a travez del tiempo

### Accesos_por_provincia : 
**Datos :** Banda ancha y Dial up consumido separado por provincia y año-trimestre

**Transformacion :** Cambiados a tipo numérico las columnas AÑO y TRIMESTRE,cambiado el valor "- 0" de las columnas (BANDA ANCHA,DIAL UP), cambiados los nuloes en la columna DIAL UP por el dato del trimestre anterior

**Objetivo :** Generar un KPI indicando la diferencia entre el crecimiento de BANDA ANCHA y DIAL UP 

### Ingresos_por_periodo : 
**Datos :** Ingresos trimestrales de los operadores por el servicio de Internet fijo

**Transformacion :** Cambiados a tipo numérico las columnas AÑO y TRIMESTRE

**Objetivo :** Realizar un KPI indicando el crecimiento de ingresos de los operadores de internet y mostrar el crecimiento de las ganancias en los ultimos años

### Localidades_con_internet : 
**Datos :** Listado de localidades con conectividad a internet, con detalle por tipo de conexión.

**Transformacion :** Arreglados los nombres de unas provincias que estaban mal, agregada una columna que indica si todas las columnas de tecnologias son "--" o si alguna es "SI" para identifica las localidades sin internet

**Objetivo :** Hacer una tabla demostrativa de las localidades que no tienen ningun tipo de conexion a internet

### Tablas adicionales:

-Se creo una tabla Calendario con las fechas desde el principio de 2014 hasta el final de 2020.
Adicionalmente se creo una columna "Fecha_Año_Trimestre" combinado AÑO y TRIMESTRE en todas las tablas excepto Localidades_con_internet para relacionar con fechas de calendario

-Se creo una tabla provincias con todas las provincias que aparecen en las tablas y se relaciono con las provincias de cada tabla



