# GIT_may19_academy
Exercise1
1.- Create on C:/ a folder with name: /academyGitHub
2.- Open git bash
3.- Clone  and create branch: branch-<name>
                              git clone https://github.com/DigitalAcademies/GIT_may19_academy.git
                              git checkout develop
                              git checkout -b branch-<name>
4.- Open GIT_may19_academy/Exercise1/<name>.txt
5.- add in <name>.txt your name (complete) and favorite food , save it.
6.- Execute:
                              git status (check what you modified)
                              git add <file>
                              git commit -m "Exercise1 <name>"
                              git push origin branch-<name>
6.- Check on https://github.com/DigitalAcademies/GIT_may19_academy the changes everybody pushed on their branch
7.- Create PR to develop https://github.com/DigitalAcademies/GIT_may19_academy/pulls

-----------------------------------------------------------------------------------------------------------
Exercise2
-Objective: create a file for each team with the names of all the members in ASC order and resolve conflicts.
1.- Create feature branch:
                              git flow feature start TASK-<number> develop
2.- Add your name: FEDacademy\Exercise2\<team>.txt and save it
               execute:
                              git status (check what you modified)
                              git add <file>
                              git status
                              git commit -m "Exercise2 TASK-# <name>"
                              git push origin feature/TASK-<number>
3.- Create PR just Person #1 to develop (always check your changes before submit your PR)
               (Estefany will merge PR for #1)
4.- Person #2 should pull latest changes:
                              git pull origin develop (always execute a git pull)
                              (resolve conflicts)
                              git status
                              git add <file>
                              git commit -m "merging conflicts TASK-#"
                              git status
                              git push origin feature/TASK-<number>
5.- Create PR just Person #2 to develop (always check your changes before submit your PR)
               (Estefany will merge  PR for #1)
6.- Then #3 should pull latest changes:
                              git pull origin develop (always execute a git pull)
                              (resolve conflicts)
                              git status
                              git add <file>
                              git commit -m "merging conflicts TASK-#"
                              git status
                              git push origin feature/TASK-<number>
7.- Create PR just Person #3 to develop (always check your changes before submit your PR)
               (Estefany will merge PR for #3)
8.- Person #4 should pull latest changes:
                              git pull origin develop (always execute a git pull)
                              (resolve conflicts)
                              git status
                              git add <file>
                              git commit -m "merging conflicts TASK-#"
                              git status
                              git push origin feature/TASK-<number>
9.- Create PR just Person #4 to develop (always check your changes before submit your PR)
10.- Estefany will merge PR for #4
