# Utilise l'image Node.js
FROM node:14

# Définir le répertoire de travail
WORKDIR /app

# Copier les fichiers et installer les dépendances
COPY package*.json ./
RUN npm install

# Copier le reste du projet
COPY . .

# Exposer le port 5000
EXPOSE 5000

# Démarrer l'application
CMD ["npm", "start"]
