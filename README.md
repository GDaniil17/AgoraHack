# LPrediction
В этом репозитории находится модуль ML, API и Frontend
## ML
-------------
## API
API работает с Docker контейнерами, в которых прописаны зависимости и особенности сборки бэкенд части нашего сервиса. API представляет методы для получения списка товаров, результата поиска эталонов и эталонных характеристик для различных товаров.
API написании на языке Python и являются кроссплатформенными, то есть могут быть запущены в различных окружениям. 
Для сборки достаточно выполнить три команды Docker:
### docker pull exppi/dockerhub:agora-hack-windows
### >docker run -i -t -p 0.0.0.0:8000:8000 -d exppi/dockerhub:agora-hack-windows
И перейти по ссылке: http://localhost:8000/doc

![image](https://user-images.githubusercontent.com/32881349/185777289-a7e22cbf-a786-455c-a787-b5999457555a.png)

http://51.250.29.0/


