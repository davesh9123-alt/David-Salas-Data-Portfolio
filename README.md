# David Salas - Portfolio de proyectos de Data Analytics

English:
Welcome to my Data Analysis Portfolio! This repository showcases my skills and experience in the field of data analysis. Here, you will find a collection of projects and analyses that demonstrate my ability to extract insights and make data-driven decisions.

Español:
¡Bienvenido/a a mi portafolio de análisis de datos! Este repositorio muestra mis habilidades y experiencia en el campo del análisis de datos. Aquí encontrarás una colección de proyectos y análisis que demuestran mi capacidad para extraer información valiosa y tomar decisiones basadas en datos.

## Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Postgresql](https://img.shields.io/badge/PostgreSQL-4169E1.svg?style=for-the-badge&logo=PostgreSQL&logoColor=white)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-%2334A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B.svg?style=for-the-badge&logo=Streamlit&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7.svg?style=for-the-badge&logo=Render&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/github_copilot-8957E5?style=for-the-badge&logo=github-copilot&logoColor=white)
![Google Gemini](https://img.shields.io/badge/google%20gemini-8E75B2?style=for-the-badge&logo=google%20gemini&logoColor=white)


## Table of Contents

- [Proyecto: Nuevo embudo de pago - Analisis de pruebas A/B](https://github.com/davesh9123-alt/S16_Analisis_test_AB_embudo_eventos)
- [Proyecto: Estrategia de Retencion para Model Fitness](https://github.com/davesh9123-alt/S14_Analisis_Retencion_Gimnasio)
- [Proyecto: Analisis basado en eventos y test A/A/B](https://github.com/davesh9123-alt/S12_Analisis_Eventos_Embudo_Test_AAB)
- [Proyecto: Analisis de Resultados de Prueba A/B](https://github.com/davesh9123-alt/S11_Analisis_Test_AB_Online_Store)
- [Proyecto: Analitica de Marketing en Showz (Analisis de Cohortes)](https://github.com/davesh9123-alt/S10_Analitica_Marketing_Showz_Cohortes)
- [Proyecto: ICE Games Sales - ¿Qué juegos son más exitosos?](https://github.com/davesh9123-alt/ICE_games_sales_2016)


## [Proyecto: Nuevo embudo de pago - Analisis de pruebas A/B](https://github.com/davesh9123-alt/S16_Analisis_test_AB_embudo_eventos)

Una tarea analítica para una tienda en línea internacional. Nuestros predecesores no consiguieron completarla: lanzaron una prueba A/B y luego abandonaron (para iniciar una granja de sandías en Brasil). Solo nos dejaron las especificaciones técnicas y los resultados de las pruebas.

**Descripción técnica**

- Nombre de la prueba: `recommender_system_test`
- Grupos: А (control), B (nuevo embudo de pago)
- Fecha de lanzamiento: 2020-12-07
- Fecha en la que dejaron de aceptar nuevos usuarios: 2020-12-21
- Fecha de finalización: 2021-01-01
- Audiencia: 15% de los nuevos usuarios de la región de la UE
- Número previsto de participantes de la prueba: 6 000

**Propósito de la prueba**: probar cambios relacionados con la introducción de un sistema de recomendaciones mejorado.

**Resultado esperado**: dentro de los 14 días posteriores a la inscripción, los usuarios mostrarán una mejor conversión en vistas de la página del producto (el evento `product_page`), instancias de agregar artículos al carrito de compras (`product_cart`) y compras (`purchase`). En cada etapa del embudo `product_page → product_cart → purchase`, habrá **al menos un 10% de aumento**.


## Estudiar la conversion en diferentes etapas del embudo

Las conversiones de ambos grupos son muy similares, sin embargo la conversion de grupo A (el grupo de control) es ligaramente mejor con un 34.07% de conversion en la etapa de compra, mientras que el grupo B se queda un poco por debajo con 32.37% de conversion. Estos resultados no son muy favorables para el nuevo embudo de pago.

<img width="1247" height="699" alt="embudo_gruposAB_output" src="https://github.com/user-attachments/assets/3c7e99f6-1876-4300-b8dc-04dfe25debae" />

<img width="1238" height="699" alt="Conversion_gruposAB_output" src="https://github.com/user-attachments/assets/d1b6f52b-b9cb-4b1f-ba86-54b2509bbc95" />


## [Proyecto: Estrategia de Retencion para Model Fitness](https://github.com/davesh9123-alt/S14_Analisis_Retencion_Gimnasio)

En este proyecto trabajamos con la cadena de gimnasios Model Fitness. Nos brindaron datos de sus clientes con la finalidad de analizar el comportamiento de sus usuarios y desarrollar una estrategia de retencion. Es decir, nos pidieron analizar los datos para crear un estrategia para evitar la cancelacion de las suscripciones.

Los indicadores de pérdida varían de un campo a otro. Si un usuario o una usuaria compra en una tienda en línea con poca frecuencia, pero con regularidad, no se puede decir que ha huido. Pero si durante dos semanas no ha abierto un canal que se actualiza a diario, es motivo de preocupación: es posible que tu seguidor o seguidor/a se haya aburrido y te haya abandonado.

En el caso de un gimnasio, tiene sentido decir que un/a cliente se ha ido si no viene durante un mes. Por supuesto, es posible que estén en Cancún y retomen sus visitas cuando regresen, pero ese no es un caso típico. Por lo general, si un/a cliente se une, viene varias veces y luego desaparece, es poco probable que regrese.


## Matriz de correlacion entre caracteristicas

La matriz de correlacion nos brinda numero mas exacto de la relacion entre la cancelacion (variable objetivo) y las demas caracteristicas. Por ejemplo podemos observar que las caracteristicas de genero y telefono no tienen ninguna correlacion directa con la cancelacion por lo que facilmente podemos ignorar estas caracteristicas. Por otro lado, las caracteristicas con mayor relacion son lifetime (tiempo), avg_class_frequency_current_month (la frecuencia media de visitas durante el mes en curso) y la edad. El periodo de contrato o suscripcion tambien tiene una correlacion a tomar en cuenta.

<img width="1127" height="990" alt="matriz_correlacion_gym_output" src="https://github.com/user-attachments/assets/78271dbb-d515-45ad-b10e-139511c88285" />


## [Proyecto: Analisis basado en eventos y test A/A/B](https://github.com/davesh9123-alt/S12_Analisis_Eventos_Embudo_Test_AAB)

En este proyecto analizamos el embudo de ventas de una tienda online de productos alimenticios. Investigamos el comportamiento de los usuarios de la app de la empresa. Posteriormente analizamos los resultados de la prueba A/A/B que realizaron. La prueba consistio en cambios en el tipo de fuente para las letras de la aplicacion. Es decir, dos grupos (grupos A) se les dio la version antigua con fuentes originales y el grupo experimental (grupo B) se le dio una version con fuentes nuevas. Nuestra tarea consistio en descubrir que version tiene mejores resultados.

**Objetivos**: Descubrir que version de la aplicacion tiene mejores resultado para las ventas. Se busca al menos un 10% de mejora en las ventas con la nueva version.


## ¿Que proporcion de usuarios pasan de una etapa a la siguiente? - Enbudo de Eventos

De acuerdo a los resultados del embudo de eventos, la etapa en la que se pierden mas usuarios es de Main Screen a Offers Screen. Solo 61.9% de la etapa anterior continuan hacia la pagina de Offers. Cerca de un 40% de usuarios no pasan de la Main Screen a la etapa siguiente.

* MainScreenAppear: 7419 usuarios --> 100%
* OffersScreenAppear: 4593 usuarios --> 61.9% --> 61.9% de la cantidad de arriba
* CartScreenAppear: 3734 usuarios --> 50.3% --> 81.3 de la cantidad de arriba
* PaymentScreenSuccessful: 3539 usuarios --> 47.7% --> 94.8% de la cantidad de arriba
* Tutorial: 840 usuarios --> 11.3% --> 23.7% de la cantidad anterior

<img width="1223" height="362" alt="Screenshot_20260604164037" src="https://github.com/user-attachments/assets/437ecf68-16d3-42b2-9319-56bbad32abd9" />


## [Proyecto: Analisis de Resultados de Prueba A/B](https://github.com/davesh9123-alt/S11_Analisis_Test_AB_Online_Store)

El objetivo de este proyecto fue analizar los resultados de una prueba A/B realizada por una tienda online anonima. Se nos proporcionaros los datos de los resultados generados por las pruebas y nuestra tarea fue verificar la validez y confiabilidad de los datos, un analisis exploratorio de los resultados obtenidos por ambos grupos (A y B) y finalmente la aplicacion de pruebas de significancia estadistica para determinar con mayor rigor las diferencia entre los grupos experimentales.


## ¿Cual fue el ingreso de cada grupo por separado?

La grafica muestra como los ingresos de ambos grupos fueron muy similares los primeros 5 dias. Posteriormente los ingresos acumulados del grupo B se incrementaron un poco mas que el grupo A y a partir del dia 13 los ingresos del grupo B fueron claramente superiores que los del grupo A. Al final, los ingresos del grupo A fueron: 64554.9, mientras que los ingresos del grupo B fueron: 92840.6. Esto es (64554.9 / 92840.6) x 100 = 69.53 %, es decir que el grupo B tuvo un poco mas de 30% mas de ingresos que el grupo A.

<img width="1179" height="582" alt="Screenshot_20260604142226" src="https://github.com/user-attachments/assets/91bce844-93d7-4d6f-9ed4-e58bddc0db16" />


[Proyecto: Analitica de Marketing en Showz (Analisis de Cohortes)](https://github.com/davesh9123-alt/S10_Analitica_Marketing_Showz_Cohortes)

El objetivo de este analisis fue optimizar los gastos de Marketing de la tienda online Showz,  una de las tiendas en línea más populares y confiables a nivel mundial para coleccionistas de figuras de acción.


## Resultados del analisis de cohortes y la tasa de retencion

El mapa de calor muestra mas claramente como la retencion disminuye a lo largo de los meses siguientes a la primera visita. Hay cohortes que mantienen una retencion mas alta, pero en general disminuyen a lo largo del tiempo. Tambien podemos observar que las primeras cohortes parecen tener una mayor rentecion los primeros meses que las cohortes mas nuevas, al menos en el periodo de tiempo que examinamos. La cohorte de 2017-06 (junio 2017), es decir, la primera cohorte, es la que presenta una mayor rentencion.

<img width="1015" height="619" alt="Screenshot_20260604133835" src="https://github.com/user-attachments/assets/91f0134c-ef34-4c2e-9e54-af19a760bfd8" />


[Proyecto: ICE Games Sales - ¿Qué juegos son más exitosos?](https://github.com/davesh9123-alt/ICE_games_sales_2016)

Este análisis se centra en los factores que influyen en el éxito de los videojuegos vendidos en la tienda online de ICE. Utilizando datos de 2016 sobre reseñas de usuarios y expertos, géneros, plataformas y ventas históricas, el objetivo es identificar patrones que predigan qué juegos tendrán un buen rendimiento en 2017. El proyecto incluye la preparación de datos, el análisis exploratorio de datos y la creación de modelos para comprender la dinámica de la industria del videojuego, orientar las decisiones de inversión y las estrategias publicitarias para optimizar las promociones de videojuegos.


## Generos de videojuegos mas populares historicamente

Historicamente los generos mas populares (aquellos que suelen ser mas rentables) son los generos de Accion, Disparos y Deportes. Este tendencia se mantiene a lo largo de varias generaciones de consolas.

<img width="873" height="604" alt="genre_top_games" src="https://github.com/user-attachments/assets/b2d4de8a-e35c-4228-aacf-bdc16c4c21a1" />


## Contact me

- LinkedIn: https://www.linkedin.com/in/davidsalasherrera/
- E-mail: davidsalasherrera@outlook.com
- GitHub Page: https://davesh9123-alt.github.io/
