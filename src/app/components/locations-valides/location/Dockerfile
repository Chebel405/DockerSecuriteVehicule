FROM mongo

# Définition du workdir
WORKDIR /app/component/

RUN npm install

COPY locations.component.ts / app/

# Exposition du port 8083
EXPOSE 8083

# Démarrage du serveur
CMD ["npm", "start"]



