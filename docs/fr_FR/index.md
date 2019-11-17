
eWeJee
==============================

Description
-----------

Ce plugin à pour but d’intégrer à Jeedom TOUT vos équipements compatible eWeLink sans les flasher.
Grace à un bouton de synchronisation, un clic et tout vous équipements sont importé dans Jeedom.

> **Info**
>
> Le pugin passe par le cloud eWeLink

> ** IMPORTANT **
> eWeLink n'accepte qu'une seul connexion pas compte, donc dès que vous lancer le plugin, cela va déconnecter votre smartphone.
> Pour palier à cela, il est conseillé de faire une compte eWeLink pour Jeedom, vous pouvez partager vos équipements entre compte
> eWeLink.


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

Sur cette page vous devez rentrez votre login et mot de passe de l’application eWeLink.
Sauvgardez et cliquez sur verifier la connexion.

![login](../images/login.png)

> **Important**
>
> Il faut impérativement attendre 5 minutes après avoir lancé l'installation des dépendances.

Si vous avez le méssage "Echec d'authentification, veillez vérifier vos identifiants" : 

- Le mot de passe ne peut pas contenir de signe "$".
- Vérifiez vos identifants, le login doit etre l'adresse mail utilisé dans l'aplication eWeLink.
- Si vos identifiants sont correct, vérifiez que le démon est bien lancé et que les dépendances sont "OK".
- Regardez les log "eWeJee_node" dans la section "Logs et surveillance", les dernières lignes vous indique l'érreur, si vous ne la comprenez pas, contactez moi sur community.


Le plugin
=========

Rendez vous dans le menu Plugins &gt; objets connectés pour retrouver le plugin.

![plugin_obj_ewejee](../images/plugin_obj_ewejee.png)

Sur cette page, il vous suffit maintenant de cliquer sur le petit plus au-dessus de synchroniser pour synchroniser tous les équipements de l'application eWeLink.

![sync](../images/sync.png)

Une fois que c'est fait si vous ne voyez pas les équipements, recharger la page (CTRL + F5).

![sync2](../images/sync2.png)


Gestion
==========

Dans la partie gestion vous avez :
-	Synchroniser : Ce bouton sert à synchroniser tous les équipements de l'application eWeLink.
> **Info**
>	Une détection des equipements déjà connus à été ajouté, donc plus besoin de tout supprimer.
>	Si vous avez un equipement à acutaliser, supprimer le.
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
- L'objet parent.
- La catégorie.
- Une case de commentaire.

![onglet_equip](../images/onglet_equip.png)

> **Important**
> Le nom de l’équipement ne doit pas être changé il doit correspondre au nom que vous avez dans l’application.
> La case de commentaire peut-être utilisé comme vous le souhaitez, cela vous permet de mettre un commentaire à votre équipement.


Interrupteur / relais / prises
----------------------
Vous avez une commande action par « band » (Channel, cannal) qui effectue un "on" s’il est éteint et un "off" s’il est allumé et un équipement info qui vous indique s'il est allumé ou éteint.
Vous avez plusieurs moyens de metre à jour les commandes info : 

- La mise a jour se fait automatiquement dès qu'un changement d'état est éffectué (même en allumant un interrupteur sans passer par l'appli ou le plugin par exemple)
- Vous povuez mettre à jour manuellement avec le bouton suivant : 

![btn_update](../images/btn/update)

> **Info**
> Il est normal de voir plusieurs channel et etat même si votre equipement n'a qu'un channel, car dans la synchronisation 
> on récupère tous les paramètres et sonoff a 4 paramètres, et ceci même pour les equipements qui n'en ont qu'un seul.
> Vous pouvez suprimmer ceux qui sont en trop.

![onglet_cmd_switch2](../images/onglet_cmd_switch2.png)

Pour les relais utilisé en "contact sec", l'état de change pas car celui-ci envoi un "push" sur le relai.

Compatibilitée
=========

Ce plugin est à ces débuts et pour pouvoir ajouter des équipements qui ne sont pas prévus, ou qui ne fonctionnent pas, il faut m'envoyer le fichier sync.json qui se trouve dans le dossier plugins/ewejee/core/js/sync.json

> **Important**
>	Ce fichier contient toutes les données que eWeLink possède, soit votre IP publique, l'apikey etc... 
>   Je n'ai pas besoin de ces informations personnels, donc vous pouvez ouvrir ce fichier avec un éditeur de texte pour supprimer ces données.

Vous pouvez l'envoyer à l'adresse mail suivante : wn68320@gmail.com

Je pourrais alors adapter le code afin de le rendre compatible.

Si vous avez des questions, surtout n'hésitez pas à me contacter, le mieux est par mail que je consulte régulièrement.



Changelog
=========

Changelog détaillé :
<https://github.com/foulek57/jeedom-ewejee/blob/master/docs/fr_FR/changelog.md>

Liste des équipements compatibles à 100%
=================================

<http://www.google.com>
