1 Задание

![01](https://github.com/user-attachments/assets/4786df66-313d-48a5-97e8-2017d4299dba)

![Снимок](https://github.com/user-attachments/assets/4deaafe6-9d6b-42ff-b287-b70666b34e23)

Входной точкой является composer-api: action_v2

Запрос прошел через 32 сервиса

Затрачено время 60.94ms

https://tracing-prod.o3.ru/trace/18e300c673bc5d03?env=prod

2 Задание

Ищем гафану с нужныи БД

Имя синхронной реплики http://prodpostgres6722-90112z504.h.o3.ru:7001/ 

![01](https://github.com/user-attachments/assets/fb1c89ec-97fa-4d6e-8da2-d0654508f6cc)

Находим нужный гаджет

![02](https://github.com/user-attachments/assets/62a4d5b0-1a29-42b2-8883-a5aab585f634)

3 Задание

Идем на logging.o3.ru пишем в поиске service: "pvz-api-return-seller-giveout"

Находим подходяюю ошибку под условия

https://logging.o3.ru/messages/0931689395010000-70012d16ccd7bafa

Переходим по трейсу и смотрим его

https://tracing.o3.ru/trace/2555bb1cb23fbe05?env=prod

Ответы на вопросы

  1.PVZ_polo_anas
  
  2.5.94ms
  
  3.service: "pvz-api-return-seller-giveout" AND message:"39932-7162"
  
4 Задание

