# Что будем делать сегодня
1) Закончим приложение "Calculator" и внесем необходимые исправления
2) Воспользуемся услугой Git Pages(бесплатый хостинг) и сделаем наш "Calculator" доступным всему миру по определенному url
3) Если успеем, начнем верстать макет "Super Host"

# Что не успели пройти в прошлом уроки(долги)
1) Обнуление стилей браузера
2) rgb, rgba (альфа канал, 16-тиричная система)
3) Анализ макета перед версткой

# Что сделали(Что успели)
1) Закончили приложение "Calculator"
2) Выложили "Calculator" на Git Pages по адресу https://kirill2007-cpu.github.io/lesson-8/
3) Обнуление стилей normalize.css
4) Затронули понятие "Рефакторинг"

# Ключевые моменты урока
1) При разработке программы можно следовать следующей стратегии <br/>
    а) Вначале написать "сырое решение". Т.е. рабочее решение которое может быть не эффективным в плане производительности и иметь некрасивый код с повторяющимися моментами и без "Best practices" <br/>
    б) Потом заняться рефакторингом, т.е. приведение кода к читабельному виду применяя при этом "Best practices".
 Почему именно такой подход? Во всем должны быть отдельные этапы которые постепенно приближают к главной цели. При решении задачи нужно сперва сконцетрироваться именно на тех моментах которые именно "решают данную задачу".(Пример: Сказали пробить дыру в стене на кухне - взяли и пробили. Задача решена и не важно как). Следующим этапом мы должны избавиться от повторяющегося кода если это возможно. Далее применяем "Best practices" и конечно же следим за тем, что-бы код был читабельным (Убрать мусор который появилься от дыры которую сделали в стене, замазать цементом трещины которые пошли от ударов). Решение задачи нужно всегда разбивать на этапы. <br/>
 
 # Фраза дня
 1) Любой может писать код который поймет компьютер. Хорошие программисты пишут код, который понимают люди.(Martin Fowler)
 Источник: https://boliev.ru/yet_another_clean_code_post/
 
 # Рекомендации
 Опытные программисты рассматривают систему как историю, которую они должны рассказать, а не как программу, которую нужно написать. Они используют средства выбранного ими языка программирования для конструирования гораздо более богатого и выразительного языка, подходящего для этого повествования (Robert Martin)
 
 # Шпаргалка
 1) Для того чтобы тэг input  сделать только для чтения ему нужно прописать аттрибут readonly
 2) Для того чтобы убрать обводку фокуса(input, button  и д.р.) прописываем css свойство outline: none;
 3) Для того чтобы проект был доступен для входа по url(Git Pages) <br/>
  а) Переходим по ссылке Settings <br/>
  б) Находим секцию GitHub Pages <br/>
  в) Находим подсекцию Source <br/>
  г) Выбираем master branch <br/>
  
# Задание на дом
На гидхабе я залил новую, отрефакторенную версию программы "Calculator" в репозитории "calculator-refactored". Твоя задача посмотреть на эту версию и сравнить ее с прошлой. Посмотри что изменилось, есть ли что-то новое чего ты еще не знаешь? Постарайся найти, если сможешь как еще можно улучшить данное приложение, есть ли что-то что не учтено, или работает не правильно. Если найдешь расскажи как это можно исправить.

# Вопросы студента
Еще не заданы
