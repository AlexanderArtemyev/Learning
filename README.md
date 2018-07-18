# Learning
* `lesson3_practice_backprop_pytorch__Artemyev_AI.ipynb` <br> Использовал torch version 0.3.1.post2. <br> При решении возникли вопросы:

1 Чтобы использвовать `LinearClassifier` с оптимизатором torch (Adam) понадобилось написать ещё один метод класса `LinearClassifier`: `named_parameters`.  Можно ли было обойтись без него?

2 При выичислении `loss.backward` потребовалось задать `retain_graph=True`. Если этого не делать, рассчёт падает на одной из первых итераций. Интересно, в чём причина. Можно ли было обойтись без `retain_graph=True`?
