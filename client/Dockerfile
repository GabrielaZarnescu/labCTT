FROM node:18-alpine

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
ENV REACT_APP_BACKEND_URL http://localhost:5000
CMD ["npm", "start"]