# Site with auth and reg + database
# Used MySQL

Чтобы на меню отображались странички, в базу надо добавить:
INSERT INTO `pages`(`url`, `name`, `title`, `secure`, `alias`) VALUES ('/','Главная','Наш супер-сайт!','0','/index.php');
INSERT INTO `pages`(`url`, `name`, `title`, `secure`, `alias`) VALUES ('/second.php','Вторая страница','Страничка супер-сайта!','0','');
INSERT INTO `pages`(`url`, `name`, `title`, `secure`, `alias`) VALUES ('/secret.php','Личный кабинет','Личный кабинет пользователия','1','');



url	VARCHAR(255)
name VARCHAR(255)
title	VARCHAR(255)
secure	TINYINT(1)
alias VARCHAR(255)



login	VARCHAR(255)
password	VARCHAR(255)
name VARCHAR(255)
