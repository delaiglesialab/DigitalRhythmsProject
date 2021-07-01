# Paso 1 de 2: Obteniendo los datos

Este paso es bastante sencillo y debiera tomar poco tiempo, pero para que sea incluso más fácil, hemos documentado cada uno de los clics requeridos. Así que no se alarme, esto no será tan lento o complejo como la longitud de esta página parece sugerirlo.

### Cómo obtener los datos de actividad de su teléfono Android:

El primer paso es hacer clic en el enlace aquí abajo para ir al servicio  Takeout de Google.

### <a href="https://takeout.google.com" target="_blank"> takeout.google.com </a>

Asegúrese de iniciar sesión con la misma cuenta que utiliza como principal en su teléfono Android.

A continuación, haga clic en "deseleccionar todo" como se muestra a continuación, ya que solo queremos exportar los datos de actividad de las aplicaciones.

![1](https://user-images.githubusercontent.com/68754864/96494580-2dd69800-1264-11eb-93a3-8a2270246b41.png)


Luego desplácese hacia abajo para encontrar el cartel "Mi actividad". Por lo general, se encuentra entre "Mapas" y "Mis mapas".

Marque la casilla de verificación a la derecha y haga clic en el botón "Formatos múltiples" a la izquierda.


![2](https://user-images.githubusercontent.com/68754864/96494591-2fa05b80-1264-11eb-8639-2863cdcbf71d.png)


En la ventana emergente, asegúrese de que los *Registros de actividad* estén configurados en el formato HTML como la imagen de abajo y **NO** JSON. Haga clic en "Aceptar" para continuar.


![3](https://user-images.githubusercontent.com/68754864/96494593-3038f200-1264-11eb-87f8-0b629b36ce14.png)


Ahora haga clic en el botón que dice "Todos los datos de actividad incluidos", y en la ventana emergente, primero haga clic en "Deseleccionar todo" y luego marque la casilla de verificación para Android como se muestra abajo. Haga clic en "Aceptar" para continuar.


![4](https://user-images.githubusercontent.com/68754864/96494595-30d18880-1264-11eb-8b41-3469de97fd8c.png)


Desplácese hacia abajo y haga clic en "Paso siguiente".


![5](https://user-images.githubusercontent.com/68754864/96494596-316a1f00-1264-11eb-814e-f31320e5c922.png)


En el segundo paso, seleccione la frecuencia "Exportar una vez". Puede escoger el tipo de archivo de descarga que sepa que puede abrir (la mayoría de las personas se sentirán familiarizadas con el formato '.zip').

El tamaño máximo de archivo predeterminado de 2 GB (.zip) puede ser dejada tal como está; ¡pero no se alarme! La descarga no será muy grande (<100 MB) dependiendo de cada usuario.

Haga clic en "Crear exportación", y estará (casi) listo.

![6](https://user-images.githubusercontent.com/68754864/96494598-3202b580-1264-11eb-8605-0c415020ab06.png)


Una vez que haga clic en "Crear exportación", verá un nuevo banner como este, indicándole que la creación de su archivo está en marcha.

![7](https://user-images.githubusercontent.com/68754864/96494600-329b4c00-1264-11eb-8fc3-c50fc6694cd1.png)

Este proceso no debiera tomar más de 5 minutos. **Sin embargo, puede recibir una notificación en su teléfono y/o un correo electrónico de Google, pidiéndole que confirme que fue usted quien solicitó esta exportación. Es posible que no reciba un enlace de descarga hasta que abra ese correo electrónico o notificación y haga clic en "Sí".**

Ahora puede sentarse a esperar el mensaje de Google, que puede tomar más o menos tiempo dependiendo de la cola de trabajo en los servidores de Takeout. Siéntase libre de pausar estas instrucciones aquí y continuar cuando sea conveniente para usted. Salga a caminar, coma algo, haga un poco de yogo, o llame a un amigo/a - pero no se quede simplemente mirando la pantalla hasta que su archivo esté disponible :)

Alternativamente, si vuelve a cargar la página, encontrará un nuevo cartel en la parte superior con un botón para "Administrar exportaciones", tal como se muestra a continuación.


![8](https://user-images.githubusercontent.com/68754864/96494602-3333e280-1264-11eb-9783-3fd16e0bfc68.png)


Al hacer clic en él, se abrirá una nueva página con su historial de exportaciones, y dirá que su exportación está en curso. Si tiene suerte, verá la exportación con el enlace de descarga disponible de inmediato (provisto que hay confirmado ya desde su correo electrónico o teléfono). Si todavía no está disponible la descarga, simplemente espere y vuelva a cargar en un momento y debería obtener la opción de descarga.


![9](https://user-images.githubusercontent.com/68754864/96494604-33cc7900-1264-11eb-9f82-d90ccdc70ec5.png)


La descarga puede requerir que vuelva a iniciar sesión ingresando su contraseña. Una vez que lo haya descargado, abra el archivo comprimido usando su administrador de archivos favorito. (su sistema operativo puede que abra estos archivos sin problemas).

Una vez abierto el archivo, ingrese en la carpeta ***"Takeout"***, luego a la carpeta ***"My Activity/Mi actividad"***, y finalmente a la carpeta ***"Android"*** para encontrar el archivo ***"Mi actividad.html"***.

![10](https://user-images.githubusercontent.com/68754864/96496886-76dc1b80-1267-11eb-9805-562158c3a71e.png)

Copie y guarde este archivo en una ubicación conveniente para cargarlo en el siguiente paso.

**¡Felicitaciones! Ahora ya ha conseguido su archivo de datos de uso de aplicaciones en Android. Eso es todo en este primer paso.**

Le recomendamos que abra este archivo en su computadora y lo revise, si así lo quiere. El archivo mostrará una lista aparentemente interminable de nombres de aplicaciones y las horas en las que fueron utilizadas, **pero ningún tipo de información personal.**

Una vez que se sienta cómodo con compartir este archivo con nosotros, haga clic en el botón más abajo.

[<img src = "https://user-images.githubusercontent.com/42762378/101690680-9dfae080-3a93-11eb-8552-e4a65f2babfc.png" height = "30" width = "120">](https://delaiglesialab.github.io/DigitalRhythmsProject/es/Questionnaires)

<hr>

Sin embargo, si todavía tiene dudas, le ofrecemos la opción de generar un nuevo archivo más sencillo del cual se hayan removido todos los nombres de las aplicaciones antes de que pueda compartirlo con nosotros. Haga clic en el ícono de abajo que lo llevará a un tutorial en ***Google Colab*** con las instrucciones necesarias - pero antes de hacerlo, considere una vez más compartir el archivo original con nosotros, que nos permitirá realizar análisis incluso más interesantes. Recuerde que sus datos serán anonimizados y conservados en un servidor seguro. Si aún así prefiere remover toda la información de los nombres de sus aplicaciones, abra el link de abajo y siga las instrucciones antes de continuar.

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/delaiglesialab/DigitalRhythmsProject/blob/main/es/espa%C3%B1ol_Android_Timestamps_Notebook.ipynb)

Una vez que haya obtenido el archivo (de extensión CSV) a través de este proceso, continúe haciendo clic <a href="https://delaiglesialab.github.io/DigitalRhythmsProject/es/Questionnaires"> aquí. </a>
