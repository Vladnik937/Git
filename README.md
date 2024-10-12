# Git
GitHub_HW_2
1. На локальном репозитории сделать ветки для:
- Postman  - ` git branch Postman `
- Jmeter - ` git branch Jmeter `
- CheckList - ` git branch CheckList `
- Bag Reports - ` git branch Bug_report `
- SQL - ` git branch SQL `
- Charles - ` git branch Charles `
- Mobile testing - ` git branch Mobile_testing `

2. Запушить все ветки на внешний репозиторий - ` git push origin --all `
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта - ` git checkout Bug_report ` -> ` touch bug_report.txt ` -> ` vim bug_report.txt `
4. Запушить структуру багрепорта на внешний репозиторий - ` git add bug_report.txt ` -> ` git commit -m "create bug_report.txt" ` -> ` git push origin Bug_report ` 
5. Вмержить ветку Bag Reports в Main - ` git checkout main ` -> ` git merge Bug_report `
6. Запушить main на внешний репозиторий. - ` git push `
7. В ветке CheckLists набросать структуру чек листа. - ` git checkout Checklist ` -> ` touch check_list.txt ` -> ` vim check_list.txt ` 
8. Запушить структуру на внешний репозиторий - ` git add check_list.txt ` -> ` git commit -m "create check_list.txt" ` -> ` git push origin CheckList ` 
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main - ` github ---> compare & pull request ----> create pull request --> Merge ` 
10. Синхронизировать Внешнюю и Локальную ветки Main - ` git checkout main ` -> ` git fetch ` -> ` git pull `
