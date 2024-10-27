# Title: Ideas - L’IA appliquée à l’imagerie médicale : les enjeux pour accéder à la data et comment rendre l’IA performante avec peu de données ?

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Ideas](https://www.telecom-paris.fr/fr/ideas "Ideas") > [L’IA appliquée à l’imagerie médicale : les enjeux des données](https://www.telecom-paris.fr/fr/ideas/ia-imagerie-medicale-donnees)

[](https://www.telecom-paris.fr/fr/accueil)

# Télécom Paris Ideas  
L’IA appliquée à l’imagerie médicale : les enjeux des données

## L’IA appliquée à l’imagerie médicale :  
  
quels enjeux pour accéder à la data et comment rendre l’IA performante avec
peu de données ?

[Elsa Angelini](https://perso.telecom-paristech.fr/angelini/) et [Pietro
Gori](https://www.telecom-paris.fr/pietro-gori), enseignants-chercheurs à
Télécom Paris, sept. 2023.

Quelles promesses porte l’intelligence artificielle dans le traitement de
l’imagerie médicale ? Les enjeux pour accéder à la data sont considérables,
pour entraîner les algorithmes d’IA et faire progresser l’identification et la
recherche sur les maladies. Mais comment cela fonctionne t-il ? Qu’entendons-
nous par data en imagerie médicale ? Quels sont les moyens d’accéder à la data
et comment rendre l’IA performante avec peu de données ? Quelles sont les
initiatives pilotées par les États ?

Elsa Angelini et Pietro Gori nous livrent leur éclairage sur ces enjeux
cruciaux afin de garantir les progrès dans la détection, la prévention ainsi
que la compréhension des maladies.

Propos recueillis par Isabelle Mauriac

## Podcast

Retrouvez cette interview en format audio dans le cadre des [podcasts Télécom
Paris Ideas](https://podcast.ausha.co/telecom-paris-ideas) :

Podcast Michel Desnoues, Télécom Paris

## Entretien

— Pour rentrer dans le vif du sujet, pouvez-vous nous dire tout d’abord, Elsa,
ce que l’on entend par data en imagerie médicale ?

En imagerie médicale, on a la chance de travailler sur plusieurs types de
modalités, qui sont très différentes. Les principales modalités sont les IRM,
la radiographie et la version tridimensionnelle ou scanners – on parle de CT
–, et l’échographie, principalement. Il y a aussi l’imagerie nucléaire, sur
laquelle on a été amenés à travailler un peu. Et enfin il y a de plus en plus
de ce qu’on appelle l’imagerie optique, qui sert aussi à étudier l’intérieur
du corps humain et faire des diagnostics.

— On voit que les données d’imagerie médicale sont déjà de type très différent
suivant les modalités d’acquisition, mais il y a bien d’autres sources de
données que celles-là… Pouvez-vous nous parler de ces données médicales
complémentaires, qui seront notamment essentielles à la « médecine
personnalisée » de demain ?

Tout à fait. Le reste des données sont qu’on appelle des métadata, qui
viennent avec les images et qui peuvent inclure plusieurs types de données.
Les plus classiques, ce sont les informations sur le patient, telles que
l’âge, le sexe, l’indice de masse corporelle, etc. Mais il y a aussi des
données plus complexes, des dosages sanguins, par exemple, qui peuvent venir
avec les images, ou de plus en plus, on s’oriente vers des données vraiment
très complexes, tout ce qui est marqueurs génétiques ou protéomiques. De plus
en plus dans notre domaine de recherche, on est amenés à travailler avec des
données hétérogènes, donc à avoir une connaissance qui va au-delà de la
physique des images médicales, déjà assez vaste. Et cette profusion de data
nous pousse à réfléchir à la manière dont on va intégrer ces données dans les
algorithmes, comment on va formuler le problème qui nous est posé, et comment
on va le résoudre ensuite.

— Donc il y a toutes ces données, mais aussi les annotations… Un algorithme
d’IA n’a pas seulement besoin d’images et de variables cliniques, il a aussi
besoin d’annotations de ces images médicales, qui lui indiquent par exemple où
est la maladie et quel sujet est malade ou est sain. Pouvez-vous nous en
parler ?

Effectivement, dans la phase de montage, notamment de nos jours, dans tout ce
qu’on appelle les approches d’apprentissage statistique et, plus globalement,
d’IA, il y a deux enjeux. D’abord, c’est travailler non seulement sur une
image, mais sur des cohortes d’images qui nous permettent d’apprendre vraiment
sur une population assez diversifiée, ce qu’est, par exemple, un certain type
de tumeur, et comment aller la détecter à l’intérieur du corps. Et ensuite ce
sont les annotations.

Sur l’aspect des cohortes, il faut savoir qu’il n’y a pas un seul type de
cohorte, mais plusieurs.  
Nous sommes amenés à nous demander très en amont si on préfère aller chercher
des cohortes rétrospectives ou prospectives, c’est-à-dire travailler sur des
choses qui ont déjà été acquises, mais les réutiliser pour autre chose, ou
alors vraiment construire, par exemple avec une équipe de médecins, une série
d’acquisitions qui vont être très propres, bien ciblées sur une population de
patients… Cela s’appelle des prospectifs. Et ensuite, il y a deux types de
cohortes aussi, qui pour le coup existent déjà, et qui peuvent être utilisées,
qui sont soit des registres, soit des cohortes cliniques. L’intérêt des
registres, c’est que ce sont des cohortes déjà nettoyées, qui ont déjà été
préparées pour être étudiées plusieurs fois par plusieurs équipes de
chercheurs, et partagées. Donc elles sont nettoyées, avec des aspects de
format de données qui sont importants, mais aussi anonymisées, et cela est
évidemment essentiel pour tout accès par des chercheurs.

Il y a des cohortes qui existent dans nos domaines, totalement open access,
par exemple, quand on participe à des challenges, de plus en plus populaires
dans nos conférences. Il y a aussi des cohortes un peu plus régulées, à propos
desquelles il faut justifier un projet qu’on a en tête, puis qu’on se mette
d’accord sur les conditions et les coûts d’accès et de maintenance. UK
Biobank, par exemple, est partagé sur ce même modèle-là. Et enfin, il y a les
cohortes cliniques, pour lesquelles c’est beaucoup plus compliqué, parce qu’il
faut discuter directement avec l’hôpital et se mettre d’accord sur un
protocole de recherche, et ensuite les conditions d’accès aux données.

L’autre partie, ce sont les annotations, parce qu’une fois qu’on a la cohorte,
il faut aussi être sûr qu’on a les bonnes annotations dont on a besoin pour
les images. Elles sont de deux types : soit du contourage ou des petits points
de marqueurs qui indiquent, par exemple, où est la lésion dans le cerveau, ou
bien où est la tumeur dans l’abdomen, soit c’est plus au niveau de l’image
elle-même qui nous indique juste la présence d’une lésion pancréatique sans en
savoir plus, par exemple. Cela s’appelle des annotations de bas niveau ou de
haut niveau. Et tout cela est très chronophage à préparer et à structurer,
demande beaucoup de temps d’expert pour le contourage, ou même de
l’interopérabilité entre bases de données, si on veut disposer d’annotations à
un niveau fiable. Donc, c’est rare et cher. On fait des progrès dans les
outils d’annotations qu’on fournit au médecin, pour qu’ils aillent plus vite
et qu’ils puissent faire ça plus rapidement. Mais quoi qu’il arrive, nous
aussi, pour préparer l’avenir de façon un peu robuste…

  * 

… on réfléchit de plus en plus à des algorithmes qui n’ont pas besoin de
beaucoup d’annotations de bas niveau, ou alors qui n’ont besoin que
d’annotations de haut niveau pour faire le même diagnostic et fournir la même
assistance au médecin, par exemple : qui ait la même valeur, mais avec moins
d’annotations, ou moins détaillées.

— Il y a donc ce sujet du recours à moins d’annotations et globalement, il y a
le sujet du manque de données pour faire travailler l’intelligence
artificielle, pour la faire progresser. Pour entraîner les algorithmes, on a
besoin de beaucoup de data… Or, l’IA appliquée à l’imagerie médicale souffre
justement d’un manque de données. Pietro, pouvez-nous nous en parler ?

Déjà, il faut dire pourquoi il y a besoin de données. L’intelligence
artificielle et plus particulièrement l’apprentissage (aujourd’hui, on entend
beaucoup le terme deep learning) a besoin de beaucoup de données et la donnée
est devenue une ressource très chère, très importante.

En imagerie médicale, il existe peu de données, c’est le premier point. Et
comme, justement, Elsa l’a rappelé, c’est aussi difficile d’accéder à ces
données parce qu’on a plusieurs bases des données.

On ne peut pas accéder à toutes les bases des données pour des questions de
sécurité, de privacy, ce qui est normal. Donc, la question qu’effectivement
beaucoup de chercheurs se posent, c’est comment faire mieux avec peu de
données.

Et il y a une deuxième question qui, je pense, est très spécifique à
l’imagerie médicale, toujours liée au manque de données, qui est la diversité
et les biais de données.

Évidemment, on voudrait créer des algorithmes d’IA et d’apprentissage qui
peuvent être généralisés à toute la population humaine. Mais ce qui se passe
en pratique, c’est qu’on a des petits jeux de données et qui souvent sont, par
exemple, acquis dans un seul hôpital, avec un seul protocole, une même
machine. C’est ce que l’on appelle « l’effet site », c’est-à-dire que
l’algorithme d’IA est entraîné sur un jeu de données très spécifique. Cela
veut dire que si on a amené à l’utiliser sur d’autres sujets qui viennent
d’autres hôpitaux, cela ne marchera pas, il n’aura pas la même performance,
parce qu’il a appris sur un jeu de données très précis. On parle de biais de
données dans ce cas-là, et notre activité de recherche consiste à trouver les
biais, parce qu’on ne les connaît pas tout le temps, et une fois qu’on les a
identifiés, d’essayer de les éliminer dans les algorithmes.

— Et vous, Pietro, comment réfléchissez-vous à cette problématique ?

Avec Elsa, nous faisons partie de l’équipe [Images](https://www.telecom-
paris.fr/fr/recherche/laboratoires/laboratoire-traitement-et-communication-de-
linformation-ltci/les-equipes-de-recherche/image-modelisation-analyse-
geometrie-synthese-images) de Télécom Paris. Nous sommes sollicités par des
hôpitaux et des industriels, surtout pour développer des algorithmes qui
soient plus efficaces et robustes. Plus efficaces, c’est-à-dire qui utilisent
de moins en moins d’annotations et des données, ce dont on vient de parler.
Également, dans le sens où dans les hôpitaux, la plupart du temps, les données
ne peuvent pas sortir, et que les données doivent être analysées à l’intérieur
des hôpitaux, qui n’ont pas de grands serveurs de calcul. Par conséquent, nos
algorithmes d’IA doivent pouvoir être déployés à l’intérieur de l’hôpital, et
donc, doivent être efficaces.

Puis il y a une spécificité de notre équipe : nous sommes à Télécom Paris,
dans une école d’ingénieur, pas dans une grande université associée à une
faculté de médecine, comme cela se pratique à l’étranger. Et nous ne sommes
pas non plus une équipe INRIA ou CNRS, qui est à l’intérieur d’un hôpital.

Nous travaillons avec beaucoup d’hôpitaux sur plusieurs applications
cliniques, donc…

  * 

… notre cœur de métier consiste vraiment à développer des méthodes d’analyse
d’image, d’interprétation d’images, d’IA, d’apprentissage, pour que ce soit
robuste et efficace et que cela puisse bénéficier à plusieurs applications
cliniques, avec plusieurs partenariats, à la fois des hôpitaux et des
industriels.

— Et sur ces questions d’accessibilité de la data, quel est le contexte
international et y a-t-il des modalités d’accès variables aux données ? Quels
sont les pays les plus en avance sur le sujet ?

À l’international, il y a plusieurs niveaux de maturité de création de
registres de données médicales, ainsi que de structuration à grande échelle.
On a besoin là d’animations ou d’initiatives qui soient pilotées au niveau
national, ce qui commence à émerger en France, mais cela se fait déjà dans
d’autres pays qui sont plus avancés que nous. Donc, par exemple, on peut
citer, encore une fois, UK Biobank en Angleterre qui couvre vraiment la
population anglaise globalement, à travers tout le pays, qui la suit depuis
plusieurs années maintenant, et régulièrement acquiert une batterie d’examens,
dont des examens d’imagerie, sur des participants volontaires, parmi les
Anglais dès leur majorité. Cela a généré un nombre de papiers et de progrès
très importants sur la compréhension de maladies chroniques, notamment
cardiovasculaires, ainsi que les liens avec des problèmes complexes, tels que
l’exposome : l’effet, par exemple, de la pollution ou de l’endroit où on vit
sur l’évolution ou l’émergence de différentes pathologies. C’est un très bel
exemple, qui fonctionne très bien.

Il y a d’autres pays qui sont structurés ainsi à l’échelle nationale depuis
plusieurs années, comme le Danemark, dont les données de la population entière
sont vraiment structurées a priori, dès le passage à l’hôpital, en registres
pour pouvoir être mises à disposition pour des projets de recherche. Et puis,
il y a les États-Unis, où le NIH (l’équivalent de notre ANR en France)
investit énormément d’argent, et depuis plusieurs années, pour financer des
cohortes de recherche ou des registres qui vont pouvoir être réutilisés par
les équipes de chercheurs qui en font la demande et qui sont acceptées ensuite
dans des protocoles d’accès assez simples.

— Et plus précisément, comment cela se passe en France ?

Tout d’abord, il existe des projets européens. Des appels à projets visaient à
accéder à de la data et fédérer des équipes, structurer la donnée, avec l’idée
aussi d’impliquer des industriels, petits et moyens, pour qu’ils viennent en
soutien à tout l’effort que cela demande derrière, au niveau de la
structuration de ces bases de données. Il existe des projets en cours pour
essayer de mettre en œuvre des cloud européens, hébergeurs de données de
santé, qui soient ensuite accessibles plus facilement. L’effort national est
sans doute le plus important, et en France le HDH (health data hub), a
entrepris depuis quelques années d’animer ce genre d’effort, de structurer et
de lancer la dynamique nationale.

Puis de plus en plus, dans les hôpitaux, des initiatives d’association sont
lancées. Par exemple, nous avons la chance d’être dans le Paris Saclay Cancer
Cluster, qui investit dans la data, en mettant l’argent dans les hôpitaux,
afin justement qu’ils structurent, nettoient leurs données et les rendent
accessibles à toute une communauté nationale de chercheurs et d’industriels
soutenant et développant de nouvelles solutions pour l’innovation et pour les
nouvelles thérapies contre le cancer en France.

## Vidéos

Pour afficher ce contenu, merci d’accepter les cookies des vidéos Youtubedes
extraits de réseaux sociaux (Twitter, Instagram & Facebook).To display this
content, please accept third party cookies for Youtube videosFacebook,
Instagram and Linkedin excerpts.

Réglages

« Nous travaillons avec des données très différentes (IRM, scanner, radio,
échographie, imagerie optique). Il faut aussi avoir accès à des métadonnées
(âge, sexe, IMC du patient) ainsi que, de plus en plus, aux diagnostics
cliniques. »  

Pour afficher ce contenu, merci d’accepter les cookies des vidéos Youtubedes
extraits de réseaux sociaux (Twitter, Instagram & Facebook).To display this
content, please accept third party cookies for Youtube videosFacebook,
Instagram and Linkedin excerpts.

Réglages

« En imagerie médicale, nous avons un problème de manque de données. À Télécom
Paris, nous développons des algorithmes nécessitant peu de données et surtout
peu de ressources de calcul. »

Vidéos Michel Desnoues, Télécom Paris

[](https://www.telecom-paris.fr/fr/ideas/sommaire)

