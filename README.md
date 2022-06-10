# madriz-geocanciones

Un repo colaborativo donde poder añadir geoposicionar canciones relacionadas con Madrid

Por ejemplo:

- "La Puerta de Alcalá" de Ana Belén. Busco las coordenadas de la Puerta de Alcalá, por ejemplo buscandolo
en Google Maps u OpenStreetMap y copio las coordenadas de la url

https://www.google.com/maps/place/Puerta+de+Alcal%C3%A1/@40.419992,-3.6909257,17z/data=!3m1!4b1!4m5!3m4!1s0xd42289a4a865227:0x98278b3a144a86f1!8m2!3d40.419992!4d-3.688737

la latitud es 40.419992 y la longitud es-3.6909257

- Haces un fork del proyecto (boton arriba a la derecha del interface de Github) y eso te crea un repo igual a este pero con tu usuario.

- En tu repo editas el fichero `lista.csv`  . Puedes usar el mismo editor que viene en github

Añades una linea

`La Puerta de Alcalá;Ana Belén;40.419992;-3.6909257; https://open.spotify.com/track/29opVIw8I1BOZntEn3Un2I`

- Nombre de la canción ; Autor; Latitud ; Longitud; enlace a la canción

- Vamos a usar el punto y coma como separador porque hay títulos que usan la coma pero no creo que haya ninguno que use el punto y coma

- Preferiblemente en enlace a la canción será de Spotify al menos por ahora. *Recuerda quitar el código de rastero que añade por defecto al final*)

- Creas una PR (pull request) hacia este repositorio para que se mergee junto con los cambios de la demás gente


Crea tantas entradas como quieras