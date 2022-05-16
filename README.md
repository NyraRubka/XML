# XML
21. Создать внешний репозиторий c названием XML.
 22. Клонировать репозиторий XML на локальный компьютер.-  git clone https://github.com/NyraRubka/XML.git
 23. Внутри локального XML создать файл “new.xml”. - cat > new.xml
 24. Добавить файл под гит.- git add new.xml 
 25. Закоммитить файл.-  git commit -m "new"
 26. Отправить файл на внешний GitHub репозиторий. - git push
 27. Отредактировать содержание файла “new.xml” - vim new.xml
написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
<p>"Ann Yerchenko"</p>
<p1>"27"</p1>
<p2>"0"</p2>
<p3>"2000"</p3>
 28. Отправить изменения на внешний репозиторий. - git commit -am "add info", git push
 29. Создать файл preferences.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях - vim preferences.xml
 (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
<p>"Adam"</p>
<p1>"Eva"</p1>
<p2>"fish"</p2>
<p3>"summer"</p3>
<p4>"Canada"</p4>
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
<p>"JS"</p>
<p1>"Terminal"</p1>
<p2>"Git"</p2>
<p3>"Postman"</p3>
 32. Сделать коммит в одну строку.- git commit -am "add info"
 33. Отправить сразу 2 файла на внешний репозиторий. git push
 34. На веб интерфейсе создать файл bug_report.xml.
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
<p>ID</p>
<p1>Summary</p1>
<p22>Description</p2>
<p3>Steps To Reproduce</p3>
<p4>Actual Result</p4>
<p5>Expected Result</p5>
<p6>Attachments</p6>
<p7>Priority</p7>
<p8>Severity</p8>
<p9>Status</p9>
<p10>Component/Environment</p10>
<p11>Fix Version</p11>
<p12>Assignee</p12>
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 38. Синхронизировать внешний и локальный репозиторий XML - git pull
