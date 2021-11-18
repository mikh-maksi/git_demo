# Название бота
Описание бота.

## Список команд
/start -  
/help -  
/...  

## Предложения (для чего пользоваться вашим ботом)...

<a href = "https://innovations.kh.ua/">Харьковский инновационный портал</a>

## Как работать с GitHub
* git clone [вставить ссылку, взятую под зеленой кнопкой Code в репозитарии]    (произойдет клонирование репозитария)
* Закройте окно git bash
* Перейдите в созданную папку (имя - совпадает с именем склонированного репозитария
* Откройте git bash в этой папке
* Произведите изменения в папке
* Далее - в git bash напишите
* git add .
* git commit -m first_commit
## Как работать с Gheroku
1. Ставим Heroku cli
2. Логинемся на Heroku login
3. Создаем файлы <a href = "https://github.com/mikh-maksi/git_demo/blob/main/Procfile">Procfile</a> , <a href = "https://github.com/mikh-maksi/git_demo/blob/main/requirements.txt">requirements.txt</a>, <a href = "https://github.com/mikh-maksi/git_demo/blob/main/runtime.txt">runtime.txt</a>
4. git init
5. git add .
6. git comit -m first 
7. heroku create app_name
8. git remote -v
9. git push heroku master
10. heroku ps
11. heroku ps:scale worker=1
