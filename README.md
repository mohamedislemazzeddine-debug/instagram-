# Login Page Project

Ce projet est une **page de login** simple hébergée sur GitHub Pages. Il permet de simuler un système de connexion où toutes les tentatives de login, réussies ou non, sont automatiquement enregistrées dans un **Google Sheet** via un **Google Apps Script**. Cela inclut le nom d'utilisateur, le mot de passe saisi et la date/heure de la tentative.  

La page de login affiche toujours un message **“Incorrect login!”** pour chaque tentative, ce qui permet de tester la collecte de données sans créer de véritable authentification. Le projet est idéal pour apprendre à connecter une page web à un Google Sheet, comprendre le fonctionnement de **fetch**, et gérer des formulaires HTML/CSS simples.  

## Installation et utilisation

1. Déployer le Google Apps Script lié à ton Google Sheet avec les paramètres :  
   - **Execute as : Moi**  
   - **Who has access : Anyone**  
   - Autoriser le script via Google  

2. Copier le lien Web App dans le fichier `index.html` à la place de `WEB_APP_URL_HERE`.  

3. Héberger `index.html` sur GitHub Pages et tester la page de login. Les logins apparaîtront automatiquement dans ton Google Sheet.  

Ce projet combine HTML, CSS, JavaScript et Google Apps Script pour créer un workflow simple mais complet pour collecter et enregistrer des données utilisateur.
