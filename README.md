# Blog_manytomany_reversible
Repository associé à un article du site https://blog.manuso.fr

# Initialiation du projet

1. Créer un fichier .env.local
2. Ajouter la variable DATABASE_URL=mysql://LOGIN:MDP@127.0.0.1:3306/blog_manytomany_reversible?serverVersion=5.7
3. Remplacer LOGIN et MDP par vos informations
4. Exécuter les commandes suivantes :

php bin/console doctrine:database:create
php bin/console doctrine:schema:update --force
php bin/console cache:clear



