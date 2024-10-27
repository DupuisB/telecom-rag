# Title: Ideas - Plongée au cœur de la consommation énergétique des algorithmes

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Ideas](https://www.telecom-paris.fr/fr/ideas "Ideas") > [Performance des algorithmes et maîtrise de l’impact carbone](https://www.telecom-paris.fr/fr/ideas/performance-algorithmes-maitrise-impact-carbone)

[](https://www.telecom-paris.fr/fr/accueil)

# Télécom Paris Ideas  
Performance des algorithmes et maîtrise de l'impact carbone

## Comment concilier performance des algorithmes et maîtrise de leur impact
carbone ?

Entretien avec Leonardo Linguaglossa, enseignant-chercheur à Télécom Paris,
avril 2023.

Mots-clés : basse consommation, économie d’énergie, optimisation, neutralité
carbone

Propos recueillis par Isabelle Mauriac

— Pourquoi avez-vous choisi de travailler sur l’empreinte carbone du numérique
?

On constate un intérêt croissant pour les sujets liés à la consommation
énergétique des services numériques. Aujourd’hui l’indicateur est le CO2
équivalent : tout peut être traduit en CO2 et les opérateurs téléphoniques ou
énergétiques nous envoient nos factures en mentionnant notre impact CO2. Or ce
qu’on appelle l’empreinte carbone correspond pour les services numériques en
partie à un algorithme qui doit être exécuté sur un serveur. Mais d’un autre
côté, cet impact carbone de nos algorithmes représente seulement une partie de
notre facture énergétique globale (et donc de nos émissions de CO2), car il
faut prendre aussi en compte l’énergie dépensée pour la fabrication de ce
serveur, le coût du transport du matériel, la durée de vie (plus elle est
longue plus on réduit l’impact carbone) : il existe de nombreuses variables.

— Les impacts en termes de consommation énergétique et donc d’émission carbone
sont-ils ceux que l’on croit ?

Je souhaiterais justement que ma recherche aide à préciser cela ! L’un des
objectifs de mon travail est de mesurer la part de la mise en œuvre des
algorithmes dans le système global. Par exemple si j’envoie un mail, je dois
prendre en compte le routage, le stockage et pas seulement les calculs, les
opérations que le serveur va réaliser. Je cherche aussi in fine à analyser les
compromis possibles entre les performances de l’algorithme et sa consommation
énergétique. J’interroge aussi l’impact d’une réduction de la puissance de
calcul sur les émissions de CO2. Est-il significatif ou à la marge ? Tout cela
demande d’évaluer avec plus de précision quels sont les postes les plus
significatifs de notre empreinte carbone. Aujourd’hui on ne peut ps le dire
avec précision.

  * 

« Tout cela demande d’évaluer avec plus de précision quels sont les postes les
plus significatifs de notre empreinte carbone. Aujourd’hui on ne peut pas le
dire avec précision. »

— Concrètement, comment cela pourrait se passer ? Quel seraient ces compromis
?

Cela se joue sur les deux terrains : quelle est la part de la consommation
énergétique des algorithmes dans le fonctionnement du numérique, mais aussi
peut-on réduire cette consommation par des arbitrages ? Puis-je déployer une
partie de ces calculs dans des dispositifs à basse consommation énergétique
par exemple ? (je pense aux raspberry, dispositifs embarqués de la taille
d’une carte bleue, moins puissants mais qui consomment beaucoup moins que les
serveurs). Est-il possible d’éteindre les serveurs plutôt que de les faire
tourner en continu ? Par exemple, dès que l’on fait une recherche sur Google,
un data center est en train de tourner. Ce n’est pas le cas pour le routage
des e-mails où les serveurs ne sont pas actifs en permanence.

Mais parfois les alternatives ne valent pas le coup d’être mises en place. Les
performance d’un système basse consommation sont bien inférieures et il faut
le mettre en regard cet impact avec la réduction effective des émissions de
CO2. Et puis bien évaluer si l’impact de l’algorithme est vraiment
significatif. La consommation énergétique EDF est-elle corrélée au calcul
nécessaire pour effectuer cet algorithme ou non ? Si je déploie mes
dispositifs basse consommation, vais-je consommer beaucoup moins d’électricité
en gardant un certain niveau de performance ou non ? Et à partir de cela,
quelles sont les autres variables impliquées dans la consommation énergétique
globale ? Il est important de bien identifier où se trouvent les centres
majeurs de consommation pour ne pas se tromper de cible.

  * 

« Cela se joue sur les deux terrains : quelle est la part de la consommation
énergétique des algorithmes dans le fonctionnement du numérique, mais aussi
peut-on réduire cette consommation par des arbitrages ? »

— Aujourd’hui, qui à votre avis a le plus d’impact sur la consommation
énergétique des algorithmes?

Les plus gros consommateurs sont sans nul doute l’infrastructure du cloud et
bien sûr le minage des bitcoin qui nécessite des calculs considérables et des
dispositifs énergivores qui tournent en permanence.

Une chose est sûre : l’impact de chacun de nous, singulièrement, est bien
moindre que celui des entreprises ou des organisations. Ma conviction est
qu’une décision individuelle a aujourd’hui moins d’impact qu’autrefois, tant
il existe de variables. Ainsi je ne suis pas à l’aise quand je reçois ma
facture EDF ou celle de mon opérateur de portable indiquant mon impact CO2. En
tant que consommateur, je ne suis responsable que d’une partie du bilan
carbone et ma consommation individuelle n’est sans doute pas le meilleur
indicateur au regard de l’ensemble des services numériques utilisés tout au
long de la chaîne de valeur. Il n’est pas facile aujourd’hui d’avoir accès à
des bases de données fiables permettant de comparer réellement ces ordres de
grandeur. D’ailleurs on peut aussi s’interroger sur les métriques utilisées…
Aujourd’hui il n’existe pas de méthode de calcul partagée. Chaque entreprise
peut s’appuyer sur des métriques pour affirmer que son data center est green
ou qu’il est « CO2 neutre ». Cette question doit a minima être traitée par les
politiques publiques au niveau communautaire.

  * 

« Aujourd’hui il n’existe pas de méthode de calcul partagée. Chaque entreprise
peut s’appuyer sur des métriques pour affirmer que son data center est green
ou qu’il est “CO2 neutre” »

— Comment les entreprises se positionnent aujourd’hui ?

Beaucoup d’entreprises cherchent aujourd’hui à absorber leur empreinte carbone
en disant « Je vais neutraliser mon empreinte carbone en finançant des projets
qui vont absorber l’équivalent de mes émissions de CO2 ». Mais quand Google
échange ses tonnes de CO2 émises contre le financement de projets pour
l’énergie solaire ou la plantation d’arbres, on ne peut parler d’équivalence à
cause du décalage dans le temps de ces projets : alors que les émission sont
instantanées, les compensations en termes d’absorption ou d’économie de CO2
sont décalées dans le temps. C’est flagrant dans le cas des plantations de
forêts où ce décalage se mesure en dizaines d’années…

De plus, pour arriver à compenser, faut-il déjà évaluer de façon cohérente. Il
manque une méthodes de calcul bien formalisée et partagée.

— Quels sont les freins à la mise en œuvre par les entreprises d’une politique
numérique vertueuse en termes d’émission de CO2 ?

Il faudrait une vraie convergence d’opinion et des politiques gouvernementales
volontaristes, comme ce fut le cas par exemple pour résorber le trou dans la
couche d’ozone, où le gouvernement avait imposé des normes très strictes aux
producteurs de réfrigérateurs et de climatiseurs, contraints à ne pas utiliser
certains gaz. Dans ce cas précis, peu d’acteurs avaient beaucoup d’impact sur
l’émission de gaz à effet de serre. Aujourd’hui le numérique, l’alimentation,
l’agriculture, les transports… tous les secteurs ont un impact carbone, ce qui
complique la donne. Et les politiques divergent. Il suffit qu’un pays se
retire de l’accord pour pousser certaines entreprises à échapper au système.
Enfin, la pression du consommateur/citoyen sur les émissions de CO2 n’est pas
assez forte car l’utilisateur final n’a pas la perception immédiate de ce
qu’il pourra gagner.

Pour prendre l’exemple de la souveraineté et de la protection des données, en
Europe, le RGPD est plus strict que la réglementation américaine : les
fournisseurs de services sont contraints à plus de contrôles mais en échange
offrent plus de protections au consommateur. Celui-ci paiera peut-être le
service (l’hébergement de son site Internet par exemple) un peu plus cher en
Europe mais aura comme contrepartie la protection de ses données. Beaucoup
d’entreprises attirées par le régime de protection des données plus laxiste
outre-Atlantique ont d’ailleurs été rappelées à l’ordre par les consommateurs
qui ne voulaient pas que leurs données soient localisées aux États-Unis. Pour
le contrôle des émissions de CO2, la contrepartie est moins visible et ne
bénéficie pas directement à l’utilisateur. Elle est plus diffuse dans le temps
également. Or les êtres humains sont moins à l’aise avec les décisions à long
terme. Si un peu plus de CO2 est consommé, on jugera qu’il n’y a pas d’impact
immédiat… ce qui est faux ! C’est donc un sujet plus compliqué où chacun ne
voit pas directement l’avantage de réduire sa consommation énergétique.

[](https://www.telecom-paris.fr/fr/ideas/sommaire)

