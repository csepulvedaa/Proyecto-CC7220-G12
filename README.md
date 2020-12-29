# Proyecto-CC7220-G14

En este repositorio se encuentran los archivos de los que consta este __proyecto__.
Se trabajó con una base de datos que califica series y peliculas de anime.
Los archivos son: 
- Proyecto_LWDD.ipynb: Notebook de Collaboratory con el script.
- anime.csv : Archivo con información de animes. Contiene la siguientes caracteristicas.  
  - anime_id: numero identificador de la serie.
  - name: el nombre del anime.
  - genre: genero(s) a los que pertenece la ser.
  - type: tipo del anime (serie de tv, pelicula, OVA, etc).
  - episodes: la cantidad de capítulos del anim.
  - rating: calificación promedio ponderado de los usuarios (usuario que clasifican mas series, tienen un voto mas poderoso).
  - members: cantidad de usuarios que evaluaron la serie en el archivo rating.csv
- rating.csv : Archivo con información de las clasificaciones de los usuarios.
  - user_id: generado para identificar usuarios de forma anonima.
  - anime_id: numero identificador de la serie. 
  - rating: calificación del usuario a la serie
- output.ttl: Archivo de salida para el script de _Collaboratory_. Contiene el grafo RDF sobre el cual hacer las consultas del proyecto.
- Querries.sparql: archivo con las consultas realizadas. 
