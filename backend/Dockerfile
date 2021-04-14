FROM node:14-alpine
WORKDIR /appb
COPY package*.json ./
RUN npm install
COPY ./ ./
#RUN npm run build
#EXPOSE 3001
CMD [ "npm", "start" ]
