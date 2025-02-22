# Revenue_Test_applied_stats
Небольшой проект по прикладной статистике с использованием `Критерия Стьюдента (T-test)`.

**Описание задачи:** Компания запустила новую функцию в мобильном приложении — персональные рекомендации товаров. Тебе нужно определить, повысила ли эта функция `средний чек пользователей`. В начале у нас есть данные по группам - `контрольная (где не происходило изменений)` и `тестовая (этой группе дали новую функцию приложения)`. Главная задача - оценить, нововведение. Пусть `H0 - ничего не изменилось, все осталось прежним`, `H1 - изменилось, выкатываем изменение для всех пользователей`. Будем это понимать с помощью `альфы`, оно равно `0,05`. Если `p-value` после применения `Критерий Стьюдента` больше альфы - не отвергаем нулевую гипотезу. Если меньше - отвергаем и выкатываем наши изменения. Решение представлено в файле `revenue_AB_test.ipynb`  
