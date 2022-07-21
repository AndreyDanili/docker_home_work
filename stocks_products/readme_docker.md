## Сборка образа
docker build . --tag=my_stock_products

## Запуск образа и создание миграций
docker run -d -p 8000:8000 my_stock_products