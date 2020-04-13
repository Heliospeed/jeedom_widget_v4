# Widget Hygromètre (Jeedom v4)
Widget permettant d'afficher une image d'un thermomètre et à côté la température + (stats).

Voici ce que donne cela donne en image  
![](../doc/hygrometer/hygrometer_example.png)

## Le script
- [Dashboard/Mobile : hydrometer](./cmd.info.numeric.hygrometer.html)

## Les images
Il faut recopier les images dans `/var/www/html/data/img` soit en les copiants sur le serveur, ou en utilisant l'interface.

|Plage de température °C|>=00 et <10|>=10 et <20|>=20 et <=30|>30 et <40|>=40 et <50|>=50 et <60|>=60 et <70|>=70 et <80|>=80 et <90|>=90 et <100|=100&nbsp;|
|-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Images|![](./img/hygrometer00.png)|![](./img/hygrometer01.png)|![](./img/hygrometer02.png)|![](./img/hygrometer03.png)|![](./img/hygrometer04.png)|![](./img/hygrometer05.png)|![](./img/hygrometer06.png)|![](./img/hygrometer07.png)|![](./img/hygrometer08.png)|![](./img/hygrometer09.png)|![](./img/hygrometer10.png)|


## Les paramètres (tous optionnels)

|Parametre|version|valeur|Aperçu|Description|
|-|-|-|-|-|
|largeurDashboardPx|Dashboard|[20-29] (px)||Permet d'agrandir la largeur de l'image jusqu'à sa resolution maxi. La valeur par défaut est "20" px|
|largeurMobilePx|Mobile|[20-29] (px)||idem|