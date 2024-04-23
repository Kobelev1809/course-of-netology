# Выполнение домашнего задания по теме «Объекты и классы. Инкапсуляция, наследование и полиморфизм»

На данный момент в домашем задании выполнены следующие этапы...

## Этап № 0. Инициализации репозитория, добавления в него файла классов из квиза и создание дополнительных файлов.
В данном этапе для выполнения домашнего задания были реализовано:
1. создан локальный Git-репозиторий;
2. в репозиторий был добавлен файл .gitignore;
3. добавлен файл с классами ментора и студента из выполненного квиза;
4. создан файл README.md с описанием выполненных пунктов;
5. выполнен первоначальный коммит.

## Этап № 1. Выполнено задание № 1. - Наследование.
Hа данном этапе было реализовано:
1. класс Student остался без изменения, а класс Mentor стал родительским;
2. создан новый дочерний класс лекторов (Lecturer), унаследованный от класса Mentor;
3. создан новый дочерний класс экспертов (Reviewer), унаследованный от класс Mentor;
4. все выполненные изменения были отражены в файлe README.md;
5. создан коммит о выполнении задания №1 (Task No. 1 is completed).

## Этап № 2. Выполнено задание № 2. - Атрибуты и взаимодействие классов.
Hа данном этапе было реализовано:
1. метод выставления оценок был перенесён из класса Mentor в класс Reviewer;
2. в классе Lecturer был перезагружен метод ```__init__()``` родительского класса с добавлением атрибута-словаря оценок;
3. в классе Student был реализован метод выставления оценки лекторов ```rate_lecture()```;
4. все  изменения были отражены в файлe README.md;
5. создан коммит о выполнении задания №2 (Task No. 2 is completed).

## Этап № 3. Выполнено задание № 3. - Полиморфизм и магические методы.
Hа данном этапе было реализовано:
1. перезагружен магический метод ```__str__()``` для всех классов;
2. релизация метода ```__str__()``` у проверяющих, лекторов и студентов выполнена в соответствии с указанным в задании образцом;
3. выполнена реализация возможности сравнения студентов между собой по их средней оценке за домашние задания с использованием операторов сравнения;
4. выполнена реализация возможности сравнения лекторов между собой по их средней оценке за лекции с использованием операторов сравнения;
5. все выполненные изменения были отражены в файлe README.md;
6. создан коммит о выполнении задания №3 (Task No. 3 is completed).

## Этап № 4. Выполнено задание № 4. - Полевые испытания.
Hа данном этапе было реализовано:
1. было создано по два экземпляра каждого класса;
2. были вызваны все созданные методы;
3. была реализована функция подсчета средней оценки за домашние задания по всем студентам в рамках конкретного курса (аргументы функции: список студентов и название курса);
4. была реализована функция подсчета средней оценки за лекции всех лекторов в рамках курса (аргументы функции: список лекторов и название курса);
5. все выполненные изменения были отражены в файлe README.md;
6. создан коммит о завершении домашнего задания (Homework is completed).