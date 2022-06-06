# GitHub_HW_2


1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

git branch Postman
git branch Jmeter
git branch CheckLists
git branch BugReports
git branch SQL
git branch Charles
git branch MobileTesting


2. Запушить все ветки на внешний репозиторий

git push -u origin --all


3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

git checkout BugReports
cat > bug_report.txt


4. Запушить структуру багрепорта на внешний репозиторий

git add bug_report.txt
git commit -m "add structure"
git push


5. Вмержить ветку Bag Reports в Main

git checkout main
git merge BugReports -m "merge_BugReports"


6. Запушить main на внешний репозиторий

git push


7. В ветке CheckLists набросать структуру чек листа

git checkout CheckLists
cat > check_list.txt


8. Запушить структуру на внешний репозиторий

git add check_list.txt
git commit -m "add structure"
git push


9. На внешнем репозитории сделать Pull Request ветки CheckLists в Main

Compare and pull request
Create pull request


10. Синхронизировать Внешнюю и Локальную ветки Main

git checkout main
git pull

