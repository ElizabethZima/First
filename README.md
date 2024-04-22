# First

Что делает программа: Она принимает строку с математическим выражением и разбивает ее на отдельные кусочки - токены.
Как это работает:
Если встречается число (например, 123), программа понимает, что это число и добавляет его в список токенов.
Если встречается знак операции (например, + или *), программа понимает, что это знак операции и также добавляет его в список токенов.
Если программа видит что-то другое, например, букву или специальный символ, она не понимает, что с этим делать, поэтому она помечает это как "неизвестный токен".


После добавления max и sqr

Теперь программа также может распознавать функции, такие как "max" и "sqr". Например, если вы введете "max(3, 5)", она поймет, что это вызов функции "max" с аргументами 3 и 5, и добавит это в список токенов.
Если программа видит что-то, чего она не знает, она все равно помечает это как "неизвестный токен".
