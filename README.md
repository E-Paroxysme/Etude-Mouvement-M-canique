# 🔬 Étude de Mouvements Mécaniques

Application web interactive pour l'enseignement de la mécanique en Sciences de l'Ingénieur au lycée.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Licence](https://img.shields.io/badge/licence-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📋 Description

Cette application permet aux élèves de **visualiser et expérimenter** les différents types de mouvements mécaniques de manière interactive. Elle couvre les mouvements rectilignes et circulaires, uniformes et uniformément accélérés.

## ✨ Fonctionnalités

### 🎯 4 Simulations Complètes

1. **MRU - Mouvement Rectiligne Uniforme** (Chariot sur rail)
   - Vitesse constante
   - Vecteur vitesse visible
   - Équation : `x(t) = x₀ + v₀ × t`

2. **MRUA - Mouvement Rectiligne Uniformément Accéléré** (Voiture)
   - Accélération constante
   - Vecteurs vitesse et accélération
   - Équations : `x(t) = x₀ + v₀ × t + ½ × a × t²` et `v(t) = v₀ + a × t`

3. **MCU - Mouvement Circulaire Uniforme** (Disque vinyle)
   - Vitesse angulaire constante
   - Vecteur vitesse tangentielle
   - Équation : `θ(t) = θ₀ + ω₀ × t`

4. **MCUA - Mouvement Circulaire Uniformément Accéléré** (Roue)
   - Accélération angulaire constante
   - Vecteurs vitesse et accélération tangentielles
   - Équations : `θ(t) = θ₀ + ω₀ × t + ½ × α × t²` et `ω(t) = ω₀ + α × t`

### 📊 Visualisation en Temps Réel

- **Animations fluides** des objets en mouvement
- **Vecteurs cinématiques** (vitesse et accélération)
- **Graphiques dynamiques** qui se tracent pendant la simulation :
  - Position/Angle en fonction du temps
  - Vitesse en fonction du temps
  - Accélération en fonction du temps
- **Affichage numérique** des valeurs instantanées

### ⚙️ Contrôles Interactifs

- Réglage de la **vitesse initiale** avec slider
- Réglage de l'**accélération** avec slider
- Boutons **Démarrer / Pause / Réinitialiser**
- Interface intuitive par onglets

### 📥 Export de Données

Chaque simulation permet d'exporter :
- **Fichier CSV** : toutes les données (temps, position, vitesse, accélération)
- **Image PNG** : capture des 3 graphiques avec titre et labels

Parfait pour les comptes-rendus et l'analyse de données !

## 🚀 Utilisation

### Installation

1. Cloner le dépôt :
```bash
git clone https://github.com/E-Paroxysme/Etude-Mouvement-M-canique.git
cd Etude-Mouvement-M-canique
```

2. Ouvrir le fichier `Etude_Mouvement.html` dans un navigateur web

**Aucune installation supplémentaire requise !** L'application fonctionne 100% hors ligne.

### Guide d'utilisation

1. **Sélectionner** un type de mouvement via les onglets
2. **Régler** les paramètres (vitesse, accélération) avec les sliders
3. **Lancer** la simulation avec le bouton "▶ Démarrer"
4. **Observer** l'animation et les graphiques qui se tracent en temps réel
5. **Mettre en pause** pour analyser les valeurs à un instant précis
6. **Exporter** les données et graphiques si besoin
7. **Réinitialiser** pour recommencer

## 💡 Objectifs Pédagogiques

- Comprendre les **équations du mouvement**
- Visualiser la **relation entre position, vitesse et accélération**
- Différencier **mouvements uniformes et accélérés**
- Établir le **lien entre grandeurs linéaires et angulaires**
- **Expérimenter** et analyser des données réelles

## 🎓 Public Cible

- **Élèves** : Lycée - Sciences de l'Ingénieur
- **Enseignants** : Support de cours interactif
- **Niveau** : Première / Terminale

## 🛠️ Technologies Utilisées

- **HTML5** : Structure et Canvas pour les animations
- **CSS3** : Interface moderne et responsive
- **JavaScript Vanilla** : Logique de simulation et graphiques

**Aucune dépendance externe** - Fonctionne sur réseau restreint

## 📱 Compatibilité

- ✅ Chrome / Edge
- ✅ Firefox
- ✅ Safari
- ✅ Tous navigateurs modernes supportant HTML5 Canvas

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 👤 Auteur

**Elie Pacheco**

---

## 🤝 Contributions

Les contributions sont les bienvenues ! N'hésitez pas à :
- Reporter des bugs
- Proposer de nouvelles fonctionnalités
- Améliorer la documentation

## 📝 Changelog

### Version 1.0.0 (2025-11-28)
- ✨ Simulation complète des 4 types de mouvements
- 📊 Graphiques dynamiques en temps réel
- 🎨 Vecteurs vitesse et accélération
- 📥 Export CSV et PNG
- 🎯 Interface intuitive par onglets
- 🔄 Affichage progressif des courbes
- ⏱️ Animations ralenties pour meilleure observation

---

<div align="center">
  Développé avec ❤️ pour l'enseignement de la mécanique
</div>
