# Сборка образа
docker build . --tag=my_nginx_project

# Запуск образа
docker run -d -p 80:80 my_nginx_project