Тестовый файл для семинара 1 по курсу контроль версий углубленно

контроль версий углубленно.
Семинар 1 

# Задание 1
* git clone склонировать репозиторий на компьютер
* git remote -v позволяет посмотреть все удаленные подключения к репозиторию
* git remote remove origin удаляет ссылки на удаленные подключения этого репозитория 
* далее создаем пустой репозиторий на гитхабе и командами 
git remote add origin https://github.com/konopleva-nina/ProgLanguage_HomeWork.git
git branch -M main
git push -u origin main
добавляем новые ссылки для подключения 

задание 2
git remote add sourse https://github.com/konopleva-nina/Homework_lesson_3.git добавляем еще одну ссылку для удаленного подключения
git fetch --all стянуть изменения со всех удаленных репозиториев (только скачивает)
git log origin/main ^main посмотреть изменения в первом скачиваемом репозитории origin
git log sourse/main ^main посмотреть изменения вo втором скачиваемом репозитории sourse 
git merge origin/main добавить изменения из первого удаленного репозитория origin
git merge sourse/main добавить изменения из второго удаленного репозитория sourse
git push -u origin main отправить изменения в первый удаленный репозиторий
git push -u sorse main отправить изменения во второй удаленный репозиторий