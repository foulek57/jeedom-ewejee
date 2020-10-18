# Changelog

- A venir : 
	- [ ] Mise en place d'une fonction de traitement d'alertes (date et heure).
	- [ ] ...Récupération des noms saisis dans l'application eWeLink (J'ai besoin de bêta testeur pour ceci...Envoyez moi un message !!).
	- [ ] Vérification si l'équipement est en ligne avant d'envoyer une commande.
	- [ ] Test de l'activation du pulse
    - [ ] *Si possible* Retour d'état sans Cloud.
    - [ ] Ajout d'un cron journalier pour récupérer les stats POW et les ajouter à l'historique


- ../10/2020 : V2.0.0 (Stable)

- 30/09/2020 : V2.0.0 (Bêta)
	- [x] Correction de bug de l'installation des dépendances
	- [x] Correction de bug sur la récupération des IP et MAC des Sonoff
	- [x] Ajout logo "LAN" dans l'équipement, quand ce dernier fonctionne en LAN
	- [x] Correction du bouton "Activation LAN" qui était par défaut activé
	- [x] Refonte du RFBridge (Il faut supprimer l'équipement et refaire une synchronisation du RFBridge)
	- [x] Ajout d'une détection d'un nouvel appareil RF et automatisation de l'ajout d'une nouvelle commande pour ce dernier
	- [x] Modification de la mise à jour des informations des capteurs RF (Info reste enregistrée quand un autre capteur se déclenche)
	- [x] Optimisation du démmarage du demon (Plus rapide)
	- [x] Correction des logs
	- [x] Ajout de la compatibilité des capteurs de porte/fenètre sonoff (Egalement Zigbee)
	- [x] Correction du bug de la case qui ne restait pas cochée pour forcer le cloud
	- 


- 21/08/2020 : V2.0.0 (Bêta)
    - [x] **Ajout d'une fonctionalité LAN pour les équipements compatible.**
    - [x] Ajout des stats du POW sur le mois (Final)
    - [x] Ajout d'un système de sauvegarde des données de conso du POW par mois et années
    - [x] Ajout de 16 commandes pour le rf bridge portant le total à 32
    - [x] Amélioration visuelles diverses
    - [x] Correction d'un bug sur la fonctionalité LAN
    - [x] Remontée des noms pour le RFBridge
    - [x] Correction d'un bug dans la synchronisation
    - [x] Modification du cron pour le POW (ID unique par POW pour éviter les conflits)
    - [x] Correction d'un bug dans l'installation des dépendances
    - [x] Déplacement des logs détaillés dans un fichier .txt, pour plus de visibilité en cas d'erreur
    - [x] Suppression d'un fichier provoquant un bug dans l'installation des dépendances
    - [x] Ajout d'un démon LAN
    - [x] Ajout de la gestion du démon LAN et Cloud dans la configuration
    - [x] Ajout de 2 voyants d'état des démons dans le panneau de gestion
    - [x] Correction du bug des photos manquantes, alors que la photo n'est pas manquante
    - [x] Mise à jour de la documentation
    - [x] Relance du démon avant synchronisation
    - [x] Correction du script pour récupérer les IP
    - [x] Ajout d'une case pour forcer le fonctionnement en cloud (Pour par ex. le TH10 ou TH16 qui, suivant la version de firmware, ne fonctionne pas en LAN)
    - [x] Ajout images : POW + Camera


- V1.1.7 (Bêta)
	- [x] Ajout KingArt KING-Q4 (Volets)
	- [x] Ajout KingArt KING-M4 (Inter avec variateur)
	- [x] Ajout du Sonoff D1 dimmer
	- [x] Correction ampérage en intensité pour SonOff Pow *Merci @olive*

- 16/01/2020 : V1.1.6 (Stable)

- 08/01/2020 : V1.1.6 (Bêta)
	- [x] Ajout d’un bouton pour forcer la remontée des informations du Sonoff POW
	- [x] MAJ Documentation
	- [x] Ajout d’un cron 5/10/15/30, 1H ou journalier pour programmer la remontée des infos du Sonoff POW configurable dans la configuration de l’équipement
	- [x] Ajout d'une détection si l'equipement est connecté.
	- [x] Ajout d'une détection si l'équipement n'est plus connecté.
	- [x] Ajout d'une photo de l'équipement (Si la votre n'y est pas, merci de m'envoyer le modèle inscrit dans la configuration du plugin)
	- [x] Ajout de la compatibilité de l'ampoule B1 
	- [x] Ajout des stats du POW sur le mois (dev en cours)
	- [x] Nettoyage du script serveur
	- [x] Relance automatique du serveur s'il se ferme
	- [x] Mise à jour du script d'installation des dépendances
	- [x] Lancement du serveur sur le local (en cas de non sélection entre http et https)
	- [x] Réorganisation de la configuration de l'équipement


- 20/01/2020 : V1.1.5 Version stable

- 16/01/2020 : V1.1.5 (Bêta)
	- [x] Récupération de l'adresse ip et port interne et externe
	- [x] Ajout de la possibilité de faire tourner le plugin en SSL (https) *Pour pouvoir fermer le port 80*
  	- [x] Correction des bugs sur l'ifan.
	- [x] Amélioration de la réactivité sur l'iFan.
	- [x] Ajout du changement de couleur du "Ultrasonic Humidifier" AGW-D7 (WI16) *Merci à kubico29*


- 14/01/2019 : V1.1.4 (Stable)

- 09/01/2019 : V1.1.4 (bêta)
	- [x] Mise en place d'un bouton ON (Qui ne fera que on) et OFF (Qui ne fera que off) en remplacement du ON/OFF actuel *Il faudra refaire une synchronisation*
	- [x] Amélioration de la réactivité ON/OFF (Instantané) *Il faudra refaire une synchronisation*


- 05/01/2019 : V1.1.3 (Stable)
	
- 22/12/2019 : V1.1.3 (Bêta)
	- [x] Ajout du "Ultrasonic Humidifier" AGW-D7 (WI16) *Merci à kubico29*
	- [x] Amélioration du script d'installation des dépendances.
	- [x] Résolution du problème d'installation sur Debian stretch -> 9.XX
	- [x] Ajout de la possibilité de modifier le port du localhost *Merci à Vincent*
	- [x] Ajout d'un bouton pour ajouter une commande "action" par channel pour avoir un "ON" et un "OFF" pour les assistant (Google, Alexa....).


- 02/12/2019 : Passage de la V1.1.2 en stable.

- 30/11/2019 : V1.1.2 (Bêta)
	- [x] Ajout d'un chat en ligne pour le support : http://www.domometz.fr/index.php *(N'oubliez pas de laisser votre adresse mail pour être avertis des réponses)*
	- [x] Ajout de la reconnaissance de la marque et du modèle.
	- [x] Suppression du fichier d'installation après installation.
	- [x] Ajout de la compatibilité 100% du RF Bridge *(Un grand merci à Michel !)*
	- [x] Modification du type de données du sonoff pow.

- 26/11/2019 V1.1.1b (Stable)
    - [x] Mise à jour pour correction des bug.

- 25/11/2019 V1.1.1b (Bêta)
    - [x] Mise à jour pour correction des bug.

- 21/11/2019 V1.1.1a (Bêta et Stable)
    - [x] Mise à jour pour correction des bug.

- 20/11/2019 : Passage de la V1.1.1 en stable.

- 19/11/2019 : V1.1.1 (Bêta)
	- [x] Ajout de la reconnaissance du modèle.
	- [x] Ajout d'un cron15 pour une mise à jour (Toutes les 15 minutes pour la bêta, passage à 1h ulterieurement).
	- [x] Correction du bug de duplication de serveur lorsque la connection est interrompue par l'utilisateur qui se connecte sur l'application eWeLink.
	- [x] Ajustement des commandes pour l'ifan02 et 03.
	- [x] Mise à jour de la documentation.
	- [x] Ajout d'options pour les commandes (Historiser, afficher, masquer...).
	- [x] Correction case "commentaire".
  

- 17/11/2019 : V1.1 (Bêta) (MISE A JOUR DES DEPENDANCES OBLIGATOIRE !! + Resynchronisation obligatoire )
	- [x] Ajout d'une API pour la mise à jour des états en temps réel.
	- [x] Ajout de la mise à jour de l'état quand il est changé hors plugin.
	- [x] Refonte complète du script, passage en POO pour une meilleure gestion du moteur du plugin.
	- [x] Refonte complète du serveur : 
	- [x] Ajout de la région en 'eu' (Pour etre informé d'un changement d'état).
	- [x] Ajout d'une détection en cas de déconnexion au serveur eWeLink.
	- [x] Ajout de l'envoi des données en format JSON vers Jeedom.
	- [x] Fermeture de la connexion eWeLink lors du redémmarage du démon (Sinon on reçoit les infos plusieurs fois)
	- [x] Ajout d'un ping et réponse au pong de eWeLink afin de garder la connexion ouverte.
	- [x] Mise à jour du script d'installation des dépendances.
	- [x] Ajout de la remonté de : 
	- [x] Température
	- [x] Humiditée
	- [x] Ampères
	- [x] Voltage
	- [x] POW
	- [x] Ajout de la compatibilité des ifan02 et ifan03

- Sortie stable
- Beta V0.0.1
	- [x] Nouvelle façon d'importer les équipements.
	- [x] Ajout de tous les paramètres d'un sonoff dans les commandes.
	- [x] Récupération du nom des channels (en test...).
	- [x] Ajout d'une case de commentaire dans chaque équipement.
	- [x] Compatibilité avec la quasi totalité des interrupteurs sonoff.
	- [x] Amélioration visuelle.
	- [x] Amélioration du temps de réponse.
	- [x] Amélioration du système de rafraîchissement des informations/Widget.
	- [x] Amélioration de l'installation des dépendances
	- [x] Ajustement du sous type "info" -> "Autre".
	- [x] Optimisation du demon.
- 12/10/2019 Amélioration du retour d'état et ajout doc en Allemand et Anglais
- 12/10/2019 Passage en version Beta
- 07/09/2019 Version Alpha
