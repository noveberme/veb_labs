# veb_labs
Для добавления лабораторной работы необходимо:
1) Открыть Visual Studio Code и клонировать репозиторий. Для этого сверху найдите вкладку View, в которой найдите Terminal. Откроется Terminal, в который надо ввести команду:  git clone https://github.com/noveberme/veb_labs.git
   
   Для создания новой ветки: git checkout -b surname-name1
   
   Вместо surname_name пишете свои ФИ, а вместо цифры номер ЛР
3) Находите папку своей группы, в ней ответственный создает файл .html, как в папке example. Это страничка вашей группы. В ней вы изменяете только тег li и все, что находится внутри
4) В папке своей группы создаете папке со своим ФИО. Нейминг, как в примере: ФамилияИО. И также как и в примере копируете файл .html для вашей личной странички.
5) В вашей личной папке создаете папки с лабораторными работами. Нейминг: task1, task2 и так далее, и в них уже добавляете файлы вашей ЛР
6) Для добавления на гитхаб откройте терминал, как и в пункте 1 и введите команду
git add . (обратите внимание, точка тоже часть команды)
7) Далее для создания коммита команда: git commit -m "Описание изменений", а затем: git push origin имя-ветки
8) Для создания пул реквеста перейтите на гитхаб, найдите свою ветку и создайте на ней пул реквест (3 точки справа от знака удаления)
9) Ждете merge или сообщение о том, что надо что-то исправить через commit
