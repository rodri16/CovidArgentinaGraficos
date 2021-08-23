# Covid-19 Coronavirus Argentina Gráficos by RJC

En este repositorio dejo el código, gráficos y tablas que arme durante el Covid-19 a partir de Marzo 2020 en Argentina.

-----------
Todos los días actualizo los gráficos que se pueden ver directamente acá...

Tasas diarias de contagios, muertos, recuperados y tests, calculo la media de 7 días que es la curva en color y en gris la variación diaria. Entre <> el valor de los últimos 7 días, Max es el valor máximo y el valor actual se ven a la derecha del gráfico.
![Ejemplo Grafico con la Tasa Diaria sublplot](/Graficos/2021/Agosto/TasaDiaria_MA_23Aug.png)

-----------
Cantidad de gente vacunada primera y segunda dosis.
![Vacunados primera y segunda dosis](/Graficos/2021/Agosto/Vacunas_23Aug.png)

-----------
TOTALES: Contagios, Muertos, recuperados y pruebas diagnósticas (tests)
![Ejemplo Grafico del total](/Graficos/2021/Agosto/Contagios_tot_23Aug.png)

-----------
Total de pruebas diagnósticas (tests) diarias
![Ejemplo tests diarios](/Graficos/2021/Agosto/TestDiarioBar_23Aug.png)

-----------
Relación entre Tests y positivos, el porcentaje de testeados que es positivo.
![Ejemplo relacion tests y positivos](/Graficos/2021/Agosto/Tasa_Cont_Test23Aug.png)

-----------
Estos son ejemplos de gráficos de tasa diaria, totales, tests, etc, pero hay muchos otros en /Graficos.

Desde Octubre se publica un reporte al día con todos los datos. Con estos armo la base de datos "Covid20_Arg.txt" con los datos separados por comas. (csv)

Despues con Python armo un notebook "Covid20_Arg_Python_notebook.ipynb" donde saco los gráficos y tablas.

En la carpeta Graficos encuentran todos los gráficos... muchos, por día unos 5/7.
En la carpeta Reportes gobiernos, eso, los reportes del gobierno
En la carpeta csv_datos_completos, las tablas csv que fui armando día a día

## Datos
Los datos se reportan una vez al día, antes dos veces al día. 

Los informes los saco de este link https://www.argentina.gob.ar/coronavirus/informe-diario
Grafana con los datos en tiempo real https://www.argentina.gob.ar/salud/coronavirus-COVID-19/sala-situacion
Vacunados en tiempo real  https://www.argentina.gob.ar/coronavirus/vacuna/aplicadas


Dato curioso (al menos para mi): en Tierra del fuego se reportan los contagios de Malvinas y se aclara "debido a la ocupación ilegal del Reino Unido, Gran Bretaña e Irlanda del Norte no es posible contar con información propia sobre el impacto del COVID -20 en esa parte del territorio argentino"

Para obtener los datos rápido ya que los informes los publican con retardo sigo en Twitter a https://twitter.com/norabar y https://twitter.com/TotinFraire que hace un gráfico buenisimo de la reparticion por provincias.

También https://twitter.com/RGonzalez_PhD publica datos sobre el Covid con modelos epidemiologicos (demasiado para mi pero los gráficos estan buenísimos) https://github.com/rodralez/covid-19

También hay una mega Base de datos de https://twitter.com/infomapache en https://docs.google.com/spreadsheets/d/16-bnsDdmmgtSxdWbVMboIHo5FRuz76DBxsz_BbsEVWA/edit#gid=0

## Otros links interesantes

Reporte mundial https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40310423467b48e9ecf6

Gráficos de casos mundiales del Financial Times de https://twitter.com/jburnmurdoch en https://www.ft.com/coronavirus-latest

Gráficos y reporte diario de Italia https://lab.gedidigital.it/gedi-visual/2020/coronavirus-i-contagi-in-italia

Otra página con lindos gráficos de Coronavirus https://ourworldindata.org/grapher/daily-deaths-covid-19?time=2020-03-08..&country=BRA+FRA+ITA+ESP+GBR

Canal de Telegram con actualizaciones sobre el Covid en Italia https://t.me/covid19

## Always Git remember...
git add .

git commit -m "Nuevos datos" 

git push origin master

## Run notebook in miniconda...

(base) C:\Users\rodri>activate rodri

(rodri) C:\Users\rodri>jupyter notebook