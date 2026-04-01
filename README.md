# 🎓 English Coach IA — n8n + Mistral

Application de coaching en anglais propulsée par l'IA Mistral. Deux modes : conversation guidée et shadowing audio pour l'amélioration de la prononciation.

## 🎯 Fonctionnalités

- **Mode Conversation** : dialogue IA avec corrections grammaticales et suggestions
- **Mode Shadowing** : exercices de répétition audio pour la prononciation

## 📋 Workflows (4)

| Workflow | Description |
|----------|-------------|
| English Coach - Mistral Agent | Agent conversationnel (backend) |
| English Coach - Serve HTML | Interface web principale |
| English Coach - Serve HTML Shadowing | Interface mode shadowing |
| English Coach - Shadowing Agent | Agent IA pour le shadowing |

## 🛠️ Stack

- **Orchestration** : n8n self-hosted
- **LLM** : Mistral AI (Mistral Large)
- **Interface** : HTML/CSS/JS servi directement par n8n
- **Accès** : Webhook HTTP

## 🚀 Import dans n8n

1. Importer les 4 JSON du dossier `workflows/`
2. Configurer le credential Mistral AI
3. Activer tous les workflows
4. Accéder à l'interface via l'URL webhook du workflow "Serve HTML"
