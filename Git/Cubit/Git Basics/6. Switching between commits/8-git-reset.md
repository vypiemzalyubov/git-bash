**8. В директории /home/box/REPO располагается локальный репозиторий. Необходимо при помощи команды git reset откатиться к предыдущему коммиту без изменений в индексе или рабочем каталоге. Ничего удалять/создавать/коммитить не нужно.**

```bash
cd /home/box/REPO
git reset --soft HEAD~1
```
