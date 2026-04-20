# 🤖 AI-Powered SysAdmin Assistant (n8n + Groq + SSH)

Un bot Telegram intelligent capable de surveiller et de diagnostiquer une infrastructure Windows via SSH, en utilisant l'IA pour l'analyse des données en temps réel.

## 🚀 Fonctionnalités
- **Monitoring Matériel :** Vérification de l'espace disque (C:) et de la RAM via PowerShell.
- **Diagnostic Réseau :** Analyse des connexions actives (`netstat`) et test de connectivité (`ping`).
- **Intelligence Artificielle :** Intégration de **Groq (Llama 3)** pour transformer des logs techniques bruts en conseils actionnables.
- **Routage Intelligent :** Capacité de différencier les commandes système des questions de chat générales.
- **Sécurité :** Accès sécurisé via SSH et interface Telegram cryptée.

## 🛠 Stack Technique
- **Orchestration :** [n8n](https://n8n.io/)
- **LLM :** Groq Cloud (Llama 3 70B)
- **Communication :** Telegram Bot API
- **Système :** Windows PowerShell via SSH

## 📸 Aperçu du Workflow
![Workflow n8n](./path-to-your-image/screenshot-n8n.png)

## ⚙️ Configuration
1. **Importation :** Importer le fichier `.json` fourni dans votre instance n8n.
2. **Variables d'environnement :**
   - `TELEGRAM_BOT_TOKEN`
   - `SSH_HOST`, `SSH_USER`, `SSH_PASSWORD`
   - `GROQ_API_KEY`
3. **Prompt Système :** Le bot est configuré pour répondre en Français/Darja avec un ton professionnel et amical.

## 📄 Licence
Ce projet est sous licence MIT. Libre à vous de l'utiliser et de l'améliorer !

<img width="1562" height="672" alt="Screenshot 2026-04-20 163626" src="https://github.com/user-attachments/assets/b2da40dc-cbe8-4d36-be3f-9afd0d6649f0" />
