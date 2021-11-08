# Игры — Формирование модели монетизации
Проект выполнен во время обучения на курсе Аналитик Данных от Яндекс.Практикум.  

Цель данного проекта - предложить модель монетизации для мобильной игры "Космические братья".  
Подход на данный момент уже определен создателями игры - рекламу будут показывать при создании игровой постройки. При разработке модели нужно учесть, что слишком назойливая реклама может отпугнуть пользователя.  
Установленная цель - достичь окупаемости маркетинговых расходов на привлечение игроков за то время, что игроки тратят на прохождение первого уровня.  

В нашем распоряжении данные первой когорты игроков: датасет с информацией о времени события, типе события (постройка здания, завершение уровня, завершение проекта), типе здания, user id.  

Помимо основного датасета есть два датасета с информацией о рекламных активностях:    
* Датасет с информацией о переходах пользователей по объявлению и стоимости кликов. 
* Датасет с id пользователя и информацией об источнике, с которого пришел пользователь.   

В рамках исследования:  
* проведем исследовательский анализ данных;  
* проверим как разные события влияют на совершение целевого события (завершения уровня);  
* проверим статистические гипотезы  
*  подготовим рекомендации по возможной модели монетизации  
*  дополнительно подготовим дашборд и презентацию

Используемые библиотеки:  
* pandas  
* numpy
* matplotlib
* seaborn
* scipy

# Games - monetisation model development
Project is completed during studying at Practikum by Yandex Data Analysis course.

Project task is to suggest a monetisation model for a mobile game "Space Brothers".  
The approach is already defined by game developers - ads will be shown on a building creating screen. While developing a model we should consider that too much ads may frighten the palyers.  
The goal set - achieve full pay-back of marketing spendings while players complete the first level of the game.  

We have the data of the first cohort of players: a dataset with info about event time, event type (building construction, level completed, project completed), building type, user id.  

Besides the main dataset we have two additional datasets with marketing data:   
* info on users clicks on ads and clicks costs  
* user ids and user source  

Within our research:  
* we will conduct exploratory data analysis  
* check how different events impact the objective event achievement (lelvel complition)  
* statistical hypothesis testing  
* recommendations on possible monetisation model  
* dashboard and presentation  

Libraries used:

* pandas  
* numpy  
* matplotlib  
* seaborn  
* scipy  