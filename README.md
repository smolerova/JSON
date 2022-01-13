JSON

Создать внешний репозиторий c названием JSON.
Клонировать репозиторий JSON на локальный компьютер.
git clone https://github.com/smolerova/JSON.git
Внутри локального JSON создать файл “new.json”.
touch “new.json”
Добавить файл под гит.
git add new.json
Закоммитить файл.
git commit -m “add new file”
Отправить файл на внешний GitHub репозиторий.
git push
Отредактировать содержимое файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
{
“person”: {
“name”: “Natallia”,
“lastName”: “Smolearova”,
“middleName”: “Vasilevna”,
“age”: 32
},
“pet”: 1,
“salary”: 500
}

Отправить изменения на внешний репозиторий.
git add new.json
git commit -m “add data to the new.json”
git push
Создать файл preferences.json
touch “preferences.json”
В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
{
“favourites”: {
“favoriteMovie”: “The Shawshank Redemption”,
“favoriteSeries”: “Criminal Minds”,
“favoriteFood”: “Grilled Meat”,
“favoriteSeason”: “Summer”
},
“wishList”: {
“Country”: “Portugal”
}
}
Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
touch “skills.json”
{
“skills”: [
“Bash”,
“Git”,
“Postman”,
“DevTools”,
“VPN”,
“Mobile Testing”,
“Charles”,
“SQL”
]
}

Отправить сразу 2 файла на внешний репозиторий.
git add .

На веб интерфейсе создать файл bug_report.json.

Сделать Commit changes (сохранить) изменения на веб интерфейсе.
На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
{

“ID”:”12”,

“Summary”:”The Familyapplication allows the input of letters in the field Birth Day”,

“Severity”:”Major”,

“ StepsToReproduce”:[

 "Start the Family application",
 "Click on Husband tab",
 "Click on New button",
 "Try to input letters in the field Birth Day"
],

“ExpectedResult”:”Letters are not entered in the field Birth Day”,

“Actual Result”:”The field Birth Day allows input of letters”

}

Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Синхронизировать внешний и локальный репозиторий JSON
git fetch
git pull
