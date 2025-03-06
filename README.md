# Эффекты самоорганизации в рекомендательных системах

## Assets

- [LinkReview](link_review.md)
- [Code](code)
- [Paper](paper)
- [Slides](slides)

## Abstract

В данной работе исследуются эффекты самоорганизации в рекомендательных системах, где потребители и товары эволюционируют во времени как результат многократного машинного обучения. Мы рассматриваем динамическую систему, в которой распределения признаков потребителей 
f
t
c
f 
t
c
​
  и товаров 
f
t
w
f 
t
w
​
  обновляются на каждом шаге 
t
t через оператор эволюции 
D
t
D 
t
​
 , зависящий от рекомендаций 
w
=
h
u
(
c
,
f
t
c
,
f
t
w
)
w=h 
u
​
 (c,f 
t
c
​
 ,f 
t
w
​
 ) и вероятности заключения сделки 
q
(
c
,
w
,
z
)
q(c,w,z), где 
z
z — скрытый параметр. Мы показываем, что при определённых условиях в системе возникает петля положительной обратной связи, приводящая к искажению распределений данных и концептуальному дрейфу.

Для изучения этого явления мы используем нейронную коллаборативную фильтрацию (NCF) для восстановления и обновления функции 
q
(
c
,
w
,
z
)
q(c,w,z) на основе истории сделок. Эксперименты проводятся на данных MovieLens 100K, где мы демонстрируем, как рекомендации влияют на долгосрочное поведение системы. Мы также уточняем условия возникновения положительной обратной связи и предлагаем методы для её смягчения.

Наша работа впервые применяет многократное машинное обучение для анализа самоорганизации в многоагентных системах с рекомендательными алгоритмами. Разработанная имитационная модель позволяет предсказывать долгосрочные эффекты скрытых петель обратной связи, что имеет важное значение для проектирования устойчивых рекомендательных систем.

----
Training a neural network involves searching for the minimum point of the loss function, which defines the surface in the space of model parameters. The properties of this surface are determined by the chosen architecture, the loss function, and the training data. Existing studies show that as the number of objects in the sample increases, the surface of the loss function ceases to change significantly. The paper obtains an estimate for the convergence of the surface of the loss function for the transformer architecture of a neural network with attention layers, as well as conducts computational experiments that confirm the obtained theoretical results. In this paper, we propose a theoretical estimate for the minimum sample size required to train a model with any predetermined acceptable error, providing experiments that prove the theoretical boundaries.

## Licence

Our project is MIT licensed. See [license](LICENSE) for details.
