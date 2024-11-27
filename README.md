# Домашнее задание к занятию "`ELK`" - `Козырев Роман`


### Задание 1. Elasticsearch

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.


### Решение 1.

![image](https://github.com/user-attachments/assets/334f13cb-89ce-4241-96d3-3aaa53dc63ef)



### Задание 2. Kibana

Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.


### Решение 2

![image](https://github.com/user-attachments/assets/a67a4614-4105-40c2-bd65-2e44d6b50d58)



### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

### Решение 3

![image](https://github.com/user-attachments/assets/404e3182-4e09-4971-ba3e-a0cd1f1c9b69)


### Задание 4. Filebeat

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.


### Решение 4

![image](https://github.com/user-attachments/assets/4eaf7bbc-f505-4205-9432-63921e167847)

![image](https://github.com/user-attachments/assets/93cc88ec-29c6-4f19-b42f-c80703b8a899)



