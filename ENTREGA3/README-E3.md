# ENTREGA_3

Repositorio sobre resultados de las ERM.

Bases de datos utilizadas para el análisis:
CEPLAN: Información para el planeamiento (https://www.ceplan.gob.pe/informacion-sobre-zonas-y-departamentos-del-peru/)

Población estimada al año 2020
Población mayor a 80 años al2020
Población con alguna discapacidad 2020
Indice de Vulnerabilidad Alimentaria
IDH 2019
Porcentaje de personas en situación de pobreza
Porcentaje de personas en situación de pobreza extrema
ONPE: Resultados ERM 2018 (https://www.onpe.gob.pe/elecciones/)

Ausentismo en la provincia de Lima
Votos inválidos en la provincia de Lima
% de otos válidos de cada organización política al Municipio Metropolitano a nivel distrital
Organización ganadora al Municipio Metropolitano a nivel distrital
Contenido del repositorio:
ceplan.xlsx: Base de datos con variables de planeamiento (independientes)
erm2018.xlsx: Base de datos con los resultados de las ERM 2018 a nivel LM (dependiente)
lima.xlsx: Base con variables socidemográficas a nivel distrital limpia
clean_data.Rmd: Rmd con el proceso de limpieza
Ver Github pages por aquí: https://alexanderbenit7.github.io/ERM2018/




### Bases de datos utilizadas para el análisis:

BANCO MUNDIAL: *Información sobre algunas de las variables independientes y la dependiente* (<https://datos.bancomundial.org/>)

- Desempleo juvenil (porcentaje del resultado total de la mano de obra de jovenes que se encuentran en la edad de 15 a 22 años)
- Inversión extranjera directa, entrada neta de capital (balanza de pagos, US$ a precios actuales)
- Crecimiento del PIB (% anual)

CIA: *Información sobre algunas de las variables independientes* (<https://www.cia.gov/the-world-factbook/references/guide-to-country-comparisons/>)

- Obesidad (orcentaje de ciudadanos que son considerados obesos en un país)
- Gastos de educación (compara el gasto publico en educacion como porcentaje al PIB)
- Infraestructura de Carreteras (kilometros de Carreteras pavimentadas y no pavimentadas y las suma)

### Contenido del repositorio:

- *desempleoBM.csv*: Base de datos con la variable de desempleo juvenil (dependiente)
- *erm2018.xlsx*: Base de datos con las variables independientes escogidas: d
  - inverex.csv
  - *PBI.csv*
  - *ObesidadCIA.csv*
  - *GastosEdu.csv*
  - *RoadW.csv*

- *dataunificada.csv*: Base con variables independientes escogidas a nivel mundial limpia
- *DATALIMPIA.Rmd*: Rmd con el proceso de limpieza


Ver Github pages por aquí: [luccemhu.github.io](https://luccemhu.github.io/)

# LIMPIEZA
  - 5 variables independientes 
  - 1 variable dependiente
  
  
  
  
  
  
  
  
  
  
  
  
  
  
En este repositorio se encuentran los archivos de la unificacion de las variables en una sola data, su exportacion y también el avance del trabajo final a traves de una regresion lineal:







