# jeedom_widget_v4
Mes widgets Jeedom

Je n'ai pas trouvé dans les templates de bases le widget que j'avais besoin.
Je me suis donc décidé à customiser un widget (en m'appuyant sur la doc Jeedom)

## Widget d'info binaire contenant l'icone de l'info et sa valeur

Voici ce que donne cela donne en image
![Exemple](./doc/cmd.info.binary.commandIconAndValueIcon/cmdIconAndValue_Example.png)

Le code est disponible ici : [commandIconAndValueIcon](./dashboard/cmd.info.binary.commandIconAndValueIcon.html)

Si l'on ne veut pas afficher le "time widget", il faut ajouter un paramètre au widget.

|Parametre|valeur|Aperçu|Description|
|-|-|-|-|
|timeWidget|on/off|on :<br>![ex. avec time widget](./doc/cmd.info.binary.commandIconAndValueIcon/cmdIconAndValue_timeWidget.png)<br>off :<br>![ex. sans time widget](./doc/cmd.info.binary.commandIconAndValueIcon/cmdIconAndValue.png)|haut (on/off) : icone de l'info<br/>milieu (on/off) : icone On/Off<br/>bas (on) : le temp écoulé|
|tagIconName|string<br>(ex :`<i class='...'></i>`)||la balise contenant l'icone de remplacement de la commande|
|commandName|string (ex : Etat)||Le nom de la commande a afficher|
|iconOn|string<br>(ex :`<i class='...'></i>`)||la balise contenant l'icone a afficher la valeur est vraie.<br> (par défaut :`<i class='fas fa-circle'></i>`)|
|iconOff|string<br>(ex :`<i class='...'></i>`)||la balise contenant l'icone a afficher la valeur est fausse.<br> (par défaut :`<i class='far fa-circle'></i>`)|

## Installation et affectation du widget

La procédure est détaillée ici : [Procédure d'installation](./doc/InstallationProcedure.md)