# ateliers-ml-2019

### Before all : to re-align with the forked repo git remote -v
`git remote add upstream https://github.com/42-AI/ateliers-ml-2019.git`
`git fetch upstream`
`git checkout master`
`git commit -m 'previous week s work'`
`git merge upstream/master`

### Conda environment to reactivae proper
`source activate AtelierML` ou `source activate AtelierML`
AtelierML ou encore LabML
`conda deactivate`

to find which `conda info --envs`

ensuite :
`jupyter notebook`

## Installation de python et de ses modules

Nous utiliserons Miniconda, qui permet d'installer un environnement minimal pour Python. Vous devrez installer Miniconda dans le sgoinfre. Pour ce faire:

  -Allez dans le sgoinfre et créez un dossier au nom de votre login, avec le chmod en 700:

    cd /sgoinfre/goinfre/Perso
    mkdir VOTRE_LOGIN
    chmod 700 VOTRE_LOGIN

  -Allez dans le dossier créé et téléchargez-y Miniconda

    cd VOTRE_LOGIN
    curl -o miniconda3.sh https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
    sh miniconda3.sh
  
  -ATTENTION!! Durant l'exécution du script d'installation, il faut indiquer le chemin d'installation approprié

    /sgoinfre/goinfre/Perso/VOTRE_LOGIN/miniconda3

  -Dans votre fichier .zshrc (ou alternative), ajoutez la ligne suivante:

    export PATH="/sgoinfre/goinfre/Perso/VOTRE_LOGIN/miniconda3/bin:$PATH"

  -Réinitialisez votre terminal

    $> source ~/.zshrc

  -Vérifiez que l'opération a bien été effectuée

    $> which python
    /sgoinfre/goinfre/Perso/VOTRE_LOGIN/miniconda3/bin/python

  -Installer jupyter
  
    conda install jupyter
  
  -Clonez ce repo dans votre dossier favori
  
  -Déplacez-vous dans le repo cloné
  
  -Lancer jupyter
    
    jupyter notebook
    
  -Une fenêtre s'ouvrira dans votre navigateur. Ouvrez le notebook de la semaine sur lequel vous voulez travailler.
