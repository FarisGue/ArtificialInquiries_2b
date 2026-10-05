# ArtificialInquiries_2b

## Présentation

Ce projet est une adaptation numérique de l'exercice 2b
"All the Things You Could Do" du document
*Artificial Inquiries: A Vademecum for Workers in the Age of AI*.

L'exercice original invite l'utilisateur à réfléchir aux tâches qu'il réalise
actuellement sans l'aide d'un LLM et à identifier les tâches pour lesquelles
une intelligence artificielle pourrait apporter une assistance.

L'objectif n'est pas uniquement d'automatiser le travail, mais d'étudier
comment l'IA peut augmenter les capacités de l'utilisateur.

## Thème

Le projet s'inscrit dans le thème :

**LLM Wiki Is Not a Magic Knowledge Machine**

Plus généralement, le projet s'intéresse à la gestion des connaissances
assistée par l'intelligence artificielle.

La question principale est :

**Comment l'IA peut-elle aider à organiser et maintenir les connaissances
sans remplacer le jugement humain ?**

## Exercice choisi

L'exercice choisi est :

**Exercise 2b – All the Things You Could Do**

Dans l'exercice original, l'utilisateur doit réfléchir aux tâches qu'il
effectue sans LLM et imaginer les tâches pour lesquelles un LLM pourrait
l'aider.

L'idée importante est la différence entre :

- automation : déléguer une tâche à la machine ;
- augmentation : utiliser l'IA pour améliorer ou étendre les capacités humaines.

## Adaptation numérique

L'exercice a été transformé en une application web appelée :

**Human or AI? – Knowledge Task Mapper**

L'utilisateur peut ajouter une tâche puis déterminer le niveau d'assistance
qu'il souhaite recevoir de l'IA.

Trois catégories sont proposées :

- Human Only
- AI Can Assist
- AI Can Do Most of the Task

L'utilisateur peut également préciser :

- ce que l'IA peut faire ;
- ce qui doit rester sous contrôle humain ;
- pourquoi il a choisi ce niveau d'assistance.

## Exemple

Exemple de tâche :

**Organize my university notes**

L'utilisateur peut choisir :

**AI Can Assist**

L'IA peut :
- organiser les notes ;
- résumer les documents ;
- connecter les idées.

L'humain conserve :
- la vérification de l'information ;
- le choix des sources ;
- la décision finale.

## Fonctionnement de l'application

L'application contient quatre étapes :

### 1. Introduction

Présentation de l'exercice et de son objectif.

### 2. Task

L'utilisateur ajoute une tâche et indique son importance et sa fréquence.

### 3. Reflection

L'utilisateur choisit ce que l'IA peut faire et ce qui doit rester sous
contrôle humain.

### 4. Results

L'application affiche les tâches dans trois catégories :

Human Only | AI Can Assist | AI Can Do Most of the Task

Une synthèse est ensuite générée à partir des réponses de l'utilisateur.

## Technologies utilisées

Le prototype utilise uniquement :

- HTML5
- CSS3
- JavaScript

Aucun framework ou serveur n'est nécessaire.

Les données sont enregistrées localement dans le navigateur grâce à
`localStorage`.

## Pourquoi ces technologies ?

HTML permet de créer la structure de l'application.

CSS permet de gérer l'interface graphique et le responsive design.

JavaScript permet de gérer les interactions, les tâches, les résultats
et le stockage local.

Le choix de technologies simples permet de créer un prototype léger,
facile à exécuter et facile à comprendre.

## Stockage des données

Chaque tâche contient plusieurs informations :

- nom de la tâche ;
- importance ;
- fréquence ;
- niveau d'assistance de l'IA ;
- rôles attribués à l'IA ;
- responsabilités humaines ;
- justification de l'utilisateur.

Ces informations sont stockées dans le navigateur avec `localStorage`.

## Objectif pédagogique

L'objectif du prototype n'est pas de décider automatiquement quelles tâches
doivent être confiées à l'IA.

L'utilisateur reste responsable de cette décision.

L'outil sert principalement à provoquer une réflexion sur la répartition
du travail entre humain et intelligence artificielle.

## Lancer le projet

Télécharger ou cloner le repository.

Puis ouvrir simplement :

`index.html`

dans un navigateur web.

Aucune installation supplémentaire n'est nécessaire pour le prototype.
