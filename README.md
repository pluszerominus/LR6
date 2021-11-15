# LR6
1. Клонируем репозиторий на компьютер  
![Клонируем репозиторий на компьютер](https://github.com/pluszerominus/LR6/blob/report/Screen/1.jpg)
3. Добавили файл на GItHub и подтягиваем изменения в локальный репозиторий  
![Добавили файл .txt](https://github.com/pluszerominus/LR6/blob/report/Screen/2.jpg) 
5. Получаем историю операций для каждой ветки   
![история операций для каждой ветки](https://github.com/pluszerominus/LR6/blob/report/Screen/3.jpg)
7. Смотрим последние изменения  
![Последние изменения](https://github.com/pluszerominus/LR6/blob/report/Screen/4.jpg)
9. Для слияния с папкой main переходим в неё   
![](https://github.com/pluszerominus/LR6/blob/report/Screen/5.1.jpg)
11. Начинаем слияние но из-за конфликта слияние не завершается   
![](https://github.com/pluszerominus/LR6/blob/report/Screen/6.1.jpg)
13. Выводим причину конфликта и решаем его изменив файлы  
![](https://github.com/pluszerominus/LR6/blob/report/Screen/7.jpg)
15. Удаляем ненужную ветку  
![](https://github.com/pluszerominus/LR6/blob/report/Screen/9.jpg)
17. Делаем изменения в файле и коммитим их  
![](https://github.com/pluszerominus/LR6/blob/report/Screen/10.jpg) 
19. Делаем "хард" коммит  
![](https://github.com/pluszerominus/LR6/blob/report/Screen/11.jpg)
21. Создаём ветку для отчёта  
![](https://github.com/pluszerominus/LR6/blob/report/Screen/12.jpg)
23. Загружаем ветку в удалённый репозиторий  
![](https://github.com/pluszerominus/LR6/blob/report/Screen/13.jpg)
24. Лог команд  
git clone https://github.com/pluszerominus/LR6  
git pull  
git reflog --all  
git log -p  
git checkout main  
git merge  master  
git diff  
git branch -d master  
git add addfile.txt  
git commit -m "new information"
git commit -m "new information 2"
git reset --hard HEAD
git checkout -b report
git branch
git push --set-upstream origin report
