# Programmation parallèle : multithreading en Perl
Ce répertoir est là pour pouvoir suivre la finalisation de mon mémoire de fin d'étude du master MIAGE informatique de la finance à Paris-Dauphine.
La première partie est présenté suite à la mise en production du script optimisé pour mon premier projet à la BNP Paribas.
La deuxième partie est en cours de finalisation, elle montrera une application de la méthode trouvée pour le cas d'un script de sauvegarde.

# Contenue du mémoire
Le projet principal du mémoire à pour but de trouver une méthode générale et applicable à tout type de langage pour faire du multithreading. 
La première partie du mémoire prend pour exemple d'application de la programmation parallèle le script de récupération de l'uptime d'un équipement. 
La seconde partie (non disponible encore), est d'appliquer la méthode trouvée à un script de sauvegarde d'un data center.

En ce mémoire nous avons décidé de rester en langage Perl pour trois raisons : <br>
  1) Perl est un langage de programmation permettant de lire les fichiers texte et de customiser cette lecture qui est fondamentale lorsque l'on doit manipuler des fichiers sur les équipements d'un data center
     et les interpréter dans le résultat du script.
  3) C'est un langage proche du Python avec une composante orientée objet : utilisation de référence, pointeur, création de classe pour l'application de multithreading.
  4) Le défis de réaliser un objectif dans un langage où les méthodes de programmation parallèle ne sont pas connues.
Nous pouvons donc trouver en cette première partie du mémoire une structure de code d'un script en programmation parallèle, facilement applicable à d'autre langage et reproductible.

# Remarque sur la réalisation du mémoire
L'intérêt annexe de faire ce projet en Perl est, qu'à l'heure de la démocratisation de l'intelligence artificielle, aucune ligne de code ne fut écrite à l'aide de ChatGPT.
En effet, même si ChatGPT va proposer une solutions, elle ne sera pas viable dans le contexte d'application du script. Bien souvent, j'ai du m'aider des programme donnée sur la documentation CPAN
ou encore sur le forum Stackoverflow et Developper.com. 
Tout dû être fait et travaillé en grande partie à l'aide de la documentation (CPAN), des formations Perl issues de la communauté Perl sur internet et du travail colaboratif.
En outre, ce travail est une preuve de ma capacité d'autonomie dans la réalisation de mon travail de développeuse.
Ma connaissance en Python m'a permis de comprendre les bibliothèques utilisées dans le data center en Perl, qui est très similiaire à la notion de classe en Python,
mais aussi de pouvoir utiliser les formats initiaux en Python sur du multithreading.

