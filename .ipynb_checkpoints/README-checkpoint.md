# Spinoff3
"Et si on allait ensemble plus loin avec MongoDB"

# Prérequis : 
* Python3
* Git

# Voici les étapes pour accéder au notebook : 


### Copier le repository de travail Spinoff3
> git clone https://github.com/phil3in/Spinoff3

### Aller dans le repository floupics
> cd Spinoff3

### Créer son environnement virtuel
> python3 -m venv nomDeEnv

### Activer son environnement (Windows)
> nomDeEnv\Scripts\activate.bat

### Activer son environnement (Mac OS)
> source nomDeEnv/bin/activate

### Installer jupyter lab
> pip install jupyterlab

### Afin d'acceder aux scripts ils nous faut lancer jupyter lab : 
> jupyter-lab

### Installer PyMongo
> pip install pymongo


# Instructions pour installer et lancer MongoDB :

### Aller sur le site officiel :

https://www.mongodb.com/try/download/community?tck=docs_server

### Télécharger la version courante de MongoDB Community Server.

### Lancer l'installateur

### Choisir l'installation complète et incluant MongoDB Compass

### Vous pouvez installer MongoDB comme service Windows.

### Autrement, vous devrez le lancer manuellement. Pour ça, créez la variable path "C:\Program Files\MongoDB\Server\4.4\bin" dans Windows

### Nous pouvons maintenant lancer dans git bash 

> mongod

### puis

> mongo

#### (Pour plus de détails, voir https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/#install-mongodb-community-edition)


## Voilà, il ne vous reste plus qu'à lancer dans l'ordre les cellules du JupyterLab pour créer la base de données et y insérer les données.

### Pour vérifier vos création / insertions / lancez MongoDB Compass et connectez-vous en laissant les paramètres par défaut. Il faut que Mongo soit lancé en parallèle.