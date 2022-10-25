# PostgreSQL & PGAdmin 4

## Démarrage de l'activité
* Il faut cloner le repository et entrer dans le dossier avant de commencer le cours
```sh
$ git clone https://github.com/Harrylepap/DONNEE1.git 
$ cd DONNEE1
```
* Executer la commande suivante pour allumer les machines
```sh
$ docker-compose up -d
```

## Requirements:
* docker >= 17.12.0+
* docker-compose


## Variable à modifier si besoin
This Compose file contains the following environment variables:

* `POSTGRES_USER` valeur par defaut **postgres**
* `POSTGRES_PASSWORD` valeur par defaut **postgres**
* `PGADMIN_DEFAULT_EMAIL` valeur par defaut **admin@admin.com**
* `PGADMIN_DEFAULT_EMAIL` valeur par defaut **root**

## Connexion à PostgreSQl en ligne de commande:
```sh
$ docker exec -it postgres_srv /bin/bash 
$ psql -U $POSTGRES_USER
```

## Connexion à PostgreSQl sur interface graphique:
* **URL:** `http://localhost:5050`
* **Username:** `PGADMIN_DEFAULT_EMAIL`
* **Password:** `PGADMIN_DEFAULT_EMAIL`

