# Installer les différentes librairies

- python3
- fastai
- fasterai
- pytorch
- tqdm
- codecarbon


## Exemple

> pip install fastai
> pip install fasterai
> pip install torch
> pip install pytorch
> pip install tqdm
> pip install codecarbon

# Ouvrir le .ipynb 

> jupyter notebook

# Préparer les données

Les données de mouvement doivent être structurées comme suit:

- DATA
|_ TRAIN
    |_ Pose 1
    |_ Pose 2
    |_ ...
|_ TEST
    |_ Pose 1
    |_ Pose 2
    |_ ...


Il faut essayer de respecter une proportion de 80% données de TRAIN et 20% de données de TEST. Le réseau de neurones entrainé sera en mesure de s'adapter à un nombre variable de différentes classes de poses.


# Exécuter les cellules

Ceci peut être fait plus rapidement avec le raccorci SHIFT+ENTER.

