# 🏭 Équipe Industrielle Claude Code

> Système de développement industriel avec 12 agents IA spécialisés, optimisé pour Windows avec PowerShell 7.x

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PowerShell](https://img.shields.io/badge/PowerShell-7.x+-blue.svg)](https://github.com/PowerShell/PowerShell)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Compatible-green.svg)](https://docs.anthropic.com/claude-code)
[![Windows](https://img.shields.io/badge/Windows-10%2F11-blue.svg)](https://www.microsoft.com/windows)

## 🎯 Vue d'Ensemble

**Équipe Industrielle Claude Code** est un système révolutionnaire qui coordonne **12 agents IA spécialisés** pour automatiser et industrialiser le développement logiciel. Optimisé pour Windows avec PowerShell 7.x, WSL2, et Task Scheduler, il transforme votre processus de développement en machine industrielle high-performance.

### ✨ Caractéristiques Principales

- 🎯 **12 Agents Spécialisés** : Orchestrateur, Product Owner, Architecte, Tech Lead, UX/UI, Frontend/Backend, DevOps, QA, Data Engineer, DBA
- 🪟 **Optimisation Windows Native** : PowerShell 7.x, WSL2, Task Scheduler, Performance Monitor
- 🔄 **Workflows Automatisés** : BUILD mode (nouveaux projets) et RUN mode (optimisation)
- 📊 **Monitoring Temps Réel** : Dashboard, alertes intelligentes, métriques de performance
- 💾 **Sauvegarde Enterprise** : Points de récupération automatiques, récupération intelligente
- 🎛️ **Interface Utilisateur** : Scripts batch conviviaux, commandes rapides
- 📚 **Documentation Vivante** : Auto-générée, synchronisée, searchable

## 🚀 Installation Rapide

```powershell
# 1. Cloner le repository
git clone https://github.com/kbekouchi/equipe-industrielle-claude-code.git
cd equipe-industrielle-claude-code

# 2. Installation automatique (Administrateur requis)
.\setup\installation-complete.ps1

# 3. Premier lancement
.\demarrage-rapide.bat

# 4. Authentification Claude Code
claude auth login

# 5. Premier projet test
.\workflows\orchestration-projet.ps1 -NomProjet "test" -TypeProjet "web-app" -Complexite "simple" -Mode "build"
```

## 👥 Les 12 Agents Spécialisés

| Agent | Rôle | Responsabilités Principales |
|-------|------|---------------------------|
| 🎯 **Orchestrateur** | Coordination générale | Planification, priorisation, handoffs |
| 📋 **Product Owner** | Vision produit | Requirements, roadmap, stakeholders |
| 🏗️ **Architecte Platform** | Architecture technique | Design patterns, scalabilité, ADRs |
| ⚡ **Tech Lead** | Excellence technique | Standards, mentoring, code review |
| 🎨 **Lead UX** | Expérience utilisateur | Research, parcours, accessibilité |
| 🎨 **Lead UI** | Interface utilisateur | Design system, composants, assets |
| ⚛️ **Lead Frontend** | Développement frontend | Apps, performance, tests UI |
| 🔧 **Lead Backend** | Développement backend | APIs, services, intégrations |
| 🚀 **DevOps Platform** | Infrastructure & CI/CD | Automation, monitoring, déploiements |
| 🧪 **QA Industrial** | Qualité & tests | Strategy, automation, quality gates |
| 📊 **Data Engineer** | Données & analytics | Pipelines, BI, insights |
| 🗄️ **DBA Industrial** | Base de données | Design, performance, sécurité |

## 🔄 Workflows Principaux

### BUILD Mode - Nouveaux Projets
```
Product Owner → Vision & Requirements
     ↓
Architecte → Fondations Techniques
     ↓
UX/UI → Design & Prototypes
     ↓
Frontend + Backend → Développement (parallèle)
     ↓
DevOps → Platform & Déploiement
     ↓
QA → Tests & Validation
     ↓
Data + DBA → Analytics & Optimisation
```

### RUN Mode - Optimisation Continue
```
Data Engineer → Analytics & Insights
     ↓
UX → Analyse Comportement Utilisateur
     ↓
Tech Lead → Analyse Performance
     ↓
DevOps → Optimisation Infrastructure
     ↓
Frontend/Backend → Optimisation Code
     ↓
QA → Validation Qualité
```

## 📁 Structure du Projet

```
equipe-industrielle-claude-code/
├── 📁 agents/                     # Définitions des 12 agents (.md)
├── 📁 workflows/
│   ├── lifecycle/                 # Scripts BUILD/RUN
│   ├── management/                # Gestion équipe
│   ├── monitoring/                # Surveillance temps réel
│   └── utilities/                 # Utilitaires et outils
├── 📁 setup/                      # Scripts d'installation
├── 📁 templates/                  # Templates projets
├── 📁 docs/                       # Documentation complète
├── 📁 examples/                   # Projets d'exemple
├── 🔨 demarrage-rapide.bat        # Interface utilisateur principale
├── 📋 brief-systeme.md            # Contexte pour Claude Code
└── 📖 README.md                   # Ce fichier
```

## 🛠️ Utilisation Quotidienne

### Interface Conviviale
```batch
# Lancer l'interface principale
.\demarrage-rapide.bat

# Options disponibles :
# 1. Créer nouveau projet
# 2. Vérifier statut équipe
# 3. Dashboard monitoring
# 4. Sauvegarde projet
# 5. Monitoring système
```

### Commandes PowerShell Directes
```powershell
# Gestion équipe
.\workflows\management\gestion-equipe.ps1 verification-sante
.\workflows\management\gestion-equipe.ps1 liste-projets

# Orchestration projet
.\workflows\orchestration-projet.ps1 -NomProjet "app-mobile" -TypeProjet "mobile" -Complexite "moyen" -Mode "complet"

# Monitoring temps réel
.\workflows\monitoring\dashboard-temps-reel.ps1 -NomProjet "MonProjet"

# Sauvegarde enterprise
.\workflows\utilities\sauvegarde-enterprise.ps1 -TypeSauvegarde "incrementale"
```

### Commandes Rapides
```batch
# Statut rapide
.\commandes-agents.bat statut MonProjet

# Vérifier bloqueurs
.\commandes-agents.bat bloqueurs MonProjet

# Moral équipe
.\commandes-agents.bat humeur MonProjet
```

## 📊 Métriques de Performance

### Gains Attendus
- **⚡ +400% Vélocité** développement
- **🔧 -60% Bugs** en production
- **⏱️ -50% Time-to-Market**
- **💰 -35% Coûts** opérationnels
- **📈 +200% Qualité** livrée

### Métriques Techniques
- Temps réponse agents : **<2 secondes**
- Disponibilité système : **>99.9%**
- Précision handoffs : **>95%**
- Succès quality gates : **>90%**
- Automatisation : **>90% processus**

## 🔧 Prérequis Système

### Obligatoire
- **Windows 10/11** (Pro ou Enterprise recommandé)
- **PowerShell 7.x+**
- **Git** + Git Credential Manager
- **Node.js 18+** + npm
- **Claude Code CLI**
- **16GB+ RAM** (recommandé)

### Optionnel mais Recommandé
- **WSL2** + Ubuntu (compatibilité cross-platform)
- **Docker Desktop** (containerisation)
- **Visual Studio Code** + Extension Claude Code
- **Windows Terminal** (expérience développeur améliorée)

## 📚 Documentation

- 📖 **[Guide Utilisateur Complet](docs/guide-utilisateur.md)**
- 📋 **[Référence Rapide](docs/reference-rapide.md)**
- 🗺️ **[Roadmap Implémentation](docs/roadmap-implementation.md)**
- 🆘 **[Guide Dépannage](docs/troubleshooting.md)**
- 🎯 **[Bonnes Pratiques](docs/best-practices.md)**

## 🤝 Intégration Claude Code

### Utiliser avec Claude Code
```bash
# Briefer Claude Code avec le contexte complet
claude-code --instructions-file agents/orchestrateur.md --include "brief-systeme.md" --conversation-id "equipe-main" "Nous démarrons une session avec l'équipe industrielle"

# Orchestre un nouveau projet
claude-code --instructions-file agents/orchestrateur.md --conversation-id "projet-xyz" "Orchestre la création du projet XYZ selon les workflows définis"

# Monitoring projet existant
claude-code --instructions-file agents/orchestrateur.md --include "projets/MonProjet/contexte.md" "Analyse le statut du projet et coordonne les actions nécessaires"
```

## 🚨 Support & Dépannage

### Problèmes Fréquents
```powershell
# Claude Code ne fonctionne pas
npm uninstall -g @anthropic-ai/claude-code
npm install -g @anthropic-ai/claude-code
claude auth login

# Scripts PowerShell bloqués
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

# Problème droits
# → Lancer PowerShell en Administrateur
```

### Logs & Diagnostics
- **Logs Windows** : `eventvwr.exe` → Application → "EquipeIndustrielle"
- **Validation système** : `.\workflows\management\gestion-equipe.ps1 verification-sante`
- **Monitoring perf** : `perfmon.exe`

## 🎯 Exemples d'Utilisation

### Créer App E-commerce
```powershell
.\workflows\orchestration-projet.ps1 `
  -NomProjet "ecommerce-b2b" `
  -TypeProjet "web-app" `
  -Complexite "complexe" `
  -Mode "complet"
```

### Optimiser App Existante
```powershell
.\workflows\orchestration-projet.ps1 `
  -NomProjet "app-existante" `
  -TypeProjet "optimisation" `
  -Complexite "moyen" `
  -Mode "run"
```

## 🔄 Roadmap

### Version 1.0 (Actuelle)
- ✅ 12 agents spécialisés
- ✅ Workflows BUILD/RUN
- ✅ Monitoring temps réel
- ✅ Sauvegarde enterprise

### Version 1.1 (Q1 2025)
- 🔄 Intégration Teams/Slack
- 🔄 Dashboard web
- 🔄 Analytics avancées
- 🔄 Templates industrie

### Version 2.0 (Q2 2025)
- 🔄 Multi-équipes support
- 🔄 Cloud deployment
- 🔄 AI-powered insights
- 🔄 Mobile app

## 🤝 Contribution

Les contributions sont les bienvenues ! Voir [CONTRIBUTING.md](CONTRIBUTING.md) pour les guidelines.

### Comment Contribuer
1. Fork le repository
2. Créer une branche feature (`git checkout -b feature/nouvelle-fonctionnalite`)
3. Commit les changements (`git commit -am 'Ajoute nouvelle fonctionnalité'`)
4. Push la branche (`git push origin feature/nouvelle-fonctionnalite`)
5. Créer une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir [LICENSE](LICENSE) pour plus de détails.

## 🙏 Remerciements

- **Anthropic** pour Claude Code
- **Microsoft** pour PowerShell et l'écosystème Windows
- **Communauté Open Source** pour les outils et bibliothèques

## 📞 Contact & Support

- 🐛 **Issues** : [GitHub Issues](https://github.com/kbekouchi/equipe-industrielle-claude-code/issues)
- 💬 **Discussions** : [GitHub Discussions](https://github.com/kbekouchi/equipe-industrielle-claude-code/discussions)
- 📧 **Email** : [Votre email]

---

**🚀 Transformez votre développement en machine industrielle avec l'Équipe Industrielle Claude Code !**

*Développé avec ❤️ en France 🇫🇷*
