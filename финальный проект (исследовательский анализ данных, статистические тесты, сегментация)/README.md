**ПОСТАВЛЕННЫЕ ЗАДАЧИ:** Проанализировать данные о клиентах банка и выделить из них наиболее склонные к уходу сегменты с целью подготовки таргетированных рекомендаций.
***
**ИСПОЛЬЗУЕМЫЕ ИНСТРУМЕНТЫ И НАВЫКИ:** `pandas`, `matplolib`, `seaborn`, `phik`, `scipy`, `statistics`, `предобработка данных`, `исследовательский анализ данных`, `анализ корреляций`, `статистические тесты`.
***
**ОПИСАНИЕ ПРОЕКТА:** Для решения поставленных задач 
1. Провел предобработку данных: 
  - установил природу возникновения дубликатов и применил подходящий метод обработки;
  - установил природу возникновения пропусков и применил подходящие методы обработки пропусков.
2. Провел исследовательский анализ данных:
  - выявил "рисковые" значения признаков клиентов;
  - сформировал портреты типичного лояльного клиента и типичного ушедшего клиента;
  - рассчитал корреляцию между признаками с помощью библиотеки `phik` и оценил получившиеся значения по шкале Чеддока;
3. Выбрал подходящие статистические тесты и проверил 2 гипотезы:
  - с помощью `T-теста` проверил наличие статистической значимой разницы в средних зарплатах лояльных и ушедших клиентов.
  - с помощью `Z-статистики` проверил наличие статистически значимой разницы между долями ушедших клиентов в двух городах.
4. На основе имеющихся признаков и их "рисковых" значений сформировал 4 сегмента клиентов, в которых доля оттока в 2 раза превышает средний уровень по банку.
5. Провел приоритезацию сегментов и разработал ряд таргетированных рекомендаций для каждого из них.
6. Подготовил презентацию с обобщенными результатами проекта.
