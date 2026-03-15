<<<<<<< HEAD
1. Инициализация репозитория
   git init
   Создаёт новый локальный репозиторий Git в текущей папке.

2. Клонирование репозитория
   git clone <URL_репозитория>
   Скачивает удалённый репозиторий на ваш компьютер.
   Пример:
   git clone https://github.com/user/repo.git

3. Проверка статуса изменений
   git status
   Показывает:
   Изменённые файлы.
   Файлы, готовые к коммиту (staged).
   Файлы, не отслеживаемые Git (untracked).

4. Добавление файлов в staging
   git add <файл> # Добавить конкретный файл
   git add . # Добавить все изменённые файлы
   Подготавливает файлы к коммиту (помещает в staging area).

5. Фиксация изменений (коммит)
   git commit -m "Сообщение коммита"
   Сохраняет изменения в локальном репозитории с описанием (сообщением).
   Пример:
   git commit -m "Добавлен новый компонент Header"

6. Загрузка изменений на GitHub/GitLab
   git push origin <ветка>
   Отправляет локальные коммиты в удалённый репозиторий.
   Пример (для ветки main):
   git push origin main

7. Получение изменений с удалённого репозитория
   git pull origin <ветка>
   Скачивает и сливает (merge) изменения из удалённого репозитория в локальную ветку.
   Пример:
   git pull origin main

8. Создание новой ветки
   git branch <имя*ветки> # Создать ветку
   git checkout <имя*ветки> # Переключиться на ветку
   Или сразу создать и переключиться:
   git checkout -b <имя_ветки>

9. Слияние веток (Merge)
   git merge <имя_ветки>
   Объединяет изменения из указанной ветки в текущую.
   Пример (слить ветку feature в main):
   git checkout main
   git merge feature
10. Просмотр истории коммитов
    git log
    Показывает список коммитов с хешами, авторами и сообщениями.
    Для компактного вывода:
    git log --oneline
11. Отмена изменений
    Отмена изменений в файле (до коммита):
    git restore <файл>
    Отмена последнего коммита (с сохранением изменений):
    git reset --soft HEAD~1
    Полная отмена коммита (удалит изменения):
    git reset --hard HEAD~1
12. Удаление ветки
    git branch -d <имя*ветки> # Удалить локальную ветку
    git push origin --delete <имя*ветки> # Удалить ветку на GitHub
13. Работа с .gitignore
    Создайте файл .gitignore в корне проекта и укажите файлы/папки, которые не нужно отправлять в репозиторий.
    Пример:
    node_modules/
    .env
    \*.log
14. Принудительная загрузка (если нужна перезапись)
    git push --force origin <ветка>
    ⚠️ Опасно! Используйте только если уверены (например, после git rebase).

15. Краткая шпаргалка по порядку работы
    Сделали изменения в файлах → git add .
    Зафиксировали коммитом → git commit -m "Описание"
    Загрузили на GitHub → git push origin main
=======
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
>>>>>>> 850c06a0cc2d118c5788d70ea613c729e271a5f8
