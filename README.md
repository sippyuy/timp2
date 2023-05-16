# Лабораторная работа №2
## Part I
- Создайте пустой репозиторий на сервисе github.com (или gitlab.com, или bitbucket.com).
- Выполните инструкцию по созданию первого коммита на странице репозитория, созданного на предыдещем шаге.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/1.png)
  ![](https://github.com/sippyuy/timp2/blob/main/screens/2.png)
- Создайте файл hello_world.cpp в локальной копии репозитория (который должен был появиться на шаге 2). Реализуйте программу Hello world на языке C++ используя плохой стиль кода. Например, после заголовочных файлов вставьте строку using namespace std;.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/3.png)
  ![](https://github.com/sippyuy/timp2/blob/main/screens/4.png)
- Добавьте этот файл в локальную копию репозитория.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/5.png)
- Закоммитьте изменения с осмысленным сообщением.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/6.png)
- Изменитьте исходный код так, чтобы программа через стандартный поток ввода запрашивалось имя пользователя. А в стандартный поток вывода печаталось сообщение Hello world from @name, где @name имя пользователя.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/7.png)
- Закоммитьте новую версию программы. Почему не надо добавлять файл повторно git add?
  ![](https://github.com/sippyuy/timp2/blob/main/screens/8.png)
- Запуште изменения в удалёный репозиторий.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/9.png)
- Проверьте, что история коммитов доступна в удалёный репозитории.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/10.png)
## Part II
- В локальной копии репозитория создайте локальную ветку patch1.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/11.png)
- Внесите изменения в ветке patch1 по исправлению кода и избавления от using namespace std;.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/12.png)
- commit, push локальную ветку в удалённый репозиторий.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/13.png)
  ![](https://github.com/sippyuy/timp2/blob/main/screens/14.png)
- Проверьте, что ветка patch1 доступна в удалёный репозитории.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/15.png)
- Создайте pull-request patch1 -> master.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/16.png)
- В локальной копии в ветке patch1 добавьте в исходный код комментарии.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/17.png)
- commit, push.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/18.png)
- Проверьте, что новые изменения есть в созданном на шаге 5 pull-request
  ![](https://github.com/sippyuy/timp2/blob/main/screens/19.png)
- В удалённый репозитории выполните слияние PR patch1 -> master и удалите ветку patch1 в удаленном репозитории.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/20.png)
  ![](https://github.com/sippyuy/timp2/blob/main/screens/21.png)
- Локально выполните pull.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/22.png)
- С помощью команды git log просмотрите историю в локальной версии ветки master.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/23.png)
- Удалите локальную ветку patch1.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/24.png)
## Part III
- Создайте новую локальную ветку patch2.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/25.png)
- Измените code style с помощью утилиты clang-format. Например, используя опцию -style=Mozilla.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/26.png)
- commit, push, создайте pull-request patch2 -> master.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/27.png)
- В ветке master в удаленном репозитории измените комментарии, например, расставьте знаки препинания, переведите комментарии на другой язык.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/28.png)
- Убедитесь, что в pull-request появились конфликтны.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/29.png)
- Для этого локально выполните pull + rebase (точную последовательность команд, следует узнать самостоятельно). Исправьте конфликты.
- Сделайте force push в ветку patch2
  ![](https://github.com/sippyuy/timp2/blob/main/screens/30.png)
- Убедитель, что в pull-request пропали конфликтны.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/31.png)
- Вмержите pull-request patch2 -> master.
  ![](https://github.com/sippyuy/timp2/blob/main/screens/32.png)
