# Лабараторная работа №3
### 1. Установка виртуальных машин и их запуск.

При выполнении первых двух лабараторных работ я и так использовал VirtualBox, так что мне понадобилось добавить только две дополнительные виртуальные машины. Ubuntu - основная вирутальная машина, UbuntuB и UbuntuC - дополнительные машины, созданные для сдачи лабараторной работы. <tb>
![image](https://github.com/user-attachments/assets/83b497a0-41a4-4647-85e2-70c11ca87a0e)

VirtualBox автоматически настраивает виртуальный адаптер для доступа в интернет. Доступ всех трех машин в интернет:<tb>
![image](https://github.com/user-attachments/assets/2d7edf84-edd6-497b-898a-430e0c747654) <tb><tb>

### 2. Создание, настройка виртаульных сетей. Подключение машин в вирт. сетям.

Создаю дополнителую вирутальную сеть, одна вирутальная сеть есть по умолчанию, она будет использоваться для UbuntuB. Также на данном этапе необходимо запоминить IPv4 адреса, они понадобятся для соеденения машин между собой. <tb>
![image](https://github.com/user-attachments/assets/ec9e4a5f-29d4-49ca-91c9-b4f7c87287e1)

![image](https://github.com/user-attachments/assets/64ac3f15-7eef-417e-a12c-3f764ecc596d) <tb><tb>

На Ubuntu подключаю Адаптер 2 и Адаптер 3 к виртуальным сетям 1 и 2 соответсвенно.
 ![image](https://github.com/user-attachments/assets/795f5ff8-4769-4870-a10e-97af5e7671a0)
 ![image](https://github.com/user-attachments/assets/eaaf1126-a4ef-4d8a-ae71-7f96e3b00fab)

На UbuntuB и UbuntuC использую адаптеры 1, так как подключение к интернету не обязательно. Использую подключение к  виртуальным сетям 1 и 2 для UbuntuB и UbuntuC соответственно.
![image](https://github.com/user-attachments/assets/3eb636ab-3db6-4056-ae5b-bab58b8237d5)
![image](https://github.com/user-attachments/assets/e4fa209b-2a3c-4759-abd1-89f6da4529f8) <tb><tb>

### 3. Проверка результатов
Запускаю Ubuntu и UbuntuB, проверяю их связь между собой. Для этого использую IPv4 адрес, который записал ранее (см. п. 2).
![image](https://github.com/user-attachments/assets/2ef38fb8-ed8e-49d0-93fc-fdc133f26a13) <tb><tb>

Запускаю Ubuntu и UbuntuC, проверяю их связь между собой. Для этого использую IPv4 адрес, который записал ранее (см. п. 2).
![image](https://github.com/user-attachments/assets/ed22198d-312c-41c0-8537-965cd0befeb6)

Запускаю UbuntuB и UbuntuC, ее, очевидно, нет, так как машины подключены к разным сетям.
![image](https://github.com/user-attachments/assets/6d4730b3-23be-4aa9-9b43-466e17710a67)







