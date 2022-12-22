# Распознавание жестов руки 

Основная идея заключается в том, чтобы использовать жесты рук для управления какими-то программами (запуск скриптов), например, включать или отключать микрофон в zoom.

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

## Графики при обучении
### Сверточная нейронная сеть

![Acc handmodel](src/modelACC.png)

![Loss handmodel](src/modelLOSS.png)

### MobileNetV2

![Acc MobileNetV2](src/accPreTrained.png)

![Loss MobileNetV2](src/lossPreTrained.png)

### Результаты на тестовых данных

![test handmodel](src/testResult.png)

### Роли

- Ватрубин Николай - скачка и подготовка данных
- Попов Никита - обрезка фото и обучение сверточной сети
- Жданова Екатерина - обучение предобученной модели


**Также презентация находится в директории presentation**
