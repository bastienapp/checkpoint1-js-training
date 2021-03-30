# Entraînement au CHECKPOINT 1

## I. Récupération et initialisation du projet

### 1. Dépôt local

Récupère le contenu de ce dépôt en local. **Ne fait pas de Fork !**

Dans ton dépôt local, crée une branche ayant le format suivant : la ville de ton cursus en minuscule, ton prénom et nom sans accents ni espaces, séparés par des tirets, avec le nom en majuscule. Exemple : pour **Éloïse Durant**, crée une branche **lyon-eloise-DURANT**.

**Passe sur cette branche pour la suite de l'entraînement**

> Conseil : ajoute et envoie tes modifications en local après chaque exercice, pour éviter les mauvaises surprises

### 2. .gitignore

Crée le fichier _.gitignore_ dans la racine du projet, afin d'ignorer tous le dossier `node_modules`.

## II. HTML/CSS

Tu trouveras un dossier `web` dans la racine de ton dépôt local.

Tu as été embauché pour réaliser l'intégration de la page d'accueil du site de la Wild Code School !

La structure du fichier _index.html_ est déjà présente, tu vas donc devoir modifier le fichier _style.css_ afin que le site s'affiche de la façon suivante :

- [Version mobile](./templates/template-mobile.png)
- [Version desktop (>= 768px)](./templates/template-desktop.png)

> Tu trouveras aussi ces deux images dans le dossier `templates`

#### Les couleurs à utiliser sont les suivantes :

- "#39424E" : couleur par défaut du texte et de fond du pied-de-page
- "#F76C6C" : couleur de fond du bouton "Apply now"

#### Attention de respecter les points suivant :

- ne pas modifier la structure du HTML, sauf pour ajouter des classes
- créer l'intégration en _mobile first_
- n'utiliser que des _flex box_ pour positionner des éléments
- la version desktop s'affiche pour les résolutions **768px** et supérieure
- en version desktop, les colonnes des trois articles font **250px** de large et doivent être espacée en "space-around"
- ne pas supprimer le code déjà présent dans _style.css_
- tu n'as pas à ajouter ou modifier de taille de police (_font-size_) : tout est déjà configuré.

## III. Algorithmes

Crée un fichier `algos.js` avec les trois fonctions ci-dessous :

### 1. Majeur

L'école organise une soirée de fin d'année et tous les élèves majeurs sont invités. Afin d'éviter d'envoyer des invitations aux élèves mineurs, tu dois créer une méthode qui vérifie l'âge d'un élève et qui retourne s'il est majeur.

Crée une fonction nommée _hasLegalAge_, qui retourne vrai si l'âge passé en argument est supérieur ou égal à 18 et faux sinon.

### 2. Groupes

Tu dois répartir les élèves d'une classe en deux groupes. Chaque élève possède un numéro et tu veux utiliser cette donnée pour l'assigner à un groupe A ou B.

Crée une fonction nommée _getGroup_, qui reçoit le numéro d'un élève. S'il est pair, retourner le caractère A, sinon retourner le caractère B.

### 3. Groupes

L'école a besoin de compter de nombre de ses futurs étudiants souhaitant faire du JavaScript. Pour cela elle a envoyé un sondage demandant le langage à étudier. Certains candidats ont écrit JavaScript avec des minuscules et majuscules mal placées, ex : "javascript" ou "JAVASCRIPT", au lieu de "JavaScript".

Crée une fonction nommée _countStudents_, qui reçoit un tableau contenant les langages choisis par les candidats. Retourne le nombre de candidats ayant choisi le langage JavaScript, sans tenir compte de la casse (majuscule/minuscule).

## IV. Quiz

Tu trouveras un fichier `questions.txt` à la racine de ton dépôt local.

Tu peux éditer le fichier manuellement pour ajouter tes réponses.

> Merci de répondre honnêtement, sans t'aider d'Internet !

## V. Finalisation

Envoie les modifications de ta branche locale et pousse ces modifications sur le dépôt distant.

Dans GitHub, vérifie que la branche existe et que tes modifications sont bien présentes.

Tu peux revenir dans Odyssey et partager le lien vers ta branche sur GitHub.
