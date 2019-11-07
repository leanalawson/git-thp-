## 1. Introduction

As-tu déjà travaillé en entreprise ou sur un projet étudiant ? Si oui, tu t'es peut-être déjà retrouvé dans mon cas avec un dossier qui ressemble à ça : 





En gros, c'est souvent le bordel dans le monde des moldus du code. Ces derniers passent leur temps à créer des milliers de fichiers, juste au cas où ils auraient besoin de revenir à une version précédente.

Maintenant, imagine devoir travailler en équipe sur des dossiers de code contenant des milliers de fichiers. [Créer des visions number](index_VERSIONNUMBER.html) à tire-larigot n'est clairement pas la meilleure solution. L'idéal serait d'avoir un logiciel capable de faire des photographies à un instant T d'un dossier, et de préciser pour chacune de ces sauvegardes la réponse aux 4 questions suivantes :

- **Quoi** : quels fichiers ont été modifiés dans cette photographie ?
- **Qui** : qui est responsable de cette modification ?
- **Quand** : de quand cette modification date ?
- **Pourquoi** : pourquoi cette modification existe-t-elle ?

Avec un tel logiciel, fini le stress et les dossiers remplis de fichiers inutiles ! Bonne nouvelle : ce genre de logiciels existe et on les appelle des "gestionnaires de version" (version control software). J'aime bien ce [schéma](https://www.git-tower.com/learn/git/ebook/en/desktop-gui/basics/what-is-version-control) qui explique bien à quoi ils servent : 

Comprends-tu maintenant pourquoi le gestionnaire de version appelé [Git](https://git-scm.com/) est un super logiciel, et pourquoi c'est un indispensable dans l'univers du code ? Dans cette ressource, nous verrons comment l'installer et s'en servir. Ensuite, nous verrons de quelle manière l'utiliser pour mettre ses dossiers en ligne avec GitHub (un équivalent de DropBox) pour te permettre de partager ton code et collaborer facilement avec d'autres devs.

## 2. Contexte et historique 

Tout comme il existe plusieurs explorateurs Internet (Firefox, Chrome, Safari, etc), il existe plein de logiciels de gestion de versions ([SVN](https://subversion.apache.org/), [BitKeeper](https://www.bitkeeper.org/), etc). Nous allons travailler avec Git pour ce cours car c'est de très très loin le plus connu et utilisé.
Git a été créé en 2005 par Linus Torvald, qui a (entre autres) créé le système d'exploitation Linux.

[GitHub](https://github.com/) est un service de mise en ligne de projets "versionnés" via Git, créé en 2008. Il a été racheté par Microsoft en 2018 pour la modique somme de 7,5 milliards de dollars.

En gros, voici ce que font Git et GitHub :

- **Git** est un logiciel de gestion de versions. C'est à dire, un logiciel permettant de photographier à l'instant T les fichiers d'un dossier.
- **GitHub** est un service en ligne qui utilise Git, et qui permet entre autres de : 
       ° Mettre en ligne ses dossiers Git (dans ce qu'on appelle "un repository").
       ° Collaborer à plusieurs sur un même dossier Git.


