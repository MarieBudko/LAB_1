В этой задаче используется сверточная нейронная сеть из пяти слоев: два сверточных Conv2d и три линейных Linear. Во всех слоях используется активация relu.

В цикле обучения используется оптимизатор SGD, функция потерь CrossEntropyLoss. Всего производится 50 эпох обучения.

* Зависимость функции потерь от номера эпохи для обучающих данных

![Image alt]( https://github.com/MarieBudko/LAB_1/blob/master/graf_1.png?raw=true)

* Зависимость функции потерь от номера эпохи для контрольных данных

![Image alt]( https://github.com/MarieBudko/LAB_1/blob/master/graf_2.png?raw=true)

* Зависимость метрики качества(точность) от номера эпохи для обучающих данных

![Image alt]( https://github.com/MarieBudko/LAB_1/blob/master/graf_3.png?raw=true)

* Зависимость метрики качества(точность) от номера эпохи для контрольных данных

![Image alt]( https://github.com/MarieBudko/LAB_1/blob/master/graf_4.png?raw=true)
