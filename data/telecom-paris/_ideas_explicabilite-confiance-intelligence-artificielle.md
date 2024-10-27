# Title: Ideas - IA : explicabilité et confiance ?

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Ideas](https://www.telecom-paris.fr/fr/ideas "Ideas") > [Explicabilité et confiance en l’IA ?](https://www.telecom-paris.fr/fr/ideas/explicabilite-confiance-intelligence-artificielle)

[](https://www.telecom-paris.fr/fr/accueil)

# Télécom Paris Ideas  
Explicabilité et confiance en l'intelligence artificielle ?

## Explicabilité et confiance en l’intelligence artificielle ?  

[Florence d’Alché-Buc](https://www.telecom-paris.fr/florence-dalche-buc),
professeure à Télécom Paris, spécialiste de l’intelligence artificielle, oct.
2024

Florence d’Alché nous parle des questions d’explicabilité et de confiance dans
l’IA. Ces questions se posent avec acuité depuis l’arrivée des IA génératives,
ainsi que dans le cadre des réflexions actuelles sur leur régulation.

S’il s’agit surtout d’en réguler les risques, cela suppose de comprendre en
amont comment sont conçus ces grands modèles de langage.  
L’[IA Act](https://www.telecom-paris.fr/fr/ideas/regulation-intelligence-
artificielle), qui entrera en vigueur en 2025, va d’ailleurs introduire des
obligations de transparence et d’explicabilité pour ces modèles.

  * 

Propos recueillis par Isabelle Mauriac

### Podcast

Retrouvez cette interview en format audio dans le cadre des [podcasts Télécom
Paris Ideas](https://podcast.ausha.co/telecom-paris-ideas) :

Podcast enregistré le 29 février 2024 par Michel Desnoues, Télécom Paris

## La confiance, notion cruciale

— Pourquoi le sujet de la confiance dans ces modèles de langage et leurs
prévisions sont aujourd’hui centraux dans les questionnements autour de
l’intelligence artificielle ?

Aujourd’hui, les outils de l’IA sont déployés dans tous les secteurs
d’activité de la société, les applications grand public comme les applications
dans des entreprises.

Et ce sont justement nos usages de l’IA qui révèlent certaines failles.

  * 

Par exemple, les modèles de langage peuvent affabuler. Certains modèles de
prévision vont manquer de transparence et d’explicabilité. Donc cette question
apparaît maintenant de manière aiguë dans à peu près tous les secteurs où l’IA
est présente.

— L’irruption des IA génératives dans les usages du grand public a accéléré
cette prise de conscience, du besoin de transparence et de confiance dans les
algorithmes. Mais j’imagine que la nécessité d’une régulation de l’IA a priori
et a posteriori ne date pas d’hier. Pouvez-vous mettre cela en perspective ?

Oui, c’est vrai. C’est une question qui s’est posée très tôt dans le
développement de l’IA, notamment l’IA « tirée par les données ». L’IA qu’on
connaît aujourd’hui a déjà connu plusieurs révolutions. Il y a dix ans, la
résurgence des réseaux neurones, en particulier des réseaux neurones très
profonds et leurs résultats spectaculaires, notamment en vision, ont renouvelé
cette question.  
Une deuxième révolution, il y a à peu près trois ans, concerne cette IA
générative où on est passé de modèles de reconnaissance qui étaient
essentiellement prédictifs, à des modèles génératifs qui sont capables de
produire des phrases entières, des images nouvelles, conditionnées souvent par
un système de prompt, c’est-à-dire ce qu’on leur demande. Et se posent les
questions de confiance de différentes manières au fil de ces développements.  
Ces questions de robustesse, d’équité, d’explicabilité, de confiance, de
confidentialité, se posent de manière différente dans ces systèmes d’IA
génératives, avec, de manière beaucoup plus aiguë, les problèmes de confiance
sur des données créées, des données générées…

Se pose la question de l’origine de ces données, de la qualité, de la
confiance qu’on peut avoir dans ces données qui sont également produites par
l’IA elle-même.

  * 

## Les dimensions de l’explicabilité

— Vous avez cité différentes dimensions de cette notion d’explicabilité,
revenons dessus et creusons un peu chacune d’entre elles… Vous parliez de
robustesse, d’équité, d’explicabilité, de confidentialité… Les prend-on dans
l’ordre ? Y en a-t-il d’autres ?

Commençons par la robustesse. C’est d’abord une robustesse aux bruits, aux
contaminations, par exemple des données acquises avec des capteurs. Puis il y
a la robustesse aux attaques « adversariales », c’est-à-dire celles d’agents
malicieux qui vont essayer de modifier les données perçues et captées. Donc la
robustesse va être une capacité extrêmement importante pour les outils d’IA,
soit dans la phase d’apprentissage, au moment où le modèle est calibré, soit
même à l’étape d’inférence afin que le système de prévision ne s’appuie pas
sur une donnée contaminée, fausse. Donc la robustesse est vraiment le socle
nécessaire à installer pour un outil d’IA.

  * 

La fiabilité est très liée à la robustesse, mais elle fournit une prévision
avec un intervalle de confiance, dire à quel point finalement le système
propose une prédiction avec un certain niveau d’assurance. Cela peut être
extrêmement important, par exemple, si on pense au véhicule autonome, pour
redonner la main aux conducteurs, ce qui implique techniquement une capacité à
s’abstenir. Donc il faudra dans cet exemple que le système puisse vous dire «
dans cette situation-là, je sais bien prédire ou je sais mal prédire ».
L’autre versant fondamental, vu notamment par exemple dans les systèmes de
reconnaissance faciale ou dans les systèmes de diagnostic, est l’équité,
c’est-à-dire à quel point il est sûr qu’un algorithme d’apprentissage permet
de définir un système équitable qui traite toute catégorie d’une population,
de manière égale pour toute entrée.

  * 

— Et donc c’est une question, j’imagine, qui rejoint celle de la préoccupation
des biais ?

Effectivement, dans les bases de données qui servent à l’apprentissage de ces
systèmes, si certaines catégories, certaines données ne sont pas présentes, il
ne sera pas possible de les exploiter, ainsi un manque de performance sera
constaté au moment de la prévision. Ce biais doit donc être corrigé et c’est
évidemment un thème de recherche extrêmement important, qui est d’ailleurs
traité à Télécom Paris.

Puis il y a bien sûr l’explicabilité qui recouvre finalement beaucoup de
choses : j’ai un système, il est prédictif, il prédit une valeur de sortie et
j’aimerais savoir quels sont les éléments de la variable d’entrée qui
conduisent à cette prévision, c’est-à-dire quels sont les éléments qui peuvent
permettre de comprendre pourquoi le système a fourni cette sortie. En
regardant les IA génératives, l’explicabilité va être : si le système produit
une phrase, il faudrait savoir quels sont les éléments qui conduisent à une
réponse du système. Donc l’explicabilité est vraiment un problème clé.

  * 

La confidentialité, c’est autre chose. Par exemple dans des problématiques
médicales, à l’hôpital, il faudra évidemment être extrêmement attentif à ce
que soient préservés l’anonymat et la confidentialité des données pendant
l’apprentissage du système.

  * 

— Vous parliez de données de santé, cela m’amène à vous poser la question de
savoir s’il est obligatoire d’avoir toutes les propriétés ou si, en fait, tout
dépend justement du secteur concerné, des applications de ces IA et s’il est
possible de rechercher certaines propriétés et non d’autres selon les usages ?

  
Oui, c’est vraiment une question intéressante, il est vrai que pendant des
années nous nous sommes concentrés sur la performance de l’IA et aujourd’hui
nous sommes conscients que, selon les domaines d’application, vont plutôt être
privilégiées la propriété de robustesse et celle d’explicabilité, ou bien
celles d’équité et de confidentialité par exemple…

Donc oui, tous ces critères-là, assez difficiles à satisfaire en même temps,
simultanément, vont pouvoir éventuellement être sollicités dans certaines
applications et non d’autres. On imagine que pour certaines applications qui
sont, disons, ludiques, avec peut-être moins d’impact que par exemple un
diagnostic médical, ou va lâcher prise sur certains de ces critères.

— Nous parlions de l’explicabilité qui est peut-être un peu plus générique…
elle permet aussi la traçabilité, j’imagine que c’est important de décrire les
algorithmes pour pouvoir éventuellement les récupérer ou bien les certifier
dans certains secteurs sensibles par exemple ?

Au-delà de l’explicabilité, la traçabilité, la transparence du processus de
conception d’une IA est crucial…

  * 

… et la phase d’apprentissage jusqu’à, bien sûr, la phase d’inférence, doivent
être reproductibles et les plus transparentes possible pour différentes
raisons. Bien entendu, afin de pouvoir partager l’information et vérifier le
contenu et le comportement de ces systèmes. Mais effectivement, cela ne porte
pas que sur les algorithmes, il est question de traçabilité dès le moment où
j’acquiers des données, je les annote… Dans les systèmes d’IA génératives, on
parle d’open source, d’open data, d’open weight, c’est-à-dire de paramètres
partagés et lisibles. Ensuite il y a le code lui-même. Donc la transparence
est à différents niveaux.

## Simplification nécessaire ?

— Pour revenir à l’actualité et aux développements récents, on a un peu
l’impression que, jusqu’à aujourd’hui, l’IA est avant tout tournée vers la
performance, avec une « course à l’échalote » entre les modèles d’Intelligence
artificielle et génératives, comme ChatGPT, mais aussi Bard (de Google),
Claude (d’Anthropic), récemment le chat de Mistral AI… Les dimensions de
l’explicabilité ne sont-elles pas un peu perdues de vue aujourd’hui ?

Il est vrai que j’aime dire que les dix dernières années ont été les « dix
glorieuses » de l’IA, c’est-à-dire qu’effectivement nous avons eu
simultanément un accès à des capacités de calcul extrêmement puissantes et à
un très grand nombre de données, notamment grâce au web, avec des algorithmes
développés dans les laboratoires de recherche. Et finalement c’est « allons-y,
développons des modèles très complexes ». Cela a donné effectivement des
résultats spectaculaires, mais sans doute, dans cette course à la performance,
a été privilégié le fait que nous sommes capables aujourd’hui de construire
des modèles qui trouvent les régularités presque parfaitement dans les données
et qui peuvent atteindre un niveau de modélisation extrêmement bon.

La contrepartie, c’est que l’accent a moins été mis sur l’élégance
mathématique, sur certaines garanties théoriques puisque la direction est
naturellement vers des modèles dits « sur-paramétrisés », de nature très
complexe (plusieurs centaines de couches de calcul). En effet, il est beaucoup
plus difficile d’obtenir des garanties avec cette complexité-là.

  * 

— De ce fait, afin de bénéficier d’une explicabilité satisfaisante et de la
transparence, faudrait-il plutôt aller vers une simplification de ces modèles
et peut-être passer par de l’hybridation ?

Oui, il est possible de passer par l’hybridation, en tenant compte par exemple
de propriétés mathématiques et, finalement, en diminuant le besoin d’énormes
cohortes de données, mais plus généralement on va s’intéresser à la frugalité
des modèles aujourd’hui.

Pour des raisons évidentes, liées à la crise énergétique et au changement
climatique, un nouveau paramètre, un nouveau critère revient sur le devant de
la scène : « comment résoudre les mêmes problèmes avec une efficacité forte et
une taille de modèles, un nombre de données moins importants ». Et cela a un
rapport avec l’explicabilité puisque on peut effectivement penser que
l’explicabilité peut passer par de la frugalité.

Même si cela n’est pas toujours le cas, des méthodes frugales s’appuyant sur
des projections dans des sous-espaces aléatoires ou de la compression qui ne
vont pas forcément aller vers la transparence et l’explicabilité, parfois les
deux se rencontrent.

Explicabilité et frugalité peuvent donc se conjuguer.

  * 

— Quel est selon vous le rôle des académiques dans ces travaux et ces
réflexions très importantes en cours, au cœur de la régulation de
l’intelligence artificielle sur la confiance dans l’IA ? Comment, vous
chercheurs, travaillez-vous sur ces sujets avec les entreprises ?

Il faut distinguer deux dimensions. D’abord on voit bien que nous avons des
problèmes techniques, mais ils sont aussi associés à des problèmes qu’il est
possible de traiter avec des spécialistes du droit, des sociologues, des
philosophes.

L’IA n’est plus la chasse gardée des mathématiques appliquées et de
l’informatique. C’est vraiment important de le dire, et c’est également ainsi
que ce thème est abordé à Télécom Paris.

Les usages de l’IA, qui révèlent donc un certain nombres de failles et
pointent de nombreux challenges techniques que nous cherchons à relever, sont
en lien aussi avec ce que la régulation de l’IA va demander de plus en plus.
Quand on regarde par exemple l’industrie du logiciel, les normes et les
certifications qui sont imposées pour la sortie d’un certain nombre d’outils
sont extrêmement importantes et fournissent une garantie de qualité. Mais en
IA, nous sommes encore très loin de ces normes-là et de ces certifications. Et
sans doute seront-elles utiles pour un certain nombre de domaines, notamment
dans les usages de l’IA critique.  

En tant qu’académiques, nous pouvons essayer de discuter avec celles et ceux
qui font les normes et qui définissent ces certifications pour proposer des
solutions utiles, de la conception de l’IA jusqu’à son usage.

  * 

[](https://www.telecom-paris.fr/fr/ideas/sommaire)

