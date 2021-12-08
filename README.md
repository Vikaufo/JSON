# JSON
1. **Cоздать внешний репозиторий c названием JSON.**

Зайти в раздел Repositories на Github. Нажать "NEW". Создать репозиторий "JSON"

2. **Клонировать репозиторий JSON на локальный компьютер.**

Перейти в репозиторий "JSON", вкладка "Code", скопировать HTTPS. В терминале вызвать команду git clone https://github.com/Vikaufo/JSON.git

 3. **Внутри локального JSON создать файл “new.json”.**

cd JSON 

touch new.json

 4. **Добавить файл под гит.**
 
git add new.json

 5. **Закоммитить файл.**
 
git commit -m "Add new file"

 6. **Отправить файл на внешний GitHub репозиторий.**
 
git push

 7. **Отредактировать содержание файла “new.json” - написать информацию о себе. Всё написать в формате JSON.**
 
vim new.json (i - инфа о себе) esc :wq

 8. **Отправить изменения на внешний репозиторий.**
 
git add .

git commit -m "Modifided file"

git push

 9. **Создать файл preferences.json**
 
touch preferences.json

 10. **В файл preferences.json добавить информацию о своих предпочтениях в формате JSON.**
 
vim preferences.json (i - предпочтения) esc :wq

 11. **Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON**
 
touch skills.json

vim (i - навыки) esc :wq

 12. **Отправить сразу 2 файла на внешний репозиторий.**
 
git add . && git commit -m "Add preferences and skills" 

git push

 13. **На веб интерфейсе создать файл bug_report.json.**
 
Вкладка "Add file - Create new file". Указать комментарий.

 14. **На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.**

Нажать "Edit this file"

 15. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
 
Нажать "Commit changes"

 16. **Синхронизировать внешний и локальный репозиторий JSON**
 
git pull
