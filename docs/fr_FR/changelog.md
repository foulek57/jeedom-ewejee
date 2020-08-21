# Changelog

- A venir : 
	- [ ] Mise en place d'une fonction de traitement d'alèrtes (date et heure).
	- [ ] ...Récupération des noms saisie dans l'aplication eWeLink (J'ai besoins de bêta testeur pour ceci...Envoyez moi un message !!).
	- [ ] Vérification si l'équipement est en ligne avant d'envoyer une commande.
	- [ ] Test de l'activation du pulse


- V2.0.0 (Bêta)
    - [x] **Ajout d'une fonctionalité LAN pour les équipements compatible.**
    - [x] Ajout des stat du POW sur le mois (Final)
    - [x] Ajout d'un systeme de sauvgarde des données de conso du POW pas mois et annees
    - [x] Ajout de 16 commandes pour le rf bridge portant le total a 32
    - [x] Amélioration visuel divers
    - [x] Correction de bugs sur la fonctionalitée LAN
    - [x] Remonté des noms pour le RFBridge
    - [x] Correction de bugs dans la synchronisation
    - [x] Modification du cron pour le POW (ID unique par POW pour éviter les conflits)
    - [x] Correction d'un bug dans l'installation des dépendances
    - [x] Déplacement des logs détaillés dans un fichier .txt, pour plus de visibilitée en cas d'érreur
    - [x] Suppression d'un fichier provoquant un bug dans l'installation des dépendances
    - [x] Ajout d'un démon LAN
    - [x] Ajout de la gestion du démon LAN et Cloud dans la configuration
    - [x] Ajout de 2 voyants d'état des démons dans le panneau de gestion
    - [ ] Correction du bug des photo manquantes, alors que la photo n'est pas manquante
    - [ ] *Si possible* Retour d'état sans Cloud.
    - [ ] Ajout d'un cron journalier pour récupérer les stat POW et les ajouter à l'historique
    - [ ] Mise a jour de la documentation
    - [ ] Relance du démon avant synchronisation
    - [ ] Correction du script pour récupérer les IP
    - [ ] Ajout d'une case pour forcer le fonctionnement en cloud (Pour par ex. le TH10 ou TH16 qui, suivant la version de firmeware, ne fonctionne pas en cloud)


- V1.1.7 (Bêta)
	- [x] Ajout KingArt KING-Q4 (Volets)
	- [x] Ajout KingArt KING-M4 (Inter avec variateur)
	- [x] Ajout du Sonoff D1 dimmer
	- [x] Correction ampérage en intensité pour SonOff Pow *Merci @olive*

- 16/01/2020 : V1.1.6 (Stable)

- 08/01/2020 : V1.1.6 (Bêta)
	- [x] Ajout d’un bouton pour forcer la remonté des informations du Sonoff POW
	- [x] MAJ Documentation
	- [x] Ajout d’un cron 5/10/15/30, 1H ou journalier pour programmer la remonter des infos du Sonoff POW configurable dans la configuration de l’équipement
	- [x] Ajout d'une détection si l'equipement est connecté.
	- [x] Ajout d'une détection si l'équipement n'est plus connecté.
	- [x] Ajout d'une photo de l'équipement (Si la votre n'y est pas, merci de m'envoyer le model inscrit dans la configuration du plugin)
	- [x] Ajout de la compatibilitée de l'ampoule B1 
	- [x] Ajout des stat du POW sur le mois (dev en cours)
	- [x] Nétoyage du script serveur
	- [x] Relance automatique du serveur s'il se ferme
	- [x] Mise à jour du script d'installation des dépendances
	- [x] Lancement du serveur sur le local (en cas de non selection entre http et https)
	- [x] Réorganisation de la configuration de l'équipement


- 20/01/2020 : V1.1.5 Version stable

- 16/01/2020 : V1.1.5 (Bêta)
	- [x] Récupération de l'adresse ip et port interne et externe
	- [x] Ajout de la possibilitée de faire tourner le plugin en SSL (https) *Pour pouvoir fermer le port 80*
  	- [x] Correction des bogues sur l'ifan.
	- [x] Amélioration de la réactivitée sur l'iFan.
	- [x] Ajout du changement de couleur du "Ultrasonic Humidifier" AGW-D7 (WI16) *Merci à kubico29*


- 14/01/2019 : V1.1.4 (Stable)

- 09/01/2019 : V1.1.4 (bêta)
	- [x] Mise en place d'un bouton ON (Qui ne fera que on) et OFF (Qui ne fera que off) en remplacement du ON/OFF actuel *Il faudra refaire une synchronisation*
	- [x] Amélioration de la réactivitée ON/OFF (Instantané) *Il faudra refaire une synchronisation*


- 05/01/2019 : V1.1.3 (Stable)
	
- 22/12/2019 : V1.1.3 (Bêta)
	- [x] Ajout du "Ultrasonic Humidifier" AGW-D7 (WI16) *Merci à kubico29*
	- [x] Amélioration du script d'installation des dépendances.
	- [x] Résolution du problème d'installation sur Debian 9
	- [x] Ajout de la possibilitée de modifier le port du localhost *Merci à Vincent*
	- [x] Ajout d'un bouton pour ajouter une commande "action" par channel pour avoir un "ON" et un "OFF" pour les assistant (Google, Alexa....).


- 02/12/2019 : Passage de la V1.1.2 en stable.

- 30/11/2019 : V1.1.2 (Bêta)
	- [x] Ajout d'un chat en ligne pour le support : http://www.domometz.fr/index.php *(N'oubliez pas de laisser votre adresse mail pour être avertis des réponses)*
	- [x] Ajout de la reconaissance de la marque et du modèle.
	- [x] Suppression du fichier d'installation apres installation.
	- [x] Ajout de la compatibilitée 100% du RF Bridge *(Un grand merci à Michel !)*
	- [x] Modification du type de données du sonoff pow.

- 26/11/2019 V1.1.1b (Stable)
    - [x] Mise à jour pour correction des bug.

- 25/11/2019 V1.1.1b (Bêta)
    - [x] Mise à jour pour correction des bug.

- 21/11/2019 V1.1.1a (Bêta et Stable)
    - [x] Mise à jour pour correction des bug.

- 20/11/2019 : Passage de la V1.1.1 en stable.

- 19/11/2019 : V1.1.1 (Bêta)
	- [x] Ajout de la reconaissance du modèle.
	- [x] Ajout d'un cron15 pour une mise à jour (Toutes les 15 minutes pour la bêta, passage a 1h ulterieurement).
	- [x] Correction du bug de duplication de serveur lorsque la connection est intérompu par l'utilisateur quui se connecte sur l'aplication eWeLink.
	- [x] Ajustement des commandes pour l'ifan02 et 03.
	- [x] Mise à jour de la documentation.
	- [x] Ajout d'options pour les commandes (Historiser, afficher, masquer...).
	- [x] Correction case "commentaire".
  

- 17/11/2019 : V1.1 (Bêta) (MISE A JOUR DES DEPENDANCES OBLIGATOIRE !! + Resynchronisation obligatoire )
	- [x] Ajout d'une API pour la mise a jour des états en temps réel.
	- [x] Ajout de la mise à jour de l'état quand il est changé hors plugin.
	- [x] Refonte complete du script, passage en POO pour une meilleur gestion du moteur du plugin.
	- [x] Refonte complete du serveur : 
	- [x] Ajout de la région en 'eu' (Pour etre informé d'un changement d'état).
	- [x] Ajout d'une détéction en cas de déconnexion au serveur eWeLink.
	- [x] Ajout de l'envoi des données en format JSON vers Jeedom.
	- [x] Fermeture de la connextion eWeLink lors du redémarage du démon (Sinon on reçois les infos plusieurs fois)
	- [x] Ajout d'un ping et réponse au pong de eWeLink afin de garder la connexion ouverte.
	- [x] Mise à jour du script d'installation des dépendances.
	- [x] Ajout de la remonté de : 
	- [x] Température
	- [x] Humiditée
	- [x] Ampères
	- [x] Voltage
	- [x] POW
	- [x] Ajout de oa compatibilitée des ifan02 et ifan03

- Sortie stable
- Beta V0.0.1
	- [x] Nouvelle façon d'importer les équipements.
	- [x] Ajout de tout les paramètres d'un sonoff dans les commandes.
	- [x] Récupération du nom des channels (en test...).
	- [x] Ajout d'une case de commentaire dans chaques équipements.
	- [x] Compatibilitée avec la quasi totalitée des interrupteurs sonoff.
	- [x] Amélioration visuelle.
	- [x] Amélioration du temps de réponse.
	- [x] Amélioration du système de rafraichissement des informations/Widget.
	- [x] Amélioration de l'installation des dépendances
	- [x] Ajustement du sous type "info" -> "Autre".
	- [x] Optimisation du demon.
- 12/10/2019 Amélioration du retour d'etat et ajout doc en Allemand et Anglais
- 12/10/2019 Passage en version Beta
- 07/09/2019 Version Alpha
