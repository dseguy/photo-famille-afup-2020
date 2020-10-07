# Forum AFUP 2020 : la phpoto de famille

Ceci est l'album photo de famille elePHPant pour le [forum AFUP 2020](https://event.afup.org/forum-php-2020/). 

Traditionnellement, les forums, conférences et autres rassemblements PHP sont l'occasion pour le patriache des elePHPants, ["Trisaïeul"](https://afieldguidetoelephpants.net/#variations), de rassembler ses enfants, petits-enfants, et arrière-*-petits-enfants pour une photo de famille. Cette année, c'est une photo de famille en ligne! 

La photo de famille sera disponible à la fin du forum AFUP. Elle sera aussi présente lors de la conférence sur les '14 ans de la vie de l'elephpant' durant le forum. 

## Sommaire

  - [Préparatifs](#préparatifs)
  - [Action](#action)
  - [Pull request](#pull-request)
  - [Built With](#built-with)
  - [Voir l'album](#voir-l-album)
  - [Auteurs](#auteurs)
  - [Licence](#licence)
  - [Remerciements](#remerciements)

## Préparatifs

Pour la photo de famille, vous aurez besoin de : 
+ un elePHPant, ou plusieurs
+ un appareil photo
+ vous-même (optionel, en fait)
+ Vérifiez la licence du projet, pour attribuer aux photos la même ou une autre compatible. 

### Action

Choisissez un cadre pour votre photo, installez les elephpants et vous-même. 

Les accessoires sont bienvenus, tant qu'ils respectent le code de [conduite du forum](https://afup.org/p/986-code-de-conduite). 

Composez le tout méticuleusement, et ensuite : 

__clic-clac__ : prenez une photo! 

Sauvez la photo sur votre ordinateur, avec votre nom ou pseudonyme, et ensuite, envoyez-la sur ce site. 

### Pull Request

Si vous êtes autonomes, envoyez la photo avec un PR sur [photo-famille-afup-2020](https://github.com/dseguy/photo-famille-afup-2020). 

Sinon, voici un synopsis rapide pour soumettre votre photo 

+ Faites un 'fork' du projet [photo-famille-afup-2020](https://github.com/dseguy/photo-famille-afup-2020) sur votre compte github. 
+ En ligne de commande, clonez le dépot :
```git clone https://github.com/dseguy/photo-famille-afup-2020```

+ Ajoutez votre photo dans le dossier de l'album. 
+ Ajoutez votre photo au dépot, et envoyez le tout sur github : 
```git add album/<votre photo>.jpeg
git commit -m 'ma photo elePHPant pour le forum PHP 2020'
git push origin
```
+ Rendez-vous maintenant sur votre compte github, sur le dépot qui a été forké au début : [https://github.com/<votre compte>/photo-famille-afup-2020](https://github.com/<votre compte>/photo-famille-afup-2020);
+ Utilisez le bouton 'Pull Request' et 'Create pull request' pour  envoyer une PR à l'album de photo de famille. 
+ MERCI ! On s'occupe de recevoir les photos, et de les ajouter à l'album et de mettre votre nom dans le fichier de contributeurs.

## Voir l'album

Vous pouvez voir l'album en ligne, ou bien en local. Pour cela, installez [thumbsup](https://thumbsup.github.io/), et produisez l'album avec la commande suivante : 

```
npm install -g thumbsup
thumbsup --input ./album --output ./website
```

C'est la commande qui sera utilisée pour produire le site en ligne.

## Licence

Cette photo de famille est mise à disposition selon les termes de la [Licence Creative Commons Attribution - Pas d’Utilisation Commerciale - Partage dans les Mêmes Conditions 4.0 International](http://creativecommons.org/licenses/by-nc-sa/4.0/).

## Auteurs

  - **Damien Seguy** - [@faguo](https://www.twitter.com/faguo)

Voir aussi la liste des [contributeurs](./CONTRIBUTORS.md) qui ont contribué à ce projet.

## Remerciements

  - Vincent Pontier, pour avoir dessiné l'elephpant
  - [AFUP]() pour avoir organisé le forum 2020