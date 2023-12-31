#  Дипломная работа по профессии «Системный администратор»
[Terraform:](https://github.com/imp-85/diplom/tree/main/terraform)

Инициализируем систему - Проверяем конфигурацию - Запускаем применение
![terraform init](/pic/init-validate-apply.jpg "init-validate-apply")

Применяется
![terraform apply](/pic/apply-begin.jpg "apply")

Закончило применяться
![terraform apply-end](/pic/apply-end.jpg "apply-end")

Смотрим что получилось
![Инфраструктура](/pic/created-infrastructure.jpg "Yandex Cloud Infrastructure")

Виртуальные машины
![VM](/pic/vm-in-yc.jpg "Yandex Cloud VM's")

Снапшоты
![snapshots](/pic/snapshots.jpg "Yandex Cloud Snapshots")

[Ansible:](https://github.com/imp-85/diplom/tree/main/ansible)

Формируем файл HOSTS:(https://github.com/imp-85/diplom/blob/main/ansible/inventory/hosts.ini) для доступа к виртуальным машинам через bastion-host
![ansible-host](/pic/ansible-hosts.jpg "Ansible-Hosts")

Проверяем доступность хостов
![ansible-ping](/pic/ansible-ping.jpg "Ping")

Пробуем зайти на bastion-host
![bastion-host](/pic/enter-bhost.jpg "BH")

Пробуем заходить на остальные VM по SSH
![ssh](/pic/ssh-keys.jpg "ssh")

Запускаем плейбук настройки веб серверов
![servers-playbook](/pic/web-node-log-file.jpg "servers-playbook")

Проверяем nginx
![nginx](/pic/nginx-service.jpg "nginx")

Проверяем Node Exporter
![Node Exporter](/pic/node_exp.jpg "Node Exporter")

Log Exporter
![Log Exporter](/pic/prometheus-nginxlog.jpg "Log Exporter")

Используем CURL для проверки
![curl](/pic/curl.jpg "curl")

Ну и пробуем посмотреть всю эту "мазню" в браузере
![site](/pic/site.jpg "site")

Запускаем остальные плейбуки

Prometheus
![Prometheus](/pic/prometheus.jpg "Prometheus")

Elasticsearch
![Elasticsearch](/pic/elastic.jpg "Elasticsearch")

Grafana
![Grafana](/pic/grafana.jpg "Grafana")

Kibana
![Kibana](/pic/kibana.jpg "Kibana")

Результат
![grafana-1](/pic/graf1.jpg "grafana-1")
![grafana-2](/pic/graf2.jpg "grafana-2")
![filebeat-elas](/pic/filebeat-in-elast.jpg "filebeat-elas")
