**5. В директории /home/box/REPO располагается локальный репозиторий. Необходимо при помощи команды git diff определить, в каком файле было произведено меньше всего добавлений в последнем коммите и записать его название в файл /home/box/answer.**

```bash
cd /home/box/REPO
git log
git diff b84d06a2363b087fe8264fe4f5744af306a46a1b
echo 'mCpNSoItfT'>>/home/box/answer
```
