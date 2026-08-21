# 👑 Dicta MD

Bot WhatsApp multisession basé sur **Baileys**, avec système de plugins, pairing par code et stockage MongoDB.

> Développé par **Dicta** — *Mr DIcta Dev*

---

## ✨ Fonctionnalités

- 🔌 **Système de plugins** — commandes modulaires, faciles à ajouter/retirer
- 🔗 **Pairing par code** — connexion via `pair.html`, pas besoin de scanner un QR
- 🗄️ **MongoDB** — sauvegarde de session et de configuration
- 👥 **Gestion de groupes** — anti-call, paramètres de groupe, auto-join
- 🎬 **Téléchargements** — YouTube, Facebook, Instagram, APK
- 🖼️ **Médias & stickers** — création de stickers, conversion vidéo, vue unique
- 🛡️ **Anti-suppression** — récupère les messages supprimés
- ⚙️ **Identité personnalisable** — nom du bot, nom du dev, préfixe de commande

---

## 📂 Structure du projet

```
├── main.js                # Point d'entrée principal
├── config.js               # Configuration générale
├── config/
│   └── bot-identity.json   # Identité du bot (nom, dev, liens)
├── pair.html                # Page web de pairing
├── lib/                     # Fonctions internes (database, utils, anti-delete...)
└── plugins/                  # Commandes du bot
```

---

## 🚀 Installation

```bash
git clone <lien-du-repo>
cd Dicta-MD-Bot
npm install
npm start
```

Configure ensuite tes variables (MongoDB URI, numéro du dev, etc.) dans `config.js`.

## 🔗 Connexion

1. Lance le bot
2. Ouvre `pair.html`
3. Entre ton numéro WhatsApp et récupère le code de pairing
4. Colle le code dans WhatsApp > Appareils liés

---

## ⚙️ Configuration rapide

| Paramètre        | Valeur par défaut |
|-------------------|--------------------|
| Nom du bot        | `Dicta MD`          |
| Préfixe           | `.`                |
| Base de données   | MongoDB            |

---

## 📜 Commandes

Tape `.allmenu` une fois le bot connecté pour voir la liste complète des commandes disponibles.

---

## 🛠️ Développeur

**Dicta** — *Mr Dicta Dev*
Premier projet de développement 🩸
