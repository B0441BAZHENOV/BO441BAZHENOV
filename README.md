# LR6
Лабораторная работа №6
Работу выполнил Баженов Константин Григорьевич

ПРОГРЕСС РАБОТЫ
1. Настройка клиента
https://user-images.githubusercontent.com/94684615/142628432-b59b2c96-68b8-4c80-8421-395186eece6d.png
2. Клонирование удаленного репозитория
https://user-images.githubusercontent.com/94684615/142629129-d6e36c67-3dd7-4d66-98b8-8642e882cac7.png
3. Добавление файла через интерфейс гита
https://user-images.githubusercontent.com/94684615/142629238-ba2bbaa5-4a55-4c2b-96c3-24777950a8a7.png
4. История операция для каждой ветки
https://user-images.githubusercontent.com/94684615/142631863-02bfb535-e75e-403a-85d7-baa49ad9db0b.png
5. Слияние в ветку master, решение конфликтов
https://user-images.githubusercontent.com/94684615/142631958-9397f6cb-e37c-4ed7-97d8-0397c8104ba2.png
6. Сделать комит с изменениями 
https://user-images.githubusercontent.com/94684615/142632237-eeb03f44-687a-43bf-a2e6-3016ba2f1883.png
7. Хард откат комита 
https://user-images.githubusercontent.com/94684615/142632418-d27ef0ed-461a-4e83-8a51-2635221e4caf.png
8. Создать ветку для отчета
https://user-images.githubusercontent.com/94684615/142632470-c82e7bd0-0aac-436e-960a-fd2a59a34014.png



COMMAND LOGS

git config -l

git clone git@github.com:reven-n1/LR6.git

cd LR6/

git pull

/добавление файла через интерфейс гита/


git log

git diff(git show commit~ commit)

git checkout master

git merge origin/branch1



/решение конфликта/

git add mergefile.txt

git branch -d branch1



git add .........

git commit -am "1st change"

/изменения/



git reset --hard HEAD~2

git checkout -b "report"



ФОРМАТИРОВАННАЯ ИСТОРИЯ КОММИТОВ
https://user-images.githubusercontent.com/94684615/142632515-534ca4b7-63a0-4792-9311-9d3d0543e0c0.png

