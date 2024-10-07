# versionning_test
repo de test pour cours git

# Liste de commande 

### Fichier hello.txt

`` git clone https://github.com/mariloumars/versionning_test.git ``

`` git add hello.txt ``

`` git commit -m "Ajoue fichier" ``

``  git add . ``

`` git commit -m "Modification Hello" ``

`` git push ``

### Gestion de conflit

`` git add . ``

`` git commit -m "Insertion erreur" ``

`` git log ``

`` git reset HEAD^ ``

`` git status ``

`` git commit -m "Annuler commit" ``

`` git pull `` 

`` git add hello.txt `` 

`` git commit -m "Conflit" ``

`` git add . ``

`` git commit -m "Conflit resolve" ``

`` git push ``

### Création et gestion de branch

`` git branch ``

`` git branch NewBranch ``

`` git checkout NewBranch ``

`` checkout main ``

`` git branch -d NewBranch ``

### Gestion de tag

`` git log ``

`` git tag v1.0 19e3893b3ec3e898a9edfcf6b6d073a8f73b318d ``

`` git push --tags ``

`` git tag -d v1.0 ``

### Grep

`` git grep "Bonjour" ``