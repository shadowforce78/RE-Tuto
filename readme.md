# Plateforme d'Apprentissage au Reverse Engineering

## 🎯 Objectif
Développer une plateforme web gratuite et interactive pour apprendre le **reverse engineering** (RE) en passant par des **cours théoriques**, des **vidéos explicatives** et des **crackmes** à analyser et résoudre soi-même.

L'objectif est d'offrir un apprentissage progressif où l'utilisateur peut :
- Suivre des **mini-cours** avec des concepts expliqués simplement
- Visionner des **vidéos pédagogiques** pour chaque concept
- Télécharger des **crackmes** et les analyser pour pratiquer les techniques apprises
- Suivre sa **progression** et obtenir des feedbacks sur ses réussites

---

## 🚀 Fonctionnalités principales
- **Cours interactifs** : Chaque module présente un concept spécifique avec des explications théoriques simples et un exemple vidéo.
- **Crackmes à résoudre** : Chaque cours est suivi d'un crackme à analyser pour mettre en pratique la théorie.
- **Suivi de progression** : L'utilisateur peut voir ses progrès à travers la plateforme et accéder à un système de validation ou de solution après avoir testé son approche.
- **Plateforme simple et gratuite** : Pas de coûts d'hébergement, tout est fait pour être accessible aux étudiants et passionnés de RE.

---

## 🧑‍💻 Stack technique

- **Frontend** : HTML/CSS/JS (ou Vue.js/React.js pour plus de modularité)
- **Backend** : Flask (Python) ou Express (Node.js)
- **Base de données** : SQLite (pour garder tout simple et léger) ou MongoDB (si besoin de plus de flexibilité)
- **Authentification** : Auth maison avec JWT ou gestion de sessions
- **Stockage des vidéos** : Hébergement via YouTube (vidéos privées ou non-répertoriées)
- **Déploiement** : Vercel (pour le frontend) et VPS (pour le backend)

---


## 🏗️ Contribution

Nous accueillons toute aide sur ce projet ! Que tu sois développeur, créateur de contenu pédagogique ou passionné de reverse engineering, tu peux contribuer.

### Rôles recherchés

Nous recherchons activement des personnes pour rejoindre l'équipe :

- **Frontend Dev (1)** : HTML/CSS/JS, Vue.js ou React.js pour créer une interface simple et claire
- **Backend Dev (1)** : Flask (Python) ou Express (Node.js) pour la gestion des utilisateurs et des APIs
- **Créateurs de Crackmes (2)** : Pour concevoir des défis variés allant du facile au complexe
- **Créateurs de contenu pédagogique (2)** : Pour rédiger des cours et créer des vidéos explicatives

### **Fais tes modifications et commits**

```bash
git add .
git commit -m "Ajout d'un nouveau module ou crackme"
```

### **Pousse ta branche et ouvre une pull request**

```bash
git push origin nouvelle-feature
```

---

## 📝 Tâches à accomplir

Voici la liste des tâches à venir pour la plateforme :

1. **Frontend :**
   - Créer l'interface de la page d'accueil, des cours, et du suivi de progression.
   - Rendre le site responsive et agréable à utiliser.
   
2. **Backend :**
   - Implémenter l'API pour l'authentification et la gestion de la progression.
   - Développer une API pour récupérer les modules, vidéos et crackmes.

3. **Création de contenu :**
   - Développer des crackmes à résoudre pour chaque module.
   - Créer des vidéos courtes expliquant chaque concept.

---

## 🤝 Partenaires et Mentors

Si tu souhaites participer à la création de contenu ou du code, n'hésite pas à rejoindre la discussion sur notre Discord (Pas encore ;-;) ou à me contacter directement par [message privé](https://discord.com/users/918916801994309752)

---

## 🎓 License

Ce projet est sous la **[MIT License](LICENSE)**, ce qui signifie que tu peux librement l'utiliser, le modifier et le distribuer, tant que tu gardes la mention de l'auteur original.