## Análisis de datos en Python al estilo Excel con Mito
-------

Mito es una interfaz gráfica de Python para el análisis de datos, basado en **JupyterLab**, con un funcionamiento similar al de las hojas de cálculo. Permitiendo llevar a cabo complejos análisis en pocos segundos, creando además de forma automática código Python con el que repetir las operaciones en cualquier conjunto de datos similar. Lo que permite crear análisis de datos en Python al estilo de Excel.


Algunas de las operaciones que se pueden realizar con Mito de forma visual sobre cualquier conjunto de datos se incluye la unión, el filtrado, la ordenación, la visualización, el uso de fórmulas y la creación de tablas resumen.

💣Instalación de Mito

Para instalar Mito es necesario tener Python 3.6 o posterior y ejecutar en la terminal los siguientes comandos:

`python -m pip install mitoinstaller`

`python -m mitoinstaller install`

Una vez hecho esto se puede abrir JupyterLab y abrir Mito ejecutado en una celda las siguientes instrucciones:

`import mitosheet`

`mitosheet.sheet()`

En caso de que ya se disponga de un DataFrame en memoria sobre el que se desee trabajar, solamente hay que pasarlo como parámetro a la función mitosheet.sheet(), en caso contrario se puede importar desde la propia herramienta cualquier archivo.

