# Инструкция для работы с Git краткий курс 

## Что такое _Git_
_Git_ — это распределенная система управления версиями. Это означает, что локальный клон проекта является полным репозиторием управления версиями. Полнофункциональные локальные репозитории упрощают работу в автономном режиме или в удаленном расположении. Разработчики фиксируют свою работу локально, а затем синхронизируют свою копию репозитория с копией на сервере.

## Создание локального репозитория
Работы с Git-ом может быть с разных программ, как с командной строки в самом Git так и с таких программ как Visual Studio, Visual Studio Code и др.

_Рассмотрим работу с командной строки самого Git_
* Находим, скачиваем и устанавливаем _Git_ (Если не знаете как, то оно вам не нужно) ;-) 
* Создаем папку в которой будем работать (не важно как) в Git команда _mkdir название папки_. 
* Перейдите в папку при помоши командф _cd название папки_ (Указываем как можно точнее).
* Далее вводим команду _git init_.
* Если вы все правельно сделали и не увидели в вашей командной строке ничего подозрительного, то при вводе команды _ls -a_ отобразится ( *./ ../ .git/* ) приступаем к работе

## Создание файла и работа с файлом
1. Создаем файл с помошью команды _tuch название файла.расширение_
2. Попасть в файл мы можем при помощи команды _vim название файла.расширение_
3. Файл откоется в текстовом формате, выполняем изменения или пишем что нужно или не нужно, затем все сохраняем при помощи _esc затем ставим : вводи wq и нажимаем enter_ запомните все делается на англ. раскладке клавиатуры иначе я вам не завидую.:-))

## Добавление в очередь и commit
