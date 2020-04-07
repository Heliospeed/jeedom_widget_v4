# jeedom_widget_v4
Mes widgets Jeedom

Je n'ai pas trouvé dans les templates de bases le widget que j'avais besoin.
Je me suis donc décidé à customiser un widget (en m'appuyant sur la doc Jeedom)

## Widget d'info binaire contenant l'icone de l'info et sa valeur

Voici ce que donne cela donne en image
![Exemple](./doc/cmd.info.binary.icon-cmdIconAndValue/cmdIconAndValue_Example.png)

Il y a deux versions l'une avec le délais indiquant le changement de la valeur et l'autre sans.

|Time widget|Aperçu|Description|Code|
|-|-|-|-|
|Présent|![ex. avec time widget](./doc/cmd.info.binary.icon-cmdIconAndValue/cmdIconAndValue_timeWidget.png)|haut : icone de l'info<br/>milieu : icone On/Off<br/>bas : le temp écoulé|[cmdIconAndValue_timeWidget.html](./dashboard/cmd.info.binary.icon-cmdIconAndValue_timeWidget.html)|
|Absent|![ex. sans time widget](./doc/cmd.info.binary.icon-cmdIconAndValue/cmdIconAndValue.png)|haut : icone de l'info<br/>milieu : icone On/Off<br/>bas : espace vide|[cmdIconAndValue.html](./dashboard/cmd.info.binary.icon-cmdIconAndValue.html)|

## Installation et affectation du widget

La procédure est détaillée ici : [Procédure d'installation](./doc/InstallationProcedure.md)