# Семинары по машинному обучению для бакалавров 3 курса кафедры ММП и магистров 1 курса кафедр ИИТ и МФ факультета ВМК МГУ, осенний семестр 2022/2023
В репозитории находятся материалы и домашние задания по семинарам "ММРО 2022/2023"

<p align="center">
<img src="http://funzoo.ru/uploads/posts/2009-11/1258648863_tn.jpg" height=200pt> <img src="https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/trash/kernel_trick.jpg" height=200pt>
</p>

:white_check_mark: **Курс сдается через систему [anytask](ДОБАВИТЬ). Инвайт можете получить у преподавателя**


:white_check_mark: **Полезные ссылки:**

* Текущие связанные курсы
    * [Курс практикум на эвм](https://github.com/mmp-practicum-team/mmp_practicum_fall_2022)
    * [Общий курс по МЛ](https://github.com/MSU-ML-COURSE/ML-COURSE-22-23)

* Материалы прошлых лет:
  * [Материалы древних времен](https://github.com/esokolov/ml-course-msu)
  * [Вышкинский аналог курса](https://github.com/esokolov/ml-course-hse)
  * [Курс лекций по ММРО 20/21 (в те времена он читался эксклюзивно для ММП)](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%80%D0%B0%D1%81%D0%BF%D0%BE%D0%B7%D0%BD%D0%B0%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%92.%D0%92.%D0%9A%D0%B8%D1%82%D0%BE%D0%B2%29)
  * [Общий курс по МЛ 21/22](https://github.com/MSU-ML-COURSE/ML-COURSE-21-22)
  * [Курс ММРО 19/20, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2019)
  * [Курс ММРО 20/21, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020)
  * [Курс ММРО 21/22, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021)

# Правила выставления оценок

:white_check_mark: **По этому курсу (ММРО) в конце семестра будет экзамен**

Общая оценка по нему выставляется по следующей формуле:
![](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/trash/formula.png)
, где 

* Check — 5 * <сумма баллов за проверочные> / <суммарный макс балл за проверочные>
* Labs — min(5, 5 * <сумма баллов за лабораторные + конкурсы + теор. дз.> / <суммарный макс балл за (лабораторные + конкурсы + теор.дз) (без бонусов)>
* Exam — оценка за экзамен, до 5 баллов

Причем
* Для общей оценки 5 необходимо сдать **все (5)** _лабораторные работы (4) и теор. дз. (1)_ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за эказамен не меньше 4;
* Для общей оценки 4 необходимо сдать **не менее 3-х** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* Для общей оценки 3 необходимо сдать **не менее 2-x** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* floor — округление дробного числа до ближайшего целого вниз.

**Обратите внимание,** что округление общей оценки (и только ее) производится вверх.

:white_check_mark: **По курсу лекций в конце семестра будет зачет без оценки**

Для получения этого зачета вам необходимо сдать **не менее 2-x** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов))

# Занятия

| Дата | Номер | Тема | Материалы | ДЗ |
| :---: | :---: | --- | --- | --- |
| 8 сентября  | Семинар 1 | Работа с табличными данными. Pandas. Разведочный анализ данных | [Ноутбук с семинара](https://github.com/mmp-mmro-team/mmp_mmro_fall_2022/blob/main/seminars/Seminar1/sem_pandas.ipynb) | [Легкая домашка на пандас](https://github.com/mmp-mmro-team/mmp_mmro_fall_2022/blob/main/homework-practice/Homework_practice_1/numpy_pandas_matplotlib_2022.ipynb)   |
| 15 сентября  | Семинар 2 | Быстрый поиск ближайших соседей | https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/lecture-notes/lecture20-knn.pdf |  ¯\\\_(ツ)\_/¯ |
| 22 сентября  | Семинар 3 | Особенности knn и разновидности метрик |  https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/seminars/sem19-knn.pdf   |  ¯\\\_(ツ)\_/¯ |
| 29 сентября  | Семинар 4 | sklearn и особенности линейной регрессии | https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/seminars/sem02-sklearn-linregr.ipynb | ¯\\\_(ツ)\_/¯ |
| 6 октября | Семинар 5 | Векторное дифференцирование | [Хороший cheat sheet по дифференцированию](https://github.com/mmp-mmro-team/mmp_mmro_fall_2022/blob/main/seminars/sem05_vect_matrix_diff.pdf) | [Домашка на линейную регрессию](https://github.com/mmp-mmro-team/mmp_mmro_fall_2022/blob/main/homework-practice/homework-practice-02-linregr.ipynb)  |
| 13 октября | Семинар 6 | Логистическая регрессия: оценивание вероятностей и вывод функционала, калибровка вероятностей | [Семинар (раздел 1)](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/lecture-notes/lecture05-linclass.pdf) | ¯\\\_(ツ)\_/¯ |
| 20 октября | Семинар 7 | Теорема Куна-Таккера и двойственные задачи | https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/seminars/sem13-kkt.pdf | [Хардкорная домашка на дифференцирование](https://github.com/mmp-mmro-team/mmp_mmro_fall_2022/blob/main/homework-theory/matrix_differentiation_mmro.pdf)   |
| 27 октября | Семинар 8 | Ядровые обобщения методов, задачи на ядра | https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/seminars/sem14-kernels.pdf |  ¯\\\_(ツ)\_/¯ | 
| 3 ноября | Семинар 9 | Метрики качества классификации, задачи на площади под кривыми |  https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/seminars/sem05-linclass-metrics.pdf  | [Домашка на линейную классификацию](https://github.com/mmp-mmro-team/mmp_mmro_fall_2022/blob/main/homework-practice/hw_practice_3.ipynb)  |
| 10 ноября | Семинар 10 | Разложение ошибки на смещение и разброс | https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/lecture-notes/lecture08-ensembles.pdf  | ¯\\\_(ツ)\_/¯ |
| 17 ноября | Семинар 11 | Вывод критериев информативности для деревьев, разглядывание картинок про деревья | [ссылка 1](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/seminars/sem07-trees.pdf) [ссылка 2](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/seminars/sem07-trees.ipynb) | ¯\\\_(ツ)\_/¯ |
| 24 ноября | Семинар 12 | Градиентный бустинг | https://github.com/esokolov/ml-course-hse/blob/master/2021-fall/lecture-notes/lecture10-ensembles.pdf | ¯\\\_(ツ)\_/¯ |
| 1 декабря | Семинар 13 | Почему градиентный бустинг так устроен | https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/seminars/sem09-gbm-part1.pdf  | [последний бой](https://github.com/mmp-mmro-team/mmp_mmro_fall_2022/blob/main/homework-practice/hw-practice-4.ipynb) |
| 8 декабря | Семинар 14 | coming soon |  | ¯\\\_(ツ)\_/¯ |
| 15 декабря | Семинар 15 | coming soon |  | ¯\\\_(ツ)\_/¯ |

   
