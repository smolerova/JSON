# JSON
Git Homework 
 4. Создать внешний репозиторий c названием JSON. 
 5. Клонировать репозиторий JSON на локальный компьютер.
 git clone https://github.com/smolerova/JSON.git
 6. Внутри локального JSON создать файл “new.json”.
 touch “new.json”
 7. Добавить файл под гит. 
  git add new.json
 8. Закоммитить файл.
 git commit -m "add new file"
 9. Отправить файл на внешний GitHub репозиторий.
 git push
 10. Отредактировать содержимое файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

{
    "person": {
        "name": "Natallia",
        "lastName": "Smolearova",
        "middleName": "Vasilevna",
        "age": 32
    },
    "pet": 1,
    "salary": 500
}

 11. Отправить изменения на внешний репозиторий.
 git add new.json
 git commit -m "add data to the new.json"
 git push
 12. Создать файл preferences.json 
touch  “preferences.json”
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
{
    "favourites": {
        "favoriteMovie": "The Shawshank Redemption",
        "favoriteSeries": "Criminal Minds",
        "favoriteFood": "Grilled Meat",
        "favoriteSeason": "Summer"
    },
    "wishList": {
        "Country": "Portugal"
    }
}


 14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
touch  “skills.json”

{
    "skills": [
        "Bash",
        "Git",
        "Postman",
        "DevTools",
        "VPN",
        "Mobile Testing",
        "Charles",
        "SQL"
    ]
}

 15. Отправить сразу 2 файла на внешний репозиторий.
 git add .

 16. На веб интерфейсе создать файл bug_report.json.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

{
  "ID":"12",

  "Summary":"The Familyapplication allows the input of letters in the field Birth Day",

  "Severity":"Major",

  " StepsToReproduce":[

     "Start the Family application",

     "Click on Husband tab",

     "Click on New button",

     "Try to input letters in the field Birth Day"

  ],

  "ExpectedResult":"Letters are not entered in the field Birth Day",

  "Actual Result":"The field Birth Day allows input of letters"

}


 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 20. Синхронизировать внешний и локальный репозиторий JSON 
git fetch
git pull
