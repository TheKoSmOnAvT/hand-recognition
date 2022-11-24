# Распознавание жестов руки 

Основная идея заключается в том, чтобы использовать жесты рук для управления какими-то программами (запуск скриптов), например, велючать или отключать микрофон в zoom.

![gestures](src/gesture_kaggle.png)

## Какие жесты мы классифицируем

- Call
- Dislike
- Like
- Mute
- Ok
- Rock
- Stop

## Данные для обучения

[kaggle](https://www.kaggle.com/datasets/kapitanov/hagrid)

## А что с кодом?

В каталоге notebooks представлены следующие скрипты:

- preparePicture.ipynb - для подготовки обучающих данных (обрезка фото)
- handModel.ipynb - модель свверточной нейронной сети
- preTrainedHandModel.ipynb - модель добученной сети MobileNetV2

## Графики и метрики
### Сверточная нейронная сеть
- ![Acc handmodel](src/.png)
- ![Loss handmodel](src/.png)
- ![classificator reporterl](src/.png)
### MobileNetV2
- ![Acc handmodel](src/.png)
- ![Loss handmodel](src/.png)
- ![classificator reporterl](src/.png)




**Также презентация находится в директории presentation**