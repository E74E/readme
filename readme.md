                     ## Настройка GIT
====
1 Проверить, стоит ли GIT : `git version`

2 Прописать свои данные (видно имя на GITHUB)
```BASH
git config --global user.name *blabla*
git config --global user.email *ot@baldy.ru*
```
посмотреть эту инфу: `cat ~/.gitconfig`

 
                     ## Инициализация репозитория
====
1. Создать папку `mrdir *имя папки*` 
2. Войти в папку `cd *имя папки*`
3. `git init`
* разгитить: `rm -rf .git`
* проверить: `git status`   
4. `git add --all` или `git add *file*`
 
====
                        ## commit  
====
`git commit -m *описание_изменений_без_пробелов_или_в_кавычках*`

посмотреть историю: `git log`



