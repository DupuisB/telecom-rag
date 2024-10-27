# Title: Salles de TP — Aide informatique  documentation

## Salles de TP > Aide informatique  documentation 

 [Aide informatique](https://doc.telecom-paris.fr/index.html)

  * [](https://doc.telecom-paris.fr/index.html) »
  * Salles de TP
  * 

* * *

# Salles de TP¶

## Postes disponibles et connexion¶

Toute personne ayant un compte à l’école a accès à l’une des 16 salles
informatiques, soit un peu plus de 500 ordinateurs récents. les salles de TP
sont disponibles pendant les horaires d’ouverture de l’école mais également à
toute heure à distance en SSH et en RDP (Bureau à distance sous Windows, et
rdesktop sous Linux).

Les personnels peuvent réserver les salles sur Synapses :
<https://synapses.telecom-paris.fr/>.

La liste complète des machines ainsi que leur statut est disponible à cette
adresse : <https://tp.telecom-paris.fr/>

Pour se connecter aux postes, vous devez utiliser les identifiants fournis
lors de la création de votre compte (login et mot de passe). Plusieurs
interfaces graphiques sont disponibles, mais la DSI recommande l’utilisation
de XFCE.

Pensez à bien vous déconnecter quand vous n’utilisez plus le poste.

## Configuration des machines¶

Les ordinateurs des salles tournent actuellement sous Linux Debian 12. De
nombreux logiciels sont installés sur les postes :

  * Matlab (avec toutes les toolbox)

  * Divers compilateurs

  * Anaconda

  * Virtualbox

  * etc

Il est possible d’ouvrir une session Windows directement à partir du menu de
connexion.

Les « home directory » des utilisateurs sont centralisés sur un serveur NFS,
et sont accessibles sur la machine dans le dossier : `/cal/homes/<LOGIN>`. La
place dans ce répertoire est très limitée mais les données sont sauvegardées
et accessibles depuis tous les postes.

Un espace local non sauvegardé est disponible dans `/home/users/<LOGIN>`.

## Machines virtuelles¶

Des machines virtuelles (VM) sont disponibles sur les postes. Dans les menus,
les VM sont accessibles via Applications ⇒ VMCatalog

Si vous souhaitez le déploiement d’une VM pour un cours, il faut nous la
fournir deux semaines avant le début du cours.

La VM doit être au format Virtualbox.

## Demande d’installation d’un logiciel¶

Il vous suffit de faire un ticket sur <https://sos.telecom-paris.fr/> en
détaillant le plus possible votre besoin. Vos demandes doivent être formulées
au moins trois semaines avant le début du cours.

## Utilisation des machines pour des calculs lourds¶

Vous pouvez recourir à ces machines pour des calculs dans le cadre de projets
académiques. Gardez à l’esprit que vous n’êtes pas les seuls à utiliser ces
machines ; arrangez vous pour que vos calculs n’aient lieu qu’en heures non
ouvrées (18h-8h) pour que les cours ne soient pas affectés.

## Accès à distance¶

Toute personne peut se connecter à distance aux salles informatiques via le
protocole SSH ou RDP.

Vous pouvez vous connecter en ssh directement sur le poste de votre choix si
vous avez préalablement activé le VPN sur votre ordinateur. Sinon, vous devez
d’abord vous connecter sur la machine passerelle `ssh.enst.fr` puis ensuite
sur le poste de votre choix.

L’autre moyen de se connecter aux postes des salles informatiques est
d’utiliser le protocole RDP. Pour cela, vous devez préalablement activer le
VPN sur votre ordinateur. La connexion RDP se fait en utilisant « Connexion
Bureau à distance » sous windows, ou un logiciel comme rdesktop sous Linux.

Pensez à bien vous déconnecter quand vous n’utilisez plus le poste.

