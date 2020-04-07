# Procédure d'installation d'un widget Jeedom v4 (Core)

## Installation d'un widget
Via l'interface de Jeedom, il faut aller sur Outils puis Widgets
![Core Widgets](./images/outilsWidgets.png)

Ensuite, il faut cliquer sur l'icone Code :  
 ![Icone Code](./images/WidgetsCodeIcon.png)

Dans l'écran suivant cliquer sur nouveau, puis renseigner le formulaire de création :  
Dans notre cas Version -> Dashboard ; Type -> Info ; Sous-Type -> Binaire ; Nom -> le nom du widget
 ![Nouveau](./images/WidgetsCodeNew.png)

Dans l'écran suivant, recopier le code et cliquer sur sauvegarder :  
 ![Edition du code](./images/WidgetsCodeEdit.png)

L'installation est terminée

## Affectation d'un widget

Une fois les fichiers recopiés, il faut les appliquer.
Pour cela aller sur l'équipement souhaité et cliquer sur l'icone engrenages :
![configuration commande](./images/cmd.info.binary_example.png)

Dans l'onglet Informations, c'est ici que l'on définit l'icône de la commande :
![Choix de l'icone de la commande](./images/defineIcon.png)

Dans l'onglet Affichage, c'est ici que l'on sélectionne le widget a appliquer (affectation du widget CustomTemp/nomDuWidget) :
![Application du widget](./images/applyWidget.png)
