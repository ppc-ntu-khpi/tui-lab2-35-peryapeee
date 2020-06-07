[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=2792269&assignment_repo_type=AssignmentRepo)
# Lab 2

## Завдання (на "п'ять")
1. Завантажте необхідні jar-файли - [jline](https://repo1.maven.org/maven2/org/jline/jline/3.10.0/jline-3.10.0.jar), [jansi](http://repo1.maven.org/maven2/org/fusesource/jansi/jansi/1.17.1/jansi-1.17.1.jar), [MyBank](https://github.com/liketaurus/TUI-Labs/blob/master/jars/MyBank.jar). Останній файл містить всі класи (*Bank, Customer, Account* та ін.) з наших попередніх лаб. *УВАГА! Також ви можете взяти всі три файли прямо з [цього ж репозиторію](https://github.com/liketaurus/TUI-Labs/blob/master/jars)*.
2. Створіть в Netbeans новий проект з назвою TUIdemo (або використайте проект, створений в ході виконання попередньої роботи). *УВАГА! Чекбокс *Create Main Class* треба **очистити** (**не створювати виконуваний клас**)!*
3. Додайте до проекту всі завантажені вами бібліотеки - правою кнопкой на проекті, обрати *Properties*, потім у дереві категорій обрати *Libraries* (другий пункт зверху), натиснути у правій частині вікна кнопку *Add JAR/Folder*, обрати jar-файли, завантажені у п. 1, натиснути *Ok*
4. Додайте до проекту файл **[CLIdemo.java](https://github.com/liketaurus/TUI-Labs/blob/master/Lab%202%20-%20CLI/CLIdemo.java)** з цього репозиторію
5. Вивчіть вихідний код у файлі, впевніться, що ви розумієте як він має працювати
6. Відкрийте консоль (під Linux - *емулятор терміналу*, під Windows - *PowerShell*), перейдіть до теки проекту (під Linux - ```cd NetBeansProjects/TUIDemo/dist```, під Windows - ```cd .\Documents\NetBeansProjects\TUIdemo\dist```). Запустіть проект (```java -jar .\TUIdemo.jar```) - ви маєте побачити запрошення (```bank>```). Натисніть **TAB** аби переглянути доступні команди. Натисніть <kbd>h</kbd> <kbd>TAB</kbd> <kbd>ENTER</kbd> аби переглянути довідку, <kbd>cus</kbd> <kbd>TAB</kbd> <kbd>s</kbd> <kbd>ENTER</kbd> аби переглянути список клієнтів банку, <kbd>Up</kbd> <kbd>Backspace</kbd> <kbd>Space</kbd> <kbd>1</kbd> <kbd>ENTER</kbd> аби переглянути інформацію про клієнта з номером 1, <kbd>Up</kbd> <kbd>2</kbd> <kbd>ENTER</kbd> аби впевнитись, що програма коректно обробляє неправильний номер клієнта, <kbd>e</kbd> <kbd>TAB</kbd> <kbd>ENTER</kbd> для виходу.Продемонстрируйте результат викладачеві.
7. Додайте ще одну команду - **report**, яка має виводити звіт за клієнтами такого ж виду, як у роботі номер 8 (див. CustomerReport).
8. Запустіть проект, впевніться, що все працює як очікувалось. Продемонстрируйте результат викладачеві.
## Результат
![](CLIdemo.png)
