FROM node:14-alpine

WORKDIR /appb

COPY package*.json ./
RUN npm install
COPY ./ ./

# ARG image_name
# ENV IMAGE=${image_name}
# ENV MYENV=${MYENV:-4000}

#RUN npm run build
EXPOSE 3001
CMD [ "npm", "start" ]
