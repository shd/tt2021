Курс теории типов, КТ, осень 2021
=================================
## Материалы
+ [конспект лекций] (https://github.com/shd/tt2018-conspect)
+ [теоретические домашние задания] (https://github.com/shd/tt2021/blob/master/hw-theory.pdf)
+ [материал для первой половины курса] Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 1
### Лямбда-исчисление, базовые определения, примеры
+ Немного об истории
+ Лямбда-выражения, синтаксис
+ Булевские выражения, чёрчевские нумералы
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 2
### Теорема Чёрча-Россера, Y-комбинатор
+ Альфа-эквивалентность, бета-редекс, бета-редукция
+ Бета-редуцируемость и параллельная бета-редукция
+ Теорема Чёрча-Россера
+ Комбинаторы: определение и примеры (I,S,K)
+ Рекурсия и Y-комбинаторы
+ Ленивые вычисления, нормальный порядок редукции
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 3
### Просто типизированное лямбда-исчисление
+ Язык просто типизированного исчисления (типы, контекст)
+ Типизация по Чёрчу и по Карри.
+ Правила вывода
+ Теоремы о типизации редукции, Чёрча-Россера, об уникальности типизации по Чёрчу.
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 4
### Импликационный фрагмент интуиционистского исчисления высказываний
+ Импликационный фрагмент интуиционистского исчисления высказываний
+ Три задачи (проверка обитаемости, проверка типа, вывод типа)
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 5
### Вывод типа. Введение в исчисление предикатов второго порядка
+ Задача унификации
+ Вывод типа в просто типизированном лямбда-исчислении
+ Исчисление предикатов второго порядка и система F, введение
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 6
### Система F. Экзистенциальные типы
+ Правила для кванторов существования
+ Экзистенциальные типы
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf
+ John C. Mitchell, Gordon D. Plotkin, Abstract Types Have Existential Type
http://homepages.inf.ed.ac.uk/gdp/publications/Abstract_existential.pdf

## Лекция 7
### Система Хиндли-Милнера.
+ Ранг типа
+ Аксиоматика
+ Алгоритм W
+ Расширения системы: экви- и изорекурсивные типы, тип для Y-комбинатора
### Где почитать
+ Luis Damas and Robin Milner, Principal type-schemes for functional programs
POPL'82: Proceedings of the 9th ACM SIGPLAN-SIGACT symposium on Principles of programming languages, ACM, pp. 207–212
+ Robin Milner, A theory of type polymorphism in programming (1978) // Journal of Computer and System Sciences, 1978, vol. 17, pp. 348--375
https://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.67.5276
+ Бенджамин Пирс, Типы в языках программирования. Издательство «Лямбда пресс» & «Добросвет», Москва, 2011

## Лекция 8
### Обобщённые типовые системы. Лямбда-куб Барендрегта
+ Аксиоматика
+ Лямбда-куб
+ Зависимые типы, примеры зависимых типов в языках программирования
+ Языки программирования на лямбда-кубе.
### Где почитать
+ Henk Barendregt, Introduction to generalized type systems.
Journal of Functional Programming 1 (2): 125-154, April 1991

## Лекция 9
### Введение в гомотопическую теорию типов, язык Аренд
+ Интуиционистские типовые системы для формализации доказательств
+ Равенство, интенсиональные и экстенсиональные типовые системы
+ Непрерывные функции
+ Связные множества, линейная связность, пути
+ Изоморфизм Карри-Ховарда-Воеводского
+ Равенство в Аренд. Простейшие примеры программ на Аренд.
### Где почитать
+ Гомотопическая теория типов
https://homotopytypetheory.org/book/
+ Cyril Cohen, Thierry Coquand, Simon Huber, Anders Mörtberg. 
Cubical Type Theory: a constructive interpretation of the univalence axiom.
https://arxiv.org/abs/1611.02108
+ Документация по языку Аренд
https://arend-lang.github.io/documentation/
+ Arend – язык с зависимыми типами, основанный на HoTT (часть 1)
https://habr.com/ru/company/JetBrains-education/blog/469569/

## Лекция 10
### Равенство в языке Аренд
+ Магия: элиминатор для интервального типа coe
+ Вспомогательные функции: transport, pmap
+ Типы Empty и Not. Доказательство неравенства
### Где почитать
+ Документация по яызку Аренд, равенство и доказательства равенства
https://arend-lang.github.io/documentation/tutorial/PartI/idtype
https://arend-lang.github.io/documentation/tutorial/PartI/equalityex

## Лекция 11
### Типы данных, специальные конструкции
+ Неравенство: два способа определения (через экзистенциальный тип и через обобщённый алгебраический тип)
+ rewrite и contradiction
+ Set и Prop
### Где почитать
+ Документация по языку Аренд

## Лекция 12
### Универсумы, гомотопические уровни, фактор-множества
+ Универсумы
+ Гомотопические уровни
+ Фактор-множества, способы определения нетривиальных равенств
### Где почитать
+ Документация по языку Аренд

## Лекция 13
### Парадокс Жирара
+ Постановка задачи, необходимость дополнительной выразительной силы теории.
+ Каков тип типа? Типовые системы U и U-. 
+ Парадокс Бурали-Форте
+ Парадокс Бурали-Форте для парадоксальных универсумов (схема доказательства)
+ Воспроизведение парадокса в системе U (схема), применение правила (\square,\triangle)
### Где почитать
+ Доказательство парадокса Хуркенса (варианта парадокса Жирара) на языке Coq
https://coq.inria.fr/library/Coq.Logic.Hurkens.html
+ Antonius J. S. Hurkens. A Simplification of Girard's Paradox

## Лекция 14
### Теорема Диаконеску
+ Конструктивная аксиома выбора и её доказуемость.
+ Сетоиды, аксиома выбора для сетоидов.
+ Аксиома выбора в HoTT и Аренде (как аксиома о перестановке кванторов и пропозиционального обрезания).

## Лекция 15
### Линейные и уникальные типы
+ Мотивация для линейных типов: гарантия от копирования/уничтожения значений, оптимизации.
+ Структурные правила (для натурального вывода) и соответствующие им комбинаторы в комбинаторном базисе BCKW.
+ Линейные типы
+ Реализация: уникальные типы
### Где прочесть
+ Philip Wadler. A taste of linear logic
+ Edsko de Vries, Rinus Plasmeijer, David M Abrahamson. Uniqueness Typing Simplified

## Лекция 16
### Система F-Sub
+ Общие понятия (что такое подтип, ко- и контравариантность)
+ Система F<:
+ Полный и ядерный вариант системы F<:
### Где прочесть
+ Бенджамин Пирс, Типы в языках программирования. Издательство «Лямбда пресс» & «Добросвет». Москва, 2011
