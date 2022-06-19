# Rapport d'expérience professionnelle

Formation développeur d'application frontend

Projet 9 : Construisez une veille technologique et effectuez un stage.

<p align="center"><img src="./assets/logo_wellcoms.png"></p>
<p align="center"><img src="./assets/logo_openclassrooms.jpg" height="187px"></p>

## Sommaire

 - I - [Remerciements](#remerciements)
 - II - [Contexte](#contexte)
 - III - [Problématique](#problematique)
 - IV - [Missions confiées](#missions)
    - a - Reprise de la bibliothèque SVG des lithologies
    - b - Amélioration du tooltip d’information des graphiques
    - c - Correction générale du CSS de l’interface
    - d - Debug
 - V - [Bilan](#bilan)

## I - <a name="remerciements"></a> Remerciements

## II - <a name="contexte"></a> Contexte

Qui suis-je ?

Je me présente, Yannis Almanric, 29 ans.
Je suis depuis presque deux ans, en alternance chez la société `Wellcoms Drilling & Geology` en tant que développeur front-end.

L'organisation qui m'accueille, basée en France, est spécialisée dans la création d'outils informatique pour de la transmission et de la visualisation de données depuis 15 ans.
Elle est spécialisée dans la récupération et le traitement de données relatives au forages pétroliers en utilisant les standards de l'industrie, c'est à dire principalement du WITSML (langage de balises basé sur XML).
L'équipe est constituée de plusieurs développeurs, un ingénieur recherche et développement, un administrateur système, un géologue, un commercial relation client, une équipe de support client et une équipe administrative.

Mon choix s'est porté sur cette entreprise car elle proposait un environnement propice à l'apprentissage, avec une petite équipe, un esprit familial et le temps nécessaire pour monter en compétence avant de se lancer dans de véritables missions (Avant de se lancer dans des projets plus complexes).
De plus l'environnement technique correspondait parfaitement aux attentes de la formation, avec JavaScript/jQuery utilisé des deux côtés. Plus un nouveau projet interne à l'entreprise en Vue.js, technologie que j'ai pu utiliser et approfondir dans le projet `Lancez votre propre site d'avis de restaurants`.

En ce qui concerne mes objectifs de formation, je compte améliorer ma maîtrise du JavaScript, une fois les différents concepts de bases acquis, améliorer la structure du code, chercher l'optimisation.
+ nouveaux objectifs

## III - <a name="problematique"></a> Problématique

Comment garantir le succès d'implémentation d'une nouvelle feature dans une application web existante ?

## IV - <a name="missions"></a> Missions confiées

Example de WITSML :

<p align="center"><img src="./assets/logs.svg" width="600px"></p>

### a - Reprise de la bibliothèque SVG des lithologies

Pourquoi le SVG (Scalable Vector Graphics) ?
Afin d'avoir un affichage graphique qu'on puisse zoomer/dézoomer sans perte de qualité grâce au vectoriel.

La lithologie va représenter un échantillon des couches géologiques, pour chaque nature de roche différente, on va appliquer une légende.

On a repris le format, afin que chaque motif ait la même dimension et corrigé certaines erreurs de code, de positionnement, voir même refaire certains motifs.

<p>Exemple de motif en 50 px : <img src="./assets/litho.svg" width="50px"></p>
<p>Exemple de motif en 100 px : <img src="./assets/litho.svg" width="100px"></p>
<p>Exemple de motif en 300 px : <img src="./assets/litho.svg" width="300px"></p>

<p>Exemple de code SVG : <img src="./assets/svg_code_example.svg" width="700px"></p>

(ajout, correction)

### b - Amélioration du tooltip d’information des graphiques

Ici le but était d'avoir un tooltip d'informations des courbes complet. On a donc ajouté la valeur du point actuellement survolé, le minimum et le maximum possible de la courbe, la couleur

### c - Correction générale du CSS de l’interface

Navigation, dashboard

### d - Debug

- Courbes logarithmiques
  - problème de format (NaN)
- Labels
  - Afficher les courbes sous forme de texte (x points affichés)
- Datetime picker
  - Corriger le style du widget
  - Ajouter un bouton de validation
- Export graphique PDF/PNG/JPEG
  - Télécharger le graphique visualisé
- Download data (CSV/XLS)
  - Télécharger les tableau de données du graphique
- Datatable
  - Afficher le tableau de données du graphique directement dans le navigateur
- Messages graphiques
- Update data
- Tri des datas, s'assurer de l'unicité des data reçues, éviter l'accumulation à chaque changement de range

## V - <a name="bilan"></a> Bilan

 - Apprentissage
 - Utilisation d'une librairie graphique (HighCharts)
 