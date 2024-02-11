# Git Helper

Привет! Этот репозиторий создан для того, чтобы помочь освоить основы Git.

## Команды Git:

- `git init`: Инициализация нового репозитория.
- `git add <filename>`: Добавление файла в индекс.
- `git commit -m 'Сообщение ккоммита'`: Создание коммита с сообщением.

## Работа с ветками:

- `git branch`: Просмотр списка веток.
- `git checkout -b <branch>`: Создание и переключение на новую ветку.

## Работа с удаленным репозиторием:

- `git remote add origin <url>`: Добавление удаленного репозитория.
- `git push -u origin <branch>`: Отпрака изменений на GitHub.

## Регистрация на GitHub:

1. Перейти на [GitHub](https://github.com/).
2. Нажмите "Sign up" и следуйте инструкциям.

## Инструкции по использованию репозитория:

1. Склонируйте репозиторий: `git clone <url>`.
2. Измените файлы, добавьте коммиты.
3. Отправьте изменения на GitHub: `git push origin <branch>`.

Happy coding!

```mermaid
graph LR;
  working_directory -- "git add" --> staging_area;
  staging_area      -- "git commit" --> local_repository;
  local_repository  -- "commit hash" --> HEAD;
```
