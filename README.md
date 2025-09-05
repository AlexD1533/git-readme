# Git команды

---

- git init  - создать репозиторий в текущей папке
- git add --all (add file.asd) - добавить в репозиторий файлы
- git commit -m "message" создать коммит, сохранить изменения
- git push синхронизировать с удаленным репозиторием
- git clone клонировать удаленный репозиторий

- git push -u origin main - первый раз дял связи локальной ветки и удаленной
- git remote add origin и адрес - связать с удаленным репозиторием
- git status - статус репозитория 
- git remote -v - совпадают ли локальный и удаленный репозитории
 - git push origin --delete main - удалить ветку на удаленном репозитории
 
 -git branch -m master - переименовать ветку на локальном


```mermaid
graph LR;
%% комментарий
  A --> B;
  [git log --oneline] --> commits info;
```


 ## Удачи!