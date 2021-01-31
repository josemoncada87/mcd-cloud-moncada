<html>
<head><meta http-equiv=Content-Type content="text/html; charset=UTF-8">
<style type="text/css">
<!--
span.cls_002{font-family:"Calibri Bold",serif;font-size:16.1px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
div.cls_002{font-family:"Calibri Bold",serif;font-size:16.1px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
span.cls_004{font-family:"Calibri",serif;font-size:12.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_004{font-family:"Calibri",serif;font-size:12.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_005{font-family:"Calibri",serif;font-size:11.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_005{font-family:"Calibri",serif;font-size:11.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_007{font-family:Arial,serif;font-size:12.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_007{font-family:Arial,serif;font-size:12.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_008{font-family:"Calibri",serif;font-size:14.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_008{font-family:"Calibri",serif;font-size:14.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_010{font-family:"Calibri",serif;font-size:12.1px;color:rgb(4,98,193);font-weight:normal;font-style:normal;text-decoration: underline}
div.cls_010{font-family:"Calibri",serif;font-size:12.1px;color:rgb(4,98,193);font-weight:normal;font-style:normal;text-decoration: none}
-->
</style>
<script type="text/javascript" src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/wz_jsgraphics.js"></script>
</head>
<body>
<div style="position:absolute;left:50%;margin-left:-306px;top:0px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background01.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:70.03px" class="cls_002"><span class="cls_002">Manual de conexión entre BigQuery (Google Cloud) y PowerBi</span></div>
<div style="position:absolute;left:85.03px;top:91.22px" class="cls_002"><span class="cls_002">(Azure Cloud) pasando por DataBricks.</span></div>
<div style="position:absolute;left:85.03px;top:144.05px" class="cls_002"><span class="cls_002">Descripción del objetivo del manual</span></div>
<div style="position:absolute;left:85.03px;top:173.25px" class="cls_004"><span class="cls_004">Visualizar en PowerBI los datos abiertos relacionados con el COVID-19 almacenados en</span></div>
<div style="position:absolute;left:85.03px;top:189.05px" class="cls_004"><span class="cls_004">Google Cloud (GCP)</span></div>
<div style="position:absolute;left:85.03px;top:212.85px" class="cls_002"><span class="cls_002">Descripción general del proceso</span></div>
<div style="position:absolute;left:85.03px;top:242.05px" class="cls_004"><span class="cls_004">El proceso a que será descrito de manera detallada a continuación, genera un flujo de</span></div>
<div style="position:absolute;left:85.03px;top:257.87px" class="cls_004"><span class="cls_004">datos que tiene origen en un conjunto de datos abiertos de google</span></div>
<div style="position:absolute;left:85.03px;top:273.67px" class="cls_004"><span class="cls_004">(</span><span class="cls_005">https://console.cloud.google.com/marketplace/product/bigquery-public-datasets/covid19-</span></div>
<div style="position:absolute;left:85.03px;top:289.48px" class="cls_005"><span class="cls_005">public-data-program</span><span class="cls_004">), el cuál es capturado en un proyecto de BigQuery herramienta de</span></div>
<div style="position:absolute;left:85.03px;top:305.27px" class="cls_004"><span class="cls_004">Google Cloud, desde dónde es extraído a través de la herramienta Azure Dataflow bajo</span></div>
<div style="position:absolute;left:85.03px;top:321.08px" class="cls_004"><span class="cls_004">autenticación OAuth 2.0 (Claves generadas desde la consola de desarrolladores), estos</span></div>
<div style="position:absolute;left:85.03px;top:336.87px" class="cls_004"><span class="cls_004">datos terminan almacenados en una Blob Storage de Azure (dentro de su respectivo</span></div>
<div style="position:absolute;left:85.03px;top:352.70px" class="cls_004"><span class="cls_004">contenedor). Desde esa ubicación son cargados a un cluster de Azure Databricks usando</span></div>
<div style="position:absolute;left:85.03px;top:368.50px" class="cls_004"><span class="cls_004">una conexión JDBC, posteriormente se les realizan algunos procesamientos y consultas</span></div>
<div style="position:absolute;left:85.03px;top:378.30px" class="cls_004"><span class="cls_004">para finalmente a través de un conector de PowerBI visualizar la información resultante.</span></div>
<div style="position:absolute;left:85.03px;top:407.90px" class="cls_002"><span class="cls_002">¿Qué vamos a necesitar?</span></div>
<div style="position:absolute;left:103.02px;top:437.30px" class="cls_004"><span class="cls_004">1.</span><span class="cls_007"> </span><span class="cls_004"> Cuenta de Google Cloud, se puede crear en: <A HREF="https://cloud.google.com/free/">https://cloud.google.com/free</A> </span></div>
<div style="position:absolute;left:103.02px;top:453.10px" class="cls_004"><span class="cls_004">2.</span><span class="cls_007"> </span><span class="cls_004"> Cuenta de Microsoft Azure, se puede crear en: <A HREF="https://my.visualstudio.com/">https://my.visualstudio.com</A> </span></div>
<div style="position:absolute;left:103.02px;top:468.92px" class="cls_004"><span class="cls_004">3.</span><span class="cls_007"> </span><span class="cls_004"> Cuenta de Postman, se puede crear en: <A HREF="https://www.postman.com/">https://www.postman.com/</A> </span></div>
<div style="position:absolute;left:103.02px;top:484.72px" class="cls_004"><span class="cls_004">4.</span><span class="cls_007"> </span><span class="cls_004"> Power Bi Desktop, se puede descargar de: <A HREF="https://powerbi.microsoft.com/es-es/downloads/">https://powerbi.microsoft.com/es-</A> </span></div>
<div style="position:absolute;left:121.05px;top:500.53px" class="cls_004"><span class="cls_004"> </span><A HREF="https://powerbi.microsoft.com/es-es/downloads/">es/downloads/</A> </div>
<div style="position:absolute;left:103.02px;top:524.33px" class="cls_004"><span class="cls_004">Si es la primera vez que se crean las cuentas relacionadas con las nubes (Azure y</span></div>
<div style="position:absolute;left:103.02px;top:540.12px" class="cls_004"><span class="cls_004">Google Cloud) se reciben créditos gratuitos para usar en los servicios.</span></div>
<div style="position:absolute;left:85.03px;top:563.75px" class="cls_002"><span class="cls_002">Instrucciones</span></div>
<div style="position:absolute;left:85.03px;top:592.95px" class="cls_004"><span class="cls_004">Estas instrucciones, asumen que las cuentas han sido creadas antes de iniciar el proceso.</span></div>
<div style="position:absolute;left:85.03px;top:608.55px" class="cls_004"><span class="cls_004">Las herramientas están configuradas en español </span><span class="cls_008">por </span><span class="cls_004">lo que si su versión está en inglés</span></div>
<div style="position:absolute;left:85.03px;top:627.35px" class="cls_004"><span class="cls_004">podrían diferir los nombres.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:802px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background02.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:70.03px" class="cls_002"><span class="cls_002">Parte 1 (Preparación de los datos en BigQuery)</span></div>
<div style="position:absolute;left:85.03px;top:99.42px" class="cls_004"><span class="cls_004">a.</span><span class="cls_007"> </span><span class="cls_004"> Estando ubicado en la consola de google cloud <A HREF="https://console.cloud.google.com/">(https://console.cloud.google.com/)</A>,</span></div>
<div style="position:absolute;left:103.02px;top:115.22px" class="cls_004"><span class="cls_004">procesa a realizar el acceso a la herramienta BigQuery, la imagen a continuación</span></div>
<div style="position:absolute;left:103.02px;top:131.03px" class="cls_004"><span class="cls_004">describe el ingreso (las zonas marcadas en amarillo, muestran los puntos de contacto).</span></div>
<div style="position:absolute;left:85.03px;top:511.92px" class="cls_004"><span class="cls_004">b.  Una vez adentro de BigQuery, seleccione en el menú izquierdo la opción marcado</span></div>
<div style="position:absolute;left:103.02px;top:527.72px" class="cls_004"><span class="cls_004">como espacio de trabajo de SQL, una vez presionado se despliega un espacio marcado</span></div>
<div style="position:absolute;left:103.02px;top:543.52px" class="cls_004"><span class="cls_004">como Explorador, en los tres puntos verticales ubicados en el lado superior izquierdo</span></div>
<div style="position:absolute;left:103.02px;top:559.33px" class="cls_004"><span class="cls_004">del Explorador presione (+AGREGAR DATOS) y de ahí en la opción (Explorar conjuntos</span></div>
<div style="position:absolute;left:103.02px;top:575.15px" class="cls_004"><span class="cls_004">de datos ppúblicos).</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:1604px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background03.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:269.08px" class="cls_004"><span class="cls_004">c.  La acción del paso (b) genera el despliegue de una nueva ventana, una vez ahí</span></div>
<div style="position:absolute;left:103.02px;top:284.87px" class="cls_004"><span class="cls_004">introduzca el texto: “covid-19 open data” en la barra de búsqueda y seleccione el</span></div>
<div style="position:absolute;left:103.02px;top:300.67px" class="cls_004"><span class="cls_004">resultado etiquetado como: “COVID-19 Open Data”, la imagen a continuación muestra</span></div>
<div style="position:absolute;left:103.02px;top:316.48px" class="cls_004"><span class="cls_004">el proceso:</span></div>
<div style="position:absolute;left:85.03px;top:479.33px" class="cls_004"><span class="cls_004">d.  En la ventana desplegada tras la selección del paso (c), presione en el botón “Ver</span></div>
<div style="position:absolute;left:103.02px;top:495.12px" class="cls_004"><span class="cls_004">Conjunto de Datos”͘ Esto generará que regrese a la ventana anterior, pero en su</span></div>
<div style="position:absolute;left:103.02px;top:510.92px" class="cls_004"><span class="cls_004">explorador se habrá fijado un nuevo proyecto (ver paso e).</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:2406px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background04.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:366.90px" class="cls_004"><span class="cls_004">e.  Ahora vamos a crear un conjunto de datos en nuestro proyecto, sobre el cuál</span></div>
<div style="position:absolute;left:103.02px;top:382.70px" class="cls_004"><span class="cls_004">copiaremos los datos del proyecto de datos abiertos</span></div>
<div style="position:absolute;left:85.03px;top:398.50px" class="cls_004"><span class="cls_004">f.   Seleccione su proyecto y posteriormente en el área de trabajo (a la derecha del</span></div>
<div style="position:absolute;left:103.02px;top:414.30px" class="cls_004"><span class="cls_004">explorador) presione el botón “Crear Conjunto de Datos”</span></div>
<div style="position:absolute;left:85.03px;top:519.53px" class="cls_004"><span class="cls_004">g.  En la ventana lateral que despliega el botón, indique el nombre del conjunto de datos,</span></div>
<div style="position:absolute;left:103.02px;top:535.33px" class="cls_004"><span class="cls_004">marque predeterminada, sin vencimiento y clave administrada por google. Finalmente</span></div>
<div style="position:absolute;left:103.02px;top:551.12px" class="cls_004"><span class="cls_004">presione “Crear conjunto de datos” en la parte inferior.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:3208px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background05.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:374.50px" class="cls_004"><span class="cls_004">h.  La acción previa generó un conjunto de datos asociados a su proyecto (1 en la</span></div>
<div style="position:absolute;left:103.02px;top:390.30px" class="cls_004"><span class="cls_004">siguiente imagen), pero por ahora no tiene ninguna tabla, vamos ahora a traer los</span></div>
<div style="position:absolute;left:103.02px;top:406.10px" class="cls_004"><span class="cls_004">datos del proyecto de datos abiertos (2 en la siguiente imagen).</span></div>
<div style="position:absolute;left:85.03px;top:659.35px" class="cls_004"><span class="cls_004">i.</span></div>
<div style="position:absolute;left:103.02px;top:659.35px" class="cls_004"><span class="cls_004">En la ventana del explorador ahora usted tiene además de su proyecto un proyecto</span></div>
<div style="position:absolute;left:103.02px;top:675.17px" class="cls_004"><span class="cls_004">llamado: “bigquery-public-data” (agregado en el paso (d)). Al desplegar este usted</span></div>
<div style="position:absolute;left:103.02px;top:690.97px" class="cls_004"><span class="cls_004">verá los conjuntos de datos disponibles:</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:4010px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background06.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:349.08px" class="cls_004"><span class="cls_004">j.</span></div>
<div style="position:absolute;left:103.02px;top:349.08px" class="cls_004"><span class="cls_004">Dentro de los datos desplegados en el paso (i), busque uno llamado:</span></div>
<div style="position:absolute;left:103.02px;top:364.90px" class="cls_004"><span class="cls_004">“covid_19_open_data”, si lo prefiere use este texto en el buscador para acelerar el</span></div>
<div style="position:absolute;left:103.02px;top:380.70px" class="cls_004"><span class="cls_004">proceso.</span></div>
<div style="position:absolute;left:85.03px;top:604.55px" class="cls_004"><span class="cls_004">k.  Ahora necesitamos transferir estos datos del proyecto de datos abiertos al proyecto</span></div>
<div style="position:absolute;left:103.02px;top:620.55px" class="cls_004"><span class="cls_004">personal, para esto seleccione el conjunto de datos con el nombre indicado en el paso</span></div>
<div style="position:absolute;left:103.02px;top:636.35px" class="cls_004"><span class="cls_004">(j) y en la información desplegada en el área de trabajo (a la derecha del explorador),</span></div>
<div style="position:absolute;left:103.02px;top:652.15px" class="cls_004"><span class="cls_004">identifique y presione el botón con nombre “Copiar conjunto de datos” (2 en la</span></div>
<div style="position:absolute;left:103.02px;top:667.98px" class="cls_004"><span class="cls_004">imagen siguiente).</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:4812px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background07.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:201.05px" class="cls_004"><span class="cls_004">l.</span></div>
<div style="position:absolute;left:103.02px;top:201.05px" class="cls_004"><span class="cls_004">El paso (k) ha desplegado una ventana emergente, seleccione en esta el nombre del</span></div>
<div style="position:absolute;left:103.02px;top:216.85px" class="cls_004"><span class="cls_004">proyecto(1) y el conjunto de datos en el cuál desea copiar(2), marque la opción de</span></div>
<div style="position:absolute;left:103.02px;top:232.65px" class="cls_004"><span class="cls_004">reemplazo de tablas y presione el botón “copiar”(4).</span></div>
<div style="position:absolute;left:85.03px;top:559.92px" class="cls_004"><span class="cls_004">m. Hecho el paso previo vamos a copiar la tabla de datos, pero ahora debemos activar las</span></div>
<div style="position:absolute;left:103.02px;top:575.95px" class="cls_004"><span class="cls_004">transferencias de datos, esto se hace presionando en la opción “Transferencia de</span></div>
<div style="position:absolute;left:103.02px;top:591.75px" class="cls_004"><span class="cls_004">datos” ubicada en el lado izquierdo debajo de la opción “Espacio de trabajo de SQL”</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:5614px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background08.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:225.25px" class="cls_004"><span class="cls_004">n.  Con esta opción de transferencia seleccionada, presione activar en el API de</span></div>
<div style="position:absolute;left:103.02px;top:241.05px" class="cls_004"><span class="cls_004">transferencias y una vez completado el proceso proceda de regreso a la opción</span></div>
<div style="position:absolute;left:103.02px;top:256.87px" class="cls_004"><span class="cls_004">“Espacio de trabajo SQL” para realizar la copia de la tabla͘ (no funciona el paso</span></div>
<div style="position:absolute;left:103.02px;top:272.68px" class="cls_004"><span class="cls_004">siguiente si no se activa la API)</span></div>
<div style="position:absolute;left:85.03px;top:288.48px" class="cls_004"><span class="cls_004">o.  Estando ubicado en el “Espacio de trabajo SQL” (1), seleccione en el “Explorador” (2) el</span></div>
<div style="position:absolute;left:103.02px;top:304.27px" class="cls_004"><span class="cls_004">proyecto de datos abiertos, y busque nuevamente el conjunto de datos</span></div>
<div style="position:absolute;left:103.02px;top:320.07px" class="cls_004"><span class="cls_004">“covid19_open_data” (3), seleccione la tabla “covid19_open_data” (4)͘ La imagen a</span></div>
<div style="position:absolute;left:103.02px;top:335.87px" class="cls_004"><span class="cls_004">continuación muestra los números.</span></div>
<div style="position:absolute;left:85.03px;top:625.75px" class="cls_004"><span class="cls_004">p.  Con la tabla seleccionada, presione el botón “copiar tabla” disponible en el lado</span></div>
<div style="position:absolute;left:103.02px;top:641.55px" class="cls_004"><span class="cls_004">derecho del área de trabajo en la parte superior.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:6416px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background09.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:148.45px" class="cls_004"><span class="cls_004">q.  En la ventana emergente lanzada por el botón seleccione la opción “buscar un</span></div>
<div style="position:absolute;left:103.02px;top:164.25px" class="cls_004"><span class="cls_004">proyecto” (1), después seleccione su proyecto personal (2) y el conjunto de datos que</span></div>
<div style="position:absolute;left:103.02px;top:180.05px" class="cls_004"><span class="cls_004">creamos antes en su proyecto (3), finalmente introduzca el nombre de la tabla que se</span></div>
<div style="position:absolute;left:103.02px;top:195.85px" class="cls_004"><span class="cls_004">creará en su proyecto personal (4) y para terminar presione el botón copiar (5).</span></div>
<div style="position:absolute;left:85.03px;top:615.75px" class="cls_004"><span class="cls_004">r.   La última acción debe dejar disponibles los datos dentro del proyecto personal (1),</span></div>
<div style="position:absolute;left:103.02px;top:631.55px" class="cls_004"><span class="cls_004">dentro de un conjunto de datos (2) y en la tabla con el nombre que le haya asignado</span></div>
<div style="position:absolute;left:103.02px;top:647.35px" class="cls_004"><span class="cls_004">(3).</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:7218px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background10.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:278.67px" class="cls_002"><span class="cls_002">Parte 2 (Preparación de las credenciales de conexión entre GCP y</span></div>
<div style="position:absolute;left:85.03px;top:299.68px" class="cls_002"><span class="cls_002">Azure)</span></div>
<div style="position:absolute;left:85.03px;top:329.07px" class="cls_004"><span class="cls_004">Durante esta parte vamos a usar la consola de desarrolladores de google</span></div>
<div style="position:absolute;left:85.03px;top:344.87px" class="cls_004"><span class="cls_004">(</span><A HREF="https://console.developers.google.com/">https://console.developers.google.com/</A>) y una cuenta de Postman</div>
<div style="position:absolute;left:85.03px;top:360.70px" class="cls_004"><span class="cls_004">(</span><A HREF="https://www.postman.com/">https://www.postman.com/</A>), el tutorial asume que ya han sido creadas las cuentas.</div>
<div style="position:absolute;left:103.02px;top:408.30px" class="cls_004"><span class="cls_004">a.  Estando en la consola de google, en el menú lateral izquierdo seleccione la opción</span></div>
<div style="position:absolute;left:121.05px;top:424.10px" class="cls_004"><span class="cls_004">“Credenciales” (1), vamos a crear una credencial de tipo O  uth 2͘0 (2) y para ellos</span></div>
<div style="position:absolute;left:121.05px;top:439.90px" class="cls_004"><span class="cls_004">debemos presionar en “+Crear Credenciales”͘ (Asegurarse de tener seleccionado el</span></div>
<div style="position:absolute;left:121.05px;top:455.70px" class="cls_004"><span class="cls_004">proyecto correcto en la parte superior)</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:8020px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background11.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:86.03px" class="cls_004"><span class="cls_004">b.  En el desplegable seleccione: “ID de cliente de O  uth”</span></div>
<div style="position:absolute;left:85.03px;top:247.87px" class="cls_004"><span class="cls_004">c.  En la ventana seleccione como tipo de aplicación “  pp de escritorio” (1), después</span></div>
<div style="position:absolute;left:103.02px;top:263.68px" class="cls_004"><span class="cls_004">inserte el nombre que desee para la aplicación (2) y finalmente presione “crear” (3)</span></div>
<div style="position:absolute;left:85.03px;top:591.15px" class="cls_004"><span class="cls_004">d.  En la ventana siguiente, debes copiar los datos de ID de cliente y secreto de cliente</span></div>
<div style="position:absolute;left:103.02px;top:606.95px" class="cls_004"><span class="cls_004">(déjalos en un bloc de notas), los vamos a necesitar más adelante. Si lo cerraste y no lo</span></div>
<div style="position:absolute;left:103.02px;top:622.75px" class="cls_004"><span class="cls_004">copiaste, puedes ver estos datos al presionar sobre el ID de cliente en la sección de</span></div>
<div style="position:absolute;left:103.02px;top:638.55px" class="cls_004"><span class="cls_004">credenciales.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:8822px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background12.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:457.72px" class="cls_004"><span class="cls_004">e.  Con los códigos generados vamos a crear un token de autenticación, para ellos vamos</span></div>
<div style="position:absolute;left:103.02px;top:473.53px" class="cls_004"><span class="cls_004">a usar la siguiente dirección web, Ojo: Debes reemplazar: =&lt;Your-client-Id> por el ID</span></div>
<div style="position:absolute;left:103.02px;top:489.33px" class="cls_004"><span class="cls_004">de cliente que acabas de copiar.</span></div>
<div style="position:absolute;left:103.02px;top:520.92px" class="cls_004"><span class="cls_004"> </span><A HREF="https://accounts.google.com/o/oauth2/v2/auth?client_id=&lt;your-client-/">https://accounts.google.com/o/oauth2/v2/auth?client_id=&lt;Your-client-</A> </div>
<div style="position:absolute;left:103.02px;top:536.72px" class="cls_004"><span class="cls_004">Id>&redirect_uri=urn:ietf:wg:oauth:2.0:oob&state=GBQAUthTest&access_type=offlin</span></div>
<div style="position:absolute;left:103.02px;top:552.52px" class="cls_004"><span class="cls_004">e&scope=</span><A HREF="https://www.googleapis.com/auth/bigquery&response_type=code/">https://www.googleapis.com/auth/bigquery&response_type=code</A> </div>
<div style="position:absolute;left:85.03px;top:584.15px" class="cls_004"><span class="cls_004">f.   Al pegarlo en tu navegador, debes ver una entrada de cuenta, selecciona la cuenta</span></div>
<div style="position:absolute;left:103.02px;top:599.95px" class="cls_004"><span class="cls_004">Gmail que tiene el acceso a Google Cloud Platform (GCP). Accede con los datos de</span></div>
<div style="position:absolute;left:103.02px;top:615.95px" class="cls_004"><span class="cls_004">login.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:9624px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background13.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:329.87px" class="cls_004"><span class="cls_004">g.  Si recibes un mensaje que dice “Google no verificó esta app”, debes presionar en</span></div>
<div style="position:absolute;left:103.02px;top:345.67px" class="cls_004"><span class="cls_004">configuración avanzada y en ir al app.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:10426px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background14.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:70.22px" class="cls_004"><span class="cls_004">h.  Marcar permitir en la siguiente ventana, si los permisos de la imagen no coinciden</span></div>
<div style="position:absolute;left:103.02px;top:86.03px" class="cls_004"><span class="cls_004">asegúrate de haber creado la cuenta asignando los permisos al usuario.</span></div>
<div style="position:absolute;left:85.03px;top:294.27px" class="cls_004"><span class="cls_004">i.</span></div>
<div style="position:absolute;left:103.02px;top:294.27px" class="cls_004"><span class="cls_004">Verificar la selección de: “Consultar y administrar tus datos en Google BigQuery” y</span></div>
<div style="position:absolute;left:103.02px;top:310.07px" class="cls_004"><span class="cls_004">después en permitir.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:11228px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background15.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:70.22px" class="cls_004"><span class="cls_004">j.</span></div>
<div style="position:absolute;left:103.02px;top:70.22px" class="cls_004"><span class="cls_004">Copia de la ventana siguiente el token correspondiente, este nos ayudará en la</span></div>
<div style="position:absolute;left:103.02px;top:86.03px" class="cls_004"><span class="cls_004">generación del código de refresco.</span></div>
<div style="position:absolute;left:85.03px;top:246.05px" class="cls_004"><span class="cls_004">k.  Ahora vamos a abrir Postman, en la ventana principal seleccionar la opción “CReate</span></div>
<div style="position:absolute;left:103.02px;top:261.87px" class="cls_004"><span class="cls_004">Request”:</span></div>
<div style="position:absolute;left:103.02px;top:368.30px" class="cls_004"><span class="cls_004">l.</span></div>
<div style="position:absolute;left:121.05px;top:368.30px" class="cls_004"><span class="cls_004">Para realizar la petición usaremos el método POST (1), con la dirección</span></div>
<div style="position:absolute;left:121.05px;top:384.10px" class="cls_010"><span class="cls_010"> </span><A HREF="https://www.googleapis.com/oauth2/v4/token">https://www.googleapis.com/oauth2/v4/token</A> <span class="cls_004"> (2) , seleccionamos la pestaña</span></div>
<div style="position:absolute;left:121.05px;top:399.90px" class="cls_004"><span class="cls_004">“Body” (3) en la opción “raw” (4) y completamos los datos (después de la imagen</span></div>
<div style="position:absolute;left:121.05px;top:415.70px" class="cls_004"><span class="cls_004">siguiente dejo la plantilla en texto), (5)(6)(7) son los datos que vienen de la consola</span></div>
<div style="position:absolute;left:121.05px;top:431.50px" class="cls_004"><span class="cls_004">de desarrolladores de google. Code es el de autenticación, id y secreto son los del</span></div>
<div style="position:absolute;left:121.05px;top:447.30px" class="cls_004"><span class="cls_004">cliente Auth2.0 creado (App de escritorio). Presionar “send” para terminar͘</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:12030px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background16.jpg" width=612 height=792></div>
<div style="position:absolute;left:121.05px;top:70.22px" class="cls_004"><span class="cls_004">Plantilla:</span></div>
<div style="position:absolute;left:121.05px;top:86.03px" class="cls_004"><span class="cls_004">{</span></div>
<div style="position:absolute;left:121.05px;top:101.83px" class="cls_004"><span class="cls_004">"code":" &lt;código> ",</span></div>
<div style="position:absolute;left:121.05px;top:117.62px" class="cls_004"><span class="cls_004">"client_id":" &lt;Id> ",</span></div>
<div style="position:absolute;left:121.05px;top:133.42px" class="cls_004"><span class="cls_004">"client_secret":"&lt; Secreto >",</span></div>
<div style="position:absolute;left:121.05px;top:149.25px" class="cls_004"><span class="cls_004">"redirect_uri":"urn:ietf:wg:oauth:2.0:oob",</span></div>
<div style="position:absolute;left:121.05px;top:165.05px" class="cls_004"><span class="cls_004">"grant_type":"authorization_code"</span></div>
<div style="position:absolute;left:121.05px;top:181.05px" class="cls_004"><span class="cls_004">}</span></div>
<div style="position:absolute;left:103.02px;top:196.85px" class="cls_004"><span class="cls_004">m. En el resultado obtenido, copiar el “refresh_token”, si no se obtuvo y aparece un</span></div>
<div style="position:absolute;left:121.05px;top:212.65px" class="cls_004"><span class="cls_004">“bad_request” debe generar de nuevo el “code” haciendo el proceso de</span></div>
<div style="position:absolute;left:121.05px;top:228.45px" class="cls_004"><span class="cls_004">autenticación:</span></div>
<div style="position:absolute;left:103.02px;top:380.30px" class="cls_004"><span class="cls_004">n.  Con esto completamos la información necesaria para ir a Azure Datafactory en el</span></div>
<div style="position:absolute;left:121.05px;top:396.10px" class="cls_004"><span class="cls_004">siguiente paso.</span></div>
<div style="position:absolute;left:85.03px;top:443.50px" class="cls_002"><span class="cls_002">Parte 3 (Configuración del Azure DataFactory)</span></div>
<div style="position:absolute;left:85.03px;top:472.92px" class="cls_004"><span class="cls_004">En este paso vamos a configurar un pipeline de Azure DataFactory, para que nos traiga los</span></div>
<div style="position:absolute;left:85.03px;top:488.73px" class="cls_004"><span class="cls_004">datos desde BigQuery, los datos quedarán alojados en un Blob Storage (también de Azure)</span></div>
<div style="position:absolute;left:85.03px;top:504.53px" class="cls_004"><span class="cls_004">dentro de su respectivo contenedor y asociado a una cuenta de almacenamiento.</span></div>
<div style="position:absolute;left:103.02px;top:528.33px" class="cls_004"><span class="cls_004">a.  Vamos a crear una cuenta de almacenamiento, para eso vamos a la página</span></div>
<div style="position:absolute;left:121.05px;top:544.12px" class="cls_004"><span class="cls_004">principal de Azure </span><span class="cls_010">https://portal.azure.com/#home</span><span class="cls_004">, de ahí vamos a seleccionar la</span></div>
<div style="position:absolute;left:121.05px;top:559.92px" class="cls_004"><span class="cls_004">opción “Cuenta de almacenamiento”͘</span></div>
<div style="position:absolute;left:103.02px;top:695.38px" class="cls_004"><span class="cls_004">b.  Dentro del gestor, presionamos “agregar”</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:12832px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background17.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:207.85px" class="cls_004"><span class="cls_004">c.  En la ventana que se lanza, vamos a insertar los datos. Seleccione primero una</span></div>
<div style="position:absolute;left:121.05px;top:223.65px" class="cls_004"><span class="cls_004">suscripción (1), después indique cuál es el grupo de recursos (2), si no tiene</span></div>
<div style="position:absolute;left:121.05px;top:239.45px" class="cls_004"><span class="cls_004">ninguno debe crear uno (2.1), después inserte el nombre de la cuenta de</span></div>
<div style="position:absolute;left:121.05px;top:255.28px" class="cls_004"><span class="cls_004">almacenamiento (3), seleccione la ubicación más cercana (4), marque Estándar en</span></div>
<div style="position:absolute;left:121.05px;top:271.08px" class="cls_004"><span class="cls_004">el rendimiento (5) y seleccione el tipo de cuenta en la versión más actual (6),</span></div>
<div style="position:absolute;left:121.05px;top:286.87px" class="cls_004"><span class="cls_004">seleccione el nivel de redundancia deseado (7) y presione “revisar y crear” (8)͘</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:13634px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background18.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:534.33px" class="cls_004"><span class="cls_004">d.  Dejamos los otros datos por defecto y al finalizar debemos ver la cuenta creada en</span></div>
<div style="position:absolute;left:121.05px;top:550.12px" class="cls_004"><span class="cls_004">el listado de cuentas de almacenamiento.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:14436px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background19.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:281.48px" class="cls_004"><span class="cls_004">e.  Ingresamos a la cuenta de almacenamiento (1) y nos disponemos a crear un</span></div>
<div style="position:absolute;left:121.05px;top:297.27px" class="cls_004"><span class="cls_004">contenedor para esto (3) en la información general (2). Presionamos sobre</span></div>
<div style="position:absolute;left:121.05px;top:313.08px" class="cls_004"><span class="cls_004">“contenedores”͘</span></div>
<div style="position:absolute;left:103.02px;top:623.55px" class="cls_004"><span class="cls_004">f.   Vamos a crear un contendor, para esto presionamos en “+Contenedor”´(1)͘ En el</span></div>
<div style="position:absolute;left:121.05px;top:639.35px" class="cls_004"><span class="cls_004">costado derecho se despliega un lateral, para que insertemos el nombre del</span></div>
<div style="position:absolute;left:121.05px;top:655.15px" class="cls_004"><span class="cls_004">contenedor (2), el nivel de acceso puede quedar en “privado”͘ Finalizamos</span></div>
<div style="position:absolute;left:121.05px;top:670.97px" class="cls_004"><span class="cls_004">presionando el botón crear en la parte inferior del lateral.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:15238px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background20.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:144.85px" class="cls_004"><span class="cls_004">g.  Al finalizar este proceso debe verse un contendor en l listado, con el nombre</span></div>
<div style="position:absolute;left:121.05px;top:160.65px" class="cls_004"><span class="cls_004">seleccionado.</span></div>
<div style="position:absolute;left:103.02px;top:330.47px" class="cls_004"><span class="cls_004">h.  Ahora que tenemos una cuenta de almacenamiento, un grupo de recursos y un</span></div>
<div style="position:absolute;left:121.05px;top:346.48px" class="cls_004"><span class="cls_004">contenedor. Vamos a comenzar con la configuración del pipeline. Para ellos vamos</span></div>
<div style="position:absolute;left:121.05px;top:362.30px" class="cls_004"><span class="cls_004">a DataFactory, para ingresar regresamos al home de Azure</span></div>
<div style="position:absolute;left:121.05px;top:378.10px" class="cls_004"><span class="cls_004">(</span><span class="cls_010">https://portal.azure.com/#home</span><span class="cls_004">) y de ahí seleccionamos DataFactories.</span></div>
<div style="position:absolute;left:103.02px;top:510.33px" class="cls_004"><span class="cls_004">i.</span></div>
<div style="position:absolute;left:128.03px;top:510.33px" class="cls_004"><span class="cls_004">l ingresar seleccionamos “+agregar” y eso nos lleva a la ventana de creación͘</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:16040px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background21.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:70.22px" class="cls_004"><span class="cls_004">j.</span></div>
<div style="position:absolute;left:121.05px;top:70.22px" class="cls_004"><span class="cls_004">En la ventana de creación, vamos a llenar los datos de la pestaña básico,</span></div>
<div style="position:absolute;left:121.05px;top:86.03px" class="cls_004"><span class="cls_004">seleccionamos la suscripción (1), el grupo de recursos que ya habíamos creado (2),</span></div>
<div style="position:absolute;left:121.05px;top:101.83px" class="cls_004"><span class="cls_004">asignamos una región (3) y un nombre y versión (4)(5).</span></div>
<div style="position:absolute;left:103.02px;top:437.10px" class="cls_004"><span class="cls_004">k.  Vamos a la pestaña de configuración de git y seleccionamos configurar después:</span></div>
<div style="position:absolute;left:103.02px;top:556.53px" class="cls_004"><span class="cls_004">l.</span></div>
<div style="position:absolute;left:121.05px;top:556.53px" class="cls_004"><span class="cls_004">Presionamos revisar y crear, después nuevamente en el botón crear en la parte</span></div>
<div style="position:absolute;left:121.05px;top:572.35px" class="cls_004"><span class="cls_004">inferior.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:16842px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background22.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:458.52px" class="cls_004"><span class="cls_004">m. La implementación tomará un tiempo, pero al finalizar debes presionar “ir al</span></div>
<div style="position:absolute;left:121.05px;top:474.32px" class="cls_004"><span class="cls_004">recurso”͘</span></div>
<div style="position:absolute;left:103.02px;top:695.17px" class="cls_004"><span class="cls_004">n.   l entrar al recurso, debemos presionar en “  uthor & Monitor”</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:17644px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background23.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:249.87px" class="cls_004"><span class="cls_004">o.  En la instancia, vamos a seleccionar “Create PipeLine”</span></div>
<div style="position:absolute;left:103.02px;top:407.70px" class="cls_004"><span class="cls_004">p.  En los recursos, presionamos + (1) y seleccionamos el pipeline (2)</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:18446px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background24.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:70.22px" class="cls_004"><span class="cls_004">q.  Después ingresamos las propiedades y listo.</span></div>
<div style="position:absolute;left:103.02px;top:349.67px" class="cls_004"><span class="cls_004">r.</span></div>
<div style="position:absolute;left:128.03px;top:349.67px" class="cls_004"><span class="cls_004">dicionamos un “CopyData” de las actividades (arrastrar al área de trabajo)͘</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:19248px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background25.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:70.03px" class="cls_002"><span class="cls_002">Parte 3.1 (Creación de Source & Sink en el Pipeline del Data</span></div>
<div style="position:absolute;left:85.03px;top:91.22px" class="cls_002"><span class="cls_002">Factory)</span></div>
<div style="position:absolute;left:103.02px;top:136.22px" class="cls_004"><span class="cls_004">a.  A partir de este punto vamos a construir el Origen(Source) de los datos y el destino</span></div>
<div style="position:absolute;left:121.05px;top:152.05px" class="cls_004"><span class="cls_004">(Sink). Para esto teniendo seleccionado el componente “copy data”, seleccione la</span></div>
<div style="position:absolute;left:121.05px;top:167.85px" class="cls_004"><span class="cls_004">pestaña “Source” y cree un nuevo “Source dataset” presionando sobre el “+New”</span></div>
<div style="position:absolute;left:121.05px;top:183.65px" class="cls_004"><span class="cls_004">(2).</span></div>
<div style="position:absolute;left:103.02px;top:350.67px" class="cls_004"><span class="cls_004">b.  En el lateral desplegable, escriba en la barra de búsqueda big (1) y seleccione el</span></div>
<div style="position:absolute;left:121.05px;top:366.50px" class="cls_004"><span class="cls_004">componente Google BigQuery (2) y después en el botón “continue”͘</span></div>
<div style="position:absolute;left:103.02px;top:670.58px" class="cls_004"><span class="cls_004">c.  Para completar la Edición seleccione el componente y presione “Open”, verifique</span></div>
<div style="position:absolute;left:121.05px;top:686.38px" class="cls_004"><span class="cls_004">que ha abierto el componente y en la pestaña de conexión en “Linked Service”</span></div>
<div style="position:absolute;left:121.05px;top:702.17px" class="cls_004"><span class="cls_004">presione el “+New”͘</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:20050px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background26.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:234.05px" class="cls_004"><span class="cls_004">d.  Al presionar New, debemos configurar la conexión usando las cadenas que</span></div>
<div style="position:absolute;left:121.05px;top:249.87px" class="cls_004"><span class="cls_004">adquirimos durante el Paso de autenticación.  Agregamos una descripción (1),</span></div>
<div style="position:absolute;left:121.05px;top:265.67px" class="cls_004"><span class="cls_004">después dejamos que de manera automática se seleccione el runtime de</span></div>
<div style="position:absolute;left:121.05px;top:281.48px" class="cls_004"><span class="cls_004">integración, sacamos el proyecto id del proyecto de BigQuery en Google Cloud</span></div>
<div style="position:absolute;left:121.05px;top:297.27px" class="cls_004"><span class="cls_004">Platform (3), marcamos como falso la solictud de acceso a drive (4), Copiamos el</span></div>
<div style="position:absolute;left:121.05px;top:313.08px" class="cls_004"><span class="cls_004">Client-ID que nos dieron en la consola de desarrolladores de google (5) e</span></div>
<div style="position:absolute;left:121.05px;top:328.87px" class="cls_004"><span class="cls_004">introducimos el secret y el refresh token (7)(8).  Y completamos el paso.</span></div>
<div style="position:absolute;left:103.02px;top:702.17px" class="cls_004"><span class="cls_004">e.  Realizamos la prueba de conexión y finalizamos.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:20852px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background27.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:146.45px" class="cls_004"><span class="cls_004">f.   Con la conexión probada, probada refrescamos (1) y seleccionamos la table (2).</span></div>
<div style="position:absolute;left:121.05px;top:162.25px" class="cls_004"><span class="cls_004">Este nombre de tabla es el mismo que tenemos en BigQuery.</span></div>
<div style="position:absolute;left:103.02px;top:269.08px" class="cls_004"><span class="cls_004">g.  Con esto completamos la creación del Source. Y regresamos al Pipeline en la</span></div>
<div style="position:absolute;left:121.05px;top:284.87px" class="cls_004"><span class="cls_004">pestaña para crear el Sink(1), presionamos “+New” (2) para continuar en el</span></div>
<div style="position:absolute;left:121.05px;top:300.67px" class="cls_004"><span class="cls_004">proceso.</span></div>
<div style="position:absolute;left:103.02px;top:629.55px" class="cls_004"><span class="cls_004">h.  En el lateral desplegado, escribir “blob” en la barra de búsqueda (1) y después</span></div>
<div style="position:absolute;left:121.05px;top:645.35px" class="cls_004"><span class="cls_004">seleccionar el dataset “Azure Blob Storage” (2).</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:21654px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background28.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:361.50px" class="cls_004"><span class="cls_004">i.</span></div>
<div style="position:absolute;left:121.05px;top:361.50px" class="cls_004"><span class="cls_004">En las opciones seleccionar Parquet (ocupa menos espacio, pero se tarda un poco</span></div>
<div style="position:absolute;left:121.05px;top:377.30px" class="cls_004"><span class="cls_004">más en traerlo desde BigQuery).</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:22456px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background29.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:428.50px" class="cls_004"><span class="cls_004">j.</span></div>
<div style="position:absolute;left:121.05px;top:428.50px" class="cls_004"><span class="cls_004">Asignamos un nombre y en el “linked Service” presionamos para crear uno nuevo.</span></div>
<div style="position:absolute;left:103.02px;top:676.38px" class="cls_004"><span class="cls_004">k.  En el desplegable, incluimos los datos solicitados: nombre del servicio (1),</span></div>
<div style="position:absolute;left:121.05px;top:692.17px" class="cls_004"><span class="cls_004">descripción (2) , indicamos que sea de una suscripción de Azure (3) y marcamos la</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:23258px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background30.jpg" width=612 height=792></div>
<div style="position:absolute;left:121.05px;top:70.22px" class="cls_004"><span class="cls_004">conexión y la cuenta (4)(5), indicamos que el tipo de prueba de conexión sea “To</span></div>
<div style="position:absolute;left:121.05px;top:86.03px" class="cls_004"><span class="cls_004">linked service” (6) y probamos la conexión, una vez probada presionamos el botón</span></div>
<div style="position:absolute;left:121.05px;top:101.83px" class="cls_004"><span class="cls_004">“crear” (8).</span></div>
<div style="position:absolute;left:103.02px;top:541.53px" class="cls_004"><span class="cls_004">l.</span></div>
<div style="position:absolute;left:121.05px;top:541.53px" class="cls_004"><span class="cls_004">Marcamos las propiedades con el nombre del parquet (1), el servicio vinculado (2)</span></div>
<div style="position:absolute;left:121.05px;top:557.53px" class="cls_004"><span class="cls_004">y la ruta (seleccionando desde la carpeta (3)), indicamos que el esquema proviene</span></div>
<div style="position:absolute;left:121.05px;top:573.35px" class="cls_004"><span class="cls_004">de la conexión o esquema y finalizamos con el botón “OK/Create”.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:24060px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background31.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:269.48px" class="cls_004"><span class="cls_004">m. Dejamos en Copy behavior: None y pasamos a la pestaña de Mapping (Aquí se</span></div>
<div style="position:absolute;left:121.05px;top:285.27px" class="cls_004"><span class="cls_004">puede personalizar la forma de conversión de los campos de las tablas)</span></div>
<div style="position:absolute;left:103.02px;top:593.15px" class="cls_004"><span class="cls_004">n.  Para traer los Esquemas desde la conexión presionamos “Import schemas” y listo.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:24862px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background32.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:226.05px" class="cls_004"><span class="cls_004">o.   Terminamos, las pestañas de Settings y User Properties quedan por defecto.</span></div>
<div style="position:absolute;left:103.02px;top:241.85px" class="cls_004"><span class="cls_004">p.   Ahora vamos a publicar y para ello presionamos “publish all”, se debe ver un</span></div>
<div style="position:absolute;left:121.05px;top:257.67px" class="cls_004"><span class="cls_004">número 3. Y debe salir que no hay errores, de lo contrario deben corregirse con las</span></div>
<div style="position:absolute;left:121.05px;top:273.48px" class="cls_004"><span class="cls_004">recomendaciones que brinda la interfaz</span></div>
<div style="position:absolute;left:103.02px;top:505.92px" class="cls_004"><span class="cls_004">q.  Finalmente vamos a ejecutar el pipeline, para ello se selecciona el pipeline y se</span></div>
<div style="position:absolute;left:121.05px;top:521.72px" class="cls_004"><span class="cls_004">presiona en “Add trigger”  seguido de “Trigger now” (2).</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:25664px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background33.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:278.48px" class="cls_004"><span class="cls_004">r.   Al ejecutarlo, podemos ver en el monitor (1) el progreso y una vez finalizado</span></div>
<div style="position:absolute;left:121.05px;top:294.27px" class="cls_004"><span class="cls_004">aparecerá verde (2).</span></div>
<div style="position:absolute;left:103.02px;top:419.10px" class="cls_004"><span class="cls_004">s.   Con esto se da por finalizado y ahora los datos están en Azure Blob Storage.</span></div>
<div style="position:absolute;left:85.03px;top:474.33px" class="cls_002"><span class="cls_002">Parte 4 (Conexión con Azure Databricks).</span></div>
<div style="position:absolute;left:85.03px;top:503.53px" class="cls_004"><span class="cls_004">Durante esta parte crearemos un cluster de Azure Databricks y probaremos algunas</span></div>
<div style="position:absolute;left:85.03px;top:519.53px" class="cls_004"><span class="cls_004">consultas básicas.</span></div>
<div style="position:absolute;left:103.02px;top:543.33px" class="cls_004"><span class="cls_004">a.  Desde el home de Azure, ingresamos a Azure DataBricks.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:26466px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background34.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:70.22px" class="cls_004"><span class="cls_004">b.  Presionamos “+ Agregar” para crear una nueva instancia.</span></div>
<div style="position:absolute;left:103.02px;top:342.27px" class="cls_004"><span class="cls_004">c.  Procedemos a configurar la instancia, insertamos los datos básicos y</span></div>
<div style="position:absolute;left:121.05px;top:358.10px" class="cls_004"><span class="cls_004">seleccionamos los elementos de nuestra suscripción creada.</span></div>
<div style="position:absolute;left:103.02px;top:640.95px" class="cls_004"><span class="cls_004">d.  Esperamos la implementación.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:27268px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background35.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:294.87px" class="cls_004"><span class="cls_004">e.  Al finalizar presionar en ir al recurso.</span></div>
<div style="position:absolute;left:103.02px;top:489.33px" class="cls_004"><span class="cls_004">f.   Presionar ir al recurso, y proceder a iniciar área de trabajo</span></div>
<div style="position:absolute;left:103.02px;top:632.35px" class="cls_004"><span class="cls_004">g.  Ahí en la barra izquierda seleccionamos los clusters</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:28070px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background36.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:70.22px" class="cls_004"><span class="cls_004">h.  Asignamos un nombre, seleccionamos un solo nodo y la versión 7.5 ML sin GPU.</span></div>
<div style="position:absolute;left:103.02px;top:388.70px" class="cls_004"><span class="cls_004">i.</span></div>
<div style="position:absolute;left:121.05px;top:388.70px" class="cls_004"><span class="cls_004">Creamos un nuevo notebook.</span></div>
<div style="position:absolute;left:103.02px;top:666.55px" class="cls_004"><span class="cls_004">j.</span></div>
<div style="position:absolute;left:121.05px;top:666.55px" class="cls_004"><span class="cls_004">Incluimos el código disponible en el html (databricks) usando los datos propios de</span></div>
<div style="position:absolute;left:121.05px;top:682.58px" class="cls_004"><span class="cls_004">su conexión.</span></div>
<div style="position:absolute;left:103.02px;top:698.38px" class="cls_004"><span class="cls_004">k.  Revisar las consultas SQL.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:28872px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background37.jpg" width=612 height=792></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:29674px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background38.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:591.55px" class="cls_004"><span class="cls_004">l.</span></div>
<div style="position:absolute;left:121.05px;top:591.55px" class="cls_004"><span class="cls_004">Al finalizar el proceso, los datos han sido creados en el cluster y pueden ser</span></div>
<div style="position:absolute;left:121.05px;top:607.35px" class="cls_004"><span class="cls_004">capturados desde PowerBI.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:30476px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background39.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.03px;top:70.03px" class="cls_002"><span class="cls_002">Parte 5 (Conexión con Power BI).</span></div>
<div style="position:absolute;left:85.03px;top:99.42px" class="cls_004"><span class="cls_004">En esta última parte usaremos el conector que trae la versión más reciente de PowerBI</span></div>
<div style="position:absolute;left:85.03px;top:115.22px" class="cls_004"><span class="cls_004">para conectarse a Azure Databricks.</span></div>
<div style="position:absolute;left:103.02px;top:139.03px" class="cls_004"><span class="cls_004">a.  Al iniciar Power BI, presione en obtener Datos:</span></div>
<div style="position:absolute;left:103.02px;top:412.50px" class="cls_004"><span class="cls_004">b.  Use la barra de búsqueda y seleccione el conector de Azure Databricks</span></div>
<div style="position:absolute;left:103.02px;top:598.95px" class="cls_004"><span class="cls_004">c.  Capture los datos del cluster en la configuración, opciones avanzadas. Y complete</span></div>
<div style="position:absolute;left:121.05px;top:614.75px" class="cls_004"><span class="cls_004">la información solicitada por el conector.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:31278px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background40.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.02px;top:277.27px" class="cls_004"><span class="cls_004">d.  Navegue en el árbol de carpetas hasta la tabla y selecciónela, para después</span></div>
<div style="position:absolute;left:121.05px;top:293.07px" class="cls_004"><span class="cls_004">presionar “cargar”</span></div>
<div style="position:absolute;left:103.02px;top:514.12px" class="cls_004"><span class="cls_004">e.  Crea algunos objetos visuales y con eso habremos finalizado el proceso.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:32080px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="849e1844-6380-11eb-8b25-0cc47a792c0a_id_849e1844-6380-11eb-8b25-0cc47a792c0a_files/background41.jpg" width=612 height=792></div>
</div>

</body>
</html>
