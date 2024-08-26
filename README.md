# Implement-Docker-compose
Voici un résumé des étapes pour créer un conteneur Docker `httpd` à l'aide de Docker Compose, de manière générale et simple :

### Étape 1 : Installer Docker Compose
1. **Télécharger Docker Compose** :
   ```bash
   sudo curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
   ```
2. **Rendre le fichier exécutable** :
   ```bash
   sudo chmod +x /usr/local/bin/docker-compose
   ```

### Étape 2 : Créer le fichier Docker Compose
1. **Créer un répertoire pour le fichier Compose** :
   ```bash
   mkdir -p /opt/docker/
   cd /opt/docker/
   ```
2. **Créer un fichier `docker-compose.yml`** 

### Étape 3 : Démarrer le conteneur
1. **Exécuter Docker Compose pour démarrer le conteneur** :
   ```bash
   sudo docker-compose up -d
   ```

### Étape 4 : Vérifier que le conteneur est en cours d'exécution
1. **Lister les conteneurs en cours d'exécution** :
   ```bash
   sudo docker ps
   ```

Ces étapes vous guideront pour créer et démarrer un conteneur Docker `httpd` sur n'importe quelle machine où Docker et Docker Compose sont installés.
