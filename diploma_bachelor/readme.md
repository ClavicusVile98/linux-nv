Принцип работы системы таков: при проходе определенного количества воды через водосчетчик, шина GPIO получает сигнал, который представляет собой значение, сохраняемое в виде необработанного числа с меткой времени в соответствующем файле, который передается через Wi-Fi или Ethernet по протоколу HTTP (методом POST) в конечную точку API, откуда данные проходят через синтаксический анализатор и записываются в базу данных. Раз в месяц показания с помощью PHP-скрипта отправляются во внешний мир (на почту управляющей компании или на сайт гос. услуг).

Основной файл - [project.c](project.c)