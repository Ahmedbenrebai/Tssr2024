# Création d'Unité d'Organisation, Groupe d'Utilisateurs et Utilisateur dans Active Directory

## 1. Connexion à l'Active Directory

Assurez-vous d'avoir les droits nécessaires pour effectuer ces actions et connectez-vous à votre contrôleur de domaine Active Directory.

## 2. Création de l'Unité d'Organisation (OU) Wilders_students

1. Dans le gestionnaire Active Directory, cliquez avec le bouton droit de la souris sur le domaine `wilders.lan`.
2. Sélectionnez "Nouveau" > "Unité d'organisation".
3. Nommez l'Unité d'Organisation comme suit : `Wilders_students`.
4. Appuyez sur "OK" pour créer l'OU.

## 3. Création du Groupe d'Utilisateurs Students

1. Dans le gestionnaire Active Directory, cliquez avec le bouton droit de la souris sur l'OU `Wilders_students` que vous venez de créer.
2. Sélectionnez "Nouveau" > "Groupe".
3. Nommez le groupe comme suit : `Students`.
4. Appuyez sur "OK" pour créer le groupe.

## 4. Création de l'Utilisateur au sein du Groupe Students

1. Dans le gestionnaire Active Directory, cliquez avec le bouton droit de la souris 
2. Sélectionnez "Nouveau" > "Utilisateur".
3. Suivez l'assistant pour créer un nouvel utilisateur en remplissant les informations nécessaires (nom, prénom, nom d'utilisateur, etc.).
4. Une fois l'utilisateur créé
5.  cliquez avec le bouton droit > ajouter à un groupe
6.  Sélectionnez le groupe `Students` et appuyez sur "OK" pour ajouter l'utilisateur à ce groupe.
