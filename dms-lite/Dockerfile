FROM node:16-bullseye-slim

#RUN apt update && apt install -y node-sqlite3
COPY . .


RUN npm install 

#port in which App is running at Localhost:3000
EXPOSE 3000

# ENTRYPOINT [ "node", "app.js" ]
ENTRYPOINT ["npm", "start"]
