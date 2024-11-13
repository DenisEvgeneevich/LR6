# Лабораторная работа №6
_Цель лабораторной работы_: изучение базовых возможностей системы управления версиями, опыт работы с Git API, опыт работы с локальным и удалённым репозиторием.

## Ход работы 

1. Клонирование репозитория, настройка клиента git, создание текстового файла, первого коммита с ним и выгрузка коммита на локальный репозиторий
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_1.png">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_2.png">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп3_3.png">
</p>

Изменения во всех коммитах:
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_4.png">
</p>

2. Создание новой ветки и обзор изменений в ней
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_5.png">
</p>

Слияние произошло без конфликтов
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_6.png">
</p>

Был создан коммит с сообщением о слиянии
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_7.png">
</p>

3. Удаление созданной ветки
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_8.png">
</p>

4. Просмотр промежуточных коммитов
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_9.png">
</p>

5. Были внесены другие изменения в репозиторий: была добавлена грамота за лучшего спутника 4 института и текстовый файл с познавательным материалом.
На данном скриншоте была добавлена картинка
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_10.png">
</p>

6. Просмотр коммитов
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_11.png">
</p>

7. Был добавлен существующий файл с изменениями, а другой файл был удалён. После чего был сделан коммит. Затем был создан коммит с добавлением картинки, который впоследствии был откатан.
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_12.png">
</p>

8. Окно при откате:
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_13.png">
</p>

9. Выгрузка коммитов, просмотр:
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_14.png">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп15_2.png">
</p>

10. Создаение ветки для отчёта и файла README.md
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_16.png">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_17.png">
</p>

11. Добавление папки со скриншотами в новую ветку:
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_18.png">
</p>

12. История операций в форматированном виде, где:
- `%h` — это сокращённый хеш коммита.
- `%an` — это имя автора коммита.
- `%ar` — это время, прошедшее с момента коммита.
- `%s` — это сообщение коммита.
<p align="center">
  <img src="https://github.com/DenisEvgeneevich/LR6/blob/report/screens/оп2_19.png">
</p>

## Лог команд
```
git clone
git config user.name
git config user.email
git add
git commit -m
git push
git show *хэш коммита*
git branch
git checkout
git log
git merge
git branch -d
git rm
git revert HEAD
git push --set-upstream origin 
git log --pretty=format:"%h - %an, %ar : %s"
```
## Вывод
В данной лабораторной работе были изучены базовые возможности системы управления версиями, был получен опыт работы с Git Api и опыт работы с локальным и удаленным репозиторие, также был получен опыт работы с Markdown.