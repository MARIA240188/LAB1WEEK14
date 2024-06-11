# LAB1WEEK14
LAB1WEEK14
Para esta práctica de laboratorio, usaremos el conjunto de datos del Caso de Negocio de Análisis de Clientes. Este conjunto de datos se puede encontrar en files_for_labla carpeta.

En esta práctica de laboratorio veremos el archivo pdf, files_for_lab/nz_water_water_resources.pdfpero veremos las otras dos tablas, es decir. page 14 table 2y page 14 table 3.

Contexto
Como se analizó durante la última lección, estas son otras dos formas en las que Tableau lee los datos de la tabla de la página 14 en el archivo PDF.

page 14 table 2representa la mitad de la información
page 14 table 3representa la otra mitad de la información
Instrucciones
Crea una unión entre las dos tablas.
Ocultar la columna Table Name.
Limpiar los datos.
Consejos :

Verá que la información de la columna 1 del archivo PDF se divide en dos columnas diferentes cuando los datos se importaron con Tableau. Seleccione las dos columnas y luego use la opción merge mismatch fieldspara combinar esas dos columnas.

Cambie el nombre de las columnas de forma adecuada (cambie el nombre de los encabezados a años, como se indica en el PDF)

A diferencia del caso anterior, aquí mantendremos todas las fuentes excepto los totales (es decir, filtraremos el total y conservaremos el resto).

Seleccione los datos y cree un pivote como se muestra a continuación Crear pivote

Cambie el nombre de las columnas como source, yeary million cubic meters.

Como habrás notado, todavía habrá algunos valores nulos en la columna million cubic meters. Elimina esos nulos.

Convierta el tipo de años de columna al tipo Fecha.

Convierte el tipo de columna million cubic metersa números enteros.

Todavía habría algunos problemas con los nombres de las fuentes en la primera columna. Seleccione el menú desplegable de columnas y elija Alias.

Como verá en el archivo PDF, hydroelectricitydebería ser abstraction for hydroelectricity; y la generación debería ser discharge from hydroelectricity generation.
Continúe y cambie esos alias. Editando_alias
Cambie las dimensiones a medidas cuando sea necesario.
Ahora vaya a la hoja, cree un gráfico y muestre las 4 fuentes principales de generación. La trama final debería verse así. Tenga en cuenta que aquí hemos utilizado un filtro en la hoja para eliminar la columna con descarga.
