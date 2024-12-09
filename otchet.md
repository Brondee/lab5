# Отчет
## Задание 1
Создал пустой файл pre-commit в папке .git/hooks, в котором прописал следующий bash скрипт, который проверяет содержится ли упоминание автора в тексте.
<img width="665" alt="Снимок экрана 2024-12-09 в 19 08 35" src="https://github.com/user-attachments/assets/f70c7e97-3bb7-4322-bd6f-821aa646d994">

Далее прописал следующий скрипт в терминале ```chmod +x .git/hooks/pre-commit```, чтобы сделать файл исполнимым.

После чего добавил пустой txt файл, в котором через vim прописал Author, чтобы файл успешно прошел проверку
<img width="528" alt="image" src="https://github.com/user-attachments/assets/ce94f44b-24b7-43d0-8808-abda9de6a985">

Далее добавил еще один txt файл, в котором в этот раз уже ничего не прописывал, из-за чего коммит не прошел проверку
<img width="490" alt="image" src="https://github.com/user-attachments/assets/6914ec37-fb5d-4b10-8199-05e414fea14a">

## Задание 2
В папке проекта прописал следующие команды для инициализации git flow и создания ветки task-managment
```
git flow init
git flow feature start task-managment
```
<img width="594" alt="image" src="https://github.com/user-attachments/assets/3c856594-bf34-4055-8586-41681944dff7">

Далее создал файл task_managment.py и выполнил коммит, после чего завершил фичу и объединил с основной веткой.\
<img width="643" alt="image" src="https://github.com/user-attachments/assets/2f2344fa-a296-43c1-8110-78dc84457768">

Далее на ветке develop начал создание релиза, после чего создал version.txt и закомитил\
<img width="643" alt="image" src="https://github.com/user-attachments/assets/fa48dde7-5424-4858-b121-1002a3c385ea">

После чего завершил релиз и объединил его с ветками "develop" и "main" и создал hotfix и объединил его с ветками "develop" и "main".
<img width="562" alt="image" src="https://github.com/user-attachments/assets/329651f3-7e15-4497-ab78-22ca2577a17c">
<img width="471" alt="image" src="https://github.com/user-attachments/assets/022cb6b8-6743-4c32-9924-08009c7b96e6">

В конце отправил все изменения на удаленный репозиторий
