# Homework 12.4

Подготовил сервера с помошью [Vagrantfile](https://github.com/Evgeniy-Nikolskiy/hw12.4/blob/main/Vagrantfile)  
Создал ключ ssh на все машины
Сгенерировал hosts.ini на основнании статьти
Запустил установку через kubespray командой: ansible-playbook -i inventory/cluster/hosts.ini --become --become-user=root cluster.yml  
Файл [host.ini](https://github.com/Evgeniy-Nikolskiy/hw12.4/blob/main/host.ini) . Пример взят на основе [статьи](https://rebrainme.com/blog/kubernetes/sozdanie-klastera-kubernetes-na-vps-s-pomoshhyu-kubespray/)

Не хватило памяти. Буду решать эту проблему в дальнейшем  
![1](https://raw.githubusercontent.com/Evgeniy-Nikolskiy/hw12.4/main/assets/1.jpg)