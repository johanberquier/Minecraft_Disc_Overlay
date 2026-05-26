# 🎵 Minecraft Music Discs Overlay

Un overlay HTML/CSS/JavaScript interactif et fluide conçu pour les streamers ou les créateurs de contenu sur Minecraft. Cet outil permet de suivre en temps réel la complétion d'une collection de disques de musique Minecraft, avec des animations visuelles et des effets sonores à chaque découverte.

---

## ✨ Fonctionnalités

* **Collection Complète :** Gère les 21 disques de musique du jeu (de la version classique jusqu'aux dernières mises à jour comme *Creator* ou *Precipice*).
* **Animation Fluide :** Un cadre Minecraft descend élégamment du haut de l'écran pour afficher le disque fraîchement récupéré avec un effet de bercement pixelisé.
* **Barre de Collection Dynamique :** Une barre centrale affiche tous les disques débloqués au cours de la session. Elle s'adapte automatiquement et passe à la ligne pour éviter de cacher l'animation ou la barre de recherche.
* **Effets Sonores (Victoire) :** Un son de réussite (sélectionné aléatoirement parmi plusieurs fichiers) se déclenche dès qu'un disque est ajouté.
* **Système de Recherche Intégrée :** Permet au streamer ou à un modérateur de chercher et valider un disque rapidement en tapant son nom.
* **Compteur en Temps Réel :** Un widget discret en bas à gauche indique le nombre de disques restants à trouver.
* **Mode Test :** Un bouton permet de simuler le déblocage de toute la collection d'un seul coup pour tester le rendu visuel.

---

## 📁 Structure des Dossiers

Pour que l'overlay fonctionne correctement, assure-toi d'avoir cette structure de fichiers sur ton ordinateur ou ton serveur :

```text
├── index.html               # Le code principal de l'overlay
├── fonts/
│   └── Minecraft.ttf        # La police d'écriture Minecraft officielle
├── disques/
│   ├── _cadre.png           # L'image du cadre d'élément (item frame)
│   ├── 5.png
│   ├── CAT.png
│   └── ... (toutes les images de disques en .png et MAJUSCULES)
└── sons/
    ├── victoire1.mp3        # Premier son de victoire
