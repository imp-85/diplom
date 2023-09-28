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

Формируем файл HOST.INI:(https://github.com/imp-85/diplom/blob/main/ansible/inventory/hosts.ini) для доступа к виртуальным машинам через bastion-host
![ansible-host](/pic/ansible-hosts.jpg "Ansible-Hosts")

Проверяем доступность хостов
![ansible-ping](/pic/ansible-ping.jpg "Ping")

Пробуем зайти на bastion-host
![bastion-host](/pic/enter-bhost.jpg "BH")

Пробуем заходить на остальные VM по SSH
![ssh](/pic/ssh-keys.jpg "ssh")
