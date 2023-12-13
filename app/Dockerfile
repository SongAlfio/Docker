FROM node:10-alpine   #specifica l'immagine di base da utilizzare 
WORKDIR /app   #imposta i directory di lavoro all'interno del container 
COPY . .
RUN yarn install --production
CMD ["node", "/app/src/index.js"]
