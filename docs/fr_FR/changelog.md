# Changelog

- 17/11/2019 : V1.1 (MISE A JOUR DES DEPENDANCES OBLIGATOIRE !! + Resynchronisation obligatoire )
	- Ajout d'une API pour la mise a jour des états en temps réel.
	- Ajout de la mise à jour de l'état quand il est changé hors plugin.
	- Refonte complete du script, passage en POO pour une meilleur gestion du moteur du plugin.
	- Refonte complete du serveur : 
	- Ajout de la région en 'eu' (Pour etre informé d'un changement d'état).
	- Ajout d'une détéction en cas de déconnexion au serveur eWeLink.
	- Ajout de l'envoi des données en format JSON vers Jeedom.
	- Fermeture de la connextion eWeLink lors du redémarage du démon (Sinon on reçois les infos plusieurs fois)
	- Ajout d'un ping et réponse au pong de eWeLink afin de garder la connexion ouverte.
	- Mise à jour du script d'installation des dépendances.
	- Ajout de la remonté de : 
	- Température
	- Humiditée
	- Ampères
	- Voltage
	- POW

- Sortie stable
- Beta V0.0.1
	Nouvelle façon d'importer les équipements.
	Ajout de tout les paramètres d'un sonoff dans les commandes.
	Récupération du nom des channels (en test...).
	Ajout d'une case de commentaire dans chaques équipements.
	Compatibilitée avec la quasi totalitée des interrupteurs sonoff.
	Amélioration visuelle.
	Amélioration du temps de réponse.
	Amélioration du système de rafraichissement des informations/Widget.
	Amélioration de l'installation des dépendances
	Ajustement du sous type "info" -> "Autre".
	Optimisation du demon.
- 12/10/2019 Amélioration du retour d'etat et ajout doc en Allemand et Anglais
- 12/10/2019 Passage en version Beta
- 07/09/2019 Version Alpha
