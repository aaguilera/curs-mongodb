# Curs MongoDB

Profe: **Oscar Romero**

En NoSQL, a diferència de les BBDD relacionals, l'arquitectura de la plataforma és molt important. Depenent de l'arquitectura el sistema farà millor o pitjor unes coses o unes altres.

Una BD NoSQL normalment es dissenya específicament per a una aplicació, a diferència de les relacionals, en què es dissenya de manera més genèrica i les poden fer servir diferents aplicacions.

Si s'espera que l'esquema canviï molt en el temps, potser NoSQL no és la millor opció.

## Sessió 1: Introducció a MongoDB

### Big Data

Definició basada en les limitacions dels sistemes antics de Data Warehouse:

- velocitat
- volum
- varietat

S'han afegit altres "v's" tradicionals:

- variabilitat
- validesa/veracitat
- valor aportat

### Objectius NoSQL

- *schemaless*: Schema no explícit. [data structure]
- Reliability/availability [recovery]
- Scalability [distribution]
- Efficiency [distribution]

Mitjans per assolir-los:

- Bases de dades distribuides: principi divide-and-conquer. Us (i abús) del paral·lelisme.
- Models de dades flexibles: reduir l'*impedance mismatch* (*gap* entre el model orientat a objectes i el model relacional)
- Noves solucions arquitectòniques de les bases de dades. Les relacionals intentaven optimitzar l'ús del disc. Les NoSQL intenten optimitzar l'ús de memòria. Pot ser més òptim accedir a la memòria d'un altre equip dins la mateixa xarxa que al teu propi disc.

Article *SQL Databases vs. NoSQL Databases* (Michael Stonebraker, Communications of the ACM, 53(4), 2010).

## Desafiaments de les bases de dades distribuïdes

### Desafiament 1: disseny de la BD

- Fragmentació (horitzontal/vertical)


## Sessió 2

L'arquitectura NewSQL segueix el model tradicional, però redissenya els mòduls que composen l'arquitectura interna relacional tradicional.
