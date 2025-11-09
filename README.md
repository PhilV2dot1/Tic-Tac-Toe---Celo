# Tic-Tac-Toe---Celo
Tic tac Toe basic

Celo : 0xD92BcD223Aa2A9818CbeB853b1d2beAa9eaf3008

🎮 Fonctionnalités du jeu
Gameplay :

Jeu solo contre une IA avec une stratégie simple mais efficace
L'IA cherche à gagner, puis à bloquer le joueur, puis utilise des positions stratégiques
Détection automatique des victoires, défaites et matchs nuls

Système de statistiques :

Nombre de parties jouées
Victoires, défaites, matchs nuls
Taux de victoire (winrate)
Série de victoires actuelle et record
Victoire la plus rapide enregistrée
Nombre total de mouvements

Leaderboard :

Classement des 10 meilleurs joueurs par nombre de victoires
Affichage du winrate, meilleure série et temps record
Mise à jour automatique après chaque partie

📋 Fonctions principales

startGame() - Démarre une nouvelle partie
makeMove(position) - Joue à une position (0-8)
forfeitGame() - Abandonne la partie en cours
getBoard(player) - Récupère le plateau actuel
getPlayerStats(player) - Récupère les stats d'un joueur
getLeaderboard() - Récupère le top 10

Le contrat n'utilise aucun fonds (pas de fonctions payable) et émet des événements pour suivre toutes les actions importantes !
