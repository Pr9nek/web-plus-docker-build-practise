FROM node:16-alpine

# Задаем рабочую директорию
WORKDIR /home/ilovedocker/app

COPY package*.json ./

RUN npm i

COPY src .

# Устанавливаем скрипт в качестве команды запуска
EXPOSE 3032
ENTRYPOINT ["node", "main.js"]