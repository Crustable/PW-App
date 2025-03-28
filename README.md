# ChurchLifeApp  

## How to push you changes to GitHub

To make changes to a project, you need to take the following steps:
1. Create a fork of the ChurchAppLife project in your profile.
2. Clone the project to a folder on your local computer.
3. Create and enter a project brunch on your local computer.
4. Make changes to the project.
5. Add modified files, commit changes and add comments.
6. Push the project to your profile.
7. Make a Pull Request for your changes to the shared project.
8. Be happy with the work done.
***
### 1. Создать fork (вилку) проекта ChurchAppLife в своём профиле.  
Зайдите в общий проект ChristianITCommunity/ChurchLifeApp  
И нажимте кнопку Fork
  
![Alt text](/docs/images_for_readme/1.jpg?raw=true "Fork main project")   

Перейдите в созданный проект в своём профиле (ваше имя)/ChurchLifeApp  
И скопируйте адрес вашего проекта (можно нажать на значок копирования в буфер)  

![Alt text](/docs/images_for_readme/2.jpg?raw=true "Copy git adress")   

***
### 2. Склонировать проект в папку на локальном компьютере.  
Установите git на свой компьютер.  

![Alt text](/docs/images_for_readme/3.jpg?raw=true "Download Git")   

Запустите терминал для гита:  

![Alt text](/docs/images_for_readme/4.jpg?raw=true "Git in PowerShell")   

Перейдите в удобный для вас каталог коммандой "cd", например:  
`cd D:\`   
Для создания нового каталога используйте команду "mkdir", например:  
`mkdir GitFolder`  
Далее переходим в папку, в которой будет лежать наш проект:  
`cd GitFolder`  
Для клонирования проекта используем команду "git clone" и добавляем строку из буфера обмена (которую мы скопировали в нашем проекте на сайте GitHub) щёлкнув правой клавишей мышки  
`git clone https://github.com/Samasiel/ChurchLifeApp.git`  
И переходим в созданную папку:  
`cd ChurchLifeApp`  

![Alt text](/docs/images_for_readme/5.jpg?raw=true "Git clone")   

***
### 3. Создать и войти в brunch (ветку) проекта на локальном компьютере.  
Создайте новую ветку в своём локальном проекте. Для этого напишите команду: git checkout -b и в двойных кавычках вставьте название таска из Trello и короткое описание будущих изменений через нижнее подчёркивание  
`git checkout -b "M579EPlq_Improve_readme.md"`  

![Alt text](/docs/images_for_readme/61.jpg?raw=true "New brunch")  

***
### 4. Внести изменения в проект.  
***
### 5. Add (добавить) изменённые файлы, commit (зафиксировать) изменения и добавить комментарии.  
Когда вы изменили нужные файлы, надо добавить изменения в проект. Git работает не с файлами, а с изменениями. Поэтому все изменения сначала нужно добавить, а потом зафиксировать.  
Команда добавления: add. Звёздочка значит, что добавляются все файлы.  
`git add *`  
Команда фиксирования изменений: commit. Обязательно надо добавить параметр -m и в двойных скобках написать комментарий. Комментарий начинается с названия таска из Trello, и добавляется описание изменений.  
`git commit -m "M579EPlq Add instruction to readme.md, about working with git"`  
В любой момент можно посмотреть статус (или состояние) проекта, командой:  
`git status`  

![Alt text](/docs/images_for_readme/6.jpg?raw=true "Git add and commit")   

***
### 6. Push (затолкнуть) проект в свой профиль.  
Push закинет ваши файлы на GitHub. В команде после слова origin указывается бранч, который надо закинуть:  
`git push origin M579EPlq_Improve_readme.md`  
Введите имя и пароль.  

![Alt text](/docs/images_for_readme/7.jpg?raw=true "Git push")  

***
### 7. Сделать Pull Request своих изменений в общий проект.  
Зайдите на GitHub, обновите страницу. Выберите ваш новый бранч и нажмите "New pull request".  

![Alt text](/docs/images_for_readme/8.jpg?raw=true "GitHub pull request")  

Обратите внимание, что ваша ветка должна быть написана справа/снизу, а ветка куда вы пушите изменения - слева/сверху.  

![Alt text](/docs/images_for_readme/9.jpg?raw=true "GitHub pull request")  

Жмём "Create pull request"  
***
### 8. Радоваться проделанной работе.  
Сожмите руку в кулак, поднимите большой палец и скажите самому себе: "Я - МОЛОДЕЦ"))  

***
## Build project

1. Склонировать проект в папку на локальном компьютере.
2. Загрузить необходимые библиотеки с помощью npm (Node Package Manager)
3. Загрузить необходимые библиотеки с помощью bower

## 1. Склонировать проект в папку на локальном компьютере.
см. предыдущую секцию

## 2. Загрузить необходимые библиотеки с помощью npm (Node Package Manager)
В папке с проектом выполнить команду:
npm install

## 3. Загрузить необходимые библиотеки с помощью bower
В папке с проектом выполнить команду:
bower install
