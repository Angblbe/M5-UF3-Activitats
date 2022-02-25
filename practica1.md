# UML: pràctica 1

Les vostres respostes, aquí.


#### Pregunta 1:
#### Què és un diagrama de classes?
<p> → El diagrama de clases es una eina que serveix per a comunicar el disseny d’un programa orientat a objectes permetent-los modelar les seves classes, atributs, operacions i relacions entre les entitats. ← <p>


#### Pregunta 2:
#### Per a què serveix un diagrama de classes?
<p> → Un diagrama de classes es podria considerar com els plànols d’un sistema. Es poden utilitzar per modelar els objectes que formen part d’un sistema, mostrar les relacions entre els objectes, descriure que fan i els serveis que proporcionen.  ← <p>

#### Pregunta 3:
#### Enumera els diferents elements que formen part d'un diagrama de classe.
<p> → Títol de clase <p>
   <p>  Atributs de clase <p>
    <p> Mètodes de clase←  <p>

#### Pregunta 4:
#### Defineix els elements nomenats anteriorment.
<p> → Títol de clase: La primera secció es reserva per l’estereotip i el nom de la classe, on es defineix la categoria de la clase, un conjunt de propietats, comportament i restriccions preestablertes. <p>
<p> Atributs de clase: La segona secció es reserva per als atributs, on es defineix quines dades pot emmagatzemar la clase, el nom i els seus tipus.
Mètodes de clase: La tercera secció es reserva per als mètodes, on es defineix el  comportament que tindrà la clase, el nom i els seus paràmetres.← <p>

#### Pregunta 5:
#### En UML, com es representa una classe?
<p> → Una classe es representa com una capça dividida en tres seccions. Dintre d’aquesta es troba la primera secció reservada per l’estereotip i el nom de la classe. Sota d’aquesta es troba la segona secció que esta destinada per als atributs i finalment la tercera secció reservada per als mètodes. ← <p>

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


<p> → Secció superior: Conté el nom de la classe. Aquesta secció sempre és necessària, ja sigui l’estereotip o d'un objecte. <p>
<p> Secció central: Conté els atributs de la classe. Aquesta secció es fa servir  per descriure qualitats de la classe. Això només cal quan es  descriu una instància específica d'una classe. <p>
<p> Secció inferior: Inclou els metodes). Això està organitzat en un format de llista. Cada operació requereix la seva línia. Les operacions descriuen com una classe pot interactuar amb les dades. <p>
 ← 
#### Pregunta 7:
#### Els atributs i mètodes d'un diagrama de classes poden ser de quatre tipus. Enumera i explica cadascun.
→  
<p> Visibilitat pública: Visible per tots els objectes. Es representa amb +. <p>
<p> Visibilitat protegida: Visible només per l'objecte i els descendents. Es representa amb #. <p>
<p> Visibilitat privada: Visible només per l'objecte. Es representa amb -. <p>
<p> Visibilitat predeterminada:  Segons com estigui establert es podra o no veure. Es representa amb ~. <p>
← 
#### Pregunta 8:
#### Quin símbol representa a cada estat?
<p> →  Public: + <p>
<p> Predeterminat:  ~ <p>
<p> Protected: # <p>
<p> Private: -    ←  <p>

#### Pregunta 9:
#### D’aquests quatre tipus, sabries dir quin es comporta diferent entre Java i C#?
<p> → Protected: #  ← <p>
 
#### Pregunta 10:
#### D’aquest quatre tipus, sabries dir quin és exclusiu de Java? Quin seria el seu equivalent a C#?
<p> → El package (predeterminat) es exclusiu de Java <p>
<p> El using es exclusiu de C# ← <p>
