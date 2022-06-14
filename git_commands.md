1.gh repo create MyTasks --public
2.mkdir MyTasks
3.cd MyTasks
4.mkdir Task1
5.echo "### Create a “Task1” folder in the master branch. Create and push ./Task1/README.md file." >> README.md
6.cd ~/MyTasks
7.git init
8.git add Task1/
9.git commit -m "Create Task1 folder"
10.git remote add origin git@github.com:uvaysjon-coder/MyTasks.git
11.git branch -M main
12.git push -u origin main
13.git checkout -b dev
14.git add test_file.txt
15.git commit -m "Create test_file.txt"
16.git push -u origin dev
17.git checkout -b %USERNAME-new_feature
18.echo "# MyTasks" >>  README.md
19.git status
20.git add README.md
21.git commit -m "Create README.md"
22.cat >> .gitignore
  .*
  !.gitignore
23.git add .gitignore
24.git commit -m "Create .gitignore"
25.cd Task1/
26.cat >> .gitignore
  .*
  !.gitignore
27.git add .gitignore
28.git commit -m "Create .gitignore"
29.git push -u origin %USERNAME-new_feature
30.git checkout %USERNAME-new_feature 
31.git reset --soft HEAD~1
32.git checkout main
33.git log >> log.txt
34.git push -u origin main
34.git checkout %USERNAME-new_feature
35.git merge dev
36.git checkout dev
37.git branch -d %USERNAME-new_feature
38.git merge main



