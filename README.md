# PintaMapa · progreso de los pintores

Partidas de los jugadores de PintaMapa, guardadas por la app.

**Todo está cifrado** (AES-256-GCM) con la contraseña de cada pintor: aquí solo hay datos ilegibles.
Ni los nombres de los pintores aparecen: cada carpeta `j/<huella>/` es una huella SHA-256 de pintor + contraseña.

* `j/<huella>/partida.json`: progreso, logros, paseos, monumentos (cifrado).
* `j/<huella>/calles-AAAA-MM.json`: calles pintadas (cifrado).

Cada jugador ve su progreso en https://luzferlux77.github.io/pintamapa-app/progreso.html con su pintor y contraseña.
