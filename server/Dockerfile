FROM node:18-alpine

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm install -g nodemon
RUN npm install
COPY . .
EXPOSE 5000
ENV TODO_APP_DATABASE_URI "mongodb+srv://laboratorctt:laboratorctt@ctt.yffcqmt.mongodb.net/?retryWrites=true&w=majority"
CMD ["npm", "start"]