# Archite IA Académie – Ressources officielles

Bienvenue dans la communauté **Archite IA Académie**, l’espace où nous apprenons à développer, déployer et opérer des solutions d’intelligence artificielle de bout en bout.  
Ce dépôt GitHub sert de coffre-fort centralisé : toutes les ressources pédagogiques et techniques mises à votre disposition sont versionnées ici afin que vous puissiez les cloner et les étudier en local.

---

## Table des matières

1. [Objectifs du dépôt](#objectifs-du-dépôt)  
2. [Ressources incluses](#ressources-incluses)  
3. [Prérequis et configuration](#prérequis-et-configuration)  
4. [Clonage en lecture seule](#clonage-en-lecture-seule)  
5. [Arborescence du projet](#arborescence-du-projet)  
6. [Licence et conditions d’usage](#licence-et-conditions-dusage)  
7. [Support et communauté](#support-et-communauté)

---

## Objectifs du dépôt

- Centraliser **tout le matériel pédagogique** de la formation : code, infrastructure, workflows et cas clients.  
- Garantir un **accès simple** (une commande `git clone`) tout en protégeant l’intégrité du dépôt : vous disposez des droits _lecture seule_ ; aucune action de push n’est autorisée côté GitHub.  
- Faciliter la **reproductibilité** : chaque ressource est versionnée, étiquetée et accompagnée de son guide d’utilisation.

---

## Ressources incluses

| Dossier racine            | Contenu principal                                                           |Lien                                                              |
|---------------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------|
| `infra-ia/`               | Infrastructure IA (n8n,Ollama, Supabase, Markitdown, Baserow, Qdrant, Caddy)| [Lien d'accès](https://github.com/Architecte-IA-Academie/infra-ia-local/tree/main)                                                     |
| `workflows-n8n/`          | Scénarios d’automatisation au format n8n.                                   | Lien d'accès                                                     |
| `agents-ia/`              | Code source des agents IA avec d'autres frameworks (Pydantic,Langchain,...) | Lien d'accès                                                     |
| `projets-clients/`        | Études de cas anonymisées et solutions livrées.                             | Lien d'accès                                                     |

> Chaque ressource est versionnée sous forme de sous-répertoire Git ou de module indépendant pour vous permettre de les cloner ou d’en faire un `git sparse-checkout` au besoin.

---

## Prérequis et configuration

- **Git ≥ 2.37**  
- Accès internet au domaine `github.com`  
- Une machine Linux/macOS/WSL ; pour Windows natif, privilégiez Git Bash ou PowerShell ≥ 7.
