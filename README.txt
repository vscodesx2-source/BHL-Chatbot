BHL EXPRESS — Chatbot by BHL Systems
====================================

DÉMARRAGE (Windows / VS Code)
1. Décompressez BHL_EXPRESS.zip.
2. Ouvrez le dossier BHL_EXPRESS dans Visual Studio Code.
3. Ouvrez le fichier index.html.
4. Cliquez avec le bouton droit et choisissez "Open with Live Server".
   Si Live Server n'est pas installé : Extensions (Ctrl+Shift+X) > cherchez "Live Server" > Install.
5. Vous pouvez aussi double-cliquer sur index.html pour ouvrir l'application dans le navigateur.

AUCUN PYTHON N'EST NÉCESSAIRE.

FONCTIONS INCLUSES
- Écran de connexion et création de compte (prototype local).
- Langues : arabe, français, anglais et italien.
- Nouvelle discussion, historique local, paramètres.
- Calcul du prix par pays et poids de 1 à 30 kg.
- Ajout automatique de 89 DT TDA par carton.
- Refus des poids supérieurs à 30 kg.
- Réponses limitées aux services BHL EXPRESS.

IMPORTANT — À LIRE AVANT MISE EN PRODUCTION
- La connexion actuelle est une démonstration locale : elle n'est PAS sécurisée pour de vrais comptes.
  Pour une vraie application publique, il faudra un backend, une base de données et un système d'authentification sécurisé.
- Les tarifs ont été recopiés visuellement depuis les photos fournies. Vérifiez-les ligne par ligne avec le tarif officiel avant toute utilisation commerciale.
- Les tableaux imprimés ne précisent pas tous les frais de chaque moyen de paiement. L'application ne les invente pas.
- La règle intégrée ajoute 89 DT TDA par carton.
- Les montants sont en DT.

MODIFIER LES TARIFS
Ouvrez prices.js. Chaque pays possède une liste de 30 prix, dans l'ordre de 1 kg à 30 kg.
Ne changez pas les valeurs sans validation du tarif officiel.

MISE A JOUR VISUELLE
- Animation d'ouverture et thème noir/rouge.
- Le logo officiel doit être placé dans assets/bhl-logo.png (PNG recommandé).
- Le tarif du tableau est affiché explicitement SANS TDA.
- 89 DT de TDA sont affichés séparément et ajoutés au total par carton.
- Aucun champ de capacité n'est demandé.
\nECRAN DE CHARGEMENT ET LOGO\nCopiez votre logo officiel au format PNG dans le dossier assets et nommez-le BHL.LOGO.png.\nAu démarrage, un écran de chargement animé s'affiche pendant environ 3 secondes.\n