# QA_GROUP30_KSENDZOV
QA CLASSES
Задание 1

Terminal commands

1) Посмотреть где я            ```pwd``` (расшифровывается Print Working Directory)
2) Создать папку               ```mkdir E:/QA/classes.homework/01```
3) Зайти в папку               ```cd E:/QA/classes.homework/01```
4) Создать 3 папки             ```mkdir phobos deimos mars```
5) Зайти в любоую папку        ```cd mars```
6) Создать 5 файлов (3 txt, 2 json)     ```touch phobos.txt deimos.txt mars.txt io.json callisto.json```
7) Создать 3 папки                     ```mkdir evropa ganimed leda```
8) Вывести список содержимого папки    ```ls -la```     
9) Открыть любой txt файл                    ```vim mars.txt```
10) Написать туда что-нибудь, любой текст.   ```нажать клавишу "i" ввести текст```
                                ```Mars is the fourth planet from the Sun```
                                ```and the second-smallest planet in the Solar System```
                                ```being larger than only Mercury```
11) сохранить и выйти.                 ```"esc" ввести  ":wq"```
12) Выйти из папки на уровень выше            ```cd ..```
13) переместить любые 2 файла, которые вы создали, в любую другую папку.   
```mv deimos.txt mars.txt leda/```
                                                                          
14) скопировать любые 2 файла, которые вы создали, в любую другую папку.   ```cp deimos.txt mars.txt /e/qa/classes.homework/01/mars/evropa/``` 
                                                                           
15) Найти файл по имени         ```find . -name mars.txt```
16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает.  ```tail -f mars.txt``` 
                                                                                       
17) вывести несколько первых строк из текстового файла       ```head -2 mars.txt```
18) вывести несколько последних строк из текстового файла    ```tail -2 mars.txt```
19) просмотреть содержимое длинного файла (команда less) изучите как она работает.   ```less name_file```
20) вывести дату и время    ```date +"%D %T"```
---

Дополнительное задание со звездочкой:


Отправить http запрос на сервер. 

curl http://162.55.220.72:5005/terminal-hw-request

приходит ещё одно задание, в этот запрос я вставляю свои имя и возраст

curl "http://162.55.220.72:5005/get_method?name=(EVGENII)&age=(41)"
приходит короткий ответ 
  "(EVGENII)",
  "(41)"
