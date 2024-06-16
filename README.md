# Dictyostelium_purpureum

Dictyostelium purpureum - вид Dictyostelium, известных как слизевики. Начинают свой жизненный цикл как одноклеточные амебы, если же пищи не хватает, амебы собираются вместе и начинают двигаться как единое тело. Клетки собираются вместе, образуя плодовое тело с спорами и  стеблем, причем часть клеток жертвует собой для образования стебля.

Число генов – 12 000

Длина генома - 33 Mb

Обитает в почвах по всему миру, температура 10-25°C 

### Код

[Colab](https://colab.research.google.com/drive/1TtuWUYpw2ytzgnuoeoqGSkHJRg3XS7qr?usp=sharing)

[Colab 2](https://colab.research.google.com/drive/1W_ZK-l8apvxyalwvw6lfscamdyz-UUh5?usp=sharing)

[ZDNABERT](https://colab.research.google.com/github/mitiau/Z-DNABERT/blob/main/ZDNA-prediction.ipynb)


### Проверяем, есть ли гены, отвечающие за эпигенетику.

[Таблица](https://github.com/inlkbr/Dictyostelium_purpureum/blob/7bc2b7e6030baf40e113a77c6c1214d7172feac0/f_output.out):
№ | Проверяемое семейство | Название гена 
--- | --- | --- 
1 | 2OG-FeII_Oxy_2 | XM_003287836
2 | BTB | XM_003293252
3 | DEAD | XM_003292608
4 | dsrm | XM_003290696
5 | G-patch | XM_003289698
6 | GNAT_acetyltr_2 | XM_003285794
7 | HA2 | XM_003287398
8 | Helicase_C	| XM_003287970
9 | HSP70 | XM_003293062
10 | Myb_DNA-binding | XM_003290056

### Смотрим куда попали найденные структуры  (гены, промотеры, межгенники, экзоны, интроны) и заполняем таблицу

Участок | Число квадруплексов | Доля квадруплексов | Число предсказаний Zhunt | Доля предсказаний Zhunt | Число предсказаний ZDNABERT | Доля предсказаний ZDNABERT |
--- | --- | --- | --- | --- | --- | --- |
Exons | 35 | 20% | 362 | 50% | 417 | 52% | 
Introns | 117 | 70% | 639 | 89% | 686 | 85%
Promoters  | 110 | 65% | 659 | 92% | 766 | 95%
Downstream  | 73 | 43% | 453 | 63% | 523 | 65%
Intergenic | 116 | 69% | 634 | 88% | 665 | 82% 

### Выравнивание

1)

![](https://github.com/inlkbr/Dictyostelium_purpureum/blob/5134ecd60c82d4efc0f36f3050b070ccd1a6226a/a1.png)
![](https://github.com/inlkbr/Dictyostelium_purpureum/blob/5134ecd60c82d4efc0f36f3050b070ccd1a6226a/t1.jpg)

2)

![](https://github.com/inlkbr/Dictyostelium_purpureum/blob/5134ecd60c82d4efc0f36f3050b070ccd1a6226a/a2.png)
![](https://github.com/inlkbr/Dictyostelium_purpureum/blob/5134ecd60c82d4efc0f36f3050b070ccd1a6226a/t2.jpg)

3)

![](https://github.com/inlkbr/Dictyostelium_purpureum/blob/5134ecd60c82d4efc0f36f3050b070ccd1a6226a/a3.png)
![](https://github.com/inlkbr/Dictyostelium_purpureum/blob/5134ecd60c82d4efc0f36f3050b070ccd1a6226a/t3.jpg)


