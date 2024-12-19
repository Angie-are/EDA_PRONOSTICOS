# Análisis Exploratorio de Datos de Equipos de Fútbol de LaLiga

Este proyecto tiene como objetivo realizar un análisis exploratorio de los datos de la Liga Española de Fútbol (LaLiga), específicamente sobre el rendimiento de los equipos durante la temporada 2024. A través de este análisis, se buscan patrones y relaciones entre diversas métricas de rendimiento, como goles marcados, tiros a puerta, faltas cometidas, tarjetas, y la posesión del balón.

## Tabla de Contenido

1. [Introducción](#introducción)
2. [Hipótesis](#hipótesis)
3. [Análisis Univariante](#análisis-univariante)
4. [Análisis Bivariante](#análisis-bivariante)
5. [Análisis Multivariante](#análisis-multivariante)
6. [Visualizaciones Relevantes](#visualizaciones-relevantes)
7. [Conclusiones](#conclusiones)
8. [Recomendaciones](#recomendaciones)
9. [Referencias](#referencias)

## Introducción

El objetivo de este proyecto es explorar y analizar las estadísticas de los partidos de fútbol de la temporada 2024 de LaLiga para entender mejor los factores que afectan el rendimiento de los equipos. El análisis se centrará en:

- Comparar el rendimiento de los equipos locales y visitantes.
- Identificar variables que afectan los resultados, como tiros a puerta, faltas, tarjetas y posesión.
- Explorar cómo las estadísticas predicen el éxito o fracaso de los equipos.

Los datos utilizados provienen de una base pública de resultados y estadísticas detalladas de los partidos. Esta base contiene más de 300 registros, cada uno representando un partido jugado durante la temporada, con información sobre goles, tiros, faltas, tarjetas y otras métricas.

## Hipótesis

1. **Ventaja del equipo local**: Los equipos locales tienen una mayor probabilidad de ganar debido a la ventaja de jugar en casa.
2. **Relación entre tiros a puerta y goles marcados**: Existe una correlación positiva entre la cantidad de tiros a puerta y los goles marcados.
3. **Faltas y tarjetas amarillas**: Los equipos que cometen más faltas tienden a recibir más tarjetas amarillas.
4. **Rendimiento de equipos con más goles a favor**: Los equipos con un mayor promedio de goles marcados por partido tienen más probabilidades de terminar la temporada en una posición alta de la tabla.
5. **Impacto de los corners en el resultado**: Un mayor número de corners a favor está relacionado con una mayor probabilidad de ganar el partido.
6. **Tendencia en el rendimiento por tiempo de juego**: Los equipos que anotan más goles en la segunda mitad tienen más probabilidades de ganar.
7. **Estrategias de ataque y defensiva**: Existen diferencias en el rendimiento defensivo y ofensivo de los equipos en función de su estrategia de juego.

## Análisis Univariante

En este análisis, se investigan las distribuciones de variables clave como los goles marcados por el equipo local y visitante (FTHG y FTAG), así como las probabilidades de victoria según diversas casas de apuestas. Se emplean boxplots para visualizar la dispersión de los datos y detectar valores atípicos.

- **Boxplots de goles locales y visitantes**: Visualización de la distribución de goles por equipo.
- **Probabilidades de victoria**: Comparación de las probabilidades de victoria dadas por Bet365, Pinnacle y otras casas de apuestas.

## Análisis Bivariante

Este análisis explora la relación entre las métricas de goles (local y visitante) utilizando un boxplot. Se examina cómo las distribuciones de goles se correlacionan entre equipos locales y visitantes, proporcionando información sobre el rendimiento en casa frente a fuera de casa.

## Análisis Multivariante

En este análisis se exploran las interacciones entre múltiples variables, como los goles y las probabilidades de victoria. El uso de boxplots permite identificar patrones y variabilidad en los datos, proporcionando una base para futuros modelos predictivos.

## Visualizaciones Relevantes

Se han generado diversas visualizaciones para entender mejor los datos:

1. **Boxplot de goles locales por equipo**: Muestra cómo se distribuyen los goles anotados por los equipos locales.
2. **Boxplot de goles visitantes por equipo**: Similar al anterior, pero para los equipos visitantes.
3. **Boxplot de probabilidades de victoria local y visitante**: Compara las probabilidades de que un equipo gane según las casas de apuestas.
4. **Comparación entre goles locales y goles visitantes**: Analiza la diferencia de goles entre equipos locales y visitantes.
5. **Histograma de resultados de partidos**: Muestra la frecuencia de victorias, empates y derrotas.
6. **Correlación entre goles y probabilidades de victoria**: Examina la relación entre los goles marcados y las probabilidades de victoria.

## Conclusiones

Algunos hallazgos clave incluyen:

- Los equipos locales suelen tener un mejor rendimiento, marcando más goles en casa que como visitantes.
- Existe una fuerte relación entre los tiros a puerta y los goles marcados.
- Las probabilidades de victoria ofrecidas por las casas de apuestas no siempre se alinean con los resultados reales.
- Algunos equipos, como "Valladolid", tienen un bajo rendimiento a pesar de generar muchas oportunidades de gol.

## Recomendaciones

Basado en los resultados del análisis, se sugieren las siguientes recomendaciones:

- **Mejorar la precisión de los tiros**: Los equipos deberían centrarse en mejorar la efectividad de sus tiros a puerta.
- **Analizar equipos atípicos**: Equipos como "Valladolid" deberían revisar su estrategia ofensiva.
- **Optimización defensiva**: Estudiar equipos con buen rendimiento defensivo para replicar sus tácticas.
- **Impacto de faltas y tarjetas**: Investigar cómo las sanciones afectan el rendimiento de los equipos.
- **Aprovechar goles en la segunda mitad**: Ajustar tácticas para mejorar el rendimiento en la segunda mitad de los partidos.

## Referencias

Este análisis se ha realizado utilizando herramientas como Python, Pandas, Matplotlib, Seaborn, Numpy, Statsmodels y Scikit-learn. Los datos fueron obtenidos de [Football-Data.co.uk](https://www.football-data.co.uk/), una fuente confiable de estadísticas de fútbol.


