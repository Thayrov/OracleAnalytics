# Oracle Analytics: visualizando datos

## Clase 1: Oracle Analytics

Realiza la descarga de Oracle Analytics en la página oficial, haciendo clic en "Descargar" en el producto Oracle Analytics Desktop.

A continuación, es necesario que inicies sesión en tu cuenta de Oracle. Si no tienes una cuenta, puedes crear una de forma gratuita seleccionando la opción "Crear Cuenta". Registra tus datos y, seguidamente, la cuenta será creada. Para quienes ya poseen una cuenta, el nombre de usuario generalmente es el correo electrónico utilizado durante el registro.

Una vez que hayas iniciado sesión, aparecerá una página donde debes seleccionar tu sistema operativo. Luego, selecciona la opción "I reviewed and accept the Oracle License Agreement" para aceptar los términos y condiciones de uso del software.

Ahora, simplemente debes hacer clic en "Descargar" y esperar a que se complete el proceso, lo que generará el archivo ejecutable para la instalación del software en tu máquina.

Abre el archivo ejecutable en tu equipo para realizar la instalación del Oracle Download Manager. Este te solicitará el directorio donde deseas almacenar el archivo comprimido (.zip) que contiene el ejecutable para la instalación de Oracle Analytics Desktop. Tras elegir el directorio de almacenamiento, haz clic en "Siguiente" para continuar con la instalación.

Después de completar la descarga, haz clic en el icono de carpeta en la esquina inferior izquierda para acceder al archivo (.zip) descargado.

Si has cerrado la ventana, puedes encontrar el archivo (.zip) en el directorio donde se almacenó. Al localizar este archivo, procederemos a descomprimirlo para instalar Oracle Analytics Desktop.

Tras descomprimir el archivo, obtendrás un nuevo ejecutable. Para instalar Oracle Analytics, ejecútalo y selecciona la opción "Launch after install" para que el software se inicie automáticamente una vez que se complete la descarga. Finalmente, haz clic en "Instalar".

Después, haz clic en "Finalizar".

A partir de este momento, Oracle Analytics Desktop está listo para ser utilizado.

## Clase 2: Creando el proyecto

Ha llegado el momento de poner en práctica tus conocimientos, transformando y tratando algunos datos. Comenzaremos creando una nueva conexión para importar nuestra base de datos. Para ello, haz clic en la opción "Crear", ubicada en la esquina superior derecha de tu pantalla.

Selecciona la opción "Conjunto de datos" o, en caso de que ya hayas importado los archivos con los que trabajaremos, elige la opción "Directorio de Trabajo".

Para importar la base de datos, selecciona el archivo y arrástralo hasta la nueva ventana, o haz clic en el ícono y busca el archivo en el directorio donde se encuentra almacenado en tu entorno.

Una vez cargados los datos, modifica el nombre del archivo y los separadores de casillas decimales.

Después de añadir el archivo importado, una nueva pantalla estará disponible para realizar el tratamiento de los datos.

En el lado izquierdo de la pantalla, en el área de "Recomendaciones", encontrarás una serie de sugerencias que el software identifica automáticamente y que nos permiten realizar un tratamiento a los datos.

En caso de que realices una modificación y decidas no mantenerla, puedes eliminar esta etapa haciendo clic en la "x" situada dentro de la caja de texto con el nombre de la modificación realizada y seleccionando "Excluir Etapa".

Si no encontramos las modificaciones que deseamos hacer en las recomendaciones, podemos realizarlas de forma manual.

**Para saber más: Augmented Analytics**

Augmented Analytics o Análisis aumentado es una tecnología que emplea la Inteligência Artificial (IA) y técnicas de Machine Learning para automatizar el proceso de análisis de datos realizado con las herramientas analíticas.

Algunos de los procesos mediante los cuales esta tecnología nos auxilia son en la exploración, identificación y preparación de los datos, generando insights que aumentan la forma como exploramos y analizamos estos datos. Dicha automación disminuye, o incluso, hasta sustituye el tiempo dedicado a la organización y el análisis de los datos realizado por los profesionales.

Es como si la máquina tuviese el poder de leer mentes y presentase exactamente lo que se necesita saber antes de que los profesionales analicen los datos propiamente.

Las organizaciones que comiencen a utilizar esta tecnología tienen el potencial de ganar una ventaja competitiva en el mercado y se cree que prontamente Augmented Analytics será esencial para cualquier proyecto de BI.

## Clase 3: Creando gráficas

Para empezar con la configuración del recurso "Explicar columna", necesitamos ir al directorio C:\Program Files\Oracle Analytics Desktop.

A continuación, debes seleccionar el archivo install_dvml.cmd.

Al hacer doble clic en el archivo install_dvml.cmd, se abrirá una ventana del símbolo del sistema para descargar e instalar el recurso.

Al concluir la instalación, aparecerá un mensaje solicitando reiniciar el computador. Tras reiniciar tu equipo, el recurso quedará completamente instalado. En Oracle Analytics, podrás hacer clic derecho sobre cualquier columna y la opción "Explicar" estará disponible.

**Para saber más: cuándo utilizar el gráfico de barras**

El gráfico de barras es muy útil para comparar categorías. Generalmente son usados para evitar el desorden de los datos, cuando las leyendas son muy extensas o si tenemos más de 10 items para comparar.

Dentro del gráfico de barras existen algunos subtipos:

Barras agrupadas: Los items son agrupados en el eje vertical, permitiendo una comparación rápida de valores.
Barras apiladas: Una única barra es utilizada para exhibir los items y los colores de las leyendas son separados de manera bien evidente.
Barras 100% apiladas: Trabajan bajo el mismo concepto de barras apiladas, con la diferencia de que los valores son exhibidos en porcentajes.
Tips para crear un gráfico de barras:

Nombra los ejes.
Coloca leyendas de valores en las barras.
Evita gráficos “arco-íris”, o sea, no dejes el gráfico de todos los colores. Es mucho mejor utilizar un solo color o varias tonalidades de un mismo color.

## Clase 4: Interacción entre las visualizaciones

En la clase anterior, aprendimos un poco sobre el uso de mapas a través del análisis de facturación en relación a los departamentos de los clientes del Club del Libro. Para profundizar más en mapas, especialmente el mapa de calor ampliamente utilizado en visualización de datos, vamos a considerar una situación hipotética.

Construyendo el mapa de calor
Para aprender a manipular y generar mapas de calor en Oracle Analytics, exploremos el siguiente ejemplo: Charlene es una analista de datos en un comercio electrónico de dulces llamado Candy Candy. Ella está a cargo de analizar los datos de facturación por mes de la empresa en 2021 y necesita presentar sus datos en un mapa de calor por solicitud de su jefe.

Los datos recolectados con la facturación por mes se presentan de la siguiente forma:

Fecha	2021
01/2021	1900,00
02/2021	84408,00
03/2021	-9643,00
...	...
Para destacar los datos sin necesidad de añadir muchos recursos y hacer la tabla más fácil de leer, podemos transformarla en un mapa de calor en el software de Oracle Analytics. Así, seguiremos los siguientes pasos:

Creando el Conjunto de Datos “Ventas”
Antes de comenzar, debes copiar los datos de la tabla en un archivo de texto o en un software de hojas de cálculo y almacenarlo con el formato .csv. Te sugiero usar el nombre candy_candy.csv. A continuación, crearemos un conjunto de datos navegando hasta el botón "Crear" en la esquina superior derecha de la pantalla inicial y seleccionaremos la opción "Conjunto de Datos".

Se abrirá el cuadro de diálogo donde debemos arrastrar el archivo candy_candy.csv hasta nuestra ventana, o hacer clic en el botón "Subir" para cargar nuestros datos en Oracle Analytics.

Tras cargar los datos, se genera un nuevo conjunto de datos. En este punto, sin hacer modificaciones aún, debemos hacer clic en el botón "Añadir" para crear nuestro conjunto de datos.

Ajustando la columna Fecha para medida de tipo Date
Ahora, somos redirigidos al conjunto de datos candy_candy. Observamos dos columnas en nuestros datos: "Fecha", que está representada como un atributo; y "2021", que contiene la facturación de Candy Candy, como medida.

Para reconocer la columna "Fecha" correctamente como medida de tiempo, necesitamos convertirla de atributo a tipo "Date". Para ello, basta con hacer clic derecho sobre la columna "Fecha" y escoger la opción "Convertir a Fecha".

Después, necesitamos identificar el formato de origen ideal para la fecha, que en nuestro conjunto de datos es mes/año, es decir, MM/yyyy. Al definir esta opción, haremos clic en "Aplicar Script" para guardar los cambios.

Al transformar la columna "Fecha" en una medida de tipo "Date", podemos extraer lapsos temporales. Crearemos una nueva columna haciendo clic en los tres puntos junto a la columna "Fecha" y seleccionaremos las opciones "Extraer → Mes del Año".

Vamos a renombrar la columna creada como "Mes". Para hacerlo, haremos clic en los tres puntos de la columna "Fecha Mes del Año 1" y escogeremos la opción "Renombrar".

Para finalizar esta etapa y guardar todos los cambios, haremos clic en "Aplicar Script" y, posteriormente, en "Crear Directorio de Trabajo" para utilizar la base de datos modificada.

Creando el mapa de calor
Para crear nuestro mapa de calor, haremos clic sostenido y arrastraremos la columna "Mes" hasta el espacio "Soltar Visualizaciones o Datos aquí".

Esta acción genera una visualización automática de "Tabla", que cambiaremos a "Tabla Dinámica". Esto lo haremos haciendo clic en "Visualización Automática" y escogiendo la opción correspondiente a "Tabla Dinámica".

Para exhibir la cantidad de ventas por mes, arrastraremos la columna "2021" a la pestaña "Valores".

En este punto, añadimos la intensidad de las ventas de 2021 arrastrando la columna "2021" a la pestaña "Color".

Para ajustar nuestro mapa de calor con colores que identifiquen mejor la idea de valores muy negativos, negativos, positivos y muy positivos, haremos clic en la esquina superior derecha de la pestaña "Color", que abrirá un menú con la opción "Administrar Designaciones".

Para alterar nuestra paleta de colores, haremos clic en la flecha al lado de la paleta de colores azules y escogeremos la que tiene el gradiente de tonos rojos y verdes.

¡Felicitaciones! Has logrado elaborar el mapa de calor a través del recurso de Tabla Dinámica.

## Clase 5: Elaborando la presentación

**Para saber más: importando visualizaciones externas**

Oracle posee una biblioteca externa en la cual encontramos varias visualizaciones diferentes que podemos importar en Oracle Analytics y así poder enriquecer aún más nuestros proyectos. Para realizar el download de una visualización externa, necesitamos acceder a la página de Oracle Analytics Library. En seguida, localizamos la extensión que deseamos importar en Oracle Analytics (por ejemplo la de Mobile Grid Bars Plug-in) y hacemos clic en Download .

Una caja de texto va a aparecer solicitando la confirmación de los términos de la licencia. y seleccionamos la opción Accept License Agreement, e iniciar sesión en tu cuenta de Oracle, para continuar con el download.

Un archivo de extensión .zip será descargado, la recomendación es que lo almacenes en el directorio de tu preferencia.

Luego de que finalice la descarga, abrimos Oracle Analytics en el menú sándwich, en la página inicial, seleccionamos la opción Consola.

Al hacer clic en Consola aparecerá el campo Visualizaciones y Compartimiento. Seleccionaremos la opción Extensiones y se abrirá una nueva página donde seleccionaremos Subir Extensión.
Localizamos el archivo en el directorio de descarga y el mismo quedará disponible en extensiones.

Para poder tener acceso a esta visualización en tu proyecto, será necesario reiniciar Oracle Analytics. Las nuevas visualizaciones importadas estarán disponibles en visualizaciones, en la opción de Visualizaciones Personalizadas.

**Para saber más: profundizando en el Storytelling**

Storytelling es el arte de contar historias utilizando técnicas inspiradas en libretistas y escritores para transmitir un mensaje de forma fluida e inolvidable. Cuando desarrollamos un proyecto para hacer una presentación, debemos tener una buena narrativa detrás de aquel contenido que pueda enriquecer su sentido y haga que las personas comprendan todo el proceso de forma objetiva.

El Storytelling es considerado uno de los soft skills más importantes en el área de datos, pues complementa y finaliza un proyecto sujetando toda la información a una línea continua.
