# Othello jeu multijoueur pour ESP32

## Description

Ce projet est une implémentation du jeu Othello conçu pour être joué en réseau entre deux ESP32. Les joueurs peuvent contrôler le jeu à l'aide de Gameboys, en utilisant les boutons directionnels (Haut, Bas, Gauche, Droite) pour effectuer leurs mouvements.

## Fonctionnalités

- **Multijoueur en Réseau:** Jouez contre un adversaire en temps réel via une connexion réseau entre deux ESP32.
- **Intégration avec Gameboys:** Utilisez les boutons directionnels (Haut, Bas, Gauche, Droite) des Gameboys pour effectuer des mouvements dans le jeu.

## Prérequis Matériels

- Deux modules ESP32 avec la connectivité Wi-Fi activée.
- Deux Gameboys équipées de boutons directionnels.

## Installation

1. **Téléversement du Code sur les ESP32:**
   - Clonez le dépôt depuis GitHub:

     ```bash
     git clone https://github.com/votre-utilisateur/othello-esp32.git
     ```

   - Téléversez le code sur chaque ESP32 en utilisant l'IDE Arduino ou un outil similaire.

2. **Connexion au Réseau Wi-Fi:**
   - Assurez-vous que les deux ESP32 sont connectés au même réseau Wi-Fi.

3. **Configuration des Gameboys:**
   - Allumez les Gameboys dans l'ordre suivant : gameboy serveur puis gameboy client.

4. **Lancement du Jeu:**
   - Lancez le jeu sur chaque ESP32.
   - Commencez à jouer en utilisant les boutons directionnels (Haut, Bas, Gauche, Droite) des Gameboys et la touche select pour sélectionner une case.

