# Laboratoria-Proy2
 En este proyecto, exploramos este aspecto del análisis de datos, destacando cómo ayuda a mejorar la comprensión de los fenómenos, respaldar la investigación y tomar decisiones informadas.
## Análisis de Éxito Musical en Spotify
###  Objetivo:
  Analizar las características de las canciones y su relación con el éxito medido en términos de streams en Spotify, así como comparar el comportamiento de las canciones en otras plataformas de música como Deezer y Apple Music. Este análisis busca identificar patrones y factores que puedan influir en la popularidad de las canciones.
### Hipótesis:
- Las canciones con un mayor BPM tienen más éxito en términos de streams en Spotify.
- Las canciones más populares en el ranking de Spotify también tienen un comportamiento similar en otras plataformas como Deezer y Apple Music.
- La presencia de una canción en un mayor número de playlists se relaciona con un mayor número de streams.
- Los artistas con un mayor número de canciones en Spotify tienen más streams.
- Las características de la canción (danceability, valence, energy, etc.) influyen en el éxito en términos de streams en Spotify.
#### Herramientas Utilizadas
- Big Query
- Power BI
- Python.
  - Bibliotecas de Python: pandas, numpy, scipy, matplotlib, seaborn.
## Metodología
### Preparación de los Datos
- Detección y manejo de valores nulos: Se eliminaron filas con datos faltantes en variables críticas.
- Normalización y escalado: Las variables numéricas se normalizaron para tener un rango uniforme.
- Codificación de variables categóricas: Las variables categóricas como el nombre del artista y género se codificaron.
- Agregación de datos: Los datos se agregaron por año y mes para analizar tendencias temporales.
- Integración de múltiples fuentes: Los datos de Spotify se cruzaron con los datos de Deezer y Apple Music para enriquecer las métricas de popularidad.
## Análisis de Datos
- Resumen Estadístico: Se calcularon medias, medianas, desviaciones estándar y distribuciones para todas las variables.
- Visualización de Datos: Se utilizaron histogramas y gráficos de dispersión para visualizar la distribución de las características musicales y los streams.
##### Hipótesis 1: Las canciones con un mayor BPM tienen más éxito en términos de streams en Spotify
Correlación: La correlación entre streams y BPM es baja (0.062), sugiriendo una relación débil.
##### Hipótesis 2: Las canciones más populares en el ranking de Spotify también tienen un comportamiento similar en otras plataformas como Deezer y Apple Music
Correlación entre plataformas:
Spotify y Deezer: 0.605.
Spotify y Apple Music: 0.616.
Deezer y Apple Music: 0.345.
Conclusión: Existe una correlación moderada entre las posiciones en los rankings de Spotify y Deezer, y entre Spotify y Apple Music, sugiriendo que las canciones populares tienden a serlo en múltiples plataformas.
##### Hipótesis 3: La presencia de una canción en un mayor número de playlists se relaciona con un mayor número de streams
Correlación: La correlación entre la presencia en playlists y los streams es de 0.684, sugiriendo una relación significativa.
##### Hipótesis 4: Los artistas con un mayor número de canciones en Spotify tienen más streams
Correlación: La correlación entre la presencia en playlists y los streams es moderadamente alta (0.685), sugiriendo una relación significativa.
##### Hipótesis 5: Las características de la canción influyen en el éxito en términos de streams en Spotify
Correlaciones:
BPM: 0.062
Danceability: 0.078
Valence: 0.029
Energy: -0.014
Acousticness: -0.093
Instrumentalness: -0.046
Liveness: -0.057
Speechiness: -0.008
Conclusión: Las características musicales como danceability, valence, y energy tienen una relación débil con el número de streams, indicando que aunque influyen, no son los únicos factores determinantes del éxito de una canción.
## Conclusiones:
El BPM tiene una influencia limitada en el éxito de una canción en términos de streams.
Las canciones populares en Spotify tienden a ser populares en Deezer y Apple Music.
Las características musicales como danceability, valence y energy influyen en la popularidad de las canciones, pero no son los únicos factores.
## Recomendaciones:
- Considerar estrategias de promoción en múltiples plataformas musicales, ya que existe una correlación entre el desempeño en Spotify y otras plataformas.
- Fomentar la inclusión de canciones en un mayor número de playlists para aumentar su exposición y potencialmente sus streams.
- Continuar investigando otros factores y características que puedan influir en el éxito de una canción, como las colaboraciones y el género musical.
