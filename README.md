# Koffi Lévis Akalete — Portfolio

🟢 **En ligne : [akaletekoffilevis.github.io](https://akaletekoffilevis.github.io)**

Portfolio personnel de **Koffi Lévis Akalete** — développeur Full Stack Junior basé à Niamey (Niger), Ambassadeur 10000 CODEURS, étudiant en Mathématiques-Informatique à l'Université Abdou Moumouni.

Site 100 % statique, **HTML / CSS / JavaScript** — aucun framework, aucun outil de build, aucune dépendance. Servi directement par **GitHub Pages** depuis la branche `main`.

## ✨ Fonctionnalités

- 🌓 Bascule thème **sombre / clair** (mémorisée, respecte la préférence système par défaut)
- 🌐 Bascule de langue **FR / EN** (mémorisée), tout le contenu piloté depuis une seule source
- 🧩 Grille de projets filtrable (Tous / Web / API / Mobile / Outils)
- 📱 Entièrement responsive, accessible, navigation clavier
- ⚡ Zéro build, zéro dépendance — fichiers statiques uniquement

## 🛠️ Stack

- HTML5 (balisage sémantique)
- CSS3 (custom properties, `color-mix`, Grid/Flexbox, sans framework)
- JavaScript vanilla (`IntersectionObserver` pour la nav active au scroll, `localStorage` pour la persistance thème/langue)

## 📁 Structure du projet

```
.
├── index.html          # Squelette de la page (contenu injecté par JS)
├── css/
│   └── style.css       # Styles, thèmes et règles responsive
├── js/
│   ├── content.js      # Source unique de tout le contenu (FR/EN) et liens
│   └── main.js         # Rendu, thème, changement de langue, interactions
├── assets/
│   ├── favicon.svg
│   └── img/
│       └── profile.png
└── README.md
```

## 🚀 Démarrage local

Aucune étape de build. N'importe quel serveur de fichiers statiques convient :

```bash
python -m http.server 8000
# puis ouvrir http://localhost:8000
```

Ou simplement ouvrir `index.html` dans un navigateur.

## 🌍 Déploiement

Servi directement par **GitHub Pages** depuis la branche `main` de ce dépôt (nom spécial `akaletekoffilevis.github.io` — GitHub le sert automatiquement à la racine du domaine du compte, aucune configuration supplémentaire nécessaire).

## ✏️ Mettre à jour le contenu

Tout le texte (FR et EN), les compétences, le parcours, les projets, les services et les certifications vivent dans [`js/content.js`](js/content.js) — modifiez les données ici et la page se re-rend automatiquement, sans toucher au HTML.

## 📬 Contact

- Email : [koffilevis21@gmail.com](mailto:koffilevis21@gmail.com)
- GitHub : [@akaletekoffilevis](https://github.com/akaletekoffilevis)
- LinkedIn : [linkedin.com/in/akalete-koffi-levis](https://linkedin.com/in/akalete-koffi-levis)
- WhatsApp : [+227 91 53 52 20](https://wa.me/22791535220)

---

© Koffi Lévis Akalete. Tous droits réservés.
