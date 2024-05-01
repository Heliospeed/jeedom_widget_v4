# Widget d'info binaire contenant l'icone de l'info et sa valeur (Jeedom v4)
Widget permettant d'afficher l'icône de la commande et en dessous un icône on/off.

Voici ce que donne cela donne en image
![Exemple](../doc/commandIconAndValueIcon/cmdIconAndValue_Example.png)

## Le script
- [Dashboard/Mobile : commandIconAndValueIcon](./cmd.info.binary.commandIconAndValueIcon.html)

## Installation
Recopier le script dans les répertoires `/var/www/html/data/customTemplates/dashboard/` et `/var/www/html/data/customTemplates/mobile/`

Remarque pour la version mobile, il est possible de faire un lien symbolique pointant vers la version sahboard pour éviter de déployer 2 fois la même version :<br/>
Dans ce cas on copie juste le script dans le répertoire : `/var/www/html/data/customTemplates/dashboard/`<br/>
 Commande pour créer le lien : `sudo ln -s /var/www/html/data/customTemplates/dashboard/cmd.info.binary.commandIconAndValueIcon.html /var/www/html/data/customTemplates/mobile/cmd.info.binary.commandIconAndValueIcon.html`<br/>
Commande pour changer le propriétaire du lien (comme les autres fichiers) :
`sudo chown -h www-data:www-data /var/www/html/data/customTemplates/mobile/cmd.info.binary.commandIconAndValueIcon.html`


ou créer manuellement un nouveau script ayant les caractéristique suivante :
|Nom|Valeur|
|-|-|
|Version|Dashboard ou Mobile|
|Type|Info|
|Sous-type|Binaire|
|Nom|CommandIconAndValueIcon (par exemple)|
et recopier le contenu du fichier.

## Les paramètres (tous optionnels)

|Parametre|version|valeur|Aperçu|Description|
|-|-|-|-|-|
|time|Dashboard<br/>Mobile|duration or date||Affiche durée ou date de la valeur|
|timeMobileOff|Mobile|0 ou 1||1 : désactive l'affichage du temp écoulé si activé pour le dashboard<br/>off :<br/>0 : reste actif comme le dashboard|
|iconOn|Dashboard<br/>Mobile|string<br/>(ex :`<i class="..."></i>`)||la balise contenant l'icone a afficher la valeur est vraie.<br/> (par défaut :`<i class="fas fa-circle"></i>`)|
|iconOff|Dashboard<br/>Mobile|string<br/>(ex :`<i class="..."></i>`)||la balise contenant l'icone a afficher la valeur est fausse.<br/> (par défaut :`<i class="far fa-circle"></i>`)|
|iconColor|Dashboard<br/>Mobile|string|![Exemple](../doc/commandIconAndValueIcon/cmdIconAndValueWithColor.png)|le code ou le nom de la couleur à appliquer (ex : "blue, "#0000FF")|
