Last login: Tue Aug 13 20:25:08 on ttys000 [khadijagan@Khadijas-MacBook-Air-2 • ~ % cd Desktop [khadijagan@Khadijas-MacBook-Air-2 Desktop % 1s
Pushing into github.doc
learn_git
gomvcoce
[khadijagan@Khadijas-MacBook-Air-2 Desktop % cd learn_git [khadijagan@Khadijas-MacBook-Air-2 learn_git % touch third.txt [khadijagan@Khadijas-MacBook-Air-2 learn_git % git init
hint: Using 'master' as the name for the initial branch. This default branch name hint: 1s subject to change. To contigure the initial branch name to use in all hint: of your new repositories, which will suppress this warning, call:
hint:
hint•
git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main'
'trunk' and
hint: development hint:
The just-created branch can be renamed via thig command:
hint:
ait branch -m
Initialized empty Git repository in /Users/khadijagan/Desktop/learn_git/.git/ khadijagan@Khadijas-MacBook-Air-2 learn_git % git add third.txt [khadijagan@Khadijas-MacBook-Air-2 learn _git % git commit -m "adding third .txt" [master (root-commit) 55648311 adding third. txt
Committer: Khadija Gannouni <khadijagan@Khadijas-MacBook-Air-2.local>
Your name and email address were configured automatically based on your username and hostname. Please check that they are accurate.
You can suppress this messade b settina them explicitlv. Run the following command and follow the instructions in your editor to edit your configuration file:
git config --global --edit
After doing this, you may fix the identity used for this commit with:
git commit
--amend --reset-author
1 file changed, 0 insertions(+), 0 deletions (-) create mode 100644 third. txt khadijagan@Khadijas-MacBook-Air-2 learn_git % git log commit 556483104f4f98698a69f8bf3ea3c82d19434589 (HEAD -> master)
Author: Khadija Gannouni <khadijagan@Khadijas-MacBook-Air-2.local>
Dates
Tue Aug 13 20:30:27 2024 +0100
adding third.txt
khadijagan@Khadijas-MacBook-Air-2 learn_git % git status
[On branch master
nothing to commit, working tree clean khadijagan@Khadijas-MacBook-Air-2 learn_git % touch fourth. txt khadijagan@Khadijas-MacBook-Air-2 learn _git % git add fourth. txt khadijagan@Khadijas-MacBook-Air-2 learn_git % git commit -m "adding fourth. txt" [master 1f31f391 adding fourth.t×t
Committer: Khadija Gannouni <khadijagan@Khadijas-MacBook-Air-2.local>
Your name and email address were configured automatically based on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the following command and follow the instructions in your editor to edit your configuration file:
git config --global --edit
Your name and email address were configured automatically based on vour username and hostname. Please check that the are accurate.
You can suppress this message by setting them explicitly. Run the following command and follow the instructions in your editor to edit your configuration file:
git config --global
--edit
After doing this, you may fix the identity used for this commit with:
git commit --amend --reset-author
1 file changed, 0 insertions (+), 0 deletions (-)
create mode 10644 TOUrin.iT
khadijagan@Khadijas-MacBook-Air-2 learn_git % rm third. txt khadijagan@Khadijas-MacBook-Air-2 learn_git % git add

khadijagan@Khadijas-MacBook-Air-2 learn_git % git commit -m "removing third. txt [master 181b9b1] removing third. txt
Committer: Khadija Gannouni <khadijagan@Khadijas-MacBook-Air-2.local>
Your name and email address were configured automatically based on vour username and hostname. Please check that the are accurate.
You can suppress this message by setting them explicitly. Run the following command and follow the instructions in your editor to edit your configuration file:
git config --global --edit
After doing this, you may fix the identity used for this commit with:
git commit
--amend --reset-author
1 file changed, 0 insertions(+), 0 deletions (-) delete mode 100644 third. txt khadijagan@Khadijas-MacBook-Air-2 learn_git % git log commit 18169b1c7acf738245802885f90065224e1c1 (HEAD -> master)
Author: Khadija Gannouni <khadijagan@Khadijas-MacBook-Air-2.local>
Date:
Tue Aug 13 20:32:25 2024 +0100
removing third.txt
commit 1f31f398cf33d29de7d5e96fc91dfae58b7208d0
Author: Khadija Gannouni <khadijagan@Khadijas-MacBook-Air-2.local>
Date:
Tue Aug 13 20:31:40 2024 +0100
adding fourth.txt
commit 556483104f4f98698a69f8bf3ea3c82d19434589
Author: Khadija Gannouni <khadijagan@Khadijas-MacBook-Air-2.local>
Date:
Tue Aug 13 20:30:27 2024
+0100
adding third. txt
khadijagan@Khadijas-MacBook-Air-2 learn_git % git config --global core.pager cat khadijagan@Khadijas-MacBook-Air-2 learn_git % git config --list --global core.pager=cat
khadijagan@Khadijas-MacBook-Air-2 learn_git % pwd
/Users/khadijagan/Desktop/learn_git khadijagan@Khadijas-MacBook-Air-2 learn_git % [
