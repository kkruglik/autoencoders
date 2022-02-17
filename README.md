# Генеративные модели и автоэнкодеры
## Примеры заданий

В этом ноутбуке мы будем тренировать автоэнкодеры кодировать лица людей. Для этого возьмем датасет [Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/).

Результаты того, как тренированный VAE кодирует и восстанавливает картинки:

![VAE output](https://hsto.org/r/w1560/webt/uw/-g/bd/uw-gbd0lej3jcbrwjzclezzpxbu.png)

Результаты того, как будет выглядеть *выпуклая комбинация* двух латентных векторов VAE: $\alpha l_1 + (1 - \alpha)l_2$, где $l_1, l_2$ – латентные векторы, $\alpha \in [0, 1]$

![VAE output](https://hsto.org/r/w1560/webt/uw/-g/bd/uw-gbd0lej3jcbrwjzclezzpxbu.png)

**Latent Representation**

Давайте посмотрим, как латентные векторы картинок лиц выглядят в пространстве. Изобразим латентные векторы картинок точками в двумерном просторанстве. Это позволит оценить, насколько плотно распределены латентные векторы изображений цифр в пространстве.

![Latent Representation of MNIST](https://hsto.org/r/w1560/webt/uw/-g/bd/uw-gbd0lej3jcbrwjzclezzpxbu.png)
