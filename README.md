# Recettes Linuxfr

## À propos


Ce dépot contient les sources LaTeX d'un petit livret qui contient une
compilation des reçettes postées par divers contributeurs du site linuxfr.org
(dans la rubrique journaux).

## Organisation du dépot

Le développement du code LaTeX en tant que tel se fera dans la branche « tex »,
le « contenu », c'est à dire les recettes seront dans la branche « contenu »,
et le tout sera mergé de temps en temps dans « main » pour former quelque-
chose de compilable, dont le pdf sera mis en lien dans le README en temps
voulu.

## Code

### Architecture des fichiers


Les fichiers contenant du code LaTeX n’étant pas du contenu en tant que tel se placera dans le répertoire "/code".
Le sous-dossier "code/fonctions" contiendra les définitions de fonctions personalisées, toutes seront séparées dans des fichiers différents et appelées dans le fichier "/code/preambule.tex". Ce fichier "/code/preambule.tex" contiendra toute les commandes du préambule, et les appels des fonctions personalisées.

### Fonctions

TODO