**1. В директории  /home/box/REPO у вас содержится склонированный репозиторий https://github.com/OSLL/git_course_example_repo. В репозитории находится файл file.txt, который менялся на протяжении 4 коммитов. Вам необходимо найти, какие данные были добавлены в file.txt в третьем коммите и удалить остальные (т.е. нужно оставить только строку, которая была добавлена во время третьего коммита).**

```bash
cd /home/box/REPO
git log file.txt
git diff c9e85307b046ce5c3cd8a29dcc9680a395b7d4ff a6733f3c4e0304d0acdf16c6c47adb87579945bf file.txt
echo 'oPL3g1jH9t6iUvNJi8QnWzWzajBqUgnx'>file.txt
git add .
git commit -m 'update file.txt'
```
