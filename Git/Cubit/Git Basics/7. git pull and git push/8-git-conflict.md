**8. В директории /home/box/REPO располагается локальный репозиторий. Необходимо при помощи команды git push отправить локальные изменения в ветку push_task_branch удаленного репозитория (origin). При выполнении задания вы столкнетесь с конфликтом. Разрешите конфликт таким образом, чтобы в файле example_file оказалась версия файла из вашего репозитория.**

```bash
cd /home/box/REPO
git fetch
git pull
git status
git add .
git commit -m 'add example_file'
git push
```
