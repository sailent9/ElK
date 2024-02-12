# Домашнее задание к занятию «ELK» Тихун Вадим


### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.


### Решение 1

![image](https://github.com/sailent9/ElK/assets/130309754/e0943f7c-c0e2-40e6-880a-588a69c58b11)











---




### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

### Решение 2
![image](https://github.com/sailent9/ElK/assets/130309754/2a1cf819-ea1d-4f13-bc24-888fca62e795)










---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

### Решение 3

![Задание-3](https://github.com/sailent9/ElK/assets/130309754/6984c061-871a-492c-9bb4-debc8ae9bcd7)










---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*


### Решение 4
![Задание-4 1](https://github.com/sailent9/ElK/assets/130309754/6d135896-32ac-438f-aa94-2e1432a83936)




git commit -m "comment"
