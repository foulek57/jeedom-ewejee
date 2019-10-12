
eWeJee
==============================

Description
-----------

Ce plugin à pour but d’intégrer à Jeedom TOUT vos équipements compatible eWeLink sans les flasher.
Grace à un bouton de synchronisation, un clic et tout vous équipements sont importé dans Jeedom.

![ewejee icon](../images/ewejee_icon.png)

Configuration
-------------

Configuration du plugin
========================

a.  Installation/Création

> **Tip**
>
> Afin d’utiliser le plugin, vous devez le télécharger, l’installer et
> l’activer comme tout plugin Jeedom.

Suite à cela vous arriverez sur cette page :

![configuration](../images/configuration.png)

Sur cette page vous avez peu de choses à faire. Il est très vivement recommandé de lancer l’installation des dépendances (même si elles apparaissent OK) et d’attendre 5 minutes avant de lancer le démon.
En attendant vous pouvez rentrez votre login et mot de passe de l’application eWeLink.
![login](../images/login.png)

> **Important**
>
> Il faut impérativement attendre 5 minutes après avoir lancé l'installation des dépendances ET avoir sauvegardé vos identifiants pour lancer le démon. 

Le plugin
=========

Rendez vous dans le menu Plugins &gt; objets connectés pour retrouver le plugin.

![plugin_obj_ewejee](../images/plugin_obj_ewejee.png)

Sur cette page, il vous suffit maintenant de cliquer sur le petit plus au-dessus de synchroniser pour synchroniser tous les équipements de l'application eWeLink.

![sync](../images/sync.png)

Une fois que c'est fait vous devez rafraîchir la page et vous verrez apparaître tous les équipements.

![sync2](../images/sync2.png)


Gestion
==========

Dans la partie gestion vous avez :
-	Synchroniser : Ce bouton sert à synchroniser tous les équipements de l'application eWeLink.
> **Important**
>	ATTENTION IL FAUT SUPPRIMER TOUT LES EQUIPEMENTS AVANT DE LANCER UNE SYNCHRONISATION !
-	Configuration : Pour voir la configuration du plugin…

Mes ewejees
=============

Affiche tous vos équipements.
1 ewejee correspond à un équipement (intérrupteur, prise etc…)

Configuration d’un ewejee
=============

Vous avez 2 onglets.

Dans l’onglet équipement vous retrouver : 

- Le nom de l’équipement.
- L'objet parents .
- La catégorie.
- Une case de commentaire.

![onglet_equip](../images/onglet_equip.png)

> **Important**
> Le nom de l’équipement ne doit pas être changé il doit correspondre au nom que vous avez dans l’application.
> La case de commentaire peut-être utilisé comme vous le souhaitez, cela vous permet de mettre un commentaire à votre équipement.


Interrupteur / relais / prises
----------------------
Vous avez une commande action par « band » qui effectue un on s’il est éteint et un off s’il est allumé et un équipement info qui vous indique s'il est allumé ou éteint.
Pour l'instant la mise a jour ne se fait que si ont appuie sur une commande action.
Une mise a jour de l’état automatique sera mis en place plus tard.
![onglet_cmd_switch2](../images/onglet_cmd_switch2.png)

Pour les relais utilisé en "contact sec", l'état de change pas car celui-ci envoi un "push" sur le relai.

Si vous avez une équippement qui n'est pas reconnu, vous aurez par défaut 4 channel et 4 etat, biensur si vous n'avez qu'un channel vous pouvez supprimer tous les autres.

Ifan
--------------

A suivre…



Compatibilitée
=========

Ce plugin est à ces débuts et pour pouvoir ajouter des équipements qui ne sont pas prévus, ou qui ne fonctionnent pas, il faut m'envoyer le fichier sync.json qui se trouve dans le dossier plugins/ewejee/core/js/sync.json
> **Important**
>	Ce fichier contient toutes les données que eWeLink posède, soit votre IP publique, l'apikey etc... 
>   Je n'ai pas besoin de ces informations presonnels, donc vous pouvez ouvrir ce fichier avec un éditeur de texte pour supprimer ces données.

Vous pouvez l'envoyer à l'adresse mail suivrante : wn68320@gmail.com

Je pourrais alors adapter le code afin de le rendre compatible.

Si vous avez des questions, surtout n'hésitez pas à me contacter, le mieux est par mail que je consulte régulèrement.




Changelog
=========

Changelog détaillé :
<https://github.com/jeedom/plugin-ewejee/commits/master>

Liste des équipements compatibles
=================================

<https://jeedom.github.io/documentation/#equipment>
