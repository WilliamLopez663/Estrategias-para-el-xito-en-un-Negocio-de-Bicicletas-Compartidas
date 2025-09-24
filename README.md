# Estrategias para el éxito en un Negocio de Bicicletas Compartidas :bike:
Este proyecto fue realizado como trabajo final del programa Google Data Analytics, en el cual busco aplicar las habilidades adquiridas en análisis de datos, limpieza, visualización y toma de decisiones basadas en datos para evaluar el éxito potencial de un negocio de bicicletas compartidas.


## Acerca de la empresa
En 2016, Cyclistic lanzó una exitosa oferta de bicicletas compartidas. Desde entonces, el programa creció hasta alcanzar una flota de 5,824 bicicletas georreferenciadas y bloqueadas en una red de 692 estaciones en toda Chicago. Las bicicletas se pueden desbloquear desde una estación y devolverse en cualquier otra estación del sistema en cualquier momento.

Hasta ahora, la estrategia de marketing de Cyclistic se basaba en la construcción de un reconocimiento de marca general y en atraer a amplios segmentos de consumidores. Uno de los enfoques que ayudó a hacer esto posible fue la flexibilidad de sus planes de precios: pases de un solo viaje, pases de un día completo y membresías anuales. A los clientes que compran pases de un solo viaje o pases de un día completo se los llama ciclistas ocasionales. Los clientes que compran membresías anuales se llaman miembros de Cyclistic.

Los analistas financieros de Cyclistic llegaron a la conclusión de que los miembros anuales son mucho más rentables que los ciclistas ocasionales. Aunque la flexibilidad de precios ayuda a Cyclistic a atraer más clientes, Moreno cree que maximizar el número de miembros anuales será clave para el crecimiento futuro. En lugar de crear una campaña de marketing que apunte a todos los clientes nuevos, Moreno cree que hay muchas posibilidades de convertir a los ciclistas ocasionales en miembros. Ella señala que los ciclistas ocasionales ya conocen el programa de Cyclistic y han elegido a Cyclistic para sus necesidades de movilidad.

Moreno estableció una meta clara: Diseñar estrategias de marketing orientadas a convertir a los ciclistas ocasionales en miembros anuales. Sin embargo, para hacer eso, el equipo de analistas de marketing necesita entender mejor cómo difieren los miembros anuales y los ciclistas ocasionales, por qué los ciclistas ocasionales comprarían una membresía y cómo los medios digitales podrían afectar sus tácticas de marketing. Moreno y su equipo están interesados en analizar los datos históricos de viajes en bicicleta de Cyclistic para identificar tendencias.


## Planteamiento del problema
La directora de marketing de Cyclistic, una empresa bicicletas compartidas de Chicago cree que el éxito futuro de la empresa depende de maximizar la cantidad de membresías anuales. Por lo tanto, se quiere entender qué diferencias existen en el uso de las bicicletas Cyclistic entre los ciclistas ocasionales y los miembros anuales. A través de estos conocimientos,se busca diseñar una nueva estrategia de marketing para convertir a los ciclistas ocasionales en miembros anuales. Sin embargo, antes de eso, los ejecutivos de Cyclistic deben aprobar las recomendaciones; por eso, la respuesta debe estar respaldada con una visión convincente de los datos y visualizaciones profesionales de los mismos.

<br>

## Preguntar
Durante esta etapa en pro de guiar mi proyecto hacia la problematica principal me realicé las siguientes preguntas: 
- ¿En qué se diferencian los socios anuales y los ciclistas ocasionales con respecto al uso de las bicicletas de Cyclistic :question: 
- ¿Por qué los ciclistas ocasionales comprarían membresías anuales de Cyclistic :question:  
- ¿Cómo puede usar Cyclistic los medios digitales para influenciar a los ciclistas ocasionales a convertirse en miembros :question:  
- ¿Que estrategias de marketing estan teniendo mayor impacto convirtiendo los ciclistas ocasionales en miembros anuales :question:

Tras reflexionar acerca de las preguntas preguntas establezco la problematica principal:  
`La empresa Cyclistic busca aumentar su base de miembros anuales, ya que estos generan mayores ingresos a largo plazo comparado con los ciclistas ocasionales. El análisis de datos permitirá entender el comportamiento de ambos grupos y detectar patrones que faciliten la conversión de usuarios ocasionales a miembros.`

<br>

## Preparar
Durante esta etapa, me aseguré de contar con datos confiables, ya que la fuente fue directamente la empresa proveedora del servicio, lo cual garantiza su autenticidad y relevancia. Posteriormente, descargué y organicé los archivos mensuales correspondientes al año de análisis.

### 📄 Descripción de la fuente de datos utilizada
1. Nombre de la fuente  
Registros de viajes mensuales de Cyclistic – Ultimos 12 meses Septiembre de 2024 a Agosto de 2025

2. Origen o propietario  
Cyclistic, empresa proveedora del sistema de bicicletas compartidas. Es la responsable de recopilar y proporcionar los datos de uso del servicio.

3. Tipo de fuente  
Datos estructurados internos, generados automáticamente por el sistema de gestión de viajes de Cyclistic.

4. Formato de los datos  
12 archivos en formato CSV, uno por cada mes desde Septiembre de 2024 a Agosto de 2025.

5. Frecuencia de actualización  
Los archivos fueron generados de forma mensual, conteniendo los viajes realizados de los ultimos 12 meses.

6. Variables o campos relevantes  
Cada archivo contiene las siguientes columnas:  
<table align="center">
<tr>
<td>
	<div align="center">
	<h4 align="center">Campo</h4>
	</div>
</td> 
<td>
	<div align="center">
	<h4 align="center">Descripción</h4>
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	ride_id
	</div>
</td> 
<td>
	<div align="center">
	Identificador único del viaje
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	rideable_type
	</div>
</td> 
<td>
	<div align="center">
	Tipo de bicicleta utilizada (por ejemplo: eléctrica, clásica, etc.)
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	started_at
	</div>
</td> 
<td>
	<div align="center">
	Fecha y hora de inicio del viaje
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	ended_at
	</div>
</td> 
<td>
	<div align="center">
	Fecha y hora de finalización del viaje
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	start_station_name
	</div>
</td> 
<td>
	<div align="center">
	Nombre de la estación donde comenzó el viaje
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	start_station_id
	</div>
</td> 
<td>
	<div align="center">
	Identificador de la estación de inicio
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	end_station_name
	</div>
</td> 
<td>
	<div align="center">
	Nombre de la estación donde terminó el viaje
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	end_station_id
	</div>
</td> 
<td>
	<div align="center">
	Identificador de la estación de destino
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	start_lat
	</div>
</td> 
<td>
	<div align="center">
	Latitud del punto de inicio del viaje
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	start_lng
	</div>
</td> 
<td>
	<div align="center">
	Longitud del punto de inicio del viaje
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	end_lat
	</div>
</td> 
<td>
	<div align="center">
	Latitud del punto de destino
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	end_lng
	</div>
</td> 
<td>
	<div align="center">
	Longitud del punto de destino
	</div>
</td> 
</tr>
<tr>
<td>
	<div align="center">
	member_casual
	</div>
</td> 
<td>
	<div align="center">
	Tipo de usuario (member para usuarios suscritos o casual para usuarios ocasionales)  
	</div>
</td> 
</tr>
</table>  

7. Volumen de datos  
Cada archivo contiene decenas o cientos de miles de registros, dependiendo del mes. El volumen total anual supera el millón de registros (estimación general para este tipo de servicios).

8. Calidad de los datos  
Aunque los datos están bien estructurados, es posible encontrar:

	Registros con estaciones vacías o coordenadas faltantes  
	Inconsistencias en fechas (como viajes con duración negativa)  
	Posibles valores atípicos en duración o distancia  
	Estos aspectos se abordarán en la fase de limpieza y validación.

9. Restricciones o licencias  
Los datos han sido proporcionados internamente por Cyclistic para uso exclusivo en este proyecto de análisis.  
No deben compartirse ni divulgarse públicamente sin autorización expresa de la empresa.

10. Método de acceso  
Los archivos se encuentran alojados en la base da datos de la empresa Cyclistic entregados en formato digital, a través del cual me permitieron el acceso solo a los archivos correspondientes del año 2021.

Realicé una revisión detallada de las columnas presentes en cada archivo para verificar que tuvieran la misma estructura. Luego, utilicé Python junto con la librería pandas para unificar todos los archivos en un único dataset, facilitando así su análisis posterior. Finalmente, empleé Microsoft Excel para asignar los tipos de datos correctos a cada columna (como fechas, cadenas de texto y números), asegurando la coherencia y calidad de los datos.
