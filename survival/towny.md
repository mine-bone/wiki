---
authors:
  - name: fpalomo
    link: https://www.fpalomo.com
categories:
  - survival
---
# Empezar en Towny
## ¿Que es Towny?
Towny es un complemento que sirve para organizar y proteger territorios. Permite a los jugadores crear ciudades y invitar a otras personas a vivir en ellas. Cada ciudad tiene un dueño, llamado alcalde, y los demás integrantes se conocen como residentes.

Además, varias ciudades pueden unirse para formar una nación, que funciona como una alianza política. Las naciones pueden enfrentarse en guerras contra otras naciones y ofrecen distintos beneficios a las ciudades que las integran.

## Como crear una ciudad
Para crear una nueva ciudad, escribe el comando `/t new <nombre de la ciudad>`. Esto creará una ciudad en el chunk en el que estás, este chunk será el spawn de tu ciudad (puedes cambiarlo más adelante).

Puedes ver información sobre tu ciudad usando el comando `/t` y puedes ver información sobre otra ciudad usando el comando `/t <nombre de la ciudad>`. Este comando muestra la siguiente información:
- Anuncio de la ciudad (Mensaje configurable pr el alcalde o sus ayudantes)
- Fecha de creación
- Número de residentes junto con su rango en la ciudad
- Tamaño (Número de chunks protegidos)
- Cantidad de dinero en el banco de la ciudad
- Cantidad de impuestos (Los impuestos se cobran a los residentes para ayudar a mantener la ciudad)
- Coste de mantenimiento de la ciudad

## Como unirse a una ciudad
Si en lugar de crear tu propia ciudad prefieres unirte a una ya existente, puedes ver todas las ciudades que han creado otras personas usando `/t list`, tendrás que solicitar a su alcalde que te invite.

## Invitar jugadores a una ciudad
Si eres el alcalde de una ciudad o uno de sus ayudantes, puedes usar el comando `/t add <jugador>` para invitar a un jugador a tu ciudad.

## Reclamar territorio
Antes de reclamar nuevos chunks, debes tener en cuenta que tu ciudad tiene un límite de la cantidad de chunks que puedes reclamar al mismo tiempo, cada residente que se una a tu ciudad añade 8 chunks adicionales al límite. Para reclamar un nuevo chunk puedes usar el comando `/t claim` (debe estar junto a un chunk que ya sea parte de tu ciudad), cada chunk que reclames restará 25 huesitos al banco de tu ciudad.

Puedes visualizar los límites de cada chunk pulsando `F3 + G` o usando el comando `/resident toggle constantplotborder`

### Outposts
Si necesitas reclamar un chunk lejos de tu ciudad, puedes hacerlo por medio de un outpost, para reclamar uno usa el comando `/t claim outpost`, para añadir terreno a un outpost existente puedes hacerlo con `/t claim`

## Costes de mantenimiento
Las ciudades y naciones tienen un coste de mantenimiento asociado, esta cantidad de huesitos se cobrará cada 24h del banco de la ciudad o nacion. Si una ciudad o nacion se queda sin dinero, esta se eliminará.

Puedes ingresar dinero en el banco de tu ciudad usando `/t deposit <cantidad>`

## Regeneración automática de ciudades
Cuando una ciudad se elimina, el terreno reclamado quedará desprotegido y comenzará a regenerarse automáticamente, **todo lo que haya construido se irá destruyendo lentamente**. Se puede detener este mecanismo con tan solo volver a reclamar el territorio de la ciudad.