git installation

stages:
U - untracked - git ko matlab nahi hai ki yeh file hai
A - added or staged - git ko ab pata hai ki yeh file hai matlab git ab is file ke baare mein aware hai, abhi track nahi kr rha hai but pata hai is file ka.
C - Committed

commands you need to know - 
git status -s => to know current status of unstaged and staged files
git log --oneline => to know current status of saved points

managing your own projects
making git available in our project
making a checkpoint or saved point
     adding files
     staging files
     committing them
going back to some previous check point
     git log --oneline - logging everything
     git reset --hard HEAD~1 - reverting back to the previous saved point, matlab agar mujhe yeh saved point nahi chahiye toh delete krdega last commit wali cheezein.

WHAT MATTERS?

THE ULTIMATE BASICS
-------------------

git ko enable karna - git init
untracked files
git ke sath files add karna - staging
saved points ya checkpoints create karna - git commit
kisi pichle checkpoint par wapas jaana - git reset

STATUS AND LOGS - MAKING POSSIBILITIES - BRANCHING
--------------------------------------------------

status dekhna
logs check karna with graph option
branch samjhna
branch merge karna

merging techniques - ff merge, three way merge, squash merge, recursive strategy merge, rebase and merge

conflicts handle karna
branch delete karna
~ stashing samjhna



