# Домашнее задание модуля 7

## Задание 1

В этом задании необходимо создать свой собственный линейный классификатор, а решение рекомендуется оформить в виде jupyter ноутбука.

Мы когда-то уже наблюдали некоторые "игрушечные" датасеты, которые доступны в библиотеки sklearn. Попробуем создать линейную модель для одного такого датасета. Для желающих полный список можно найти здесь и здесь. Нас же будет интересовать "винный" датасет, информацию о котором можно найти здесь.

    1.Загрузите датасет выполнив следующий код
    
    from sklearn.datasets import load_wine
    wine_dataset = load_wine()

    2.Изучите документацию функции train_test_split. С ее помощью датасет можно разделить на тренировочную и тестовую выборки. Первая нужна для обучения модели, а вторая - для оценки качества модели.

    3.Разделите wine_dataset на обучающую и тестовую выборки.

    4.Обучите модель на тренировочной выборке и оцените ее качество на тестовой.

    5.Попробуйте повторить шаги 3 и 4 разбив датасет на обучающую и тестовую выборки в какой-то собственной пропорции. Как это отразилось на качестве модели?

## Задание 2

Постройте линейный классификатор подобно тому, как мы это делали в задании 1 на датасете Ириса Фишера. Оформите решение в виде jupyter ноутбука.

##Задание 3

В этом задании нам предстоит построить линейный регрессор. В этот раз мы будем работать с данными о заболевании диабетом. Аналогично заданию 1 выполните следующие шаги

    1.Загрузите датасет.
    
    2.Разделите его на тренировочную и тестовую выборки.
    
    3.На тренировочной выборке обучите линейную модель.
    
    4.Оцените ее качество на тестовой выборке.
    
    5.Попробуйте повторить шаги 1-4 разбив датасет на обучающую и тестовую выборки в какой-то собственной пропорции. Как это отразилось на качестве модели?

Оформите решение в виде jupyter ноутбука.
