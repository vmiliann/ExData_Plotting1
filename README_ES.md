## Introducción

Esta asignación utiliza datos del 
<a href="http://archive.ics.uci.edu/ml/">UC Irvine Machine
Learning Repository</a>, un popular repositorio de Data Sets 
para aprendizaje automático. En particular, utilizaremos el Data Set
"Consumo de energía eléctrica de los hogares" que he puesto a disposición en el sitio web del curso:

* <b>Dataset</b>: <a href="https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip">Electric power consumption</a> [20Mb]

* <b>Descripción</b>: Mediciones del consumo de energía eléctrica en un hogar con una tasa 
de muestreo de un minuto durante un período de casi 4 años. 

Las siguientes descripciones de las 9 variables en el conjunto de datos se tomaron 
del <a href="https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption">sitio web de UCI</a>:

<ol>
<li><b>Date</b>: Fecha en el formato dd/mm/yyyy </li>
<li><b>Time</b>: Tiempo en el formato hh:mm:ss </li>
<li><b>Global_active_power</b>: Potencia activa global promediada en minutos (kilowatt) </li>
<li><b>Global_reactive_power</b>: Potencia reactiva global promediada en minutos (kilowatt) </li>
<li><b>Voltage</b>: Voltage promedio por minutos (volt) </li>
<li><b>Global_intensity</b>: Intensidad global de corriente del hogar promediada por minuto (ampere) </li>
<li><b>Sub_metering_1</b>: sub-medición de energía No. 1 (en vatios-hora de energía activa). Corresponde a la cocina, que contiene principalmente un lavaplatos, un horno y un microondas (funcionan con gas). </li>
<li><b>Sub_metering_2</b>: sub-medición de energía No. 2 (watt-hora de energía activa). Corresponde a la lavandería, que contiene una lavadora, una secadora, una nevera e iluminación. </li>
<li><b>Sub_metering_3</b>: sub-medición de energía No. 3 (watt-hora de energía activa). Corresponde a un calentador de agua eléctrico y un acondicionador de aire.</li>
</ol>

## Cargando los datos


Cuando cargue el dataset en R, por favor considere lo siguiente:

* El dataset tiene 2.075.259 filas y 9 columnas. Primero, 
calcule una estimación aproximada de la cantidad de memoria que requerirá 
el dataset en memoria antes de leerlo en R. Asegúrese de 
que su computadora tenga suficiente memoria (la mayoría de las computadoras modernas deberían estar bien).

* Solo usaremos datos de las fechas 2007-02-01 y 2007-02-02. 
Una alternativa es leer solo los datos de esas fechas en lugar de leer todo el dataset y extraer esas fechas.

* Puede resultarle útil convertir las variables Fecha y Hora en
las clases Date/Time de R usando las funciones `strptime()` y `as.Date()`.

* Tenga en cuenta que en este dataset los valores faltantes se codifican como `?`.


## Creando los gráficos

Nuestro objetivo general aquí es simplemente examinar cómo varía el 
uso de energía en el hogar durante un período de 2 días en febrero de 2007. 
Su tarea es reconstruir los siguientes grágicos, los cuales se construyeron 
utilizando el sistema de gráficas base de R.

Primero deberá bifurcar y clonar el siguiente repositorio de GitHub:
[https://github.com/rdpeng/ExData_Plotting1](https://github.com/rdpeng/ExData_Plotting1)


Para cada gráfico debe:

* Construye el gráfico y guárdalo en un archivo PNG con un ancho de 480
Píxeles y una altura de 480 píxeles.

* Nombre cada uno de los gráficos como `plot1.png`, `plot2.png`, etc.

* Cree un archivo de código R separado (`plot1.R`, `plot2.R`, etc.) que 
construya el gráfico correspondiente, es decir, el código de `plot1.R` 
construye el gráfico `plot1.png`. Su archivo de código **debe incluir código 
para leer los datos** para que la trama se pueda reproducir completamente. 
También debe incluir el código que crea el archivo PNG.

* Agregue el archivo PNG y el archivo de código R a su repositorio git

Cuando haya culminado, empuje su repositorio git a 
GitHub para actualizar su versión de GitHub. En el repositorio debe
haber cuatro archivos PNG y cuatro archivos de código R.


Las cuatro gráficas que necesitarás construir se muestran a continuación.

### Figura 1


![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 


### Figura 2

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3.png) 


### Figura 3

![plot of chunk unnamed-chunk-4](figure/unnamed-chunk-4.png) 


### Figura 4

![plot of chunk unnamed-chunk-5](figure/unnamed-chunk-5.png) 

