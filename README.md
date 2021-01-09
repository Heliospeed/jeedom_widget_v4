# jeedom_widget_v4
Mes widgets Jeedom

Je n'ai pas trouvé dans les templates de bases le widget que j'avais besoin.
Je me suis donc décidé à customiser un widget, puis second (en m'appuyant sur la doc Jeedom)

## Widget d'info binaire contenant l'icone de l'info et sa valeur
Afficher l'icône de la commande et en dessous un icône on/off.  
- [commandIconAndValueIcon](./commandIconAndValueIcon/README.md)  
*Le script fonctionne pour la version dashboard et mobile.*

## Widget thermomètre
Affiche un thermomètre en image avec la température à droite. Je suis parti de 3 images existantes qui était dans un widget jeedom v3 : thermometreIMG.<br/><br/>
Dans ma version, j'ai décliné plus d'images pour être plus précis, il y en a 13.
- [thermometer](./thermometer/README.md)  
*Le script fonctionne pour la version dashboard et mobile.*

## Widget Hygromètre
Affiche un Hygromètre en image avec la température à droite. Je suis parti des images existantes qui était dans un widget jeedom v3 : Taux_Humidite_IMG.<br/><br/>
Dans ma version, j'ai redimentionné les images pour être identique à celle du widget thermomètre.
- [hygrometer](./hygrometer/README.md)  
*Le script fonctionne pour la version dashboard et mobile.*

## Widget réveil
Affiche un réveil en image avec l'heure programmé (si elle est prévue dans les 24 prochaines heures). Je suis parti des images existantes qui était dans un widget jeedom v3 : alarm-clock.<br/><br/>
- [alarmClock](./alarmClock/README.md)  
*Le script fonctionne pour la version dashboard et mobile.*

## Widget Danfoss Living Connect
Affiche la tête Danfoss Living Connect (et permet de la piloter). Je suis parti des images existantes qui était dans un widget jeedom v3 : DanfossIMG.<br/><br/>
- [danfossLivingConnect](./danfossLivingConnect/README.md)  
*Le script fonctionne pour la version dashboard et mobile.*

## Installation et affectation d'un widget

La procédure est détaillée ici : [Procédure d'installation](./doc/InstallationProcedure.md)