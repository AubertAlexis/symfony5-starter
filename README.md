# Starter - Symfony 5

## 1 - Installation

### Depuis Github
```
git clone https://github.com/AubertAlexis/symfony5-starter.git
cd symfony5-starter
composer install
yarn install
```

## 2 - Configuration
Créer un fichier `.env.local` :
> N'oubliez pas de modifier avec vos informations.
```dotenv
DATABASE_URL=mysql://root:password@127.0.0.1:3306/symfony5-starter
```

## 3 - Génération de la structure
```
composer generate
```

## 4 - Démarer le serveur en local
```
symfony serve
yarn encore dev
```

---------------

## Fonctionnalités

   - SB ADMIN 2 thème pour l'espace d'administration.
   - CRUD pour les utilisateurs côté administrateur
