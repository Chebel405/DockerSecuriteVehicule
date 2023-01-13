From mongo 

# Définition du workdir
WORKDIR /app /component/

RUN npm install

COPY vehicule.component.ts / app/

# Exposition du port 8084
EXPOSE 8084

# Démarrage du serveur
CMD ["npm", "start"]


