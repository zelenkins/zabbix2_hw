# Домашнее задание к занятию "Zabbix 2" - Зеленкин С.С.
 
### Задание 1
Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.

### Решение 1

![Скриншот-0](https://github.com/zelenkins/zabbix2_hw/blob/main/img/1template.png)
![Скриншот-1](https://github.com/zelenkins/zabbix2_hw/blob/main/img/1items.png)

---

### Задание 2 - 3

Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.
Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.

Прикрепите в файл README.md скриншот страницы хостов, где будут видны привязки шаблонов с названиями «Задание 2-3». Хосты должны иметь зелёный статус подключения

### Решение 2 - 3

Использовал те же хосты, что были созданы в задании Zabbix 1. Не переименовывал.

Хосты с Linux by Zabbix Agent
![Скриншот-2](https://github.com/zelenkins/zabbix2_hw/blob/main/img/2hosts_lza.png)
![Скриншот-3](https://github.com/zelenkins/zabbix2_hw/blob/main/img/3hosts_lza_la.png)

Хосты с созданным темплейтом
![Скриншот-4](https://github.com/zelenkins/zabbix2_hw/blob/main/img/4hosts_zt.png)
![Скриншот-5](https://github.com/zelenkins/zabbix2_hw/blob/main/img/5hosts_zt_la.png)

Zabbix не разрешает одному хосту иметь два итема с одинаковым ключом, поэтому привязать два шаблона невозможно. В моем случае это, например, system.cpu.util.

---

### Задание 4

Создайте свой кастомный дашборд.

### Решение 4

![Скриншот-6](https://github.com/zelenkins/zabbix2_hw/blob/main/img/6dashboard.png)