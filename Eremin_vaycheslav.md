# Инструкция 
# Основные команды:

## git log — 
вызывать список действий и сохранений

## git init — 
создать репозиторий в папке на локальной машине

## git add — 
отслеживать добавленные файлы

## git commit + комментарий — 
сохранить текущее состояние

## git diff — 
показать разницу между версиями

## git chechout — 
переключиться между разными версиями


# Работа с черновиками

## git branch 
Если у нас несколько версий черновика, мы
можем вывести на экран ветку, где находимся,
командой git branch

Создать ветку можно командой git branch.Делать это надо в папке с репозиторием: git branch <название новой ветки>

## Совмещение двух вариантов текста

# git merge 
Чтобы слить любую ветку с текущей, вызываем
git merge <имя ветки для слияния с текущей>

## Удаление веток

Если ветка  больше не нужна, ее можно удалить :
git branch -d имя ветки

# Удаленный репозиторий

## Копировать внешний репозиторий на свой ПК можно командой git clone

Команда git clone составная: она не только
загружает все изменения, но и пытается слить
все ветки на локальном компьютере и в
удаленном репозитории.

## git pull -
Эта команда позволяет скачать все
из текущего репозитория и автоматически
сделать merge с нашей версией

## git push -
Эта команда позволяет отправить нашу
версию репозитория на внешний
репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ
на внешнем репозитории.

## pull request -

команда для предложения изменений
запрос на вливание изменений в репозиторий
0 comments on commit 54528ee