# HOMEWORK GIT .  TXT

1. **Создать внешний репозиторий c названием TXT.**   
 - Заходим на github.com  в свой аккаунт. 
 - Переходим на вкладку "Repositories" и создаем новый репозиторий c названием TXT. 
2. **Клонировать репозиторий TXT на локальный компьютер.** 
 - Нажимаем вкладку "Code" и копируем ссылку. 
 - Переходим в  = git bash 
 - В разделе создаем папку =  mkdir 2homework
 - Заходим в папку = cd 2homework
 - git clone https://github.com/Pitsenko/TXT.git 
3. **Внутри локального TXT создать файл “new.txt”.**  
 - touch new.txt
4. **Добавить файл под гит.**  
 - git add new.txt
5. **Закоммитить файл.**  
 - git commit -m "Add 1 txt file"
6. **Отправить файл на внешний GitHub репозиторий.**  
 - git push 
7. **Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.**  
 - vim new.txt ( Пишем данные и выходим с файла сохраняя его "ESQ -> :WQ -> Enter" )
8. **Отправить изменения на внешний репозиторий.**  
 - git add new.txt 
 - git commit -am "change file new.txt"
 - git push 
9. **Создать файл preferences.txt**  
 - touch preferences.txt
10. **В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.**  
 - vim preferences.txt (Заполняем текстовый файл и сохраняем его "ESQ -> :WQ -> Enter")
11. **Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT.**  
 - vim preferences.txt (Заполняем текстовый файл и сохраняем его "ESQ -> :WQ -> Enter")
12. **Сделать коммит в одну строку.**   
 - git add . | git commit -m "Add 2 files with comment"
13. **Отправить сразу 2 файла на внешний репозиторий.**  
 - git push
14. **На веб интерфейсе создать файл bug_report.txt.**  
 - Заходим на свою страницу в github.com -> Repositories -> TXT -> Add file -> Create new file -> Имя файла bug_report.txt 
15. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.**  
 - Edit repository details -> save changes
16. **На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.**  
 - Нажимаем на bug_report.txt ->  edit this file ->  Пишем  баг репорт. 
17. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.**  
 - Edit repository details -> save changes
18. **Синхронизировать внешний и локальный репозиторий TXT**    
 - переходим в git bash
 - git pull 
