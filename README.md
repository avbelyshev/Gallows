**Игра "Виселица".**

Принцип игры

Игрок отгадывает одно из слов считанных из файла '/data/words.txt' (в этот файл можно добавить свои слова), вводя по одной букве за ход. Слово отображается в виде нескольких пар нижних подчеркиваний, соответствующих количеству букв. Отгаданные буквы отображаются на своих местах в загаданном слове, вместо нижних подчеркиваний. В начале игры рисуется пустая виселица.

Игрок вводит буквы до тех пор пока не отгадает слово - победа, либо не превысит максимальное количество ошибок - поражение (в данной игре 7). За каждую не верную букву добавляется элемент к висилице (голова, шея, туловище, 2 руки и 2 ноги, веревка).

Игра написана на языке Ruby. Запускаем из терминала - \dir>`ruby gallows.rb`
