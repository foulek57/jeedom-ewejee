# Changelog



- --/--/---- : V1.1.2 (Beta)
	- [ ] Mise en place d'une fonction de traitement d'alèrtes (date et heure)

- --/--/---- : Passage de la V1.1.1 en stable.

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
