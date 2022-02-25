# UML: pràctica 1

Les vostres respostes, aquí.


#### Pregunta 1:
#### Què és un diagrama de classes?
→ El diagrama de clases es una eina que serveix per a comunicar el disseny d’un programa orientat a objectes permetent-los modelar les seves classes, atributs, operacions i relacions entre les entitats. ← 


#### Pregunta 2:
#### Per a què serveix un diagrama de classes?
→ Un diagrama de classes es podria considerar com els plànols d’un sistema. Es poden utilitzar per modelar els objectes que formen part d’un sistema, mostrar les relacions entre els objectes, descriure que fan i els serveis que proporcionen.  ← 

#### Pregunta 3:
#### Enumera els diferents elements que formen part d'un diagrama de classe.
→ Títol de clase
     Atributs de clase
     Mètodes de clase← 

#### Pregunta 4:
#### Defineix els elements nomenats anteriorment.
→ Títol de clase: La primera secció es reserva per l’estereotip i el nom de la classe, on es defineix la categoria de la clase, un conjunt de propietats, comportament i restriccions preestablertes.
Atributs de clase: La segona secció es reserva per als atributs, on es defineix quines dades pot emmagatzemar la clase, el nom i els seus tipus.
Mètodes de clase: La tercera secció es reserva per als mètodes, on es defineix el    comportament que tindrà la clase, el nom i els seus paràmetres.← 

#### Pregunta 5:
#### En UML, com es representa una classe?
→ Una classe es representa com una capça dividida en tres seccions. Dintre d’aquesta es troba la primera secció reservada per l’estereotip i el nom de la classe. Sota d’aquesta es troba la segona secció que esta destinada per als atributs i finalment la tercera secció reservada per als mètodes. ← 

#### Pregunta 6:
#### Completa el següent rectangle enumerant i explicant que conté cada divisió. 
Afegeix un exemple.


                ---------------------------
                |       +Usuari           |
                |------------------------ |
                | -userld: string         |   
                | -password: string       |
                | -loginStatus: string    |
                | -registerDate: date     |
                |------------------------ |
                | +verifyLogin(): bool    |
                |--------------------------


 → Secció superior: Conté el nom de la classe. Aquesta secció sempre és necessària, ja sigui l’estereotip o d'un objecte.
Secció central: Conté els atributs de la classe. Aquesta secció es fa servir  per descriure qualitats de la classe. Això només cal quan es  descriu una instància específica d'una classe.
Secció inferior: Inclou els metodes). Això està organitzat en un format de llista. Cada operació requereix la seva línia. Les operacions descriuen com una classe pot interactuar amb les dades.
 ← 
#### Pregunta 7:
#### Els atributs i mètodes d'un diagrama de classes poden ser de quatre tipus. Enumera i explica cadascun.
→  
Visibilitat pública: Visible per tots els objectes. Es representa amb +.
Visibilitat protegida: Visible només per l'objecte i els descendents. Es representa amb #.
Visibilitat privada: Visible només per l'objecte. Es representa amb -.
Visibilitat predeterminada:  Segons com estigui establert es podra o no veure. Es representa amb ~.
← 
#### Pregunta 8:
#### Quin símbol representa a cada estat?
→  Public: +
Predeterminat:  ~
Protected: #
Private: -    ← 

#### Pregunta 9:
#### D’aquests quatre tipus, sabries dir quin es comporta diferent entre Java i C#?
→ Protected: #  ←
 
#### Pregunta 10:
#### D’aquest quatre tipus, sabries dir quin és exclusiu de Java? Quin seria el seu equivalent a C#?
→ El package (predeterminat) es exclusiu de Java
El using es exclusiu de C# ← 
