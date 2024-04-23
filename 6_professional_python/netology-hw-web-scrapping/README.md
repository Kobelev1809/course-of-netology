# Домашнее задание к лекции 6.«Web-scrapping»

При выполнении данного задания было реализовано:

1. Пропарсили страницу со свежими вакансиями с поиском по "Python" и городами "Москва" и "Санкт-Петербург". Эти параметры были заданы задаются по [ссылке](https://spb.hh.ru/search/vacancy?text=python&area=1&area=2)
2. Выбраны те вакансии, у которых в описании есть ключевые слова "Django" и "Flask".
3. Выбранные вакансии записаны в json-файл с фиксацией следующих данных по ваканисям: ссылка, вилка зп, название компании, город.

Выполнено дополнительное (необязательное задание):

- реализован выбор, позволяющий выполнять поиск вакансий только с зарплатой в долларах.