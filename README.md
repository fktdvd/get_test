# hello-world
Hello World repository for Git tutorial
This is an example repository for the Git tutoial on https://www.w3schools.com

This repository is built step by step in the tutorial.

just test the git

az alábbi parancsokat tanultam meg: 
git --version 
git init
git status
git add --all
git commit -m "commit message"
git commit -a -m "commit message"
git log

Kilépni a szöveg megjelenítőből :q val lehet.

Ugyanezeket el lehet végezni a VSCode ba épült Source Control fülön

A git működik lokálisan is. A fenti commandokat el lehet végezni távoli Git felhő nélkül is. 
A céges gépen nem veszi észre a git a módosításokat, hiába vannak hozzáadva a githez. 

A Brencselés teljesen új fogalom, eddig még nem használtam.
Kommandok: 

git branch new-branch   // ahol a new-branch az új branch neve
git branch              // amivel ellenőrizni lehet a brancheket
git checkout new-branch // amivel át lehet lépni az új branchbe 
git checkout main       // visszaváltás a main-re   
git merge emergeny-fix  // egy branch bemergelése
git branch -d emergeny-fix  // a mergelt branch törlése

Eddig volt egy lokális git repositorim, amit most fel push - olok egy bitbucket felhőbe: 

git remote add origin URL //Ahol az url a Bitbuket vagy GutHub repo linkje. Beállítja a távoli repot.
git push --set-upstream origin main



