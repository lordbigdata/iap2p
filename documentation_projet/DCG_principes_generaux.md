# Web Documentaire : Partageons l'IA

## Dossier de conception - présentation du projet

<u> **_Partie 1 - Principes généraux_** </u> <br>
[ _Partie 2 - Description des contenus documentaires de l'atelier_ ](DCG_presentation_contenu_detaillé_du_documentaire.md)

### Objectif du web documentaire cible :

> L'objectif du support multimédia cible est de faciliter l'animation d'un atelier collectif **"Partageons l'IA"**.
> Ce web documentaire est destiné à initier un parcours de réflexion chez l'auditeur ou l'utilisateur au sujet de l'IA, **à partir d'exemples de situation ou de cas pratiques d'application dans le monde du travail**.

Le web documentaire doit permettre de faciliter l'accès à un vaste contenu d'apprentissage sur la thématique de l'IA, **pour un particulier comme pour un collectif**.

Il se destine à un public varié, avec des préoccupations mobilisables par une ou <b> plusieurs thématiques abordées </b>, avec un matériel sélectionné et sourcé, pour toucher des auditeurs ou des usagers les plus diversifiés possibles.

Le support est toutefois pensé pour servir d'abord une finalité : celle de constituer un <b> appui à un atelier de sensibilisation aux enjeux du dialogue social à propos d'IA et la possibilité d'une acculutration rapide à son fonctionnement </b> dans le contexte de l'entreprise.
Dans ce but, le web documentaire doit constituer un support complet d'animation pour des sessions de sensibilisations courtes, limitées à une heure, ou un support pour un ensemble d'ateliers répartis sur plusieurs demi-journées, en vue d'ainimier un court séminaire.
Les animateurs, comme les utilisateurs ponctuels, doivent y trouver **un ensemble de ressources consolidées, adaptées à la diversités des situations pratiques et des questionnements**.
A eux de mettre à profit la diversité du contenu proposé.

La solution web cible doit **être accessible et pouvoir être utilisée en autonomie par tous les publics** : salariés, représentant du personnel, chef d'entreprise, chef de projet, acteur syndical en charge de négocier ou d'accompagner et surtout aux candidats à l'inclusion dans un monde numérique....
La solution de web documentaire doit notamment offrir des alternatives de consultation sur les formats : markdown, pdf et doc (word/gooogle doc).

**Le support cible doit servir une finalité d'accompagnement pédagogique**. Il doit ambitionner uniquement de satisfaire à une volonté de partage de connaissances et de constituer une occasion d'initiation.

---

### Les sources mises à disposition dans ce web documentaire

Une sélection de sources et de références collectées et rendues faciles d'accès au sein d'un même support numérique :

- un **glossaire évolutif** : constitué d'abord de celui élaboré à l'occasion du colloque du CESE de novembre 2023
- une **collection d'extraits de presse** sur des situations concrêtes, avec un commentaire d'analyse
- une **collection thématiques de sites web**, commentés
- des **chronologies d'évènements importants** et des **dates clés d'introduction de l'IA**
- des **chiffres clés et des statistiques** sur le rapport de force socio économique et les enjeux environnementaux
- Des extraits de législations ou des renvois vers **les références juridiques**
- Des **ressources documentaires** analysées, à partir **de situations comcrètes d'application de l'IA** en entreprise

---

### Solutions techniques à retenir pour le web documentaire

##### Benchmark rapide des solutions techniques open source en fonction des fonctionnalités attendues d'un web documentaire :

| Fonctionnalité du web documentaire         | Markdowwn <br> (+ Marp) | Tiddlywiki.js <br>(+ plugins open source) | autre framework web (exemple reveal.js) |
| ------------------------------------------ | ----------------------- | ----------------------------------------- | --------------------------------------- | ------------------------------ |
| Diffusion web de texte                     | **oui**                 | **oui**                                   | **oui**                                 |
| Diffusion web de photo                     | **oui**                 | **oui**                                   | **oui**                                 |
| Diffusion de video                         | non                     | **oui**                                   | oui <br> (intgré avec plugin) )         |
| Diffusion de sons audio                    | non                     | **oui**                                   | oui                                     |
| Modalités d'animation interactive          | limitée                 | **oui**                                   | developppement <br> spécifique          |
| Modalités de navigation non linéaire       | non                     | **oui**                                   | developppement <br> spécifique          |
| Modalités de datavisualisation interactive | non                     | **oui**                                   | developppement <br> spécifique          |
| Possibilité de personnaliser le contenu    | **oui**                 | **oui**                                   | developppement <br> spécifique          |
| Possibilité narrative                      | non                     | **oui**                                   | oui                                     | developppement <br> spécifique |
| Modalité de quizz ou d'évaluation          | **oui**                 | **oui**                                   | developppement <br> spécifique          |

Pour aller plus loin : [Quel outil pour mon web doc ?](https://documentation.ac-besancon.fr/quel-outil-pour-mon-webdoc/)

Pour la maquette du web documentaire cible, il est proposé de retenir la solution open source tiddlywiki.

##### Plateforme de service dédiées au web documentaire

- [Plateforme klynt](https://www.klynt.net/fr/pricingklynt/)
- [Plateforme Racontr](https://r83c929680.racontr.com/)
- [Plateforme Génially](https://genial.ly/fr/)
- [Plateforme Thinglink](https://www.thinglink.com/fr/)

#### Avantages de la solution technique Tiddlywiki :

Avantage du framework javascript tiddlywiki :

- Libre et open source
- Permet de collecter et mettre à disposition facilement un ensemble de ressources tout en offrant des fonctionnalités de recherche avancée dans la masse d'information obtenue.
- Permet un déploiement local. Le livrable est un site web fonctionnel, à l'apparence devenue familière d'un notebook.
- le livrable est constitué d'une page web unique, hébergeable gratuitement et de façon sécurisée sur le web (pas de base de donnée ou de scripts tiers, tout est contenu dans un même fichier html, y compris les images )
- les sources sont accessibles via github, la diffusion et les évolutions sont facilitées.
- Le frameworks tiddly contient des fonctionnalités diverses d'intégration et d'animation de contenus multimedia (textes, images, avec des lecteur embarquée de son et de video disponible en tant que plugin ). IL s'agit d'une sorte de wiki incluant donc des fonctionnalités de CMS)
- la solution technique intégre des plugins faciltants la réalisation de quizz simples et la mise en oeuvre de l'interactivité spécifique via des developpements javascript qu'il est possible d'intégrer
- Le contenu peut être personnalisé facilement, y compris par des non techniciens
- > L'accessibilité est prise en charge par le framework : les résultats de tests spécifiques à l'accesibilité seront à mette disposition avec le livrable intermediaire (Etape 2).

Inconvénients du framework tiddlywiki:

- La solution technique du framework tiddliwiki ne favorise pas un rendu graphique trés poussé mais propose des fonctionnalités variées d'interaction et de datavisualisation open source.
- L'utilisateur peut trouver la prise en main du framework déroutante.
- Il existe une contraintes globale de taille du site web obtenu (Limite de poids total en Mo). Cette limite constitue cependant un atout. Elle garantie :
  _ la portabilité . L'outil ne nécessite aucune contrainte technique de déploiement sur des environnements locaux . Le support du web documentaire tient sur une clé USB adaptée.
  Il peut être utilisé sans accès à internet.
  _ la possibilité d'un déploiement technique et d'une animation dans toutes les circonstances.
  A noter : de nombreux contournements techniques autorisent de lever cette limite pour les supports média ( images, sons audio, de video...).
- Le livrable tiddlywiki et ses fonctionnalités embarquées sont difficilement transposable sur un autre framework.

Pour plus de détail : [Consulter le site de référence du framework javascript tiddlywiki.js](https://tiddlywiki.com/)

---

#### Description des livrables

Prérequis : Validation de la propostion d'un web documentaire et de la solution technique proposée

**3 livrables sur le projet** :

- Une _trame d'atelier de sensibilitation_ : "partageons l'IA" résultat de la journée organisée en présentielle dans le cadre de DialIA ( _Rapporteur : Pascal COYO_)
- Le dossier de conception générale, présentant les objectifs du web documentaire, les fonctionalités attendues et les solutions techniques retenues. (c'est le document présent)
- Le dossier de conception détaillée du contenu documentaire. Il contient la description des contenus : détail du glossaire, articles, référence jurdiques , extraits, dates clées, chiffres clés, description des animations,

Les contenus documentaires détaillés sont également livrés sous forme de supports consultables et diffusables au formats : markdown, pdf, doc.

**1 livrable technique** :

- sous la forme d'un **site web fonctionnel** developpé sur le socle d'un framework open source : **tiddlywiki.js**

Il est proposé que le site soit hebergé, lors des tests sur une page GithHub privée, ouverte à un collectif de relecture, puis une fois validée sur une page GitPage ouvert à tout public ( Pas de prise en charge de stratégie spécifique de référencement ).

Le livrable technique est réalisé et coordonné, de façon transitoire lors de l'étape 1, par Benoit SADRIN au titre de developpeur principal en tant que membre bénévole du groupe de travail DIALIA.

---

#### Etapes de conception - Proposition de déroulement :

Prérequis : Elaboration d'un planning

La livraison intervient au bout d'un processus de conception limité à 3 étapes :

**Etape 1** / Sprint 1 : Constituer et enrichir une base de connaissances, en la limitant à des contenus utiles (poids en octet) et adaptés (critères d'utilisabilité).

Le web documentaire cible est constitué d'une collection de ressources et de contenus de référence (dates clés, chiffres clés, lexique) et d'un ensemble de cas concrêts documentés (articles de presse, situations concrêtes, classées et commentées) afin d'illustrer les enjeux de l'IA et d'informer sur son fonctionnement.

Critère de selection des contenus : Il s'agit de privilégier des exemples frappants, des questionnements utiles et des exemples invitant à sortir de la pensée magique, de la solution IA forcement idéale.

Les exemples et les ressources sont collectées au sein du collectif DIALIA.

Le contenu spécifiquement documentaire peut être publié en phase finale via un ensemble de fichiers sur github.
Pendant la phase de projet, pour faciliter la mutualisation, il est proposé que les sources au format markdown et document (.doc), soient mises à disposition à la communauté sur un Google Drive.
Pendant cette phase, les ajouts à la version en cours sur GitHub peuvent être adressée par à mail à lordbigdata@gmail.com

Cette phase se termine par la _validation du cahier des charges détaillés des contenus du documentaire _ par la communauté DialIA (rapporteur à désigner ).

Le descriptif détaillé du contenu du documentaire est l'objet d'un livrable à part entière du projet.

**Etape 2** / Sprint 2 : Elaborer et finaliser plusieurs parcours/scénario de navigation adaptés selon les publics. Developper et finaliser les animations interactives proposées en vue d'un partage facilité des principaux principes et des enjeux de l'IA.

Construire et tester des parcours de navigation cohérents à partir de la base documentaire constituer à l'étape 1.
Pendant cette étape du projet, les applications de l'IA et les cas pratiques proposés à l'étude peuvent faire l'objet d'un travail d'élaboration collective et de relecture par un comité dédié (rapporteur à nommer).
Cette phase intègre la collecte des documents complémentaires disponibles afférents pour finaliser les parcours et les animations validées.

Critères de selection des situations présentées : Les exemples de solution IA selectionnées sont issues du secteur privé comme du secteur public, en phase de projet, de déploiement ou de production .
Les situations analysées et retenues intègrent des dispositifs techniques ayant recours à du machine learning (ML) , des IA génératives ou des algorithmes d'apprentissage statistiques.
Le sources utilisées sont des sources libres, accessibles en ligne ou quand il s'agit d'article de presse, exploitable sous forme de citation.

Cette phase se termine par la _validation des fonctionnalités interactives et des parcours de navigation du web documentaire par des membres du comité de relecture et des pilotes de DialIA_

**Etape 3** : Echéance de validation défintive du livrable
Phase de test précédent un GO/No GO final. Cette phase est fixée au plus tard 15 jours aprés la clôture des travaux de DIALIA.

Cette phase se termine par la _publication du livrable sous la forme d'une page web publique_ diffusée gratuitement (type page GitLab - avec une licence libre type licence [creative commons](https://creativecommons.org/licenses/by/4.0/deed.fr)

A cette étape finale:

- Le web documentaire est disponible sur un serveur gratuit public ( Une gitPage de GitHub)
- Les fichiers sources du web documentaire sont disponibles sur GitHub
- Les contenus documentaires sont fournis, quand c'est possible, sous la forme de fichiers markdown et de fichiers pdf sur un répertoire gitHub en annexe du site.

---

#### Description des fonctionnalités "interactives" du lexique :

**Sources des concepts clés** :

> Pour constituer le lexique de départ, il est proposé de s'appuyer sur la liste et les defintions publiées dans les actes du colloque du CESE ansi que dans celles de legifrance, notamment pour les traductions des concepts. La liste finale des concepts clés est validée, si posssible, par un collectif de relecteurs.

- _Novembre 2023 - L'intelligence artificielle (IA) - risques et opportunités : des enjeux à débattre_

→ Remarque sur le choix de cette source : A priori , les actes du colloque constituent un bon consensus pour la communauté DialIA.

**Autres sources** :

- _Glossaire du portail du conseil de l'europe_ : [ Lien vers le glossaire - www.coe.int](https://www.coe.int/fr/web/artificial-intelligene/glossary)

- _Liste de termes, expressions et définitions sur l'IA adoptés par Legifrance_
  [Lien vers le vocabulaire de l'intelligence artificielle - source legifrance](https://www.legifrance.gouv.fr/jorf/id/JORFTEXT000037783813)

- _Lexique en français de l'intelligence artifielle_
  [Lien vers le lexique en français sur l'IA - source wikipedia](https://fr.wiktionary.org/wiki/Cat%C3%A9gorie:L_exique_en_fran%C3%A7ais_de_l%E2%80%99intelligence_artificielle)

Voir Annexe A du dossier de conception : Descriptif détaillé du contenu de web documentaire

**Concepts complémentaires** :

- Apprentissage (humain): on part des processus chez l'humain (Chomsky) pour introduire les concepts de l'apprentissage machine (ML)

> **Fonctionnalités générales du lexique** :
>
> - Un **moteur de recherche** et une **page de glossaire dédiée** permettent de facilement naviguer entre les notions (fonctionnalité du framework de base tiddlywiki : La mise à jour de l'index du glossaire est effectuée par le framework)
> - la navigation est faciltée par un **systeme de renvois et de références entre concepts** clés via un systeme de tag et la proposition continue de suivre des scénario de consultation. Le "fil d'ariane" de la navigation est interactif (fonctionnalité du framework de base tiddlywiki)

> - Usage collectif en atelier du glossaire : partir des mots clés des auditeurs sur le fonctionnement de l'IA puis construire un premier parcours de consultation. Il s'agit de mobiliser une approche reflexive sur la collecte d'informations effectuées, et sur les thématiques abordés par le web documentaire. Aprés une première phase de bilan, sur ce qu'est ou ce que n'est pas l'IA, l'auditeur est invité à une visite adaptée, avec au choix des sessions collectives ou la mise en place d'une consultation, libre et individuelle. Ce choix doit pouvoir s'adapter selon les besoins des animateurs.

_Voir Annexe A du dossier de conception : Descriptif détaillé du contenu de web documentaire_

#### Description des fonctionnalités pour restituer les dates clés et évènements principaux

> Pour constituer les dates clés de de départ, il est proposé de s'appuyer sur celles publiées dans les actes du colloque du CESE.

- Novembre 2023 - L'intelligence artificielle (IA) - risques et opportunités : des enjeux à débattre

> **Fonctionnalités des dates clés** :
> Les dates clés sont restituées et consultables via **une "timeline" interactive** (fonctionnalité déployée via un plug-in existant)

_Voir Annexe B du dossier de conception : Descriptif détaillé du contenu de web documentaire_

<br>

#### Description des fonctionnalité utiles pour les chiffres clés et les synthèses sur les enjeux socio-économique et environnementaux :

> **Fonctionnalités des chiffres clés** :
> Les graphqiues consultables (**Datavisualisation**) sont interactifs (fonctionnalité déployée via un plug-in existant)

#### Les fonctionnalités générales des mises en situations : apprentissage par les jeux, les tests et les évaluations

Les ressources interactives (intégrées ou additionnelles) sont par exemple:

1. des **questions ou des rappels intégrés** sour la forme d'exercice phrases à trous, de questions à choix multiples ou cases à cocher , de quizz intégrés (fonctionnalité déployée via un plug-in existant)
1. des **interactions avec chapGPT** intégrées avec des propositions de prompt en fonction des situations (fonctionnalité déployée via un plug-in existant)
1. un test intégré ou additionnels permettant d'**évaluer sa compétences en vitesse de frappe au clavier** , et de le comparer à la vitesse de réponse des algorithmes génératifs de texte ou de réponses des chat intégrant de l'IA <br> → **Introduire aux enjeux de supprématie et de concurence de l'humain et de l'IA**.
1. Une fiche de présentation dédiée à une possibilité évaluation des compétences numériques : extenalisées sur le site étatique : www.pix.fr et des modalités de certifications associées
1. Une fiche de présentation dédiée à 5j5ia
1. Une présentation des modalités d'initiation au code via l'écriture de markdown : Cette atelier permet de **s'approprier et de personnaliser le contenu documentaire éditable** du web documentaire en cours de présentation)
1. Une presentation des liens et d'une **collection d' outils et tests externalisés de connaissances sur l'IA**
1. Des liens vers des petits jeux éducatifs , des didacticiels ou des activités de sensibilisation (intégrés au support web documentaire ou additionnnels : exemple

_Voir Annexe C du dossier de conception : Descriptif détaillé du contenu de web documentaire_

#### Les ressources video proposées dans le web documentaire

Le tag (@video) est un tag commun à l'ensemble des resssources video

1. Renvoi vers la video du **_colloque du CESE de novembre 2023_**.
1. Liste de videos produites dans le cadre d'une démarche d'éducation populaire sur des thèmes illustrant les thèmes du web documentaire
   - **_conférences gesticulées sur métiers du numérique et l'IA_** (Voir le programme des conférenes gesticulées dans sa région )
     - liens vers les videos de références (voir annexes D )
1. Autres ressources video : L'ensemble des ressources documentaires sont décrites dans un livrable à part entière du projet

_Voir l'annexe D du dossier de conception : Descriptif détaillé du contenu de web documentaire_
