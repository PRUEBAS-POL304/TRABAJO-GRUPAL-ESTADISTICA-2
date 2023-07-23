ENTREGA-2
============================================================

Miembros del grupo:

 + Joel B. Hu Ccallocunto (20196510)
 
 + Jose Rios (20181496)


# Factores que explican el desempleo juvenil en el mundo, 2018

## Selección de las bases de datos

- El objetivo de esta segunda entrega es descartar las variables independientes que no influyan en la variable dependiente (`Desempleo juvenil`).

- Para ello, importaremos las bases de datos escogidas, luego procederemos con la limpieza, después unificaremos las variables en una sola data y, finalmente, realizaremos las pruebas estadísticas correspondientes con la regresión lineal múltiple. 

## En conclusión: 

1. En este caso solo nos quedaremos con las siguientes bases al realizar un regresión lineal:
    
  - Variable dependiente:
    
    - *`desempleoBM.csv`*: Desempleo de jóvenes de 15 a 22 años (BM) 

  - Variables independientes:

    - *`inverex.csv`*: Inversión extranjera directa 
    
    - *`PBI.csv`*: Crecimiento del PIB (% anual)
    
    - *`ObesidadCIA.csv`*: Obesidad (CIA)
    
    - *`GastosEdu.csv`*: Gastos en Educacion (CIA)
    
    - *`RoadW.csv`*: Infraestructura de Carreteras (CIA)
    
2. Datas descartadas debido a que no se encuentra correlacion con la variable dependiente y presentan pocos casos al realizar la unificacion de las datas:

    - *`Libertad civica`*
    
    - *`geseco.csv`*
    
    - *`tugurio.csv`*

3. La data unificada con las variables finales escogidas se encuentran en el archivo llamado `df_final.csv`
