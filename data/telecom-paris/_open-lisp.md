# Title: Open LISP, implémentation open source du protocole LISP

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Recherche](https://www.telecom-paris.fr/fr/recherche "Recherche") > [Laboratoires](https://www.telecom-paris.fr/fr/recherche/labos "Laboratoires") > [Laboratoire Traitement et Communication de l’Information (LTCI)](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci "Laboratoire Traitement et Communication de l’Information \(LTCI\)") > [Logiciels libres et innovation](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci/logiciels-libres "Logiciels libres et innovation") > [Open LISP](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci/logiciels-libres/open-lisp)

[](https://www.telecom-paris.fr/fr/accueil)

# Open LISP, implémentation open source du protocole LISP

Implémentation open source du protocole LISP  
Lience : BSD license.  
Contributeurs : Luigi Iannone et al.

OpenLISP est une implémentation open source du protocole LISP fonctionnant
dans le noyau du système d’exploitation FreeBSD.

OpenLISP se concentre sur le fonctionnement du plan de données, ce qui
signifie qu’il implémente le cache LISP et la base de données LISP dans
l’espace du noyau, ainsi que les fonctions d’encapsulation/décapsulation. Tout
ce qui est lié au plan de contrôle est destiné à fonctionner dans l’espace
utilisateur.

OpenLISP ne fournit aucune implémentation spécifique du protocole du plan de
contrôle (c’est-à-dire qu’aucun protocole de distribution de la cartographie
n’est fourni). OpenLISP implémente plutôt un nouveau type de sockets, appelé
Mapping Sockets, qui fournit une API pouvant être utilisée par n’importe quel
processus de l’espace utilisateur.

[Site d'OpenLISP](http://www.openlisp.org "Site d'OpenLISP")

