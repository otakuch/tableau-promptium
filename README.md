# PROMPTIUM

**Tableau périodique du prompt engineering**

Les 65 éléments essentiels du prompting organisés en un tableau périodique interactif.

![PROMPTIUM Preview](preview.png)

## Description

Le prompt engineering n'est pas une simple rédaction d'instructions, mais un système structuré où chaque élément joue un rôle précis. Les 65 éléments essentiels du prompting sont organisés en 8 familles : les éléments de contexte définissent le cadre, les opérateurs déterminent l'action, les contraintes formatent la sortie, le raisonnement guide la réflexion, la gouvernance assure l'éthique, et les frameworks offrent des structures prêtes à l'emploi.

## Les 8 Familles d'Éléments

| Famille | Couleur | Éléments | Description |
|---------|---------|----------|-------------|
| **Contexte** | Bleu | 1-8 | Les fondations du prompt (Rôle, Public, Contexte, Ton...) |
| **Opérateurs** | Orange | 9-18 | Les actions à effectuer (Synthèse, Extraction, Critique...) |
| **Contraintes** | Jaune | 19-28 | Format et limites de sortie (JSON, Markdown, Limite...) |
| **Raisonnement** | Vert | 29-36 | Techniques avancées (Chain of Thought, Few-Shot...) |
| **Gouvernance** | Rouge | 37-44 | Éthique et conformité (Sources, Transparence, Audit...) |
| **Sécurité** | Violet | 45-50 | Protection et défense (Anonymisation, Sandbox...) |
| **Multimodal** | Rose | 51-60 | Images et vidéos (Ratio, Lumière, Style Art...) |
| **Frameworks** | Cyan | 61-65 | Structures prêtes à l'emploi (RTF, TAG, BAB, CARE, RISE) |

## Les 5 Frameworks

| Framework | Structure | Cas d'usage |
|-----------|-----------|-------------|
| **RTF** | Role → Task → Format | Contenu rapide et livrables |
| **TAG** | Task → Action → Goal | Améliorer des métriques mesurables |
| **BAB** | Before → After → Bridge | Résoudre un problème, pitcher un changement |
| **CARE** | Context → Action → Result → Example | Plan adapté à votre situation |
| **RISE** | Role → Input → Steps → Outcome | Analyse avec données réelles |

## Fonctionnalités

- Tableau périodique interactif avec 60 éléments
- Mode clair / Mode sombre
- Interface bilingue (Français / English)
- Filtrage par famille d'éléments
- Modal détaillé pour chaque élément avec template copiable
- Exemple d'assemblage de prompt
- Design responsive

## Installation

```bash
# Cloner le repository
git clone https://github.com/votre-username/promptium.git

# Accéder au dossier
cd promptium

# Installer les dépendances
npm install

# Lancer en développement
npm run dev
```

## Technologies

- React 18
- Vite
- CSS-in-JS (inline styles)
- Google Fonts (Inter, JetBrains Mono)

## Structure du Projet

```
promptium/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   └── Promptium.jsx
│   ├── App.jsx
│   └── main.jsx
├── package.json
├── vite.config.js
└── README.md
```

## Utilisation

1. **Parcourir le tableau** : Survolez les éléments pour les mettre en évidence
2. **Filtrer par famille** : Cliquez sur les boutons de catégorie en haut
3. **Voir les détails** : Cliquez sur un élément pour ouvrir sa fiche
4. **Copier un template** : Utilisez le bouton "Copier" dans la fiche d'élément
5. **Changer de thème** : Basculez entre mode clair et sombre
6. **Changer de langue** : Basculez entre FR et EN

## Exemple d'Assemblage

```
[Ro] Agis en tant qu'analyste senior.
[Ob] L'objectif est de produire une synthèse exécutive.
[Sy] Résume les points clés du document ci-joint.
[CoT] Réfléchis étape par étape.
[Li] Maximum 200 mots.
[Ha] Si une information est incertaine, indique-le.
```

## Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou une pull request.

## Auteur

**Naully Nicolas** - Version 1.0 - Janvier 2026

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.
