# Tp Script Bash

## [Le jeux du plus ou moins](https://github.com/Genisys33/Script_Bash/blob/master/pom)
 
Pour la réalisation de celui-ci j'ai d'abord fait des test sur une échelle allant de 0 à 10, la plus dur à était de limiter la saisie à des chiffres seulement, je l'ai réglé en spécifiant que je ne voulais pas que la boucle while se termine avec l'égalité des deux chiffres mais plutôt avec une incrémentation dû au fait de l'égalité des deux nombres.
Si cela fonction avec un intervalle de 0 à 10 cela fonctionne avec une de 0 à 1000 mais pour une être certain j'ai quand même essayé jusqu'à 32765.  

## [Un outils de sauvegarde](https://github.com/Genisys33/Script_Bash/blob/master/backup)

Voici le script de la sauvegarde pour le fonctionnement il suffit de modifier le chemin  de sauvegarde du dossier dans le script qui est à la ligne 4. Notre plus grosse difficulté a été de devoir faire l'update du tar sans la commande update mais aussi de détecter l'emplacement des dossiers (Résolu par un manière totalement normal ??? (Juste effacement de la ligne puis ré-écriture de celle-ci)). 
Avec la participation de [Florian Léveil](https://github.com/FlorianLeveil)

## [youtube-dl](https://github.com/Genisys33/Script_Bash/blob/master/youtube-dl)

Le plus compliqué dans youtube-dl à était de comprendre comment faire pour n'afficher que le répertoire courant et non le chemin absolu avec la commande `pwd`.

## Conclusion

Le meilleurs avec ces trois tp est que nous n'avons pas bêtement chercher les commandes sur l'internet nous avons du lire le man, comprendre celles-ci (pour ma part personnellement).
