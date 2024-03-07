# Horloge à LED linéaire

## Le temps
*On le perçoit filer comme des perles lumineuses qui sautillent sur une règle linéaire.*

*Il se renouvelle avec un cycle diurne mais nous rapproche d'une fin certaine.*

*Il rythme notre vie mais peut aussi la stresser.*

*Si toutes blessent, la dernière tue*.*

*A nous de le couper avant qu'il ne nous coupe***.

*Afin de pouvoir découvrir, inventer, concevoir et transmettre.*

*C’est un beau métier mais qu’on vit comme une passion !*

**En référence à la célèbre locution présente sur les cadrans solaires
"Vulnerant omnes, ultima necat", "Toutes blessent, la dernière tue".*

***En référence à un ancien proverbe arabe,* "الوقت كالسيف إن لم تقطعه قطعك",
*"le temps est comme une épée. Si tu ne le coupes pas, il te coupe".*

## Fonctionnement

La LED rouge indique l’heure sur l'échelle du haut 0-24.

La LED violette indique les minutes sur l'échelle du bas 0-60.

La LED bleue indique les secondes sur la même échelle.

La LED jaune le jour du mois.

L’horloge se connecte par WiFi au serveur `europe.pool.ntp.org` par NTP (Network Time Protocol) toutes les 24 h afin de se resynchroniser et avoir une précision à la seconde près.

Le code est écrit en langage C sur ESP8266 Wemos D1 mini.

Une seule sortie logique pilote les 240 LED WS2812b du ruban de 4 m

