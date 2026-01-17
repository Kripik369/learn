##Задание1
<img width="1908" height="1121" alt="image" src="https://github.com/user-attachments/assets/90aec450-a5f4-417b-8639-063f92c9d857" />
докер и докер компоуз установленны и образ скачен
<img width="1916" height="718" alt="image" src="https://github.com/user-attachments/assets/146b412d-af23-4885-8c2d-08a5d939e63b" />
образ создан
На докерхаб увы зарегестрироваться не удалось , не прогружается страница регистрации


##Задание2
<img width="1899" height="164" alt="image" src="https://github.com/user-attachments/assets/33f4fe9b-5cf8-498f-9bf1-1e77be50cf84" />
контейнер запущен
<img width="1910" height="1090" alt="image" src="https://github.com/user-attachments/assets/84449be7-e9d5-4932-a4e7-a0362d57e396" />
работает(порт 8080)
<img width="1836" height="115" alt="image" src="https://github.com/user-attachments/assets/eb5ab4f9-dd45-4b93-ae96-258ac105fff4" />
Контейнер переименован
<img width="1917" height="256" alt="image" src="https://github.com/user-attachments/assets/2c340034-4821-4715-9198-c5f0dbd7b578" />
Команда выполнена
##Задание3
<img width="1910" height="1015" alt="image" src="https://github.com/user-attachments/assets/cb1336a8-3af3-4c2d-8ea0-3d441d0c9038" />
подключил терминал к контейнеру и нажал ctrl-c
контейнер остановился тк был подключен к основному терминалу и получил с него команду на завершение процесса nginx а так как это основной процесс то контейнеру более нечего выполнять
<img width="1893" height="251" alt="image" src="https://github.com/user-attachments/assets/04eddd98-fb97-4944-aed1-42e344b0fb44" />
перезапустил контейнер
<img width="1891" height="72" alt="image" src="https://github.com/user-attachments/assets/453c90e3-9080-4f94-9cf8-4d5a77973e93" />
вошёл в контейнер
<img width="1578" height="555" alt="image" src="https://github.com/user-attachments/assets/0b774b7e-ff11-4d2c-9305-8fa032836398" />
апдейтнулся и установил vim
<img width="1091" height="452" alt="image" src="https://github.com/user-attachments/assets/f55cb53c-ef73-4fd8-9812-ca1c55db6b77" />
изменил значение порта
<img width="1242" height="345" alt="image" src="https://github.com/user-attachments/assets/1fdc0b53-1364-4a79-b418-5c6e4920ba5a" />
ввел необходимые команды
<img width="1066" height="179" alt="image" src="https://github.com/user-attachments/assets/f7cb3e1e-2545-4fb7-bed9-aa552612982a" />
в контейнере опубликован порт 80 а внутри контейнера в конфиге nginx 81 порт по этому страница доступна только внутри контейнера
<img width="1916" height="266" alt="image" src="https://github.com/user-attachments/assets/baf80050-8224-4c2d-b3cd-708619a9d741" />
доп задание , закоммитил контейнер и создал новый с верным портом
<img width="1879" height="153" alt="image" src="https://github.com/user-attachments/assets/df4243e6-3169-4c90-a6e4-dafd28057212" />
удалил контейнер не останавливая его
##Задание4
<img width="1919" height="361" alt="image" src="https://github.com/user-attachments/assets/e86f2c4d-8746-4ff6-b9fc-5ca9ce143a24" />
создал контейнеры
<img width="1919" height="453" alt="image" src="https://github.com/user-attachments/assets/6208bf64-ad82-4723-bb10-e02c047c9c03" />
зашёл в первый контейнер и создал файл ,вышел и создал файл и отобразил содержимое второго контейнера
##Задание 5
<img width="1904" height="574" alt="image" src="https://github.com/user-attachments/assets/6ec60972-9a5c-43e9-b821-adbdcdb6ba6e" />
запустил компоуз , запустился compose.yaml тк он имеет высший приоритет нежели docker-compose.yaml
<img width="1917" height="588" alt="image" src="https://github.com/user-attachments/assets/ee50f7ef-2ba2-40da-aeaf-bcada4e7a274" />
включил докер компоуз в компоуз файл
<img width="1575" height="355" alt="image" src="https://github.com/user-attachments/assets/9726a642-c355-4f20-9640-9f973b90a7a1" />
пушнул в локальный реджистри образ
<img width="1312" height="953" alt="image" src="https://github.com/user-attachments/assets/94527d46-82da-4d40-aecd-af6668b3697b" />
произвёл начальную настройку портейнера
<img width="1918" height="795" alt="image" src="https://github.com/user-attachments/assets/8bba25c2-44c0-4027-aa53-24e25d2a19c5" />
задеплоил представленный компоуз
<img width="1917" height="967" alt="image" src="https://github.com/user-attachments/assets/5ce71565-1b0e-4a34-b6ea-0778d57558b9" />
часть 1
<img width="1912" height="685" alt="image" src="https://github.com/user-attachments/assets/38557987-5f6f-47e8-a85d-9cfe3e7357ae" />
часть 2 сделал скриншот от поля "AppArmorProfile" до "Driver".
<img width="1917" height="213" alt="image" src="https://github.com/user-attachments/assets/1dfb2d5f-9c07-4cd2-b543-2f2ad12c9def" />
Предупреждение говорит о том что нашлись контейнеры которые не привязаны к компоузу 
<img width="1900" height="198" alt="image" src="https://github.com/user-attachments/assets/2442461a-4d61-4d41-af16-67c07f4769bf" />
контейнеры погашены 1 командой 




















