# useful-datasets

---

En este repositorio almaceno los conjuntos de datos que he creado durante proyectos y que creo que pueden ser de utilidad para la comunidad.

# venezuela-territorial-organization
Conjunto de tablas relacionadas de los estados, municipios y parroquias de Venezuela.

La lista de parroquias y municipios fue extraída del archivo: [Proyección de la población al 30 de junio, según entidad federal, municipios y parroquias 2000-2050](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi5pdTytvHrAhXLq1kKHdCFDHAQFjACegQIBhAB&url=http%3A%2F%2Fwww.ine.gov.ve%2Fdocumentos%2FDemografia%2FSituacionDinamica%2FProyecciones%2Fxls%2FParroquias.xls&usg=AOvVaw2CBhzw6HaH-z170nQ4WDCb) emitido por el Instituto Nacional de Estadística \(INE\). Añadí el nombre del estado al nombre del municipio para facilitar la distinción entre los múltiples municipios que poseen el mismo nombre pero pertenecen a distintos estados.

Ninguna palabra en las actividades económicas posee caracteres alfabéticos con acentos pues el sistema del SENIAT no se los coloca. Esto lo mantengo para facilitar operaciones.

# venezuela-industry-classification
Conjunto de tablas relacionadas de los sectores, industrias y actividades económicas de Venezuela.

Las actividades económicas son las definidas por el Servicio Nacional Integrado de Administración Aduanera y Tributária \(SENIAT\) en el archivo [Ayuda para la clasificación de actividad económica](http://declaraciones.seniat.gob.ve/portal/page/portal/MANEJADOR_CONTENIDO_SENIAT/03TRIBUTOS/3.0NOTICIAS_TRIBUTOS/Ayuda_Clasificacion_Actividad_Economica.xls) que además utilicé para marcar los sectores económicos.

Las industrias fueron marcadas siguiendo las reglas del Sistema de Clasificación de Industrias de Norteamérica \([NAICS](https://www.census.gov/eos/www/naics/2017NAICS/2017_NAICS_Manual.pdf)\) emitida en los Estados Unidos en el 2017.

## Características de los conjuntos de datos

* Las claves primárias de las tablas están identificadas por el prefijo "PK_"
* Las claves foráneas de las tablas están identificadas por el prefijo "FK_" 

## Características de los archivos

* Todos los caracteres alfabéticos son letras mayúsculas
* Están delimitados por punto y coma (;)
* Los registros que contengan punto y coma que no es delimitador están rodeados por comillas dobles (")
* Tienen codificación Latin-1 (ISO-8859-1)

