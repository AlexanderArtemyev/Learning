# Learning
## Задание 3 по нейросетям. 2018-07-18.

* Задание: https://github.com/Yorko/HSE_BigML_AddProfEduc/tree/master/module7_deep_learning и
* Практика к заданию: https://github.com/Yorko/HSE_BigML_AddProfEduc/blob/master/module7_deep_learning/lesson3_practice_backprop_pytorch.ipynb

* `lesson3_practice_backprop_pytorch__Artemyev_AI.ipynb` https://github.com/AlexanderArtemyev/Learning/blob/master/lesson3_practice_backprop_pytorch__Artemyev_AI.ipynb <br> Использовал torch version 0.3.1.post2. <br> При решении возникли вопросы:

1. Чтобы использвовать `LinearClassifier` с оптимизатором torch (Adam) понадобилось написать ещё один метод класса `LinearClassifier`: `named_parameters`.  Можно ли было обойтись без него?

2. При выичислении `loss.backward` потребовалось задать `retain_graph=True`. Если этого не делать, рассчёт падает на одной из первых итераций. Интересно, в чём причина. Можно ли было обойтись без `retain_graph=True`?
