
# Лабораторна работа №4


В этой ветке представлены материалы лабораторной работы. Установка и настройка всего ПО обеспечена ansible, устанавливающим nginx на виртуальные машины web1 и web2,а также меняющим порт.Балансировка нагрузки происходит на сервере robin в режиме round-robin. Кастомные страницы помогают понять, на каком сервере вы находитесь.

### Для поднятия виртуальной машины используется:
> vagrant up
### Для запуска ansible-сценария используется:
> ansible-playbook nginx.yml

### Результат балансировки(представлены кастомные страницы веб-серверов):
<a href="https://ibb.co/YhqDY8j"><img src="https://i.ibb.co/zZ08jbf/1.png" alt="1" border="0"></a>


<a href="https://ibb.co/rx5Q3f0"><img src="https://i.ibb.co/c62ywX3/2.png" alt="2" border="0"></a>
