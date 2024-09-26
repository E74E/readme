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
 
====
                        ## commit  
====
`git add --all` или `git add *file*`
`git commit -m *описание_изменений_без_пробелов_или_в_кавычках*`

посмотреть историю: `git log`  
  
====  
                         ## ssh
====
1. `cd` *перейти в домашнюю директорию*
2. *проверить есть ли ключи* `ls -la .ssh/` *.pub - это ключ*
3. ? удалить если есть ?
4. создаем ключи: `ssh-keygen -t ed25519 -c jajf@mail.ru` аккаунт github
            или   `ssh-keygen -t rsa -b 4096 -c ksad@mail.ru аккаунт github 
проверить есть ли ключи `ls -a ~/.ssh`
5. копировать содержимое .pub
6. 
====
                        ## github
====
1. зарегаться
2. меню аккаунта -> settings -> ssh and gpg keys -> new ssh key
title - придумать имя
key type - authentication key
key - вставить содержимое .pub

проверить ключ `ssh -T git@hub.com`
1. Создать рерозиторий `профиль -> your profile -> repositories -> new
2. придумать имя и создать
3. ...or push - копировать и вставить :
в папке проекта
`git remote add origin git@github.com:E74E/ddd.git`

* проверить связку :`git remove -v`

4. `$ git push -u origin main`  *main или master* 
      пушим в первый раз
    `git push`  потом


====

