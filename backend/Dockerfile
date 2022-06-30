FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV mongo_user_name=admin
ENV mongo_pass=mypass

EXPOSE 80

CMD ["npm", "start"]