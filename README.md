# TorneoMongo
Actividad 1 - Diseño y operaciones CRUD en Bases de datos NoSQL

Documento de requerimientos
El torneo implementado es un torneo de futbol 5 corto, el cual cuenta solo con 3 fases ya que es un torneo relámpago donde se enfrenta un total de 8 equipos, con las siguientes características:
•	En cada partido se tendrá un total de 3 árbitros, un central y dos laterales.

•	Cada equipo solo contara con un total de 5 jugadores.

•	Cada partido tendrá un tiempo total de 60 min, repartidos 2 tiempos de 30 min cada uno y solo con 10min de intermedio.

•	La acumulación de 2 tarjetas amarillas en un mismo partido para el mismo jugador dará como resultado una tarjeta roja.

•	La acumulación de 3 tarjetas amarillas en dos partidos consecutivos para el mismo jugador dará como resultado una tarjeta roja.

•	Al inicio del partido y pasado 10 min un equipo no se presenta, este automáticamente quedará como perdedor y se dará la victoria al equipo asistente al evento.

•	Si en el partido los equipos quedan empatados, la definición del ganador será por definición de penaltis, de los cuales el equipo ganador será el que más aciertos tenga.

Equipo1---|							                      |---Equipo5

Equipo2---|	Ganador1vs2--|		|--Ganador5vs6  |---Equipo6

Equipo3---|			          Final			          |---Equipo7

Equipo4---|	Ganador3vs4--|		|--Ganador7vs8  |---Equipo8

