# From-paycheck-to-paycheck Седьмая программа: «От зарплаты до зарплаты»
Седьмая программа: «От зарплаты до зарплаты»
Босс полюбил калькулятор миль и только поэтому доверил вам автоматизировать самое сокровенное — бухгалтерские расчёты!

Ему понадобилось нанять несколько новых сотрудников, так как местных бездельников уже не хватает. Бухгалтерия выделила бюджет на зарплаты, но он включает налоги, а в вакансии зарплату нужно указать без налогов. Впрочем, вот техническое задание:

Мяу! Мне нужна программа, которая от «грязной» зарплаты (зарплата до вычета налогов) посчитает примерную «чистую» зарплату (которая выдаётся на лапы).

Оформи программу в виде функции calculateSalary c одним параметром — величиной грязной зарплаты. Функция должна возвращать чистую зарплату.

Большая точность мне не нужна, просто считаем, что 35% величины грязной зарплаты составляют налоги, а если грязная зарплата больше или равна 100 тысячам, то налоги составляют уже 45%.

В зависимости от того, как вы будете считать проценты, итоговый результат может иметь дробную часть. Используйте Math.round для округления результатов вычисления.

Эту программу будет тестировать сам Кекс. Он будет вызывать вашу функцию (вы же напишете функцию?) с разными аргументами и проверять результат. Чтобы позвать босса для проверки программы, нажмите кнопку Заказчик, принимай программу! в консоли.
