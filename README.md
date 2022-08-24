## Инструкция по работе с Git ##

### На основе семинара Николая Мищенкова ###


*Контроль версий (контроль исходного кода) — практика, которая позволяет отслеживать
изменения исходного кода и управлять ими.*


Для работы с Git необходимо установить на локальный компьютер Git по ссылке https://git-scm.com/download

а также Visual Studio Code по ссылке https://code.visualstudio.com/download

бесплатный тренажер по Git https://learngitbranching.js.org/

1. Создать папку на ПК паример seminarControlV
2. Запустить VS code
3. Открыть папку в VS code
4. Открыть терминал

## Основные команды Git ##

* git --version -возвращает версию программы
* git init -инициализировать программу в выбранной папке
* git add -сохранить изменения (добавить файлы. названия файла указать полностью)
* git commit -вставить коментарии
* git commit -a -m -сохраняет изменения и вставляет коментарии
* git diff -проссмотреть изменения
* git log -журнал изменений, список всех комментарий
* git chekout -переходить от одной версии файлов к другой
* git checkout master -переходна главную ветку
* git status -отображает состояние рабочего каталога и раздела проиндексированных ФАЙЛОВ V2
* git branch -создает новую ветку

![а теперь картинка](/images/space.jpg)

сообщение для task3 v2
            
## Команды из второго семинара

* git branch branch_name - создает новую ветку
* git checkout branch_name -переходит на указанную ветку
* git merge branch_name -присоеденить к существующей ветке указанную ветку
* git branch -d branch_name -удалить присоедененную ветку