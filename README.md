# lab3_1
$ ss -v
ss utility, iproute2-ss111117

при компиляции ошибка 
make[1]: bison: Command not found
нужно добавить в configure проверку на наличие bison

Устанавливаем bison, запускаем make второй раз
make[1]: flex: Command not found

нужно добавить в configure проверку на наличие flex

После этого все собирается успешно
