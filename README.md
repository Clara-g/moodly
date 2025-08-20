# Mini SaaS – Suivi de l’humeur & Collaboration en équipe

**Un outil open source et respectueux de la vie privée pour suivre le moral, partager les ressentis et favoriser l’entraide au sein des équipes.**

---

## 🎯 Objectif

Offrir un outil accessible, personnalisable et respectueux de la vie privée, permettant aux équipes de :
- Suivre leur moral au quotidien
- Partager leurs émotions et ressentis
- Favoriser l’entraide et la collaboration
- Prévenir le burnout et les risques psychosociaux

---

## 🧑‍🤝‍🧑 Cas d’usage

- Suivi du moral dans une startup, PME, association, groupe projet, équipe étudiante
- Animation d’équipe à distance ou hybride
- Soutien et entraide entre collaborateurs

---

## 🚀 Fonctionnalités principales

- **Saisie rapide du ressenti** : humeur, émotion, commentaire
- **Visualisation des tendances & statistiques** : graphe individuel et collectif, historiques, moyennes, pics
- **Groupes / équipes** : partage de messages de soutien, affichage du moral global
- **Confidentialité avancée** : anonymisation possible, gestion fine des partages de données
- **Notifications & rappels** : système configurable (encouragements automatiques…)
- **Intégrations intelligentes** : suggestions de soutien, analyse de tendances (IA en option)
- **Authentification sécurisée** : classique, SSO, OAuth (selon configuration)
- **Déploiement Docker, CI/CD, cloud**

---

## 🛠️ Stack technique

- **Frontend** : React (ou Vue.js)
- **Backend** : Node.js (Express) (ou Python FastAPI)
- **Base de données** : PostgreSQL (ou MongoDB)
- **Déploiement** : Docker, GitHub Actions, Vercel/Render
- **Tests** : Jest, Cypress
- **Documentation** : Swagger, README complet

---

## ⚡ Installation rapide

```bash
git clone https://github.com/votre-utilisateur/mini-saas-humeur.git
cd mini-saas-humeur
# Backend
cd backend
npm install
npm run dev
# Frontend (dans un autre terminal)
cd frontend
npm install
npm start
```

### 🐳 Déploiement Docker

```bash
docker-compose up --build
```

### 🎯 Configuration

- Créez un fichier `.env` dans `backend` et `frontend` (voir exemples `.env.example`)
- Paramétrez les clés d’API, la base de données etc.

---

## 📊 Documentation API

- La documentation Swagger est disponible sur `/api/docs` après démarrage du backend.
- Voir le dossier `/docs` pour des exemples d’utilisation.

---

## 🤝 Contribution

Les contributions sont les bienvenues !  
Pour contribuer :
1. Forkez le repo
2. Créez votre branche : `feature/ma-feature`
3. Faites vos modifications + tests
4. Ouvrez une pull request

Consultez le fichier [`CONTRIBUTING.md`](CONTRIBUTING.md) pour plus d’infos.

---

## 🛡️ Confidentialité & sécurité

- Les données sont anonymisées et ne sont jamais revendues.
- Respect de la vie privée par défaut.
- Chaque utilisateur contrôle la visibilité et le partage de ses données.

---

## 💡 Valeurs ajoutées

- Open source, personnalisable et gratuit
- Focus sur l’entraide et la prévention du burnout
- Respect maximal de la vie privée

---

## 📄 Licence

Ce projet est distribué sous licence [MIT](LICENSE).

---

## 💬 Contact & Communauté

Questions, retours, suggestions ?  
Ouvrez une issue ou contactez-nous via [contact@mini-saas-humeur.org](mailto:contact@mini-saas-humeur.org)

---

*Merci de contribuer à un environnement de travail plus sain et solidaire !*
