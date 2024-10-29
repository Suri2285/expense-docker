FROM node:20 
EXPOSE 8080
ENV DB_HOST="localhost"
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install
CMD ["node", "index.js"]