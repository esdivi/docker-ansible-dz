# Базовый образ
FROM nginx

# Копируем файл конфигурации Nginx
COPY ./default.conf /etc/nginx/conf.d/default.conf

# Копируем index.html в папку html
COPY ./index.html /usr/share/nginx/html