# TP Intégration des données - Talend - Projet M2 MSI ID 2023-2024 [GRENOBLE IAE]

## Créer un projet Talend nommé TPINT

## Récupérer le projet

Localisez vous dans le dossier où est installé Talend : 

Depuis votre PC : 
```bash
cd "C:\Program Files (x86)\TOS_DI-8.0.1\studio\workspace"
```

Depuis les PCs de l'IAE : 
```bash
cd "C:\Program Files\Talend\TOS_DI-20200219_1130-V7.3.1\workspace"
```

Pour récupérer le projet, utiliser soit la commande git clone (recommandé) soit le fichier zip généré en cliquant sur le bouton vert "Code"
```bash
git clone https://github.com/nastoo/iae-m2msi-id-tp-integration-donnees/
```

> Etant donné que le repo est privé, il vous sera demandé de vous connecter avec votre compte Github. 


Pour mettre les fichiers Git dans le workspace de travail : 
```bash
cp -rf iae-m2msi-id-tp-integration-donnees/.*  TPINT/
```


## Téléchargement des fichiers / bases de données

Pour éviter tout problème ou bug de connexion avec les bases de données, créez un dossier `C:\tmp` dans lequel vous mettrez les fichiers suivants (sans les renommer svp) : 
- inscription-olap.db
- master.xlsx
- programme.csv.csv
- scolarite.db

## Lancement du projet

Ouvrir Talend, et changer le  workspace (au sens Talend, changer de connexion) et pointer sur le répertoire `iae-m2msi-id-tp-integration-donnees` qui doit se trouver dans votre dossier `C:\Users\username\iae-m2msi-id-tp-integration-donnees`, sauf si vous avez fait le choix de l'enregistrer ailleurs.


## Soumettre des changements

Vous pouvez utiliser Github Desktop ou la ligne de commande. Attention à bien utiliser le répertoire TPINT localisé dans workspace. 

git add . 
git commit -m "Résumer ici ce que vous avez fait"
git push 
