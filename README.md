# TrabajoE2

Integrantes:

1. Gianfranco Polar (20200841)
2. Sebastian Calero (20190100)
3. Alexander Salazar (20203899) 


### Selección del tema:

El tema a tratar es la desigualdad del ingreso de cada país. Nuestra variable dependiente es el coeficiente de GINI, el cual mide la desigualdad económica en la distribución del ingreso familiar.
El coeficiente de Gini fue elegido debido a que permite conocer de qué manera se distribuyen los ingresos entre los habitantes de un país. Mientras más alto sea el
coeficiente, mayor desigualdad se presentará.

Base de datos: CIA (Gini.coeff)

### Variables Independientes:

### Gianfranco Polar

1. Población urbana
      - Base de datos: Banco Mundial (data_gianfranco)
      - Justificación: Permite conocer si el fenómeno de la desigualdad, que es más frecuente en las ciudades, se extrapola a nivel país, según la distribución urbana o rural de su población
2. Exportaciones de metales y minerales
      - Base de datos: Banco Mundial (data_gianfranco)
      - Justificación: Esta variable permite conocer si se presenta mayor o menor desigualdad en países con economías basadas en la exportación de bienes y servicios, es decir, aquellas más modernizadas, en contraposición a las basadas en exportación de materias primas. Según González Oquendo (2009), siguiendo la teoría de la maldición de los recursos, la dependencia económica en la exportación de un commodity deteriora la calidad de vida de la población "a través del deterioro de la capacidad de absorción de la fuerza de trabajo e incrementa la desigualdad en la distribución tanto de los ingresos como de los activos".
3. Tasa de matrícula escolar
      - Base de datos: Banco Mundial (data_gianfranco)
      - Justificación: Permite conocer si hay una relación entre la tasa de matrícula escolar y los niveles de desigualdad en el ingreso. 

### Sebastian Calero

1. Gasto en investigación y desarrollo
      - Base de datos: Banco mundial (gasto_investigacion)
      - Justificación: Esta variable nos permite saber si la cantidad de dinero invertido en investigación y desarrollo inicide en la desigualdad de ingresos en un país con respecto a otro. 
2. Fuerza Laboral
      - Base de datos: CIA (fuerza_laboral)
      - Justificación: Cada estado presenta una cantidad de fuerza laboral medida en cantidad de personas que trabajan legalmente y pagan impuestos. A partir de ello, la cantidad de fuerza laboral de un país con respecto a otro nos lleva a una diferencia en la distribución de ingresos de cada país.
3. Tasa de mortalidad en un año (por cada 1.000 personas)
      - Base de datos: Banco Mundial (tasa_mortalidad)
      - Justificación: La tasa de mortalidad de un Estado con respecto a otro puede variar dependiendo de diversos factores (salud, calidad de vida, seguridad ciudadana, etc). Factor que afecta directamente la distribución de ingresos, ya que a una alta tasa de mortalidad significa que existe menos población capacitada para generar ingresos; por el contrario, si existe una menor tasa de mortalidad existirá mayor cantidad de gente que pueda generar más ingresos. 
### Alexander Salazar 

(Data_conjunta_Alex)

1. Gasto público en educación, total (% del gasto del gobierno)
      - Base de datos: Banco Mundial (Education_expenditure)
      - Justificación: Cada país invierte una cantidad de dinero para la educación, entonces, podríamos explicar si esto impacta en la percepción de ingresos de un Estado que invierte mayor cantidad de dinero en educación en comparación con otro Estado que invierte menos. Esperamos una relación lineal por la cual a mayor invertimiento en eduación de un país, menor desigualdad pues, de acuerdo con Daniele Checci (2001), mayores posibilidades de educarse para la población y una mayor calidad de la misma implican mayores oportunidades laborales y, por tanto, una menor desigualdad en el ingreso.
2. Desempleo, total (% de la población activa total). 
      - Base de datos: Banco Mundial (Unemployment_rate)
      - Justificación: Nos ayudará a responder si las tasas de desempleo alto impacta de manera negativa en el índice de ingresos de un país, o si las tasas de desempleo bajo impactan de manera positiva el índice de ingresos en un país.
3. Indice de democracia. De acuerdo con Andrew Glyn (1995) las habilidades de los trabajadores incidirían en el nivel de empleados y, consecuentemente, en la desigualdad económica. De ello se desprende que a mayor tasa de desempleo en un país se espera un mayor índice de Gini.
      - Base de datos: The Economist Intelligence Unit (Demo_index)
      - Justificación: Varios autores han considerado la posible relación entre la democracia y la desigualdad económica, esperando en muchos casos encontrar una relación inversa en la que a un mayor índice de democracia corresponde una menor desigualdad, expresada por el coeficiente de Gini. Por ejemplo, autores como VlaicuSin, R.(2020) han señalado como instituciones democráticas fuertes posbilitan la reducción de la desigualdad económica y como, por ejemplo, la participación electoral contribuye a la redistribbución del ingreso, aunque ciertamente existe un sesgo de votación a considerar por el cual los más pobres tienden a no acudir a votar, lo que lleva a que la demanda sea finalmente débil. Así, aun cuando pareciera haber una correlación simple, existen más aristas que indicarían lo contrario. Por una parte, el proyecto aquí presente se circusncribe al 2020, año de mayor incidencia de la pandemia de la Covid-19, la cual ha limitado los avances en materia de reducción de la desigualdad. Por otra parte, Acemoglu, D. y otros (2015) identifican que hay evidencia consistente sobre el efecto de la democracia en la desigualdad, especificamente en el coeficiente Gini, porque la democracia puede encontrarse capturada o porque atiende a intereses de la clase media. Por todo esto, consideramos que los países con un mayor índice de democracia no necesariamente tendrán una menor desigualdad en el ingreso promedio. 
