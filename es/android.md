# Paso 1 de 2: Obtenga los datos

Es un proceso corto que es realmente fácil, pero para que quede claro, hemos documentado cada clic requerido. Así que no te preocupes, no es ni remotamente tan lento como parece la longitud de esta página.

### Para obtener los datos de actividad de tu aplicación de Android:

El primer paso es hacer clic en el enlace de abajo para ir al servicio de comida para llevar de Google.

### <a href="https://takeout.google.com" target="_blank"> takeout.google.com </a>

asegúrese de haber iniciado sesión en la misma cuenta que la principal en su teléfono Android.

A continuación, haga clic en "deseleccionar todo" como se muestra a continuación, ya que solo queremos exportar los datos de actividad de la aplicación.


! [1] (https://user-images.githubusercontent.com/68754864/96494580-2dd69800-1264-11eb-93a3-8a2270246b41.png)


A continuación, desplácese hacia abajo para encontrar el banner "Mi actividad". Por lo general, se encuentra entre "Mapas (sus lugares)" y "Mis mapas".

Marque la casilla de verificación a la derecha y haga clic en el botón "Formatos múltiples" a la izquierda.


! [2] (https://user-images.githubusercontent.com/68754864/96494591-2fa05b80-1264-11eb-8639-2863cdcbf71d.png)


En la ventana emergente que se abre, asegúrese de que los Registros de actividad estén configurados en el formato HTML como la imagen de abajo y ** NO ** JSON. Haga clic en "Aceptar" para continuar.


! [3] (https://user-images.githubusercontent.com/68754864/96494593-3038f200-1264-11eb-87f8-0b629b36ce14.png)


Ahora haga clic en el botón que dice "Todos los datos de actividad incluidos" y en la ventana emergente, primero haga clic en "Deseleccionar todo" y luego marque la casilla de verificación para Android como se muestra. Haga clic en "Aceptar" para continuar.


! [4] (https://user-images.githubusercontent.com/68754864/96494595-30d18880-1264-11eb-8b41-3469de97fd8c.png)


Desplácese hacia abajo y haga clic en "Paso siguiente".


! [5] (https://user-images.githubusercontent.com/68754864/96494596-316a1f00-1264-11eb-814e-f31320e5c922.png)


En el segundo paso, seleccione la frecuencia "Exportar una vez". El tipo de archivo es su elección, la mayoría de las personas se sienten cómodas con .zip, elija el que sepa que puede abrir. Los archivos .tgz pueden requerir software adicional en Windows y Mac, por lo que .zip es más seguro para la mayoría. El tamaño de archivo predeterminado de 2 GB (.zip) está perfectamente bien. La descarga no debe ser demasiado grande (<100 MB) dependiendo de su uso.

Haga clic en "Crear exportación" y listo. (casi)


! [6] (https://user-images.githubusercontent.com/68754864/96494598-3202b580-1264-11eb-8605-0c415020ab06.png)


Una vez que haga clic en "crear exportación", verá un nuevo banner como este, indicándole que está en marcha. El proceso solo toma unos 5 minutos.

** Sin embargo ** puede recibir una notificación en su teléfono y un correo electrónico de Google, pidiéndole que confirme que fue usted quien solicitó una exportación. Es posible que no reciba un enlace de descarga hasta que abra ese correo electrónico / notificación y haga clic en "Sí".

¡Así que revisa tu correo electrónico!


! [7] (https://user-images.githubusercontent.com/68754864/96494600-329b4c00-1264-11eb-8fc3-c50fc6694cd1.png)


Ahora, puede sentarse y esperar el correo electrónico de Google, que a veces puede retrasarse a pesar de que el proceso en sí es bastante rápido.

Alternativamente, si vuelve a cargar la página, encontrará un nuevo banner en la parte superior, con un botón para "Administrar exportaciones", como se muestra a continuación.


! [8] (https://user-images.githubusercontent.com/68754864/96494602-3333e280-1264-11eb-9783-3fd16e0bfc68.png)


Al hacer clic en él, se abre una nueva página con su historial de exportaciones, y dirá que su exportación está en curso. Si tiene suerte, verá la exportación con el enlace de descarga de inmediato (dado que lo verificó desde su correo electrónico o teléfono). Si no es así, simplemente espere y vuelva a cargar en un momento y debería obtener la opción de descarga.


! [9] (https://user-images.githubusercontent.com/68754864/96494604-33cc7900-1264-11eb-9f82-d90ccdc70ec5.png)


La descarga puede requerir que inicie sesión nuevamente ingresando su contraseña.

Una vez que lo haya descargado, abra el archivo (zip / tgz) usando su administrador de archivos favorito. (winRAR, 7z, etc.) (su sistema operativo (es decir, windows / mac también puede admitirlo dentro del administrador de archivos, así que simplemente haga doble clic y vea lo que viene).

Una vez abierta, vaya a la carpeta "Takeout", luego a la carpeta "Mi actividad", luego a la carpeta "Android" para encontrar el archivo "Mi actividad.html".

en el archivo: / Takeout / My Activity / Android / My Activity.html


! [10] (https://user-images.githubusercontent.com/68754864/96496886-76dc1b80-1267-11eb-9805-562158c3a71e.png)


Copie y guarde este archivo en una ubicación conveniente para cargarlo en el siguiente paso.

¡Terminaste con esta etapa del proceso!

¡Le recomendamos encarecidamente que abra el archivo usted mismo! El archivo carga una página web aparentemente interminable con una lista de nombres de aplicaciones y marcas de tiempo, pero sin detalles personales. En la siguiente etapa del proceso (después de hacer clic en Continuar), recibirá un código y cambiará el nombre del archivo con él, de modo que no se le pueda volver a identificar.

Una vez que se sienta cómodo compartiendo el archivo con nosotros de forma anónima, haga clic en el botón de abajo.

[<img src = "https://user-images.githubusercontent.com/42762378/101690680-9dfae080-3a93-11eb-8552-e4a65f2babfc.png" height = "30" width = "120">] (https: / /delaiglesialab.github.io/DigitalRhythmsProject/Questionnaires)

<hr>
<hr>
<hr>

Sin embargo, si aún le preocupa, le ofrecemos la opción de extraer la información con el mismo método que usaríamos con el archivo, y obtener un archivo CSV antes de compartirlo con nosotros. Haga clic en el icono de abajo para abrir un cuaderno de Google Colab y siga las instrucciones que se encuentran dentro. También ofrece la opción de eliminar nombres de aplicaciones, pero considere no hacerlo para permitirnos la oportunidad de hacer análisis más interesantes con los datos.

[! [Abrir en Colab] (https://colab.research.google.com/assets/colab-badge.svg)] (https://colab.research.google.com/github/delaiglesialab/DigitalRhythmsProject/blob/ main / Android_Timestamps_Notebook.ipynb)

Una vez que haya obtenido el archivo CSV del cuaderno, continúe haciendo clic <a href="https://delaiglesialab.github.io/DigitalRhythmsProject/Questionnaires"> aquí. </a>
