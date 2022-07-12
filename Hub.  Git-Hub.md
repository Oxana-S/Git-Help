# git-help-3-hub
Создание репозитория на github на компьюторе, удаленно из командной строки терминала, используя команды консольного приложения hub. 

## Демонстрация
Создаём, используя Git Bash, репозиторий с именем KristinitaTest.github.io в Windows.

SashaChernykh@DESKTOP-0G54NVG MINGW32 /e     
$ mkdir KristinitaTest.github.io
#### Имя папки станет и именем Вашего удалённого репозитория.
SashaChernykh@DESKTOP-0G54NVG MINGW32 /e     
$ cd KristinitaTest.github.io

SashaChernykh@DESKTOP-0G54NVG MINGW32 /e/KristinitaTest.github.io     
$ touch README.MD

SashaChernykh@DESKTOP-0G54NVG MINGW32 /e/KristinitaTest.github.io     
$ start README.MD
#### Пишем «Repository for test GitHub features and demonstrations.» в файл README.MD.
SashaChernykh@DESKTOP-0G54NVG MINGW32 /e/KristinitaTest.github.io     
$ hub init
Initialized empty Git repository in E:/KristinitaTest.github.io/.git/

SashaChernykh@DESKTOP-0G54NVG MINGW32 /e/KristinitaTest.github.io (master)      
$ hub add . && git commit -m "Repository for Sasha tests"
[master (root-commit) b56f811] Repository for Sasha tests
 1 file changed, 1 insertion(+)
 create mode 100644 README.MD

SashaChernykh@DESKTOP-0G54NVG MINGW32 /e/KristinitaTest.github.io (master)       
$ hub create -d "Create test repository" -h "Kristinita.ru"
Updating origin
created repository: Kristinita/KristinitaTest.github.io
#### Протокол «http://» будет добавлен автоматически в имя сайта.
SashaChernykh@DESKTOP-0G54NVG MINGW32 /e/KristinitaTest.github.io (master)
$ hub push -u origin master
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 296 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/Kristinita/KristinitaTest.github.io.git
 * [new branch]      master -> master

*Ссылка на статью:*      
https://ru.stackoverflow.com/questions/504578/%D0%9A%D0%B0%D0%BA-%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D1%82%D1%8C-%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D0%B9-%D0%BD%D0%B0-github-%D1%87%D0%B5%D1%80%D0%B5%D0%B7-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%BD%D1%83%D1%8E-%D1%81%D1%82%D1%80%D0%BE%D0%BA%D1%83
