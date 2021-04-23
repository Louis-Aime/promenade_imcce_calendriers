# Amélioration de l'application "promenade" de l'IMCCE
Corrections des pages de calculs calendraires de l'application "promenade" de l'IMCCE
 
L'IMCCE, département de l'Observatoire de Paris responsable des éphémérides, a conçu dès 1991 
un service grand public donnant les correspondances entre calendriers, les lunes, les saisons et les fêtes mobiles. 
Ce service était accessible par Minitel. 
Avec l'évolution du monde numérique, l'IMCCE a progressivement converti ce service aux standards du web, et l'a intégré à l'application en ligne Promenade dans le système solaire. 
Ces opérations ont introduit des erreurs successives dans les outils de calcul, qui nuisent à leur bonne utilisation.

L'IMCCE a engagé depuis 2017 une refonte de son site web et des applications de calcul destinées au grand public. 
Malheureusement, les applications de correspondance entre calendriers, de calculs de saisons, de lunes et de fêtes mobiles n'ont pas été refondues à ce jour (mai 2019).

Un simple toilettage informatique d'une dizaine des pages web du service actuel permet de corriger les erreurs les plus flagrantes et gênantes, 
en attendant de proposer un service entièrement nouveau. C'est cette solution que nous proposons ici.

## Liste des corrections

Les corrections opérées sont listées dans le fichier [Corrections.md](./Corrections.md)

## Consultation

Une maquette de la dizaine de pages corrigées est accessible via le [site GitHub Pages associé à ce dépôt](https://louis-aime.github.io/promenade_imcce_calendriers/).

## Intégration dans l'application originale

Les utilisateurs de l'application Promenade de l'IMCCE peuvent corriger les pages de calculs de la version française de la manière suivante: 
 * Utiliser uniquement les répertoires pages4 et pages5 du dépôt GitHub, non pas ceux du répertoire docs.
 * Retirer les fichiers 51.html et 51.txt du répertoire pages5;
 * Copier les autres fichiers du répertoire pages5 dans le répertoire correspondant de l'application;
 * Copier les fichiers du répertoire pages4 dans le répertoire correspondant de l'application.
 
L'application originale est réservée à l'usage d'information et de pédagogie. Consultez la déclaration de droits d'auteur correspondante en vigueur.
Les présentes pages peuvent être insérées librement dans l'application originale et dans le respect de ses propres droits.
 
Veuillez noter toutefois que cette maquette ne corrige pas des erreurs sur certaines fêtes chrétiennes, 
qui sont affichées ou calculées de manière non conforme aux pratiques d'aujourd'hui.
