# Title: RAMSES, conception de systèmes temps réel embarqués critiques

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Recherche](https://www.telecom-paris.fr/fr/recherche "Recherche") > [Laboratoires](https://www.telecom-paris.fr/fr/recherche/labos "Laboratoires") > [Laboratoire Traitement et Communication de l’Information (LTCI)](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci "Laboratoire Traitement et Communication de l’Information \(LTCI\)") > [Logiciels libres et innovation](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci/logiciels-libres "Logiciels libres et innovation") > [RAMSES](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci/logiciels-libres/ramses)

[](https://www.telecom-paris.fr/fr/accueil)

# RAMSES

Conception des systèmes temps réel embarqués critiques.  
Lience : Eclipse Public License.  
Contributeurs : Étienne Borde et al.  

RAMSES est une plateforme d’aide à la conception des systèmes temps réel
embarqués critiques. Ce terme technique désigne des systèmes embarqués dont la
dimension temporelle est particulièrement importante : si une opération
informatique prend plus de temps que prévu pour être réalisée, il peut y avoir
une défaillance critique du système. D’un point de vue logiciel, le temps est
géré par un système d’exploitation temps-réel dont RAMSES automatise la
configuration tout en garantissant le respect des exigences temporelles du
système.

[RAMSES, maître du temps des systèmes
embarqués](https://blogrecherche.wp.imt.fr/2018/08/29/ramses-systemes-
embarques/)

Interview d’Etienne Borde sur le blog I’MTech

Les développeurs écrivent usuellement leurs systèmes à la main dans le langage
de programmation de leur choix, ou en générant ce code à partir d’un modèle.
Ils peuvent évaluer le temps de transmission des données sur le produit final,
mais avec une faible traçabilité par rapport au modèle de départ. Si une
commande prend plus de temps que prévu, les développeurs peuvent difficilement
isoler l’étape qui pose problème.

RAMSES fournit des représentations intermédiaires au fur et à mesure de sa
réalisation. L’outil analyse le temps associé à chaque tâche pour vérifier
qu’il n’y a pas de dérives excessives. Dès qu’une accumulation de mécanismes
introduit une trop forte divergence par rapport aux bornes temporelles
imposées, RAMSES alerte le développeur. La plateforme peut indiquer quelles
sont les étapes qui posent problème et ainsi faciliter la correction du code
AADL.

### RAMSES : focus technique

RAMSES (Refinement of AADL Models for Synthesis of Embedded Systems) est un
compilateur du [langage
AADL](https://fr.wikipedia.org/wiki/Architecture_Analysis_and_Design_Language)
qui permet de décrire des architectures informatiques. C’est un outil de
transformation de modèle et de génération de code C pour les systèmes
d’exploitation compatibles POSIX, ARINC653 ou OSEK. RAMSES s’interface avec
OSATE2 et propose une interface de ligne de commande à OSATE2. RAMSES procède
par raffinement dans la mesure où il produit une version simplifiée d’un
modèle AADL comme étape intermédiaire vers la génération de code. Ce modèle
simplifié comprend une sous-clause d’annexe de comportement qui exprime le
comportement résultant de l’expansion des composants AADL.

[Site de RAMSES](https://mem4csd.telecom-paristech.fr/blog/index.php/ramses/
"Site de RAMSES")

