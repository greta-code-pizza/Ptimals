## Les gardiens de Ptimals
---

Vous avez aimé "Juliette et les Ptimos" ! Vous allez adorer "Les gardiens de Ptimals", l'application mobile de sauvegarde d'animaux bien réels !

Votre mission (impossible), si vous l'acceptez, est de créer une application mobile capable de recenser les animaux que vous rencontrez !

Pour cela vous aurez besoin de consommer une API de reconnaissance d'images comme clarifai (recommandé par le professeur Long) !

Vous aurez aussi besoin de stocker une image sur imgur par exemple.

Liste des animaux à implémenter :


| Animaux | Dominance (10-80 | 100) | Stress (10-70 | 100) | Vit (2-100) | Freezer | Attaque ||:----------:|:-------:|:------:|:----------:|:----------:| 
| Chat | 40-60 | 30-40 | 25-35 | Ronronnement | Griffure profonde |
| Chien | 30-65 | 20-30 | 25-40 | Aboiement  | Morsure enragée |
| Escargot | 10 | 40 | 2 | Bave gluante | Bave toxique |
| Mouette | 22 | 50 | 35-45 |  | Coup de bec |
| Goelan | 45 | 40 | 35-45 |  | Assault |
| Cormoran | ... | ... | ... |  |  |
| Ecureil | ... | ... | ... |  |  |
| Pigeon | ... | ... | ... |  |  |


### Composants à implémenter

En vous aidant de Figma ou Marvel, créer une interface pour votre jeu favoris !

#### Connexion

Pour jouer, il vous faut vous connecter à l'application ! 
Il vous faudra donc un formulaire d'inscription en vous aidant de supabase !

#### Espace cherche

Maintenant que vous êtes connecté, vous arrivez sur votre espace 

#### Flashimals

Le flashimals est le composant permettant de prendre en photo un Ptimal !

#### Analyzer :

Vous venez de flasher un Ptimals, c'est le moment de vérité ! L'analyzer va interroger clarifai pour voir si votre capture à réussi !

#### Ptidex :

Le Ptidex est l'endroit qui recense les Ptimals capturés ! 
