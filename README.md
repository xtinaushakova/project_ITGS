# Бот ИТГС

## Задачи:

- Написать краткое описание бота (2-3 абзаца, до 150 слов) на русском, чтобы потом выложить в сообщество.
- Написать приветствие для бота, что он будет говорить, когда к нему подключаешься в первый раз (по идее, обзор команд) @pgtklddabz и @lanastya
- Прописать диалоги бота
- Написать справку по боту с описанием команд и функционала

--------ОБЩЕЕ-------

Задачи будут разделяться на разные промежутки. То есть будут задачи на день, неделю, месяц, полгода. Для каждого пользователя имеем файлы с задачами, разбитыми по дням, неделям, месяцам. Каждый день, общаясь с ботом например в 8:00, получая дружественное напоминание или деликатный вопрос вроде "Какие планы на сегодня", пользователь планирует свой день. Аналогично с неделями и месяцами - каждое воскресенье и накануне первого числа. Каждый раз, запрашивая список задач, ты получаешь не только дневные - краткосрочные задачи, но и более долгоиграющие амбиции - все списком. В конце каждого дня, недели, месяца, тебя спрашивают, удалось ли выполнить задачи. Помечаешь как выполненные те, что удались.

-------НАЧАЛО/СОЗДАНИЕ ЗАДАЧ-----

Начало общения создает персональную БД для пользователя
Бот спрашивает, что пользователь хочет сегодня/на неделю 
"Какие задачи? Напишите их, каждую с новой строки"
Пользователь отвечает, например записывая каждую с новой строки (если много) - и для такого нужен текст из разряда "Введите планы на сегодня, каждый с новой строки" и ты вводишь:
Купить хлеба
Позвонить маме
Покушать
Покорить мир
Задачи записываются в БД с маркерами времени, выполнения, текстом самой задачи

--------СЛЕЖЕНИЕ ЗА ПРОГРЕССОМ------

Чтобы быть в курсе, опция выведения задач должна выводить их сообщением все, разделенные по временным промежуткам, например (от балды пишу сейчас): 
СЕГОДНЯ
Выполнить лабу по программированию
НА НЕДЕЛЕ
Подать документы на визу на Марс
В ЭТОМ МЕСЯЦЕ
Полететь на Марс
Пожать руку Илону Маску

---------ВЫПОЛНЕНИЕ--------

Ну и конечно, выполение. В конце каждого отчетного периода (день, неделя, месяц, год - см. выше) ты получаешь напоминание/вопрос "Удалось ли выполнить поставленные задачи?" и отмечаешь.

Также нужен сценарий и произвольного действия в таком духе: выполнила задачу раньше времени или она больше не актуальна - для этого опции удаления задач и произвольная отметка задач выполненными.
