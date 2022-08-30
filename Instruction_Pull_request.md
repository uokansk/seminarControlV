# Pull request 
## последовательность
1. Зайти в нужный репозиторий
![Зайти в нужный репозиторий](/images/image1.jpg)
2. выбрать Fork
![выбрать Fork](/images/image2.jpg)
3. Создать новый Fork введя имя репозитория и жмем кнопку Creat fork. Чтобы скопировать все ветки, убираем галочку "Copy the main branch only"
![Создать новый Fork](/images/image3.jpg)
4. таким образом перебрасываем удаленный репозиторий в свой
![удаленный репозиторий в свой](/images/image4.jpg)
5. копируем ссылку 
![копируем ссылку ](/images/image5.jpg)
6. переходим в VScode
7. открываем нужную папку в VScode "файл - Открыть папку"
![Открыть папку](/images/image6.jpg)
8. в терминале набираем git status и если вышло "fatal: not a git repository (or any of the parent directories): .git" - то клонируем в эту папку иначе нужно перейти ввы с помощью команды "cd .."
9. В терминале набираем git clone и скопированную ссылку из п.5
![git clone](/images/image7.jpg)
10. В клонированном репозитории создаем новую ветку с помощью команды git checkout -b new_branch далее вводим команду git branch и проверяем в какой ветке мы находимся
![git clone](/images/image8.jpg)
11. вносим необходимые изменения и в терминале вводим команду git commit -a -m
![вносим изменения](/images/image9.jpg)
12. вводим команду git push и получаем ошибку с предложением ввести другую команду
![git push](/images/image10.jpg)
13. вводим предложенную команду и видим полученные изменения в удаленном репозитории
![git push](/images/image11.jpg)

![git push](/images/image12.jpg)
14. выбираем нужную ветку, выбираем Contribute и Open pull request
![нужную ветку](/images/image13.jpg)
15. жмем Create pull request
![Create pull request](/images/image14.jpg)
