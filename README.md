# Site with auth and reg + database
# Used MySQL

Чтобы на меню отображались странички, в базу надо добавить:
/ Главная Наш супер-сайт! 0 /index.php
/second.php Вторая страница Вторая страница супер-сайта! 0 0
/secret.php Личный кабинет Личный кабинет пользователя 1 0



url	VARCHAR(255)
name VARCHAR(255)
title	VARCHAR(255)
secure	TINYINT(1)
alias VARCHAR(255)



login	VARCHAR(255)
password	VARCHAR(255)
name VARCHAR(255)
