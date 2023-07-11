# Фреймворк PyTorch для разработки искусственных нейронных сетей
### Урок 3. Dataset, Dataloader, BatchNorm, Dropout, Оптимизация
1. Создать Dataset для загрузки данных (sklearn.datasets.fetch_california_housing)
2. Обернуть его в Dataloader
3. Написать архитектуру сети, которая предсказывает стоимость недвижимости. Сеть должна включать BatchNorm слои и Dropout (или НЕ включать, но нужно обосновать)
4. Сравните сходимость Adam, RMSProp и SGD, сделайте вывод по качеству работы модели train-test разделение нужно сделать с помощью sklearn random_state=13, test_size = 0.25
