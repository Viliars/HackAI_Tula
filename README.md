# HackAI_Tula
Цифровой прорыв в Тульской области.

Для построения решения необходимы запустить 4 jupyter ноутбука:
1) filter_data - фильтрация только тех городов/болезней/пола/возрастной группы, которые есть в тесте
2) prepare_data - подготовка новых фич (перевод категориальных фич и создание фич из временного ряда)
3) SearchTrendCoef - вычисление трендовых коэффицентов (коэффициентов роста числа больных по месяцам)
4) TrainModel - обучение основной модели и вычисление результатов на тесте