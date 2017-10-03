
### Resum

El client, després de veure un episodi, pot donar-li una valoració de l'1 al 5 en funció de si els ha agradat o no.

### Actors

Client

### Precondicions

El client ha finalitzat la reproducció d'un episodi.

### Flux Bàsic

1. El **Sistema** comprova que el client ha acabat de visualitzar un capítol i demana la seva valoració.
2. El **Sistema** es guarda l'identificador de l'usuari.
3. El **Client** dóna la seva valoració de l'episodi amb un nombre de l'1 al 5.
4. El **Sistema** publica la valoració de l'usuari juntament amb el seu identificador associat.

### Flux Alternatiu

1. a. El **Client** decideix no valorar el capítol.
	1. El **Sistema** dona a l'usuari les opcions de sortir o veure un altre capitol.

### Postcondicions

S'emmagatzema la valoració del capítol realitzada pel client.