# Developer Center Overview

El DC está organizado por componentes y por secciones transversales como `fundamentals` que quieren explicar el marco general.

Veníamos de una documentación técnica donde todo se exponía sin ofrecer una organización. El DC quiere ofrecer esa organización a nivel general y a nivel de componente.

La intención es que cualquier persona pueda dirigirse al DC para entender cualquier aspecto del stack tecnológico de CARTO.


# Fundamentals

## Rate Limiting

- Por usuario. Subrayar que es al author.
- Por map. Explicamos que las propias HEADERS ya ofrecen el status acumulado de todas las apps.

- Sliding Time Windows
- Todos los endpoints requieren autenticación.

- Caches

- HTTP Headers para entender. Las Headers son en el contexto del user.
- Explicación de las cabeceras principales.

- Explicación del error general cuando excedes límites.

- Tips para evitar rate limited: ¿por componente?

- Blacklisting? si el abuso es persistente. ¿Deberíamos preparar un form para recibir posibles quejas de limits? Idealmente debería estar pegado a un servicio de status. El actual no es perfecto, pero es un punto de partida.

- Chart para mostrar todos los límites por recurso. Y nota sobre que cualquier cosa que no esté listada ahí tiene un default.


# Componentes

- SQL
- Maps