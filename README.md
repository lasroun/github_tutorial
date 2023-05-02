# Comment créer un projet, l'initier en local et le mettre sur GitHub par ligne de commande

## Créer un nouveau projet

1. Créez un nouveau dossier pour votre projet sur votre ordinateur.

2. Ouvrez un terminal (ou une ligne de commande) et placez-vous dans le dossier de votre projet à l'aide de la commande `cd`.

   ```sh
   cd /chemin/vers/votre/projet
   ```

3. Initialisez un nouveau projet Git en tapant la commande suivante :

   ```sh
   git init
   ```

## Ajouter des fichiers à votre projet

1. Ajoutez des fichiers à votre projet en les copiant ou en les créant directement dans le dossier du projet.

2. Une fois que vous avez ajouté les fichiers que vous souhaitez inclure dans votre projet, utilisez la commande suivante pour les ajouter à l'index Git :

   ```sh
   git add nomdufichier
   ```

   Cette commande peut être répétée pour ajouter plusieurs fichiers.

3. Pour ajouter tous les fichiers à l'index Git, vous pouvez utiliser la commande :

   ```sh
   git add .
   ```

## Effectuer un commit

1. Pour enregistrer les modifications apportées à votre projet, vous devez effectuer un "commit".

2. Pour ce faire, utilisez la commande suivante :

   ```sh
   git commit -m "Message de commit"
   ```

   Assurez-vous de fournir un message descriptif qui explique les modifications que vous avez apportées.

## Créer un dépôt GitHub

1. Accédez à votre compte GitHub et cliquez sur le bouton "New Repository" pour créer un nouveau dépôt.

2. Donnez un nom à votre dépôt et cliquez sur "Create Repository".

## Mettre en ligne votre projet sur GitHub

1. Retournez dans votre terminal et ajoutez le dépôt GitHub comme "remote" en utilisant la commande suivante :

   ```sh
   git remote add origin https://github.com/votre_utilisateur/nom_depot.git
   ```

2. Vérifiez que le remote a été ajouté correctement en tapant :

   ```sh
   git remote -v
   ```

   Vous devriez voir l'adresse URL de votre dépôt GitHub.

3. Envoyez vos modifications sur GitHub en utilisant la commande suivante :

   ```sh
   git push -u origin master
   ```

   Cette commande envoie votre branche "master" (la branche principale de votre projet) vers le dépôt GitHub.

Félicitations, vous avez maintenant initier votre projet localement et le mettre en ligne sur GitHub par ligne de commande !
