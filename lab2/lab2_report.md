University: ITMO University

Faculty: FICT

Course: Network programming

Year: 2022/2023

Group: K34202

Author: Molchanova Veronika Alexandrovna

Lab: Lab1

Date of create: 18.03.2023

Date of finished: xx.xx.2023


# Конфигурация voip в среде Сisco packet tracer

## Часть 1
1. В конфигурационном режиме изменено название маршрутизатора на CMERouter.

![image](https://user-images.githubusercontent.com/90505004/226175214-18b15f3e-2016-4da7-a955-bd453844a7a8.png)

2.Отключен синтаксис ввода слов от DNS серверов, используя команду `no ip domain-lookup `.

![image](https://user-images.githubusercontent.com/90505004/226175494-3730215a-adfb-4e7d-9444-d70a02218580.png)

3. Заданы пароли для защиты маршрутизатора как в удаленном режиме, так и в режиме консоли.

![image](https://user-images.githubusercontent.com/90505004/226175698-c88c7772-0f31-41ee-bc10-69411b640fa1.png)

4. Настроен интерфейс fa0/0 на маршрутизаторе CMERouter, задан ip адрес, маска сети, статус порта переведен в активный.

![image](https://user-images.githubusercontent.com/90505004/226175835-603e28e7-db15-4d19-9844-2e2ee0a1bce6.png)

5. Настрен DHCP сервера для передачи голоса и данных на маршрутизаторе

![image](https://user-images.githubusercontent.com/90505004/226176069-d7f71fa4-5ad2-42af-8657-52f8f1e4e262.png)

6. Настроены услуги телефонии Cisco CallManager Express на маршрутизаторе.

![image](https://user-images.githubusercontent.com/90505004/226176942-7807dd96-25b3-4ffe-b35d-36180969277a.png)

7. Создать VLAN порты на коммутаторе для взаимодействия коммутатора с маршрутизатором и подключить IP телефоны. Настроены IP-телефоны и соединены с коммутатором.

![image](https://user-images.githubusercontent.com/90505004/226177947-9b9d8509-6485-4c43-9761-30e56ca805ae.png)
![image](https://user-images.githubusercontent.com/90505004/226178101-d619cbf9-e5b1-4361-b0e9-3fca5aa33eae.png)

8. Проверены звонки между телефонами.

![image](https://user-images.githubusercontent.com/90505004/226178324-726ed0a8-3587-47ca-a83c-ef68956cdac8.png)

9. В результате собрана сеть.

![image](https://user-images.githubusercontent.com/90505004/226179049-c886639f-47cd-4e26-865b-e80ad5c6219d.png)


## Часть 2
