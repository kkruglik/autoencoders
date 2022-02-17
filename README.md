# Генеративные модели и автоэнкодеры
## Примеры заданий

В этом ноутбуке мы будем тренировать автоэнкодеры кодировать лица людей. Для этого возьмем датасет [Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/).

Результаты того, как тренированный VAE кодирует и восстанавливает картинки:

![VAE output](https://github.com/kkruglik/autoencoders/blob/main/imgs/results.png)

Результаты того, как будет выглядеть *выпуклая комбинация* двух латентных векторов VAE: 

![VAE output](https://github.com/kkruglik/autoencoders/blob/main/imgs/results_2.png)

**Latent Representation**

Давайте посмотрим, как латентные векторы картинок лиц выглядят в пространстве. Изобразим латентные векторы картинок точками в двумерном просторанстве. Это позволит оценить, насколько плотно распределены латентные векторы изображений цифр в пространстве.

![Latent Representation of MNIST](https://github.com/kkruglik/autoencoders/blob/main/imgs/latent.png)
