pwd - показать рабочую директорию
ls - показать содержание текущей директории
cd first-project - переход в папку first-project
mkdir new-folder - создать папку new-folder
touch new-file.txt - создать файл new-file.txt
rm first-project.txt - удалить файл first-project.txt
rmdir new-folder - удалить папку new-folder, если она пустая
rm -r new-folder - удалить папку new-folder и ее содержимое
echo "hello" >> first-project.txt - записать hello в файл first-project.txt
cat first-project.txt - вывести содержимое файла first-project.txt
mv first-project.txt firstProject.txt - переименовать файл first-project.txt на firstProject.txt
mv first-project.txt /Users/name/Documents/ - перемесить файл first-project.txt в папку Documents

git init - инициализация пустого репозитория в текущей директории
git status - просмотр состояния изменений в репозитории
git add file.txt/ git add . - подготовка файла к коммиту, подготовка всех изменений в текущей директории к коммиту
git commit -m "Добавлен новый файл" - коммит - фиксация подготовленных изменений в репозитории с комментарием к ней
git remote add origin <SSH проекта> - привязываем свой локальный репозиторий к удаленному (куда мы будем пушить изменения). origin - стандартное имя удаленного репозитория
git branch -M main - принудительно переименовываем текущую ветку в main
git push -u origin main - отправляем ветку main в удаленный репозиторий origin и устанавливаем ее как отслеживаемую
git push - отправляем локальные коммиты в удаленный репозиторий
git pull - загружаем изменения из удаленного репозитория и объединяем их с локальной веткой
git branch new_branch - создание новой ветки
git checkout new_branch - переход в указанную ветку
git branch - просмотр всех веток и текущей
git checkout -b third_branch - создание и переход в новую ветку одновременно
git merge third_branch - слияние ветки third-branch с текущей веткой



