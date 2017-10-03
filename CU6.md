
### Resum

Un client accedeix al sistema. El client selecciona una serie i dins de la serie un episodi donat. El sistema permet al client veure l'episodi per streaming.

### Actors

Client

### Precondicions

El client fa _log in_ al sistema.

### Flux bàsic

1. El **Client** entra en la serie que vol veure.
2. El **Client** selecciona el capítol que vol veure.
3. El **Sistema** inicia el canal de streaming amb el Client.
4. El **Sistema** transmet el capítol al Client.
5. El **Client** finalitza la reproducció del capítol.
6. El **Sistema** emmagatzema que el Client ha vist el capítol.

## Flux alternatiu

3. a. El canal de streaming es talla inesperadament.
    1. El **Sistema** mostra una pantalla d'error.
4. a. El **Client** atura el capítol.
    1. El **Sistema** emmagatzema on s'ha aturat
5. a. El **Client** valora el capítol.

### Postcondicions

S'emnamgatzema la informació referent al client i la valoració que dóna del capítol.
