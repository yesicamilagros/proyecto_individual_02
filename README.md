# README

<h1 align="center"> implicancias en los accesos a una red </h1>

<p align ="center" width="100%">
    <img width="60%" src="image\intrnet.jpg">
</p>

*[Índice](#índice)

*[Descripción del proyecto](#descripción-del-proyecto)

*[Características de la aplicación y demostración](#Características-de-la-aplicación-y-demostración)

*[Acceso al proyecto](#acceso-proyecto)

*[Tecnologías utilizadas](#tecnologías-utilizadas)


*[Personas-Desarrolladores del Proyecto](#personas-desarrolladores)


*[Conclusión](#conclusión)

# descripción-del-proyecto
muy a menudo tenemos la necesidad de representar nuestro conjunto de datos en un diagrama o un dibujo representativo ,centrarse mas en el analisis , pues el proceso de EDA precede al modelamiento, se formula supuestos o hipotesis .este proyecto esta involucrado en encontrar objetos bajo analisis : las implicancias en los accesos a un internet fija , medicion de aumento de accesos segun un tipo de tecnologia que se ofrezca,el aumento de ingresos trimestrales de los operadores que brindan el servicio de internet,  medicion de aumento de accesos segun la velocidad de bajada adquirida. Y dar informe sobre como se comportan estas metricas , bajo que ambiente se esta considerando las mediciones .

# Características-de-la-aplicación-y-demostración

- primero analice los primeros dataset donde se especifica el numero de accesos al servicio de internet por cada 100 hogares por provincia y el numero de accesos al servicio de internet por cada 100 habitantes. numero de accesos al servicio de internet por cada 100 hogares por trimestre tiende a ser una distribucion normal mientras que numero de accesos al servicio de internet por cada 100 hogares por provincia  es sesgada
y existen anomalias (datos atipicos) , desde el primer trimestre del año 2014 hasta el tercer trimestre del año 2022 el numero de accesos al servicio de internet por cada 100 hogares crecio progresivamente y en provincia el mayor numero de accesos a internet lo tiene capital federal


<p align ="center" width="100%">
    <img width="60%" src="image\newplot.png">
</p>
   
- las variables numero de accesos al servicio de internet por cada 100 hogares por trimestre y numero de accesos al servicio de internet por cada 100 habitantes estan correlacionadas puesto que tiene una relacion lineal entre las dos variables con una pendiente positiva y una linealidad muy significativa. corroborando en la matriz de correlacion ( coeficiente de correlacion =1).

 <p align ="center" width="100%">
    <img width="60%" src="image\newplot (1).png">
</p>

- respecto al tipo de tecnologia ,el numero maximo de accesos a internet fijo por tipo de tecnologia esta en el tipo fibra optica , mientras que el numero minimo de accesos a internet fijo por tipo de tecnologia esta en otros tecnologias. y entre los tipos de tecnologia , ADSL tiene una mayor dispersion entre sus datos.

# personas-desarrolladores

 - Yesica Milagros Leon Ccahuana


# acceso-proyecto
 
  - link de notebook completo: https://colab.research.google.com/drive/1aSKk7TCx8O7mfnI9c6HonD-z__hhr-eo?usp=sharing
  - link de dashboard del proyecto : https://visualis.onrender.com/visualizciones

# tecnologías-utilizadas

    - ploty
    - pandas 
    - matplotlib.pyplot 
    - seaborn 
    - numpy 
    - plotly.express 

# conclusión
- se puede  usar una de la dos variables de acceso por hogar o acceso por cada 100 habitantes en trimestre. en este caso analizando sus distribuciones estadisticos optamos por elegir acceso por cada 100 hogares en trimestre puesto que tiene una mejor distribucion en cuanto a dispersion . mientra que acceso por cada 100 hogares en provincia presenta datos atipicos 

- se puede inferir de la descripcion estadistica el numero maximo de accesos a internet fijo por tipo de tecnologia esta en el tipo fibra optica , mientras que el numero minimo de accesos a internet fijo por tipo de tecnologia esta en otros. y entre los tipos de tecnologia , ADSL tiene una mayor dispersion entre sus datos.

- se puede inferir de la descripcion estadistica el numero maximo de accesos a internet fijo por tipo de tecnologia esta en el tipo fibra optica , mientras que el numero minimo de accesos a internet fijo por tipo de tecnologia esta en otros. y entre los tipos de tecnologia , ADSL tiene una mayor dispersion entre sus datos. veamos las distribuciones y diagramas

- segun ello en 2022 la tecnologia ADSL tuvo mayor numero de accesos en la provincia de buenos aires y menor numero de accesos en la provincia de san luis, veamos sobre el numero de accesos por provincia y año en este tipo de tecnologia

- el numero de acessos en total en promedio por provincia y año considerando todos los tipos de tecnologia de acceso a internet fijo .nuevamente destaca buenos aires con la mayor cantidad de acessos y san luis con la minima cantidad

- se puede inferir el maximo numero de acceso a internet fijo por velocidad de bajada esta entre 6 y 10 mbps , mientras que el minimo numero de acceso esta en 512 kbps 

- en ingresos en miles de pesos el maximo ingreso es alrededor 67 mil en pesos y el menor registrado es mas de 2 mil en pesos en los operadores de servicio , sin ninguna anomalia.
