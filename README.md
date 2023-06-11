# hse23-project

Colab: https://colab.research.google.com/drive/1Y9-QEDbaBQZwuf06Sp3zRZSiOz5M3Fs0?usp=sharing

## Описание гена

ASH1 принадлежит к TrxG белкам, выполняет функции метилирования гистонов (histone modification write) H3 (K4, K9) и H4 (K20): https://doi.org/10.1016/j.gene.2007.04.027.

Экспрессия:

![expression](https://github.com/whiteroomlz/hse23-project/blob/7e90e7d849ae53eba5601afc686d6ad85b2b6ed8/raw/gene-exp-plot.png)

Доменная структура:

![structure](https://github.com/whiteroomlz/hse23-project/blob/7e90e7d849ae53eba5601afc686d6ad85b2b6ed8/raw/structure.png)

## Выравнивание

Потерял картинку. Постараюсь успеть загрузить новую до дедлайна.

## E-values

### DataFrame:

|**Gene\Organism**|**Human**|**Mouse**|**Zebrafish**|**C.elegans**|**Drosophila**|**Ciliate**|**Yeast**|**Methanocaldococcus**|**Thermococcus**|**Tuberculosis**|**E.coli**|
|-|-|-|-|-|-|-|-|-|-|-|-|
|**H2A**|1.000000e-300|1.000000e-300|1.000000e-300|2.740000e-45|8.780000e-44|2.740000e-46|7.470000e-46|1.800|8.510000e-09|5.970000e-12|2.050000e-25|
|**H2B**|3.830000e-88|6.750000e-87|3.030000e-81|6.310000e-67|2.410000e-60|3.080000e-51|5.770000e-60|1.000|8.500000e-01|1.700000e+00|1.100000e+00|
|**H3**|2.190000e-96|1.540000e-96|1.770000e-95|4.460000e-94|9.390000e-96|8.410000e-86|3.310000e-87|0.034|5.700000e-02|4.600000e+00|9.000000e-01|
|**H4**|3.800000e-66|1.420000e-37|3.760000e-38|4.970000e-37|6.020000e-38|7.030000e-31|2.110000e-35|0.220|1.400000e-01|2.700000e+00|1.000000e-01|
|**ASH1**|1.000000e-300|1.000000e-300|1.000000e-300|9.700000e-38|1.000000e-300|2.540000e-34|4.190000e-39|0.360|6.700000e-02|7.800000e+00|2.100000e-01|

### Heatmap:

![heatmap](https://github.com/whiteroomlz/hse23-project/blob/0731db32a8258e950bc92c7e5bcd570d04b5b429/raw/heatmap.png)

## Вывод

Судя по тепловой карте, выбранный мною белок появился в эволюционной цепочке с беспозвоночными организмами (фруктовая мушка Дрозофила).
