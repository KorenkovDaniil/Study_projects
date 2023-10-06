# Определение наиболее выгодного региона нефтедобычи

Нефтедобывающей компании понадобился способ определения места, где бурить новую скважину. 
В качестве входных данных предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. 
Требуется построить модель для определения региона, где добыча принесёт наибольшую прибыль.

## Данные

- d — уникальный идентификатор скважины;
- f0, f1, f2 — три признака точек (условные значения без физического смысла);
- product — объём запасов в скважине (тыс. баррелей).

## Задача

На основе данных геологической разведки выбрать район добычи нефти

## Используемые библиотеки
*pandas, scikit-learn, scipy*

## Результаты 
Были получены средние прибыли, вероятности убытков и 95% интервалы выручки для трех регионов.
Наиболее перспективным является Первый регион: по прогнозу там ожидается самая высокая средняя прибыль, вероятность убытков практически равна нулю.
Для Нулевого и Второго регионов вероятность убытков превышает отметку в 2.5%, средняя прибыль там меньше, чем в Первом регионе, поэтому их не стоит рассматривать в качестве варианта для разработки месторождений.