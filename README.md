# dz-module-11

В созданном проекте открываем терминал и прописываем:
git init

В проекте создаем файл без навания с расширением .gitignore
В него прописываем файлы для игнорирования:
- *.sass
- /bin
- /admin
- /config


добавьте все файлы в локальное хранилище;
- git add .
- git commit -m 'add all files'



создайте новую ветку и перейдите в неё;
- git branch blog
- git checkout blog


в новой ветке создайте папку blog с файлами: index.js, index.html;
- new folder: blog
- new file: index.js
- new file: index.html

- git add .
- git commit -m 'add branch files'

загрузите на удаленный репозиторий лишь основную ветку вашего проекта.
- git checkout master
- git branch -M master
- git remote add origin https://github.com/lremiz/dz-module-11.git
- git push -u origin master
