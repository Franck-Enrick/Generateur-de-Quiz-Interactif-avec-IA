#  QuizAI — Générateur de Quiz Interactif avec Claude

> Projet personnel · JavaScript ES6+ · API Claude (Anthropic) · HTML5/CSS3

Un générateur de quiz interactif qui utilise l'IA pour créer 5 questions sur **n'importe quel thème**, en quelques secondes.

![QuizAI Screenshot](screenshot.png)

##  Fonctionnalités

-  **Génération dynamique** — entrez un thème, Claude génère 5 questions uniques
-  **Timer configurable** — 15s / 20s / 30s ou sans limite
-  **3 niveaux de difficulté** — Facile, Moyen, Difficile
-  **Explications** — chaque bonne réponse est expliquée
-  **Score & statistiques** — bonnes/mauvaises réponses, temps total
-  **Clé API locale** — rien n'est stocké ni envoyé à un tiers
-  **Responsive** — fonctionne sur mobile et desktop

##  Lancer le projet

Aucune installation requise. C'est un fichier HTML unique.

```bash
git clone https://github.com/votre-username/quizai.git
cd quizai
# Ouvrez index.html dans votre navigateur
open index.html
```

Ou utilisez un serveur local :
```bash
python -m http.server 8000
# Puis ouvrez http://localhost:8000
```

##  Obtenir une clé API Anthropic

1. Rendez-vous sur [console.anthropic.com](https://console.anthropic.com)
2. Créez un compte et générez une clé API
3. Collez-la dans le champ prévu à l'ouverture de l'app

> La clé reste dans votre navigateur. Elle n'est jamais envoyée ailleurs qu'à l'API Anthropic officielle.

##  Stack technique

| Techno | Usage |
|--------|-------|
| JavaScript ES6+ | Logique de jeu, timer, états, fetch async/await |
| HTML5 / CSS3 | Interface responsive, animations, variables CSS |
| API Claude (Anthropic) | Génération des questions et explications |
| Git / GitHub | Versioning et déploiement |

##  Structure

```
quizai/
├── index.html      # Application complète (HTML + CSS + JS)
└── README.md       # Documentation
```

##  Exemple de thèmes

- `JavaScript ES6`
- `Histoire de France`
- `PHP / Symfony`
- `Astronomie`
- `Football`
- `Chimie organique`

##  Ce que j'ai appris

- Intégration d'une API IA (appel fetch, gestion du contexte, parsing JSON)
- Rédaction de **prompts structurés** pour obtenir un output JSON fiable
- Gestion des **états asynchrones** en JavaScript vanilla
- Architecture d'un jeu en JS : états, timer, transitions, scoring
- Design responsive sans framework CSS

##  Licence


---

*Développé par [Franck-Enrick NGASSAM](https://linkedin.com/in/franck-enrick-ngassam) — étudiant ingénieur EPF, spécialisation Systèmes Numériques Intelligents.*
