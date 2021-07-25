1. установить minukube, helm >v3
   a. hosts добавить домен arch.homework ссылается на minikube ip
2. в консоли выполнить minikube start 
3. подклчюить модуль ингресс minikube addons enable ingress
   
3.1 перейти в каталог cd ./homework2/
4. выполнить деплой postgresql  helm install pg bitnami/postgresql  -f ./otus_values.yaml
5. сам сервис helm upgrade --install  dgrunskiy -f values.yaml .       
6. postman коллекция запросов User Service.postman_collection.json.
