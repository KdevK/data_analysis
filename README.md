# Проект по анализу данных в бизнесе
# Видео-отчет: https://youtu.be/nDfHP3bryV4

В этом проекте мы поставили задачу сравнить эффективность работы между 5-ю разными моделями машинного обучения: 
- Логистическая регрессия
- KNN
- Random Forest
- XGBoost
- CatBoost

## Защита проекта

## Описание проблемы
Смоделируем ситуацию. Далёкое будущее, спустя 1000 лет космический корабль под названием Титаник повторяет судьбу одноимённого затонувшего судна. Часть людей смогла спастись, часть нет. Основываясь на информации, полученной из датасета (о нём подробнее - далее), нужно обучить 5 моделей и понять, какая из них отработает лучше.

## Датасет
Ссылка: https://www.kaggle.com/competitions/spaceship-titanic/data

Датасет содержит почти 8700 строк и 10 столбцов.

Рассмотрим их подробнее:

- HomePlanet - планета, с которой отправился пассажир
- CryoSleep - согласился ли пассажир провести путешествие в крио-сне, тем самым оставшись в своей комнате на протяжение всего путешествия
- Cabin - номер комнаты пассажира
- Destination - планета, куда отправился пассажир
- Age - возраст пассажира
- VIP - оплатил ли пассажир VIP сервис
- RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - эти столбцы отражают, сколько пассажир потратил денег на указанные услуги

## Вывод
Мы создали, настроили, обучили и проанализировали 5 моделей машинного обучения: Логистическая регрессия, KNN, Random Forest, XGBoost, CatBoost. В ходе исследования и сравнения полученных результатов, мы сделали вывод о следующем порядке качества, с которым модели отработали на данной задаче кластеризации, от лучшего к худшему:

XGBoost
CatBoost
RandomForest
Логистическая регрессия
KNN
Разница между лучшим и худшим результатом составила около 3%
