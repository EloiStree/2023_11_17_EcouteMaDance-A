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
> pip install torch==2.1.0 torchvision==0.16.0 torchaudio==2.1.0 --index-url https://download.pytorch.org/whl/cpu
> pip install pytorch
> pip install tqdm
> pip install codecarbon
> pip install jupyterlab
> pip install notebook
> pip install voila

# Ouvrir le .ipynb 

> jupyter notebook
> jupyter NB

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

