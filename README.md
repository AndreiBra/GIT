# GITHUB
1. Создайте текстоовый файл как в первом ДЗ по Terminal.
2. Сценарий перенесите в этот файл.
3. На против каждого действия - напишите команду в GitBash

___
# JSON
___

4. Создать внешний репозиторий c названием JSON.
```bash
Repositories --> New --> Repos Name:JSON --> Check "Add a README file" --> Press "Create repository"
```

5. Клонировать репозиторий JSON на локальный компьютер.

```bash
git clone <repository HTTPS>
```
6. Внутри локального JSON создать файл “new.json”.

```bash
touch new.json
```
7. Добавить файл под гит.

```bash
git add new.json
```
8. Закоммитить файл.

```bash
git commit -m "the first file json"
```
9. Отправить файл на внешний GitHub репозиторий.
```bash
git push
```

10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в    формате JSON.

```bash
vim new.json` ---> input data ---> esc ---> enter ":wq"
```
```bash
#"for example"
{
	"Full Name": "Bragin Andrei Aleksandrovich" ,
	"Age": 47 ,
	"Number of pets": 1 ,
	"Salary": "1000$"
}
```
11. Отправить изменения на внешний репозиторий.
```bash
git commit -am "add name age and etc" && git push
```

12. Создать файл preferences.json
```bash
touch preferences.json
```

13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы        посетить) в формате JSON.
```bash
vim preferences.json ---> insert data ---> esc ---> enter ":wq"
```
```bash
#"for example"
{
	"favorite_movie": " The Predator",
	"favorite_series": "House M.D.",
	"favorite_food": "Basmati rice",
	"favorite_time_of_the_year": "summer",
	"country_you_would_like_to_visit": "The Hawaiian Islands US"
}
```

14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

```bash
touch skills.json
```
```bash
#"for example"
{
	"Skill1":"Testing Theory, SDLC, STLC",
	"Skill2":"Clien-server",
	"Skill3":"HTTP-methods",
	"Skill4":"HTTP status-codes",
	"Skill5":"HTTP resp, req stracture",
	"Skill6":"JSON, XML. Structure",
	"Skill7":"API Postman (JS, autotest API).",
	"Skill8":"Logs from servers",
	"Skill9":"Charles and Fiddler.",
	"Skill10":"Dev Tools(Google Chrome, FireFox).",
	"Skill11":"VPN.",
	"Skill12":"Mobile testing",
	"Skill13":"IOS, android guidelines",
	"Skill14":"XCode.",
	"Skill15":"Android Studio.",
	"Skill16":"ADB",
	"Skill17":"iOS Android proxy, vpn",
	"Skill18":"Mobile trafic sniffing. Charles and Fiddler iOS, Android.",
	"Skill19":"terminal Linux",
	"Skill20":"bash scripting",
	"Skill21":"Remote servers access",
	"Skill22":"SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).",
	"Skill23":"DB Postgres.",
	"Skill24":"Redis",
	"Skill25":"Load testing Jmeter.",
	"Skill26":"Scrum.",
	"Skill27":"Python."
}
or 
{
	"skills":[
	"Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.",
	"Что такое клиент-серверная архитектура.",
	"HTTP Методы запросов на сервер.",
	"Коды ответов HTTP сервера.",
	"Структуры HTTP запросов и ответов.",
	"Что такое JSON, XML. Их структура.",
	"Тестирование API через Postman (JS, автотесты API).",
	"Снятие и чтение логов c внешнего сервера.",
	"Снифинг http web трафика через Charles и Fiddler.",
	"Dev Tools веб браузеров (Google Chrome, FireFox).",
	"VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)",
	"Мобильное тестирование.",
	"Особенность iOS, Android, гайдлайны.",
	"Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)",
	"Сборка Android приложений на Android Studio.",
	"ADB (управление андройд девайсами).",
	"Настройка прокси и vpn на iOS и Android.",
	"Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.",
	"Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
	"Основы bash скриптинг, автоматизация рутинных задач на сервере.",
	"Доступ к удалённым серверам.",
	"Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).",
	"База данных Postgres (установка, настройка и использование).",
	"Нереляционная база данных Redis (установка, настройка и использование).",
	"Нагрузочное тестирование в Jmeter.",
	"Методология разработки Scrum.",
	"Python. (Изучение основ. Создание клиент серверного приложения)"
	]
}
```
15. Отправить сразу 2 файла на внешний репозиторий.
```bash
git add . && git commit -m add 2 file" && git push
```

16. На веб интерфейсе создать файл bug_report.json.

```bash
Add file --> Create new file --> Name: bug_report.json
```
```bash
#"for example"
{
  "Environment":"<Description of environment>",
  "ID":1 ,
  "Summary":"<What?Where?Why?>",
  "STR":{
          "Step1":"<step description>",
          "Step2":"<step description>"          
        },
        "version","<Number version>",
  "Severity":"<Can be categorized into four parts>",
  "Priority":"<Can be categorized into three parts>",
  "Expected Result":"<Description of expected result>",
  "Actual Result":"<Description of actual result>",
  "Attachments":"<link>"
}
```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit New File
```

18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
```bash
 Choose bug_report.json --> Edit this file
```

19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit changes
```

20. Синхронизировать внешний и локальный репозиторий JSON
```bash
git pull
```
___
# XML
___
 21. Создать внешний репозиторий c названием XML.    
```bash
На вэбе Repositories --> New --> Repos Name:XML --> Check "Add a README file" --> Press "Create repository"
```
 22. Клонировать репозиторий XML на локальный компьютер.
```bash
git clone <repository_linkHTTPS>
```
 23. Внутри локального XML создать файл “new.xml”.
```bash
touch new.xml
```
 24. Добавить файл под гит.
```bash
git add new.xml
```
 25. Закоммитить файл.
```bash
git commit -m "add new file"
```
 26. Отправить файл на внешний GitHub репозиторий.
```bash
git push
```
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```bash
vim new.xml
```
```bash
#for exapmle
<?xml version="1.0" encoding="utf-8"?>
<information_about_yourself>
	<full_name> Bragin Andrei Aleksandrovich</full_name>
	<age>47</age>
	<number_of_pets>1</number_of_pets>
	<future_desired_salary>1000</future_desired_salary>
</information_about_yourself>
```
 28. Отправить изменения на внешний репозиторий.
```bash
git commit -am "add info in fale "` --> git push
```
 29. Создать файл preferences.xml
```bash
touch preferences.xml
```
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```bash
vim preferences.xml
```
```bash
#for example
<?xml version="1.0" encoding="utf-8"?>
<my_preferences>
		<favorite_movie>Forrest Gump</favorite_movie>
		<favorite_series>Breaking Bad</favorite_series>
		<favorite_food>fruits</favorite_food>
		<favorite_time_of_year>winter</favorite_time_of_year>
		<country_you_would_like_to_visit>Maldives</country_you_would_like_to_visit>
</my_preferences>
```
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```bash
vim skills.xml
```
```bash
#for example
<?xml version="1.0" encoding="UTF-8"?>
<Skills_I_Learn>
	<Skill1>Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC"</Skill1>
	<Skill2>Что такое клиент-серверная архитектура.</Skill2>
	<Skill3>HTTP Методы запросов на сервер.</Skill3>
	<Skill4>Коды ответов HTTP сервера.</Skill4>
	<Skill5>Структуры HTTP запросов и ответов.</Skill5>
	<Skill6>Что такое JSON, XML. Их структура.</Skill6>
	<Skill7>Тестирование API через Postman (JS, автотесты API).</Skill7>
	<Skill8>Снятие и чтение логов c внешнего сервера.</Skill8>
	<Skill9>Снифинг http web трафика через Charles и Fiddler.</Skill9>
	<Skill10>Dev Tools веб браузеров (Google Chrome, FireFox).</Skill10>
	<Skill11>VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</Skill11>
	<Skill12>Мобильное тестирование.</Skill12>
	<Skill13>Особенность iOS, Android, гайдлайны.</Skill13>
	<Skill14>Сборка iOS приложений на XCode.</Skill14>
	<Skill15>Сборка Android приложений на Android Studio.</Skill15>
	<Skill16>ADB (управление андройд девайсами).</Skill16>
	<Skill17>Настройка прокси и vpn на iOS и Android.</Skill17>
	<Skill18>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.</Skill18>
	<Skill19>Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</Skill19>
	<Skill20>Основы bash скриптинг, автоматизация рутинных задач на сервере.</Skill20>
	<Skill21>Доступ к удалённым серверам.</Skill21>
	<Skill22>Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).</Skill22>
	<Skill23>База данных Postgres (установка, настройка и использование).</Skill23>
	<Skill24>Нереляционная база данных Redis (установка, настройка и использование).</Skill24>
	<Skill25>Нагрузочное тестирование в Jmeter.</Skill25>
	<Skill26>Методология разработки Scrum</Skill26>
	<Skill27>Python. (Изучение основ. Создание клиент серверного приложения)</Skill27>
</Skills_I_Learn>
```
 32. Сделать коммит в одну строку.
```bash
git add . && git commit -m "add skills"
```
 33. Отправить сразу 2 файла на внешний репозиторий.
```bash
git push
```
 34. На веб интерфейсе создать файл bug_report.xml.
```bash
Add file --> Create new file --> Name: bug_report.xml
```
```bash
#for example
<?xml version="1.0" encoding="utf-8"?>
<bug_report_structure>
    <summary>краткое описание</summary>
    <project>проект</project>
    <Environment>окружение</Environment>
    <ID>BUG_ID</ID>
    <component>компонент приложения</component>
    <version>номер версии</version>
    <severity>серьезность</severity>
    <priority>приоритет</priority>
    <steps_to_reproduce>шаги воспроизведения</steps_to_reproduce>
    <actual_result>фактический результат</actual_result>
    <expected_result>ожидаемый результат</expected_result>
    <additional_information>дополнения</additional_information>
</bug_report_structure>
```
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit New File
```
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```bash
Choose bug_report.xml --> Edit this file
```
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit changes
```
 38. Синхронизировать внешний и локальный репозиторий XML
```bash
git pull
```

___

# TXT
___

 1. Создать внешний репозиторий c названием TXT.
```bash
На вэбе Repositories --> New --> Repos Name:TXT --> Check "Add a README file" --> Press "Create repository"
```
 2. Клонировать репозиторий TXT на локальный компьютер.
```bash
git clone <HTTPS repo>
```
 3. Внутри локального TXT создать файл “new.txt”.
```bash
touch new.txt

```
 4. Добавить файл под гит.
```bash
git add new.txt
```
 5. Закоммитить файл.
```bash
git commit -m "add txt file"
```
 6. Отправить файл на внешний GitHub репозиторий.
```bash
git push
```
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
```bash
vim new.txt
```
```bash
1. full nsme: Bragin Andrei Aleksandrovich.
2. Age: 47.
3. number of pets: 1.
4. future desired salary: 1000$
```
 8. Отправить изменения на внешний репозиторий.
```bash
git commit -am "add name in txt file"` --> `git push
```
 9. Создать файл preferences.txt
```bash
touch preferences.txt
```
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```bash
vim preferences.txt
```
```bash
My preferences:

1)favorite moovies: "The Green Mile";
2)favorite serial: The Office;
3)favorite food: Vegetables;
4)favorite time of year: spring;
5)country i want to visit: Switzerland
```
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
```bash
vim skills.txt
```
```bash
1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
2. Что такое клиент-серверная архитектура.
3. HTTP Методы запросов на сервер.
4. Коды ответов HTTP сервера.
5. Структуры HTTP запросов и ответов.
6. Что такое JSON, XML. Их структура.
7. Тестирование API через Postman (JS, автотесты API).
8. Снятие и чтение логов c внешнего сервера.
9. Снифинг http web трафика через Charles и Fiddler.
10. Dev Tools веб браузеров (Google Chrome, FireFox).
11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
12. Мобильное тестирование.
13. Особенность iOS, Android, гайдлайны.
14. Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)
15. Сборка Android приложений на Android Studio.
16. ADB (управление андройд девайсами).
17. Настройка прокси и vpn на iOS и Android.
18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.
19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
20. Основы bash скриптинг, автоматизация рутинных задач на сервере.
21. Доступ к удалённым серверам.
22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
23. База данных Postgres (установка, настройка и использование).
24. Нереляционная база данных Redis (установка, настройка и использование).
25. Нагрузочное тестирование в Jmeter.
26. Методология разработки Scrum.
27. Python. (Изучение основ. Создание клиент серверного приложения)
```
 12. Сделать коммит в одну строку.
```bash
git add --all && git commit -m "comment"
```
 13. Отправить сразу 2 файла на внешний репозиторий.
```bash
git push
```
 14. На веб интерфейсе создать файл bug_report.txt.
```bash
Add file --> Create new file --> Name: bug_report.txt
```
```bash
Environment: <your environment>
ID: 1
Summury: <What? Where? Why?>
Steps to reproduce: 1.
                    2.
                    3.
                     ....
Expected Result: 1. ...
                 2. ...
                 3. ...
Actual Result: 1. ...
               2. ...
               3. ...
Attachments: <img/video>
```
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit New File
```
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
```bash
Choose bug_report.txt --> Edit this file
```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit changes
```
 18. Синхронизировать внешний и локальный репозиторий TXT
```bash
git pull
```
