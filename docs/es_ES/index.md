
Ce plugin permet d'envoyer un évènement à Pushover

=== Configuration du plugin

Après téléchargement du plugin il vous faut l'activer, celui-ci ne necessite aucune autre configuration.

![PushoverScreenshot](/jeedom-plugin-pushover/images/pushover_screenshot.png)

=== Configuration des équipements

La configuration des équipements Pushover est accessible à partir du menu plugin : 


Voilà à quoi ressemble la page du plugin Pushover (ici avec déjà 1 équipement) : 

Comme à beaucoup d'endroit sur Jeedom, mettre la souris tout à gauche permet de faire apparaître un menu d'accès rapide (vous pouvez à partir de votre profils le laisser toujours visible)

Une fois que vous cliquez sur l'un d'eux, vous obtenez : 

![GitHub Logo](/jeedom-plugin-pushover/images/pushover_screenshot2.png)


Vous retrouvez ici toute la configuration de votre équipement : 

* *Nom de l'équipement* : nom de votre équipement Pushover
* *Activer* : permet de rendre votre équipement actif
* *Visible* : le rend visible sur le dashboard

En dessous vous retrouvez la configuration des commandes : 

* Nom : nom de la commande
* Token:  Token pushover correspond au token de l application creee sous Pushover 
* User: User key Pushover  
* Device: par defaut a vide ; la commande sera envoyee a tous les devices cree dans Pushover 
* Priority : preciser la priorite du message 
* Retry: (obligatoire pour la priorite 2 emergency) indique le nombre de secondes entre 2 essais de push par les serveurs pushovers jusqu'a acquitement 
* Expire: (obligatoire pour la priorite 2 emergency) indique le nombre de secondes pendant lequel le message sera envoye par les serveurs pushover avant d etre marque expire et de ne plus etre envoye  
* Sound : son a jouer sur le device lors de notification 
* LocalFile: nom de fichier a joindre a chaque envoi (vide par defaut) - ne pas utiliser si on joint une image via le  plugin camera  
* Tester : permet de tester la commande
* supprimer (signe -) : permet de supprimer la commande

=== Création d'un compte  Pushover 

Creez un compte sur Pushover si ce n'est pas deja fait, en allant sur link::https://pushover.net[Pushover] : 

![GitHub Logo](/jeedom-plugin-pushover/images/pushover_screenshot3.png)

Renseignez votre adresse mail et votre mot de passe   faites creer :

Une nouvelle page apparait avec l'id User a mettre dans le champs User 


![GitHub Logo](/jeedom-plugin-pushover/images/pushover_screenshot4.png)

Avant de creer une application il faudra verifier l adresse email grace au mail envoye par Pushover 

Pour creer une application (par exemple Jeedom), cliquer sur register an application

![GitHub Logo](/jeedom-plugin-pushover/images/pushover_screenshot5.png)

une fois l application cree recuperer l id genere  pour le mettre dans le champs Token 

![GitHub Logo](/jeedom-plugin-pushover/images/pushover_screenshot6.png)

Vos devices apparaitront dans la liste apres l installation de l application Android ou IOS sur vos telephones et tablettes 

