# 🐾 Projet API Chats – React & Tailwind

Ce projet est une mini-application développée avec **React** et **Tailwind CSS**, permettant d'afficher des images et informations sur des chats aléatoires via une API publique. C'est un projet simple et visuel pour expérimenter les appels API (`fetch`) et la mise en page avec Tailwind.

## 🎯 Objectif du projet

- Consommer une API externe (`The Cat API`)
- Afficher dynamiquement une image de chat
- Recharger l’image sur clic
- Structurer un projet React moderne avec composants
- Styliser rapidement avec Tailwind CSS

## 🖼️ Aperçu

![Aperçu de l'application](./public/screenshot.png)
![Aperçu de l'application](./public/screenshot2.png)

## ⚙️ Stack technique

- ⚛️ **React**
- 🎨 **Tailwind CSS**
- 🌐 **The Cat API** — [https://thecatapi.com/](https://thecatapi.com/)

## 🔄 Fonctionnalités

- 🐱 **Affichage dynamique** des informations détaillées sur une race de chat à partir de l’API [The Cat API](https://thecatapi.com/)
- 📸 **Image de la race** affichée à partir d’un `reference_image_id`
- 🔄 **Chargement automatique** des données selon l’`id` de la race dans l’URL (grâce à React Router)
- 💬 **Description complète** de la race, son origine, son espérance de vie, son poids…
- 🌟 **Notation visuelle** (étoiles) des caractéristiques de la race : affection, intelligence, adaptabilité, etc.
- 🧠 **Tempérament** et niveau d’hypoallergénicité détaillés
- 🔗 Liens externes (CFA, VCA, Wikipedia…) affichés selon disponibilité
- ⚛️ Composants réutilisables : `Bouton`, `Spinner`, `Error`
- 🚦 **Gestion du chargement** (avec `Spinner`) et des erreurs (affichage d’un message si l’API échoue)
- 💅 **Responsive design** avec Tailwind CSS
- 🔁 **Comportement dynamique** basé sur les effets de `useEffect` et la récupération via `fetch`

## 🚀 Lancer le projet en local

```bash
# 1. Cloner le repo
git clone https://github.com/ines-taborin/Projet-API-Chats.git
cd Projet-API-Chats

# 2. Installer les dépendances
npm install

# 3. Lancer le projet
npm run dev
