# Widget Thermomètre (Jeedom v4)
Widget permettant d'afficher une image d'un thermomètre et à côté la température + (stats).

Voici ce que donne cela donne en image  
![](../doc/thermometer/thermometer_example.png)

## Le script
- [Dashboard/Mobile : thermometer](./cmd.info.numeric.thermometer.html)

## Installation

### Copier le script
Recopier le script dans le répertoire `	/var/www/html/data/customTemplates/dashboard/cmd.info.numeric.thermometer.html`  
Pour la version mobile remplacer dashboard par mobile.

ou créer un nouveau script ayant les caractéristique suivante :
|Nom|Valeur|
|-|-|
|Version|Dashboard ou Mobile|
|Type|Info|
|Sous-type|Numérique|
|Nom|Thermometer (par exemple)|

et recopier le contenu du fichier `cmd.info.numeric.thermometer.html`

### Copier les images
Il faut recopier les images dans `/var/www/html/data/img` soit en les copiants sur le serveur, ou en utilisant l'interface.

|Plage température en °C|  <0&nbsp;&nbsp;&nbsp;|>00 et <=05|>05 et <=10|>10 et <=13|>13 et <=16|>16 et <=18|>18 et <=20|>20 et <=22|>22 et <=24|>24 et <=26|>26 et <=28|>28 et <=34|  >34&nbsp;|
|-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Images|![](./img/thermometer00.png)|![](./img/thermometer01.png)|![](./img/thermometer02.png)|![](./img/thermometer03.png)|![](./img/thermometer04.png)|![](./img/thermometer05.png)|![](./img/thermometer06.png)|![](./img/thermometer07.png)|![](./img/thermometer08.png)|![](./img/thermometer09.png)|![](./img/thermometer10.png)|![](./img/thermometer11.png)|![](./img/thermometer12.png)|


## Les paramètres (tous optionnels)

|Parametre|valeur|Description|
|-|-|-|-|-|
|time|duration or date|Affiche durée ou date de la valeur|