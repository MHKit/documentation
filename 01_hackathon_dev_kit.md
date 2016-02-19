# My Human Kit - Dev kit hackathon 24-26 Mars.


## [ Bionico ](https://bionico.org/)

Bionicohand est un projet de prothèse de main électronique open
source.

Le monde de la robotique et du making produit des outils, des
techniques et des humains rendant la production de protheses a la portée
de tous.

Le projet BionicoHand reunis ces differents elements dans le but
d'ouvrir cette possibilite au delà des milieux avertis.

## HackerLoop + Bionico

Afin de servir ce but, HackerLoop propose ses services au projet
BionicoHand.

La nature open source du projet implique une organisation permettant une
continuité dans les efforts fournis par les éventuelles collaborateurs.
En d'autres termes il est très important qu'un nouvel arrivant même
temporaire (ie. dans le cas d'un hackathon), puisse commencer a batir sur
le travail déjà effectué, et limiter un maximum de dupliquer les
efforts.

Cette première mission aura pour but de mettre en place les fondations pour
les développements futurs du projet BionicoHand.

## Who are hackerloop?

Hackerloop is a collective of talented engineers and product designers searching for new uses of technology through original experiments. Open source software and open hardware are deeply rooted in our DNA and are at the core of our creations. Based in San Francisco, Prague and Paris, we thrive to build high-quality products that make sense for the end user.

We design electronic devices by combining industry standard development kits and DIY parts in order to shorten the time needed to get working prototypes. A strong background in both hardware and software startups gave us the tools and methods to quickly design and code products from scratch.

Specialized in hardware/software project design and industrialization of projects which aim at reaching the market quickly while keeping development costs low, our mission is to support you from your idea/prototype to manufacturing and product launch by applying agile methods.

## Hackerloop members

- Constantin Clauzel - constantin@hackerloop.com
- Charles Passet - charles@hackerloop.com
- Valentin Squirelo - valentin@hackerloop.com

<!--BREAK-->

## Milestone 1 - Hackathon

Cette première milestone a pour deadline le hackathon qui
aura lieu du 24 au 26 Mars.

### Livrable

Le but de cette milestone est de produire le nécessaire pour que les
participants produisent du code réutilisable et documenté.

Ce qui implique:

- Creation d'un compte github officiel pour Bionico, tout le code
  produit dans le cadre du projet bionico devra s'y retrouver.
- Production d'une documentation "Quick Start", permettant aux
  participants de facilement commencer a créer à partir de la main.
- Créer un Développement Kit permettant un développement
  incremental: le travail fournis par un groupe de participants est
  facilement utilisable par un autre groupe futur.
- HackerLoop fournis les modules de base:
  - Contrôle des moteurs
  - Myo
  - Capteur musculaire adafruit (je sais plus le nom)

### Developement Kit

Il est imperatif que la totalité du code produit lors de ces 3 jours
finisse sur github, et qu'il soit réutilisable par d'autres.

C'est pourquoi le Dévelopement Kit sera basé sur une architecture
modulaire. Les participants auront a disposition les fonctionnalités de
base de la main, leur role est de produire des modules visant a montrer
tout ce qu'on peut faire un fois qu'on a un ordinateur miniature
implanté a la place de la main.

Ce qui rend le projet Bionico si percutant ce n'est pas qu'on puisse
faire bouger des doigts avec un Myo, mais qu'on puisse rendre la
prothese open source non seulement abordable, mais surtout bien mieux
que celles disponibles sur le marche medicale.

Le developement kit est composé d'un ordinateur équipé d'un linux,
permettant l'accès aux technologies de la vie de tout les jours via ses
ports USB.
Il serait par exemple intéressant qu'un participant trouve un usage
innovant en branchant un clef 4g au bras.

Le but de ce developement kit est de faire d'une prothèse un objet de
créativité au meme titre qu'un smartphone.

C'est pourquoi il serait intéressant qu'en plus du dévelopement kit, les
participants puissent avoir a disposition un ensemble de devices USB
classiques, clef 4g, webcam, micro, capteurs infrarouges, arduinos
micros, etc... il faut qu'a la fin du hackathon, les participants aient
pu donner libre cours a leur créativité, l'innovation c'est l'usage, et
non la techno :)

### Estimation

| *livrable*                                                                                                                                                                                                                                                                                                                         | *estimation* |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| Création du compte github et de la documentation QuickStart                                                                                                                                                                                                                                                                        |  10 - 15 hrs |
| Création d'une image linux de base facilement installable  (RaspberryPI dans un premier temps).  L'image permet un hacking facile de la main, et une prise en main (haha) rapide pour les participants. Une doc sera produite pour permettre de facilement installer le système sur d'autres devices (edison, beaglebone, etc...). |  5 - 10 hrs  |
| Module permettant le contrôle des moteurs via la carte arduino du bras bionics                                                                                                                                                                                                                                                     | 5 - 10 hrs   |
| Module permettant d'interfacer avec le myo directement sur le bras. Le temps de dev dépend de ce que je trouve de viable en open source.                                                                                                                                                                                           | 10 - 30 hrs  |
| Module permettant l'utilisation des capteurs open sources (nom ?)                                                                                                                                                                                                                                                                  | 5 - 15 hrs   |
| _Total_                                                                                                                                                                                                                                                                                                                                   | 35 - 80 hrs     |

### Commande matériel

- Bras openbionics x1
- capteur pression pour les doigts
- vibreur type portable - retour sur le bras
- capteur de temperature - indication pour l'utilisateur
- leds multicolor
- clef usb 4g + sim
- accelero
- magneto
- gyro
- barometer
- myoware x 4
- capteur de lumière
- sonar
