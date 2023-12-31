# Исследование проведения выборов в Википедии

[**ПЕРЕЙТИ К ПРОЕКТУ**](https://github.com/bachurina-anna/portfolio/blob/main/%D0%92%D1%8B%D0%B1%D0%BE%D1%80%D1%8B%20%D0%92%D0%B8%D0%BA%D0%B8%D0%BF%D0%B5%D0%B4%D0%B8%D0%B8/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B2%D1%8B%D0%B1%D0%BE%D1%80%D0%BE%D0%B2%20%D0%B2%20%D0%92%D0%B8%D0%BA%D0%B8%D0%BF%D0%B5%D0%B4%D0%B8%D0%B8.ipynb)

## Описание проекта:

**Цели проекта:** 
- Исследовать данные проведения выборов в Википедии, обнаружить в них значимые инсайты
- Сегментировать пользователей, изучить статистики сегментов
- Описать и визуализировать основные находки

**Данные:**
Сайт, с которого собиралась статистика — [wikiscan.org](https://ru.wikiscan.org/)

**wiki_arbcom.xlsx** - информация о голосовании
* voter - ник голосовавшего юзера     
* can_vote - считался ли его голос действующим
* time - когда был отдан голос
* candidate - ник кандидата   
* n - порядковый номер выборов
* vote - голос за (1) или против (-1)

**wiki_userstat.xlsx** - информация о пользователях
* User - ник юзера
* Groups - закодированные дополнительные права участника
  * пустое значение - нет дополнительных прав
  * S (sysop) - администратор - может блокировать юзеров и IP
  * B (buerocrat) - бюрократ - может выдавать права администратора и другие
  * С (checkuser) - чекьюзер - может проверять IP участников
  * O (supress) - ревизор - может скрывать информацию
  * I (IPblock-exempt) - исключение из IP блокировок - может править из-под заблокированного IP
* EditsTotal — все правки
* EditsEdits — не удалённые
* EditsArticles — правки в энциклопедических статьях
* CreationsPages — количество любых созданных страниц
* CreationsArticles — количество созданных энциклопедических страниц
* TextsVolume — объём добавленного текста (байты)
* Logs — количество записей в логах о действиях, не являющихся правками
* Months — количество месяцев участия
* H/d — среднее время участия в день

  ## Содержание
1. Обзор данных
2. Предобработка данных в файле с голосами избирателей
3. Предобработка данных в файле с информацией по пользователям
4. Итоги выборов
5. Результаты выборов по дням голосования
6. Количество набранных голосов для победы
7. Консервативность избирателей
8. Кластерный анализ пользователей, участвующих в голосовании
9. Портрет конформиста и оппортуниста
10. Исследовательский анализ пользователей
11. Выводы
