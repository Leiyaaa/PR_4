# PR_4
git branch testing_1
git log --oneline -decorate
git branch testing_2
git checkout testing_2
git log --oneline --decorate --graph --all
git checkout master
git merge testing_2
git branch -d testing_1
git branch
git branch -v
git branch --no-merged
