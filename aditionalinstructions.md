git add .: the dot means you-re sending all of the files available on folder, if you're sending only an specified file you must write it's name
git push origin main: -u and remote are not anymore necessary 'cuz the remote link is already created, we only need to stablish it once
How to make a branch: we use to create branchs when we need to configure/set up a feature to the project. To do this, first we create the branch and then add the project
git checkout -b "novo-botao": creates a new branch named novo-botao and the "checkout" puts us into the new branch
git checkout master: makes us come back into main branch
git merge novo-botao: inserts the second branch into the first one, put'em together
after the merge you must push the master again into github with git push origin main
There is a writen tutotial of git and git hub at rafaballerini's account on github
we can edit files and commit directly at github
at github you can "fork" someones repository whenever you want to push someones repository to your own github