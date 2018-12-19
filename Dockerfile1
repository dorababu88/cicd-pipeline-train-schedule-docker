FROM node : carbon
WORKDIR /usr/src/app
COPY package*.json ./
RUN spm install 
COPY . . 
EXPOSE 8080
CMD [ "npm", "start"]
