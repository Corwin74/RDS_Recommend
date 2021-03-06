### Введение

Вас перевели в отдел инновационной разработки рекомендательных систем. Ваш работадель хочет увеличить средний чек продаж. После короткого изучения статей вы поняли, что ключом к успеху будет качественные рекомендации на сайте. Чем лучше вы сможете рекомендовать товар пользователю, тем чаще он будет добавлять товары в корзину. Простая логика, если пользователю нравится товар, он его добавляет в корзину -> средний чек растёт. Мы нашли золото!

### Датасет

У вас будет история оценок пользователя вместе с его обзором. Вы можете использовать текст рецензии в качестве дополнительной информации. Все оценки пользователей нормированы для бинарной классификации, если человек поставил оценку продукту больше 3 (не включительно), то мы считаем, что продукт ему понравился, если меньше 4, то продукт не понравился.

### Метрики

В качестве метрики для оценки ваших рекомендаций используется **RocAuc**.

### Условия соревнования:

+ Данное соревнование является бессрочным и доступно для всех потоков.
+ Срок выполнения соревнования устанавливаеться индивидуально в каждом потоке.
+ Тестовая выборка представлена в ЛидерБорде целиком, поэтому лучшие и победные решения буду проверяться на их "адекватность" (чтоб не было подгонки под тестовую выборку).
+ В данном соревновании вам не нужны дополнительные внешние данные. Запрещается их использовать
+ Разрешено использовать любые ML алгоритмы и библиотеки. 
