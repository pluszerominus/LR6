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
  
25. История коммитов  
  
commit 49c7f4ede5e2ed4e529b35d0753095bfc322e03f (HEAD -> report, origin/report)  
Author: pluszerominus <Top-Bletka@yandex.ru>  
Date:   Mon Nov 15 13:03:34 2021 +0300  
  
    added screenshot  
  
commit a5de2c3f6889377833d438199c5de21f1699a02e (origin/main, origin/HEAD, main)  
Author: pluszerominus <Top-Bletka@yandex.ru>  
Date:   Sun Nov 14 09:47:06 2021 +0300  
  
    new information 2  
  
commit bba075533b11be863b5f758aa7a0101855bbb16c  
Author: pluszerominus <Top-Bletka@yandex.ru>  
Date:   Sun Nov 14 09:45:44 2021 +0300  

    new information  

commit dc304215507255101ca2595ea3ce9bad97487b29  
Merge: e60f38a 73e3cbb  
Author: pluszerominus <Top-Bletka@yandex.ru>  
Date:   Sun Nov 14 09:35:09 2021 +0300  
  
    change file  
  
commit 73e3cbb07a633cd5929a20a5f281ecc39add6ac5 (origin/master)  
Author: pluszerominus <Top-Bletka@yandex.ru>  
Date:   Sun Nov 14 09:33:13 2021 +0300  
  
    change file master  
  
commit e60f38a91e104cebfc6e2c239a4a3979e93ab75f  
Merge: 9402d97 9bb6a3e  
Author: pluszerominus <Top-Bletka@yandex.ru>  
Date:   Sun Nov 14 09:32:29 2021 +0300  
  
    change file  
  
commit c31b7554004bb678603d61bf30efd8620e959e4f  
Author: pluszerominus <Top-Bletka@yandex.ru>  
Date:   Sun Nov 14 09:27:12 2021 +0300  
  
    add extra information in master  
  
commit d3ac33ef91050e4dc7cebb0024ecced4cd55ef7c  
Author: pluszerominus <Top-Bletka@yandex.ru>  
Date:   Sun Nov 14 09:26:18 2021 +0300  
  
    add extra information  
  
commit 5c22b7a9a63cdcf204e6cacc07cc1445f5f144b5  
Merge: d81beb2 e72d589  
Author: pluszerominus <Top-Bletka@yandex.ru>  
Date:   Sun Nov 14 09:21:07 2021 +0300  
  
    delete extra information  
  
commit 5a69564ea7a2eab77a99503dfe7fe6054bf5d4cf  
Author: pluszerominus <59607427+pluszerominus@users.noreply.github.com>  
Date:   Sun Nov 14 08:59:27 2021 +0300  
  
    Update mergefile.txt  
  
commit e72d5892436d3aae58e576b115271f48d49c6a88  
Author: pluszerominus <59607427+pluszerominus@users.noreply.github.com>  
Date:   Sun Nov 14 08:58:55 2021 +0300  
  
    Update mergefile.txt  
  
commit 67d45a9797df1ef524ae00a6a8d6b44c775830f6 (origin/pluszerominus-patch-1)  
Author: pluszerominus <59607427+pluszerominus@users.noreply.github.com>  
Date:   Sun Nov 14 08:44:09 2021 +0300  
  
    Update mergefile.txt  
  
commit ea8c7b1066b1c9c756e7b4da85f0478809bb175c  
Author: pluszerominus <59607427+pluszerominus@users.noreply.github.com>  
Date:   Sun Nov 14 08:43:15 2021 +0300  
  
    Update mergefile.txt  
  
commit c19376ff18d594bb04798eeca4a3db5f1f5daba8  
Author: pluszerominus <59607427+pluszerominus@users.noreply.github.com>  
Date:   Sat Nov 13 20:37:27 2021 +0300  
  
    Create addfile.txt  
  
commit 18bdbf61bd4462c034b67c065460d4ea6c508734  
Author: pluszerominus <59607427+pluszerominus@users.noreply.github.com>  
Date:   Sat Nov 13 18:27:45 2021 +0300  
  
    Rename mergefile to mergefile.txt  
  
commit 5d5573e972b5ea3ba0068f1d55d06a56f4fb264b  
Author: pluszerominus <59607427+pluszerominus@users.noreply.github.com>  
Date:   Sat Nov 13 18:26:14 2021 +0300  
  
    Create mergefile  
  
commit 80b68de8fbd21837850312843eca8dcfffa267d8  
Author: pluszerominus <59607427+pluszerominus@users.noreply.github.com>  
Date:   Sat Nov 13 18:22:00 2021 +0300  
  
    Create README.md  
  
  
