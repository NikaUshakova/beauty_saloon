# beauty_saloon
==============================Инсталляция====================================
1. Разархивируйте архив "Салон красоты.zip"
2. Для работы с приложением необходимо наличие на ПК среды для работы с базами данных
3. При отсутствии нужно установить MySql WorkBench: https://dev.mysql.com/downloads/workbench/ либо с папки INSTALL
4. После установки нужно открыть MySQL Installer - Community и установить MySQL WorkBench и MySQL Server
5. При установке используется стандартный пароль root
6. После установки, нужно запустить  MySQL WorkBench и зайти на сервер, введя пароль
7. Затем необходимо выбрать вкладку Server -> Data Import, выбрать Import from Self-Contained File и указать путь к salon_krasoti_dataBase.sql, который находится в папке PRG. Нажать Start import
8. После того, как появилась база данных на вашем ПК, можно запусить программу, которую можно взять в папке EXE
9. Необходимо изменить в коде пароль к серверу БД, чтобы соединение было корректно.


===================================Логины и пароли============================
		Пользователем с доступом в панель администратора
		login: Admin
		password: 12345678
