GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman
```
git branch postman
```
- Jmeter
```
git branch jmeter
```
- CheckLists
```
git branch check_lists
```
- Bug Reports
```
git branch bug_reports
```
- SQL
```
git branch sql
```
- Charles
```
git branch charles
```
- Mobile testing
```
git branch mobile_testing
```
2. Запушить все ветки на внешний репозиторий
```
git push -u origin postman   # і так само з іншими шести гілками 
```
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
```
git checkout bug_reports
nano  bug1.txt
```
4. Запушить структуру багрепорта на внешний репозиторий
```
git add .
git commit -m  "bug_report1"
git push
```
5. Вмержить ветку Bag Reports в Main
```
git checkout main
git merge bug_reports
```
6. Запушить main на внешний репозиторий.
```
git push
```
7. В ветке CheckLists набросать структуру чек листа.
```
git checkout check_lists
nano check_list1
```
8. Запушить структуру на внешний репозиторий
```
git add . && git commit -m "check_list1" && git push
```
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```
Заходимо на сайт GitHub
Вибираємо гілку check_lists
Натискаємо Compare & pull request
Натискаємо Create pull request
Merge pull request 
Confirm merge
```
10. Синхронизировать Внешнюю и Локальную ветки Main
```
git checkout main
git pull
```
