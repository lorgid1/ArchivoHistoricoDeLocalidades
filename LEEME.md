# AHL

Repositorio para el análisis del Archivo Histórico de Localidades del Instituto Nacional de Estadística y Geografía (INEGI). La fuente de datos contiene 4 tablas:
* Habitantes – Con información de población para cada localidad.
* Movimientos – Con información de modificaciones administrativas.
* Res_hist – Donde se encuentra una lista de bibliografía histórica para cada localidad.
* Maestro – Con información cartográfica del propio INEGI.
 
La información principal del set se encuentra en la tabla de habitantes. Es ahí donde esta el dato de población, muchas veces dividido en hombres y mujeres. Hay vacíos de información para algunas comunidades en la tabla de habitantes y tienen su porque en la tabla de Movimientos. Sin trabajar la información contenida en movimientos, el set de datos no podrá desarrollarse en todo su potencial. Movimientos es el interés principal de este repositorio, dentro de la columna ORI_MODIF se encuentra la respuesta a los vacíos temporales de la tabla Habitantes.
 
El proyecto está dividido en varios archivos Jupyter Notebooks. Cada archivo tiene una versión en español y otra en inglés. Las versiones en este último lenguaje tienen como terminación “_EN”. Los archivos que contiene el proyecto son los siguientes:
* unir_csvs_ahl.ipynb
>> En el archivo se hace una exploración inicial de las columnas presentes y se unen los registros en un solos CSV con todos los datos.
* analisis_habitantes.ipynb
>> Libreta donde se analizan el .csv con información de habitantes unido de todos los registros.
* analisis_movimientos.ipynb
>> Libreta donde se analizan el .csv con información de movimientos administrativos de las localidades.
