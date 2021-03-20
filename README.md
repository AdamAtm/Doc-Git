**GIT**

Git est un système libre permettant la gestion de versions d&#39;un code source. Il permet de revenir sur une version d&#39;un projet et facilite la collaboration entre plusieurs développeurs sur un même projet.

Ce système est décentralisé, c&#39;est-à-dire que le projet n&#39;est pas stocké seulement sur un serveur centralisé mais sur tous les ordinateurs des contributeurs en utilisant un système de connexion pair à pair1.

1. Le pair à pair est un réseau d&#39;échange où toutes les entités sont à la fois client et serveur.

Ce système fonctionne avec des lignes de commandes, mais des applications comme GitHub ou GitLab offrent une interface graphique basé sur Git et un serveur centralisé.

**Commandes Git :**

- git init : Après avoir positionné la console git bash sur le répertoire du projet, cette commande permet d&#39;initialisé, créer un dépôt lié à ce projet.

- git add [nom du fichier] : Permet de traquer un fichier et détecter si des modification ont été apportées depuis le dernier commit.

- git status : Permet de vérifier les fichiers traquer et non traquer.

- git commit -m &#39;ma description&#39; : Créer un nouvelle version du projet avec les nouveaux fichiers et les dernières modifications.

- git remote add [nom du dépôt] [url du dépôt] : Ajoute un dépôt distant où sera stocker le projet après l&#39;avoir pousser.

- git push -u [nom du dépôt (ex: origin)] [nom d&#39;un branche (ex: master)] : Permet d&#39;envoyer les différentes versions (les commits) sur un remote (dépôt distant).

- git pull [nom du dépôt] : Permet de récupérer la dernière version sur un dépôt distant.

- git clone [url du dépôt] : Permet de cloner un dépôt distant sur la machine local. Toutes les versions (commits) seront clonées.

- git log : Liste tous les commits d&#39;un projet

- git branch : Liste les branches

- git branch [nom] : Créer une nouvelle branche

- git checkout [nom d&#39;une branche] : Permet de se positionner sur une branche

- git merge [une autre branche] : Permet d&#39;ajouter les modifications faites sur une autre branche à la branche courante.

- git blame [nom d&#39;un fichier] : Permet de voir tous les modifications apportés à un fichier depuis sa première version. Il permet d&#39;identifier l&#39;auteur de ces modifications.

**Ignorer des fichiers dans les commits :**

Il est possible d&#39;exclure des fichiers du suivi de Git. Ils seront alors exclus lors d&#39;un commit ou d&#39;un git add \*.

On peut par exemple exclure les fichiers temporaires ce qui permet d&#39;alléger le téléchargement du projet, où bien exclure des fichiers sensibles tel que les fichiers .sql.

Pour mettre en place ce système, il faut créer un fichier se nommant .gitignore à la racine du répertoire. Dans ce fichier, il faut lister les répertoire, fichiers ou types de fichier à ignorer.

Exemple d&#39;un fichier .gitignore

![](RackMultipart20210320-4-1t1abgx_html_a90a5e7ee1811d49.png)
