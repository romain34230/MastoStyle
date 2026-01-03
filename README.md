🐘 MastoStyle

**Redécouvrez Mastodon avec un design moderne et épuré.**

MastoStyle est une extension Chrome qui transforme l'interface visuelle de n'importe quelle instance Mastodon (Piaille, Mastodon.social, etc.). Elle offre une esthétique "Glassmorphism" moderne, des animations fluides et améliore l'ergonomie de rédaction.

## ✨ Fonctionnalités Principales

* **🎨 Design Moderne :** Transforme les publications en cartes élégantes avec effet de verre, ombres portées et bordures arrondies.
* **🖌️ Personnalisation Totale :** Choisissez vos couleurs (fond et couleur principale) ou utilisez des thèmes prédéfinis (Modern Blue, Cyberpunk, Forest).
* **✒️ Mode Rédaction Amélioré :**
* Masque la zone de rédaction par défaut pour alléger l'interface.
* Ajoute un **bouton flottant (Plume)** en bas à gauche.
* Ouvre une fenêtre de rédaction superposée (au-dessus du flux) sans changer de page.


* **🖼️ Avatars Modernisés :** Tous les avatars passent en format carré arrondi ("Squircle") pour un look plus contemporain.
* **🔒 Respect de la vie privée :** Vos préférences sont stockées localement dans votre navigateur. Aucune donnée n'est transmise.

## 📂 Structure du projet

* `manifest.json` : Configuration de l'extension (permissions, icônes).
* `content.js` : Le cœur du système. Injecte le CSS, gère le bouton flottant et le déplacement de la fenêtre de rédaction.
* `popup.html` : L'interface du menu de l'extension.
* `popup.js` : Sauvegarde vos choix de couleurs.
* `icon.png` : L'icône de l'extension.

## 🚀 Installation (Mode Développeur)

En attendant la validation sur le Chrome Web Store, voici comment installer MastoStyle :

1. Téléchargez ou clonez ce dossier sur votre ordinateur.
2. Ouvrez Google Chrome et allez à l'adresse : `chrome://extensions/`
3. Activez le **Mode développeur** (bouton en haut à droite).
4. Cliquez sur **"Charger l'extension non empaquetée"** (Load unpacked).
5. Sélectionnez le dossier `MastoStyle`.
6. L'extension est installée ! 🎉

## 📖 Utilisation

1. Rendez-vous sur votre instance Mastodon préférée (ex: `piaille.fr`).
2. L'interface change automatiquement.
3. Pour **écrire un message**, cliquez sur le bouton rond avec une plume en bas à gauche de l'écran.
4. Pour **changer les couleurs**, cliquez sur l'icône MastoStyle (puzzle) dans la barre de votre navigateur.

## 🛠️ Dépannage

* **L'icône ne s'affiche pas :** Vérifiez qu'elle est bien épinglée dans votre barre Chrome (cliquez sur le puzzle 🧩).
* **Le design ne s'applique pas :** Actualisez la page (`F5`). Vérifiez que l'extension est activée.
* **Erreur "Connection established" :** Si vous cliquez sur l'extension alors que vous n'êtes pas sur un site Mastodon, c'est normal. L'extension ne s'active que sur Mastodon.

## 📄 Licence

Ce projet est libre de droits pour un usage personnel. Vous pouvez modifier le code pour vos propres besoins.

---

*Développé avec ❤️ pour la communauté Fédiverse.*
