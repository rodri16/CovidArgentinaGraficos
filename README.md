# Covid-19 Coronavirus Argentina Graficos by RJC

En este repositorio dejo el codigo, graficos y tablas que arme durante el Covid-19 a partir de Marzo 2020 en Argentina.

-----------
Todos los dias actualizo los graficos que se pueden ver directamente aca...

Tasas diarias en distintos graficos por separado con la media de 7 dias en negro
![Ejemplo Grafico con la Tasa Diaria sublplot](/Graficos/Diciembre/TasaDiaria_MA_17Dec.png)

-----------
TOTALES Contagios, Muertos, recuperados y pruebas diagnósticas (tests)
![Ejemplo Grafico del total](/Graficos/Diciembre/Contagios_tot_17Dec.png)

-----------
Total de pruebas diagnósticas (tests) diarias
![Ejemplo tests diarios](/Graficos/Diciembre/TestDiarioBar_17Dec.png)

-----------
Relacion entre Tests y positivos, el porcentaje de testeados que es positivo.
![Ejemplo relacion tests y positivos](/Graficos/Diciembre/Tasa_Cont_Test17Dec.png)

-----------
Estos son ejemplos de graficos de tasa diaria, totales, tests, etc, pero hay muchos otros en /Graficos.

Del reporte oficial del gobierno que publica periodicamente, saco los contagios y muertos diarios del reporte Vespertino. Del Matutino agarro los tests que hacen y los recuperados. Desde OCtubre se publica un reporte al dia.
Con estos 4 datos armo mi base de datos "Covid20_Arg.txt" con los datos separados por comas. (csv)

Despues con Python armo un notebook "Covid20_Arg_Python_notebook.ipynb" donde saco los graficos y tablas.

En la carpeta Graficos encuentran todos los graficos... muchos, por dia unos 5/7.
En la carpeta Reportes gobiernos, eso, los reportes del gobierno
En la carpeta csv_datos_completos, las tablas csv que fui armando dia a dia

## Datos
Algunas veces el reporte de muertos esta una parte en el matutino y otra en el vespertino, es como que toman una franja de 14 hs y reportan los muertos desde las 9 a las 21 y de 21 a 9hs

Los informes los saco de este link https://www.argentina.gob.ar/coronavirus/informe-diario
Dato curioso (al menos para mi): en Tierra del fuego se reportan los contagios de Malvinas y se aclara "debido a la ocupación ilegal del Reino Unido, Gran Bretaña e Irlanda del Norte no es posible contar con información propia sobre el impacto del COVID -19 en esa parte del territorio argentino"

Para obtener los datos rapido ya que los informes los publican con retardo sigo en Twitter a https://twitter.com/norabar y https://twitter.com/TotinFraire que hace un grafico buenisimo de la reparticion por provincias.

Tambien https://twitter.com/RGonzalez_PhD publica datos sobre el Covid con modelos epidemiologicos (demasiado para mi pero los graficos estan buenisimos) https://github.com/rodralez/covid-19

Tambien hay una mega Base de datos de https://twitter.com/infomapache en https://docs.google.com/spreadsheets/d/16-bnsDdmmgtSxdWbVMboIHo5FRuz76DBxsz_BbsEVWA/edit#gid=0

## Otros links interesantes

Reporte mundial https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6

Graficos de casos mundiales del Financial Times de https://twitter.com/jburnmurdoch en https://www.ft.com/coronavirus-latest

Graficos y reporte diario de Italia https://lab.gedidigital.it/gedi-visual/2020/coronavirus-i-contagi-in-italia

Otra pagina con lindos graficos de Coronavirus https://ourworldindata.org/grapher/daily-deaths-covid-19?time=2020-03-08..&country=BRA+FRA+ITA+ESP+GBR

Canal de Telegram con actualizaciones sobre el Covid en Italia https://t.me/covid19

## Always Git remember...
git add .

git commit -m "Nuevos datos" 

git push origin master


