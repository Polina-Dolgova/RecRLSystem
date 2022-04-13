# RecRLSystem

Имплементация статьи Deep Reinforcement Learning based Recommendation with Explicit User-Item Interactions Modeling (https://arxiv.org/abs/1810.12027)

Как запустить:
- Скачать датасет из https://grouplens.org/datasets/movielens/1m/
- Запустить ноутбук

Текущий статус: 
- Проблема в обучении: ищу место, с inplace-операцией, мешающей вычислению градиентов. Пока логи не помогают.
- Часть, касающаяся обучения, воспроизведена. Часть evaluation - нет, поскольку первичной целью является решение проблемы выше.
