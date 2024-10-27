# Title: Ideas - Lutter contre les biais des algorithmes de recommandation sur les réseaux sociaux

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Ideas](https://www.telecom-paris.fr/fr/ideas "Ideas") > [Contre les biais des algorithmes de recommandation](https://www.telecom-paris.fr/fr/ideas/contre-biais-algorithmes-recommandation)

[](https://www.telecom-paris.fr/fr/accueil)

# Télécom Paris Ideas  
Contre les biais des algorithmes de recommandation

## Lutter contre les biais des algorithmes de recommandation sur les réseaux
sociaux  

[Charlotte Laclau](https://laclauc.github.io/), maîtresse de conférences à
Télécom Paris, juin 2024

[](https://www.telecom-paris.fr/wp-content-EvDsK19/uploads/2022/12/charlotte-
laclau.jpg)Charlotte Laclau nous parle de l’un de ses sujets de recherche :
les algorithmes appliqués aux réseaux sociaux. Qu’il s’agisse de fake news, de
violences en ligne ou de manipulation électorale, ces algorithmes sont souvent
accusés de favoriser la diffusion de contenus générés par l’intelligence
artificielle. Alors, comment fonctionne la modération sur les réseaux sociaux
et comment leurs algorithmes peuvent créer des bulles sociales en ligne ?

Propos recueillis par Isabelle Mauriac

### Podcast

Retrouvez cette interview en format audio dans le cadre des [podcasts Télécom
Paris Ideas](https://podcast.ausha.co/telecom-paris-ideas) :

Podcast Michel Desnoues, Télécom Paris

## Pourquoi les réseaux sociaux ?

— Charlotte, pourriez-vous nous présenter vos travaux de recherche sur ce
sujet et expliquer pourquoi vous avez choisi les réseaux sociaux comme terrain
d’exploration ?

Je fais des recherches en apprentissage automatique, une sous-branche de
l’intelligence artificielle, et je m’intéresse particulièrement aux graphes,
dont les réseaux sociaux sont un exemple bien connu. Mon travail porte sur la
prédiction de liens, c’est-à-dire comprendre quelles personnes sont
susceptibles de se connecter à l’avenir.

— Avant d’entrer dans le détail de votre travail, pourquoi avoir choisi les
réseaux sociaux comme terrain d’exploration ? Est-ce parce qu’ils ont pris une
ampleur considérable dans nos vies et représentent des enjeux importants en
termes d’interaction sociale et politique ?

Effectivement, les graphes sont présents dans de nombreux domaines, mais les
réseaux sociaux sont particulièrement intéressants pour moi car ils permettent
d’étudier les biais, notamment les discriminations, et la question plus large
de l’équité. Les réseaux sociaux se prêtent bien à l’exploration de ces
problématiques. Je m’intéresse aux biais présents dans les algorithmes de
recommandation de liens sur ces graphes, et plus récemment à l’impact des
politiques visant à imposer l’équité.

Nous avons constaté que les réseaux sociaux, étant dynamiques, peuvent voir
leurs biais évoluer dans le temps. Si nous imposons une forme d’équité dans la
recommandation, nous devons nous assurer que cela réduira les biais à long
terme.

  * 

— Comment mesurez-vous l’impact à long terme de ces politiques ?

Avec de la simulation. Le principe est d’essayer de trouver des modèles qui
vont être capables de comprendre la manière dont justement les graphes
évoluent, donc d’appréhender leurs dynamiques. Et en fonction, une fois qu’on
a un modèle qui est capable de faire ça correctement, qui va pouvoir simuler
la manière dont le graphe va évoluer dans le temps, d’être capable d’aller
jouer un petit peu avec différents types d’algorithmes qui ferait la
recommandation, par exemple certains qui seraient contraints à des formes de
non-discrimination.

— Les réseaux sociaux ne sont pas homogènes. Comment prenez-vous en compte
leurs différences ?

De ce fait, il faut un modèle qui soit le plus général possible, c’est-à-dire
qu’aujourd’hui, en apprentissage, on a quand même la capacité d’aller
apprendre des modèles qui sont très complexes, et s’appliquent bien à tous
types de données. Donc l’idée est d’aller chercher un modèle qui va pouvoir
être entraîné sur différents types de graphes en fonction de ce qu’on cherche
à modéliser et qu’on va pouvoir ensuite utiliser pour faire de la simulation.
Bien évidemment, on n’aura peut-être pas le même modèle qui sera appris, par
exemple sur un graphe de type extraction de Facebook ou un graphe de type
LinkedIn, par exemple, un graphe professionnel qui va avoir une structure
potentiellement différente.

## Biais et bulles sociales

— Quels sont les principaux biais que vous avez identifiés ?

Nous examinons les préjudices causés par les algorithmes selon divers facteurs
comme le genre, la localisation ou l’affiliation politique. Nous allons
vouloir nous assurer que, de ce fait, sur les réseaux sociaux, les tâches qui
sont gérées par des algorithmes de machine learning ou d’apprentissage
automatique ne sont pas biaisées par l’un de ces facteurs. Par exemple, pour
l’affiliation politique, nous voudrions nous assurer que le système de
recommandation ne va pas créer ce qu’on appelle des bulles sociales sur le
réseau.

— De ce fait, vous parlez des bulles sociales… Mais n’est-ce pas un peu le
principe même des réseaux sociaux que de constituer des communautés qui
interagissent entre elles, non ?

Effectivement, l’idée est que l’on cherche naturellement à se connecter avec
des personnes qui nous ressemblent. Cette ressemblance peut se baser sur des
goûts musicaux, littéraires ou simplement sur des centres d’intérêt communs.
Cela semble logique. Toutefois, si l’on pense aux réseaux sociaux, il y a
aussi des réseaux professionnels, comme LinkedIn. Dans un réseau comme celui-
ci, on ne souhaite pas que des bulles se créent autour de groupes
majoritaires, par exemple, des hommes d’une certaine couleur de peau. Le
risque est que les algorithmes créent ces bulles.

Sur les réseaux professionnels, c’est aussi un problème. L’affiliation
politique sur les réseaux sociaux peut poser problème également. Aujourd’hui,
une grande partie de la population s’informe via les réseaux sociaux, et si
les algorithmes recommandent des personnalités ou des articles basés sur une
appartenance politique, cela crée un biais problématique.

— Mais ce genre de biais n’est pas tellement modéré. C’est compliqué à gérer,
car les réseaux sociaux sont conçus pour répondre à nos requêtes. Sauf cas de
force majeure, comme les fake news ou la violence en ligne, cela semble
difficile ?

Effectivement, ce n’est pas un problème de modération, qui s’applique au
contenu en lui-même. Ici, il s’agit de « débiaiser » l’algorithme derrière la
recommandation. Les algorithmes, comme ceux de LinkedIn, Facebook ou
Instagram, utilisent l’apprentissage automatique. Ils exploitent les
informations trouvées sur Internet, comme ce que nous indiquons sur nos
profils. Le problème est que ces algorithmes peuvent privilégier des critères
comme le genre, créant ainsi des bulles implicites et homogènes sans que
l’utilisateur ne s’en rende compte. Cela pose des problèmes particuliers sur
les réseaux professionnels comme LinkedIn, où l’on ne souhaite pas que le
réseau soit biaisé par certains critères lors de la recherche d’emploi, par
exemple.

— Les algorithmes sont entraînés par nos usages et nos requêtes. Ainsi, n’y
a-t-il pas un peu l’image du serpent qui se mord la queue, puisque nous les
éduquons potentiellement à mal faire et à reproduire nos biais ?

C’est là toute la difficulté de travailler sur les biais des algorithmes. Ils
sont entraînés sur nos données, qui reflètent nos comportements.

  * 

Par exemple, si j’entraîne un algorithme pour un chasseur de têtes, une
intelligence artificielle chargée de trouver les meilleurs profils pour un
emploi, et que j’utilise des données biaisées issues de chasseurs de têtes
précédents, ces biais seront reproduits dans les décisions de l’algorithme.

Le défi consiste donc à s’assurer que les données utilisées pour
l’entraînement sont les moins biaisées possible et à vérifier que l’algorithme
ne puisse pas retrouver des signaux biaisés dans les données, malgré nos
efforts. Les algorithmes sont très puissants et peuvent, malgré nous, détecter
ces biais. Un algorithme n’est pas intrinsèquement biaisé : c’est un ensemble
de lignes de code et un modèle mathématique, sans préjugés initiaux. Les biais
apparaissent parce que nous les avons. Ainsi, il y a effectivement ce
phénomène du serpent qui se mord la queue. Cependant, si nous parvenons à
utiliser des algorithmes de moins en moins biaisés, nos comportements
pourraient s’améliorer, en créant un cercle vertueux qui nous aidera à
éliminer ces biais.

Quant à la manipulation des algorithmes, elle est possible. Comme je l’ai
mentionné, les algorithmes fonctionnent sur des principes assez classiques,
utilisant toujours le même type de données en entrée, ce qui peut être
difficile à contrôler. Toutefois, des recherches sont en cours pour auditer
ces algorithmes de recommandation et comprendre leurs décisions, ce qui
pourrait limiter les manipulations. Il y a aussi une demande croissante de
transparence sur les décisions algorithmiques. Cependant, la recette peut être
biaisée, par exemple en fournissant de fausses informations. Il y a eu des cas
où des avis clients étaient en réalité faux, influençant ainsi les
recommandations. Bien que des solutions émergent pour limiter ces
manipulations, il est peu probable que nous en soyons totalement à l’abri.

## Quelles obligations pour les acteurs de la tech ?

— Concernant les GAFAM (Google, Apple, Facebook, Amazon, Microsoft), ont-elles
pris la mesure des biais et des risques potentiels ?

Oui, elles en sont conscientes. Ont-elles envie d’agir significativement ? Ce
n’est pas évident. Lorsque les problèmes d’équité dans l’apprentissage
automatique ont émergé, des équipes de recherche dédiées ont été créées chez
Google et Meta. Cependant, cet intérêt s’est quelque peu essoufflé, notamment
avec les récents licenciements dans ces entreprises, touchant souvent ces
équipes spécialisées. Les GAFAM ont pris conscience du problème, mais leurs
obligations restent floues.

— Quelle peut être l’influence de la nouvelle législation européenne sur l’IA
?

L’[AI Act](https://www.telecom-paris.fr/fr/ideas/ai-act-game) a en effet été
voté en mars au niveau européen : il est censé régir la manière dont on doit
s’assurer justement que les algorithmes développés et mis en production sont
transparents, explicables, mais également équitables. C’est une législation
qui ne mentionne pas de critères particuliers à prendre en compte, qui donne
des définitions assez vagues de ce que doit être un algorithme équitable, ce
qui va laisser à mon avis la place à beaucoup d’interprétations différentes.

Néanmoins on se dirige vers une législation qui va obliger finalement les
entreprises, GAFAM ou autres, à intégrer ces critères-là lorsqu’elles
développent des algorithmes d’apprentissage automatique.

  * 

[](https://www.telecom-paris.fr/fr/ideas/sommaire)

