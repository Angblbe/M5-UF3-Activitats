# UML: pràctica 2

Les vostres respostes, aquí.


#### Pregunta 1:
#### Un metge necessita una aplicació per mantenir les dades dels pacients, en concret necessita guardar el següent: nom; cognoms; data de naixement; DNI; gènere; alçada; pes; al·lèrgies; nom dels medicaments que pren actualment; quines malalties cròniques pateix el pacient; operacions quirúrgiques a les quals s’ha exposat el pacient. Per últim ens d


                                    |-----------------------------------|               
                                    |              +Pacient             |
                                    |-----------------------------------|
                                    | -nom: string                      |
                                    | -cognoms: string                  |
                                    | -dataNaixement: date              |
                                    | -DNI: string                      |
                                    | -gènere: string                   |
                                    | -alçada: float                    |
                                    | -pes: float                       |
                                    | -al·lèrgies: string               |
                                    | -medicamentsActuals: string       |
                                    | -malaltiesCròniques: string       |
                                    | - operacionsQuirúrgiques: string  |
                                    |-----------------------------------|
                                    | + calIMC():                       |
                                    |-----------------------------------|




#### Pregunta 2:
#### La meva tieta regenta una fruiteria al ben mig d’un petit poble i té molta curiositat per saber quina quantitat de fruita està venent, quin és el preu de cost de tota la fruita que ha venut i quants diners porta guanyats en total. De moment no li interessa fer un desglossament dels imports per tipus de fruita però sí que li agradaria calcular de forma fàcil quin ha sigut el seu marge de benefici.


                                    |-----------------------------|
                                    |         +Fruteria           |
                                    |-----------------------------|
                                    | -vendesTotals: integer      |
                                    | -costosFruitaVenuda: float  |
                                    | -beneficis: float           |
                                    |-----------------------------|
                                    |calMargeBef():               |
                                    |-----------------------------|


#### Pregunta 3:
#### Sempre m’he preguntat com ha de ser la classe UML que fa servir «Blizzard» per a guardar la informació d’una carta de «Hearthstone». A continuació tens la carta que més m’agrada, m’ajudes? Per cert, les cartes de «Hearthstone», a part de jugar-les, també es poden desencantar! 


                                    |-------------------------------|               
                                    |       +Hearthstone            |
                                    |-------------------------------|
                                    | -puntsMana: integer           |
                                    | -edicioCarta: string          |
                                    | -nomCarta: string             |
                                    | -habEspecial1: string         |
                                    | -puntsAtac: integer           |
                                    | -puntsVida: integer           |
                                    | -habEspecial2: string         |
                                    | -raresa: string               |
                                    | -dibuixPersonatge: string     |
                                    |-------------------------------|
                                    | +jugar():                     |
                                    | +encantar():                  |
                                    |-------------------------------|

