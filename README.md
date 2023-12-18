# hello

open setting - repository - Protected branches - enable force push -f 

git remote add origin https://gitlab.com/andregraunt/gopro.git

git branch -M main

git add .

git status

git commit -m "fir 1 comm"

git push -uf origin main 

git add .

git commit -m "fir 2 comm"

git push -uf origin main 

<<<<<<< HEAD
opa pa pa


=======
ko ko ko
>>>>>>> a4b0bb48fa4d712ddb1c33c2c2a5e3070a358813

merge - git config pull.rebase false

 You can do so by running one of the following commands sometime before
hint: your next pull:
hint: 
hint:   git config pull.rebase false  # merge
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.