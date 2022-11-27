# TrabajoE2

Integrantes:

1. Gianfranco Polar (20200841)
2. Sebastian Calero (20190100)
3. Alexander Salazar (20203899) 


### Selección del tema:

El tema a tratar es la desigualdad del ingreso de cada país. Nuestra variable dependiente es el coeficiente de GINI, el cual mide la desigualdad económica en la distribución del ingreso familiar.
El coeficiente de Gini fue elegido debido a que permite conocer de qué manera se distribuyen los ingresos entre los habitantes de un país. Mientras más alto sea el
coeficiente, mayor desigualdad se presentará.

### Bases de datos utilizadas para el análisis:

Base de datos utilizadas para el análisis: 

1. CIA: *Guide to Country Comparison* (https://www.cia.gov/the-world-factbook/references/guide-to-country-comparisons/)

      - Coeficiente del índice GINI-distribución del ingreso familiar (Gini.coeff.csv)
      - Fuerza Laboral (laborforce.csv)

2. Banco Mundial: *Indicators* (https://data.worldbank.org/indicator)

      - Población en aglomeraciones urbanas de más de 1 millón (% de la población total) (urban_pop.csv)
      - Exportaciones de minerales y metales (% de las exportaciones de mercancías) (export.csv)
      - Matrícula escolar, primaria y secundaria (bruta), índice de paridad de género (IPG) (school_enr.csv)
      - Madres adolescentes (% de mujeres de 15 a 19 años que han tenido hijos o están actualmente embarazadas) (embarazo.csv)
      - Tasa de mortalidad en un año (por cada 1.000 personas) (death_rate.csv)
      - Gasto público en educación, total (% del gasto del gobierno) (Education_expenditure.csv)
      - Desempleo, total (% de la población activa total) (Unemployment_rate.csv)

3. The Economist Intelligence Unit (https://country.eiu.com/All)
      - Índice de democracia al año 2020 (Demo_index)

### Justificación de las Variables Independientes:

### Gianfranco Polar

1. *Población urbana*: Permite conocer si el fenómeno de la desigualdad, que es más frecuente en las ciudades, se extrapola a nivel país, según la distribución urbana o rural de su población
2. *Exportaciones de metales y minerales*: Esta variable permite conocer si se presenta mayor o menor desigualdad en países con economías basadas en la exportación de bienes y servicios, es decir, aquellas más modernizadas, en contraposición a las basadas en exportación de materias primas. Según González Oquendo (2009), siguiendo la teoría de la maldición de los recursos, la dependencia económica en la exportación de un commodity deteriora la calidad de vida de la población "a través del deterioro de la capacidad de absorción de la fuerza de trabajo e incrementa la desigualdad en la distribución tanto de los ingresos como de los activos".
3. *Tasa de matrícula escolar*: Permite conocer si hay una relación entre la tasa de matrícula escolar y los niveles de desigualdad en el ingreso. 

### Sebastian Calero

1. *Tasa de embarazo adolescente*: Esta variable nos permite saber cómo la alta tasa de embarazo adolescente impacta de manera negativa a la distribución de ingresos en un país debido a que muchas mujeres no culminan sus estudios técnicos y/o universitarios en consecuencia de una maternidad prematura.
2. *Fuerza Laboral participativa por país*: Cada estado presenta una cantidad de fuerza laboral medida en cantidad de personas que trabajan legalmente y pagan impuestos. A partir de ello, la cantidad de fuerza laboral de un país con respecto a otro nos lleva a una diferencia en la distribución de ingresos de cada país.
3. *Tasa de mortalidad en un año (por cada 1.000 personas)*: La tasa de mortalidad de un Estado con respecto a otro puede variar dependiendo de diversos factores (salud, calidad de vida, seguridad ciudadana, etc). Factor que afecta directamente la distribución de ingresos, ya que a una alta tasa de mortalidad significa que existe menos población capacitada para generar ingresos; por el contrario, si existe una menor tasa de mortalidad existirá mayor cantidad de gente que pueda generar más ingresos. 

### Alexander Salazar 

1. *Tasa del gasto público en educación: Cada país invierte una cantidad de dinero para la educación, entonces, podríamos explicar si esto impacta en la percepción de ingresos de un Estado que invierte mayor cantidad de dinero en educación en comparación con otro Estado que invierte menos. Esperamos una relación lineal por la cual a mayor invertimiento en eduación de un país, menor desigualdad pues, de acuerdo con Daniele Checci (2001), mayores posibilidades de educarse para la población y una mayor calidad de la misma implican mayores oportunidades laborales y, por tanto, una menor desigualdad en el ingreso.
2. *Tasa de desempleo*: Nos ayudará a responder no solo si las tasas de desempleo alto impacta de manera negativa en el índice de ingresos de un país, sino si dicha relación se explica por particularidades del mercado laboral de cada país, por lo que vararía si tratamos con países desarrollados, en vías de desarrollo o subdesarrollados, o si por el contrario responde a un sistema global. Buscamos poder predecir la desigualdad económica en base a un esquema económico industrial global que desfavorecería la contratación. De acuerdo con Helpman, Itskhoki y Redding (2010), la desigualdad de ingresos está influenciada por la desigualdad salarial y el desempleo, y dichas dimensiones dependerían de las reasignaciones de trabajadores dentro y entre industrias. Estos autores indicarían que la liberalización del comercio afectaría directamente a la desigualdad de ingreso; sin embargo, dicho efecto variaría según la capacidad de los trabajadores. De acuerdo con Andrew Glyn (1995), las habilidades propias de los trabajadores justamente incidirían en el nivel de empleabilidad visible.
3. *Índice de democracia*: Varios autores han considerado la posible relación entre la democracia y la desigualdad económica, esperando en muchos casos encontrar una relación inversa en la que a un mayor índice de democracia corresponde una menor desigualdad, expresada por el coeficiente de Gini. Por ejemplo, autores como VlaicuSin, R.(2020) han señalado como instituciones democráticas fuertes posbilitan la reducción de la desigualdad económica y como, por ejemplo, la participación electoral contribuye a la redistribbución del ingreso, aunque ciertamente existe un sesgo de votación a considerar por el cual los más pobres tienden a no acudir a votar, lo que lleva a que la demanda sea finalmente débil. Así, aun cuando pareciera haber una correlación simple, existen más aristas que indicarían lo contrario. Por una parte, el proyecto aquí presente se circusncribe al 2020, año de mayor incidencia de la pandemia de la Covid-19, la cual ha limitado los avances en materia de reducción de la desigualdad. Por otra parte, Acemoglu, D. y otros (2015) identifican que hay evidencia consistente sobre el efecto de la democracia en la desigualdad, especificamente en el coeficiente Gini, porque la democracia puede encontrarse capturada o porque atiende a intereses de la clase media. Por todo esto, consideramos que los países con un mayor índice de democracia no necesariamente tendrán una menor desigualdad en el ingreso promedio. 
