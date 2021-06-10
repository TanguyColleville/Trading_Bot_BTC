# Projet MDS Trading bot on BTC : école CentraleSupelec 2020-2021 
# Groupe 07 

![CentraleSupelec Logo](https://www.centralesupelec.fr/sites/all/themes/cs_theme/medias/common/images/intro/logo_nouveau.jpg)

## Auteurs 
* Matthieu Briet : matthieu.briet@student-cs.fr
* Clément Boulay : clement.boulay@student-cs.fr
* Mohsine Zireg : moshine?zireg@student-cs.fr
* Tanguy Colleville : tanguy.colleville@student-cs.fr
* Wassim Behjal : wassim.behjal@student-cs.fr 

## Sommaire
  - [Auteurs :](#auteurs-)
  - [Sommaire](#sommaire)
  - [Introduction & Description du projet](#introduction--description-du-projet)
  - [Liens utiles](#liens-utiles)
  - [Architecture et vue d'ensemble](#architecture-et-vue-densemble)
  - [Prise en main](#prise-en-main)
    - [Instruction pour installation](#instruction-pour-installation)
    - [Utilisation](#utilisation)
  - [Conclusion](#conclusion)

## Introduction & Description du projet
Le but du projet est d'utiliser nos connaissances afin de comparer les prédictions du cours du BTC sur 30 jours avec des modèles classiques, à savoir ARIMA ARIMAX etc avec des modèles plus complexes faisant appel au deep learning. 

## Liens utiles 
* [Batch size issue ] (https://machinelearningmastery.com/use-different-batch-sizes-training-predicting-python-keras/?fbclid=IwAR3zjCnpr8tC4nYN4q2m1LXbyteFECLqfLgBupzsz5x_FWdQN76Hu3Z7Hck)
* [feature engineering random forest] (https://scikit-learn.org/stable/auto_examples/ensemble/plot_forest_importances.html)
* [RNN cheatsheet](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks)
* [ RmsProp basics ](https://towardsdatascience.com/a-look-at-gradient-descent-and-rmsprop-optimizers-f77d483ef08b)
* [ RMSprop keras](https://keras.io/api/optimizers/rmsprop/)
* [SGD](https://scikit-learn.org/stable/modules/sgd.html)
* [Loss functions & time series] (http://www.faculty.ucr.edu/~taelee/paper/lossfunctions.pdf)
* [Hand on machine learning with scikit-learn, keras & tensorflow]


## Architecture et vue d'ensemble
```

```


## Prise en main 
### Instruction pour installation 
On commence, pour travailler sur le projet ou le tester, par créer une copie locale avec `git clone https://github.com/TanguyColleville/Trading_Bot_BTC.git`  
Ensuite, afin d'importer les modules nécessaires pour faire fonctionner correctement les programmes, il faut, dans une console Python, taper la requête " pip install -r requirements.txt " et simplement appuyer sur "entrée".
Nota Bene : il est préférable de travailler dans un environnement virtuel. Pour ce faire, il vous faut suivre ces étapes :  

Se placer dans le rep du projet dans votre invite de commande  
cd Python/repDuProjet (si on est à la racine)  
Créer votre environnement virtuel via   
Python -m venv [NOM VENV]  
Activer l’environnement :   

* si MACOS :
        source [NOM VENV]/bin/activate
* si Windows :
        cd [NOM VENV] puis Scripts\Activate.bat
En demeurant dans [NOM VENV] taper pip install -r requirements.txt

### Utilisation 


## Conclusion 
Pour conclure, nous avons pris du plaisir à participer à ce projet. L'enjeux de la prédiction de time series est crucial, aussi bien dans le domaine de la finance que pour de la prédiction de charge de consommation en éléctricité. La particularité ici était la cryptomonnaie (BTC) qui présente des comportements très spécifiques mais également le nombre de données. 