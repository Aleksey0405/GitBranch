GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bug Reports
- SQL
- Charles
- Mobile testing
`git branch` Postman; `git branch` Jmeter; `git branch` CheckLists; `git branch` Bug_Reports; `git branch` SQL; `git branch` Charles; `git branch` Mobile_Testing
2. Запушить все ветки на внешний репозиторий
* `git push -u origin --all`
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
* `git checkout Bug_Reports`
* `cat > bug_report_1.txt`
    + Bug Title
    + Bug ID
    + Build number
    + Environment
    + Severity
    + Priority
    + Assigned to
    + Reported by
    + Reported on
    + Type
    + Status 
* `Enter`
* `Ctrl + D`
4. Запушить структуру багрепорта на внешний репозиторий
* `git add .` ; `git commit -m 'add bug_report_1.txt'` ; `git push`
5. Вмержить ветку Bag Reports в Main
* `git checkout main`; `git merge Bug_Reports`
6. Запушить main на внешний репозиторий.
* `git add .` ; `git commit -m 'merge Bug_Rep to main'` ; `git push` 
7. В ветке CheckLists набросать структуру чек листа.
* `git checkout CheckLists` ; `cat > text_field_name_checklist`
    + Title
    + Precondition
    + Example
    + Expected result
* `Enter`
* `Ctrl + D`
8. Запушить структуру на внешний репозиторий
* `git add .` ; `git commit - m 'add checklist.txt'` ; `git push`
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
* Перейти на https://github.com/ в нужный нам репозиторий, войти в ветку Checklists, нажать `Pull Request`
10. Синхронизировать Внешнюю и Локальную ветки Main
* `git checkout main`;`git pull`