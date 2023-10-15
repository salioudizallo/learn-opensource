# Découvrez l'Open Source
# C'est quoi l'Open Source
# Comment faire ?
Vous êtes intéressés ? Suivez ce guide pour faire vos premiers pas vers l'open source. Et en bonus, on construira ensemble une gallerie de tous les participants
## Installations et configuration
### Télécharger Git et installer
Le lien de téléchagement est le suivant: https://git-scm.com/downloads

L'installation de Git ressemble à l'installation de n'importe quel logiciel.
Seulement prêtez attention à ajouter Git aux variables d'environnement pour permettre de l'exécuter depuis la console de commandes.

### Télécharger un éditeur de code
Pour faire nos premiers pas dans la collaboration, nous aurons besoin d'un éditeur de texte qui va nous permettre de travailler efficacement

Téléchargez **Visual Studio Code** ici: https://code.visualstudio.com/Download

### Faites vos premiers tests pour vérifier l'installation
1. Ouvrir une console de commande avec `Windows + R` et vous tapez `CMD` puis `Enter`.
2. Tapez la commande `git --version`, vous devriez avoir le même résultat que ceci:
![Check the git version](git-version.png)

### Configuration
On va faire quelques configurations essentielles
1. Le nom d'utilisateur
```powershell
git config --global user.name "<Votre nom complet>"
```

2. L'adresse email
```powershell
git config --global user.email <Votre adresse email>
```

Comme ça, toutes les modifications faites seront enregistrées en votre nom, ce qui facilite la traçabilité des changements!

### Créer un compte Github
Rendez-vous sur [https://github.com](https://github.com) et créez votre compte personnel ! N'oubliez pas de choisir un nom d'utilisateur original et un mot de passe pas facile à déviner.

Si vous avez déjà un compte github, c'est parfait, connectez-vous et rendez-vous à l'étape suivante.

### Liaison Git et Github
Afin de publier vos collaborations, vos projets sur github, cette partie est essentielle.

Mais nous on va utiliser le protocole `https://` pour plus de facilité (mais ce n'est point le moyen le plus sécurisé !).

Donc on va donc attendre notre premier push pour nous authentifier à ce moment-là !