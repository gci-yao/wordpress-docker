# 🚀 Déploiement de WordPress avec Docker Compose by Charles

## 🎯 Objectif

Déployer un site **WordPress** avec une base de données **MySQL** à l'aide de Docker compose

---

## 🧰 Prérequis

Avant de commencer, vous devez avoir installé :

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/) (inclus dans Docker Desktop)
- (Optionnel) [Git](https://git-scm.com/) pour cloner le dépôt

---

## 🏗️ Étapes
1. Créer un dossier # mkdir wordpress-docker
2. Acceder au dossier # cd wordpress-docker
3. Créer le fichier docker-compose.yaml # touch docker-compose.yaml
4. Lancer les conteneurs # docker compose up -d 
5. Accéder à WordPress # Allez sur docker desktop
6. Clickez sur *containers* et lancer wordpress-app via le port 8081 ou 8080 apparu

                                ***Ou avec git**

1. git clone https://github.com/votre-utilisateur/wordpress-docker.git
2. cd wordpress-docker
3. Créer le fichier docker-compose.yaml # touch docker-compose.yaml
4. Lancer les conteneurs # docker compose up -d 
5. Accéder à WordPress #voir docker desktop
6. Clickez sur *containers* et lancer wordpress-app via le port 8081 ou 8080 apparu

## 📁 Structure du projet

wordpress-docker/
├── docker-compose.yaml
└── README.md