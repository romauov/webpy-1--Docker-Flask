## Домашнее задание к лекции 2 «Docker», Flask API контейнер
#### студент: Сергей Романов

#### группа: WebPY-1
____
команда для создания образа
```
docker build -t flask_image .
```

команда для запуска контейнера
```
docker run -p 8080:8080 --name web_flask --rm flask_image
```
