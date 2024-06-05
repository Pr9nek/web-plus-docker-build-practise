FROM node:16-alpine

# Задаем рабочую директорию
WORKDIR /home/ilovedocker/app

# Копируем скрипт в рабочую директорию
COPY hello.sh .

# Устанавливаем скрипт в качестве команды запуска
CMD ["sh", "hello.sh"]