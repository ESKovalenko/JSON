# JSON
## Homework

1. Создать внешний репозиторий c названием JSON.  `Create a new repository`
2. Клонировать репозиторий JSON на локальный компьютер. `git clone https://github.com/ESKovalenko/JSON.git`
3. Внутри локального JSON создать файл “new.json”. `touch new.json`
4. Добавить файл под гит. `git add new.json`
5. Закоммитить файл.  `git commit -m “new.json”`
6. Отправить файл на внешний GitHub репозиторий. `git push`
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
`cat > new.json`

`{`

  `"full_name": "Kovalenko Ekaterina Sergeevna",`
  
  `"age": 27,`
  
  `"pets": 2,`
  
  `"salary": 100` 
  
`}`

 8. Отправить изменения на внешний репозиторий.
`git status`

`git add .`

`git commit -m "new.json"`

`git push`

 10. Создать файл preferences.json `touch preferences.json`
 11. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

`cat > preferences. json`

`{`

  `"favourite movie": "A Dog's Purpose",`
  
 `"favourite  series” : “Friends",`
 
  `"favourite food":  “Sushi”,`
  
  `"Country": "Australia”`
  
`}`

 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

`cat > skills.json`

`{`

 ` "skills": [`
 
   `"Terminal",`
     `"Postman",`
     `"SQL",`
    `"Charles",`
   `"Fiddler",`
    `"Android Studio",`
    `"Jmeter",`
    `"Scrum"` 
    
 ` ]`
 
`}`

 12. Отправить сразу 2 файла на внешний репозиторий.
 
 `git add preferences.json skills.json`
     
`git commit -m “Preferences and Skills”`

`git push`

 14. На веб интерфейсе создать файл bug_report.json `Create new file`
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. `Commit changes`

 16. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

`{`
  `"bug_report": {`
  
    `"title": "Bug Title",`
    
    `"description": "Bug Description",`
    
    `"steps_to_reproduce": "Steps to Reproduce",`
    
    `"expected_result": "Expected Result",`
    
    `"actual_result": "Actual Result",`
    
    `"severity": "Severity Level",`
    
    `"priority": "Priority",`
    
    `"assigned_to": "Assigned To",`
    
    `"reported_by": "Reported By",`
    
    `"attachments": "attachment1.png",` 
    ]
 `}`

 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе. `Commit changes`

 17. Синхронизировать внешний и локальный репозиторий JSON `git pull`


