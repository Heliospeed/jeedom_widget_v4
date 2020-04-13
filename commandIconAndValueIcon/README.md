# Widget d'info binaire contenant l'icone de l'info et sa valeur (Jeedom v4)
Widget permettant d'afficher l'icône de la commande et en dessous un icône on/off.

Voici ce que donne cela donne en image
![Exemple](../doc/commandIconAndValueIcon/cmdIconAndValue_Example.png)

## Les scripts 
- [Dashboard : commandIconAndValueIcon](./cmd.info.binary.commandIconAndValueIcon.html)
- [Mobile : commandIconAndValueIcon](./cmd.info.binary.commandIconAndValueIcon_Mobile.html)

## Les paramètres (tous optionnels)

|Parametre|version|valeur|Aperçu|Description|
|-|-|-|-|-|
|timeWidget|Dashboard|on/off (par défaut on)|on :<br/>![ex. avec time widget](../doc/commandIconAndValueIcon/cmdIconAndValue_timeWidget.png)<br/>off :<br/>![ex. sans time widget](../doc/commandIconAndValueIcon/cmdIconAndValue.png)|haut (on/off) : icone de l'info<br/>milieu (on/off) : icone On/Off<br/>bas (on) : le temp écoulé|
|timeWidgetMobile|Mobile|on/off (par défaut off)|idem|idem sauf valeur par défaut "off"|
|tagIconName|Dashboard<br/>Mobile|string<br/>(ex :`<i class='...'></i>`)||la balise contenant l'icone de remplacement de la commande|
|iconColor|Dashboard<br/>Mobile|string|![Exemple](../doc/commandIconAndValueIcon/cmdIconAndValueWithColor.png)|le code ou le nom de la couleur à appliquer (ex : "blue, "#0000FF")|
|commandName|Dashboard<br/>Mobile|string (ex : Etat)||Le nom de la commande a afficher|
|iconOn|Dashboard<br/>Mobile|string<br/>(ex :`<i class='...'></i>`)||la balise contenant l'icone a afficher la valeur est vraie.<br/> (par défaut :`<i class='fas fa-circle'></i>`)|
|iconOff|Dashboard<br/>Mobile|string<br/>(ex :`<i class='...'></i>`)||la balise contenant l'icone a afficher la valeur est fausse.<br/> (par défaut :`<i class='far fa-circle'></i>`)|
